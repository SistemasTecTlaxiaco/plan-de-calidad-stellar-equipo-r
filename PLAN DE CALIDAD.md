# Plan de Calidad de Software (SQA) – Proyecto Giveth

**Proyecto:** Giveth – Plataforma de donaciones comunitarias Web3  
**Versión:** 1.0  
Integrantes del equipo:
- Maviel Martinez Cholula 
- Ricardo Martinez Santos
- Karen Garcia Garcia 
- Fecha: 23/09/2025
---
 El presente documento esta el plan de calidad de GIVETH plataforma que permite a usuarios realizar donaciones o financiamientos...

## 1. Introducción
Giveth es una plataforma que permite a usuarios donar y financiar proyectos comunitarios de manera transparente y segura usando blockchain. Este plan asegura que la plataforma funcione correctamente, que los fondos lleguen a los destinatarios sin errores, y que los contratos inteligentes sean confiables y seguros.

## 2. Objetivos de Calidad
- Garantizar la seguridad y transparencia de las donaciones.
- Validar que los smart contracts gestionen correctamente los fondos.
- Asegurar que la interfaz Web3 sea intuitiva y funcione en distintos navegadores.
- Detectar y corregir errores antes del lanzamiento en mainnet.

## 3. Alcance
- **Smart Contracts:** gestión de donaciones y distribución de fondos.
- **Frontend Web3:** panel de donantes y proyectos financiados.
- **Backend:** almacenamiento seguro de información de usuarios y transacciones.
- **Seguridad:** manejo seguro de claves, validación de firmas y auditorías.

## 4. Métricas de Calidad

### 4.1 Funcionales
- Cobertura de pruebas de smart contracts: ≥ 85%.
- Transacciones exitosas: ≥ 98%.
- Validación correcta de flujos de donación y retiro de fondos.

### 4.2 No Funcionales
- Latencia de confirmación de transacciones: ≤ 5 segundos.
- Disponibilidad del sistema: ≥ 99%.
- Experiencia de usuario: evaluación positiva en pruebas piloto (≥ 80%).

### 4.3 Seguridad
- Vulnerabilidades críticas en contratos: 0 antes del despliegue.
- Funciones auditadas: ≥ 90%.
- Validación de firmas y autenticación: ≥ 99%.

## 5. Tipos de Pruebas

### 5.1 Funcionales
- Unitarias de smart contracts.
- Integración: frontend → smart contracts → blockchain.
- Flujo de usuario: donación, seguimiento de fondos, retiro de fondos.

### 5.2 No Funcionales
- Rendimiento: manejo de múltiples donaciones simultáneas.
- Usabilidad: facilidad de uso del panel de proyectos y donaciones.
- Escalabilidad: capacidad de soportar crecimiento de usuarios y proyectos.

### 5.3 Seguridad
- Auditoría de smart contracts.
- Pruebas de ataques comunes: reentrancy, overflow, phishing.
- Validación de claves privadas y seguridad en almacenamiento de datos.

## 6. Procedimientos

### 6.1 Procedimiento de Pruebas
1. Configuración del entorno de prueba (testnet).
2. Ejecución de pruebas unitarias de smart contracts.
3. Pruebas de flujo completo de donaciones y seguimiento de fondos en testnet.
4. Registro de incidencias y corrección de errores.
5. Validación final antes del despliegue en mainnet.

### 6.2 Revisión de Código
- Peer review obligatorio de cada Pull Request.
- Checklist de seguridad: manejo de fondos, validación de inputs y firmas.
- Uso de herramientas de análisis de smart contracts (Slither, MythX).

### 6.3 Liberación
1. Auditoría final de smart contracts.
2. Pruebas de regresión en testnet.
3. Validación de métricas de funcionalidad, seguridad y rendimiento.
4. Despliegue en mainnet.

## 7. Roles y Responsabilidades
- **QA Engineer:** ejecutar pruebas y reportar incidencias.
- **Desarrollador:** implementar funciones y corregir errores.
- **Auditor de Smart Contracts:** revisar seguridad y lógica de contratos.
- **Product Owner / Community Manager:** validar experiencia de usuario y cumplimiento de objetivos de Giveth.

## 8. Herramientas
- **Frontend:** React + Web3.js / Ethers.js.
- **Backend:** Node.js / Firebase (opcional para almacenamiento).
- **Testing:** Hardhat, Truffle, Mocha, Chai.
- **Seguridad:** Slither, MythX.
- **Gestión de incidencias:** Jira o GitHub Projects.

## 9. Mejora Continua
- Retroalimentación de donantes y gestores de proyectos.
- Monitoreo continuo de transacciones y errores.
- Actualización de contratos y frontend según auditorías y feedback de la comunidad.
