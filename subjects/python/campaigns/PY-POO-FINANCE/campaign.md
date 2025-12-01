# Campaign: PY-POO-FINANCE – Arquitectura Financiera Modular
## General Information
Campaign Name: POO Aplicada a Finanzas
Campaign Code: PY-POO-FINANCE
Version: 1.0
Status: ■ Ready

---
## Technical Objective
Transformar un sistema de scripts funcionales (FinanceFlow) en una aplicación robusta orientada a objetos, aplicando principios de Ingeniería de Software (SOLID, Clean Code) y preparando el terreno para Data Engineering.

El objetivo es pasar de:
*"Un script que guarda CSVs"*
a:
*"Un sistema modular, extensible y testeable que proyecta flujos financieros."*

---
## Mission Structure
### Main Missions (M)
Pasos críticos de refactorización:
- **M01:** Abstracción y Herencia (Clase `Account`).
- **M02:** Polimorfismo (Eliminar `isinstance` en transacciones).
- **M03:** Capa de Persistencia (Desacoplar CSV de la lógica).
- **M04:** Integración de Pandas (Analytics básico).
- **M05:** Configuración y Entorno (Variables y Rutas).

### Side Missions (S)
Profundización en calidad de código (QA Profile):
- **S01:** Unit Testing con `pytest`.
- **S02:** Logging profesional.

### Boss Mission (B)
- **B01:** El Proyector Financiero (Motor de Simulación).

---
## Required Knowledge
- Clases, Objetos, Herencia, Polimorfismo.
- Manejo de Excepciones.
- Módulos y Paquetes.
- Pandas (Intro).
- Pytest (Intro).

---
## Domain Criteria
Al finalizar, el sistema debe:
1. Permitir agregar nuevos tipos de cuentas (ej. `Investment`) sin romper el código existente.
2. Permitir cambiar el almacenamiento (CSV a SQL) tocando un solo archivo.
3. Generar reportes de proyección financiera realistas.