# Informe del Plan de Aseguramiento de la Calidad de Software (SQA)

**Proyecto:** Giveth – Plataforma de donaciones comunitarias Web3  
**Versión:** 1.0  
Integrantes del equipo:
- Maviel Martinez Cholula 
- Ricardo Martinez Santos
- Karen Garcia Garcia 
- Fecha: 23/09/2025
---
## 1. Introducción
El presente informe describe el Plan de Aseguramiento de la Calidad de Software (SQA) del proyecto Giveth, una plataforma que facilita a los usuarios realizar donaciones y financiar proyectos comunitarios utilizando tecnología blockchain.  
El plan tiene como objetivo garantizar la seguridad, transparencia y confiabilidad en las transacciones, asegurando que los fondos lleguen íntegramente a sus destinatarios y que los smart contracts que los gestionan estén libres de vulnerabilidades críticas. Además, se busca proporcionar una experiencia de usuario intuitiva, accesible y eficiente en diferentes navegadores y dispositivos.

## 2. Objetivos de Calidad
- Asegurar la seguridad y transparencia de las donaciones.
- Validar que los smart contracts gestionen los fondos de forma correcta.
- Garantizar que la interfaz Web3 sea funcional e intuitiva en múltiples navegadores.
- Identificar y corregir errores antes del despliegue en la mainnet.

---

## 3. Alcance
Este plan cubre los siguientes componentes del proyecto:
- **Smart Contracts:** gestión de donaciones y distribución de fondos.
- **Frontend Web3:** interfaz de usuarios, panel de donantes y proyectos.
- **Backend:** almacenamiento seguro de información y registros de transacciones.
- **Seguridad:** validación de claves privadas, firmas digitales y auditorías de código.

---

## 4. Métricas de Calidad

### 4.1 Funcionales
- Cobertura de pruebas en smart contracts: ≥ 85%.
- Porcentaje de transacciones exitosas: ≥ 98%.
- Validación completa de flujos de donación y retiro.

### 4.2 No Funcionales
- Latencia de confirmación de transacciones: ≤ 5 segundos.
- Disponibilidad del sistema: ≥ 99%.
- Satisfacción de usuario en pruebas piloto: ≥ 80%.

### 4.3 Seguridad
- Vulnerabilidades críticas en contratos: 0 antes del despliegue.
- Funciones auditadas: ≥ 90%.
- Validación de autenticación y firmas: ≥ 99%.

---

## 5. Tipos de Pruebas

### 5.1 Funcionales
- Pruebas unitarias de smart contracts.
- Pruebas de integración: frontend → blockchain.
- Validación de flujos de usuario (donación, seguimiento, retiro).

### 5.2 No Funcionales
- Pruebas de rendimiento con múltiples donaciones simultáneas.
- Pruebas de usabilidad en paneles de proyectos y donantes.
- Pruebas de escalabilidad ante aumento de usuarios.

### 5.3 Seguridad
- Auditoría de smart contracts.
- Simulación de ataques comunes (reentrancy, overflow, phishing).
- Validación del almacenamiento seguro de datos y claves privadas.

---

## 6. Procedimientos

### 6.1 Procedimiento de Pruebas
1. Configuración del entorno en testnet.
2. Ejecución de pruebas unitarias de contratos.
3. Pruebas de flujo completo en entorno de pruebas.
4. Registro y corrección de incidencias.
5. Validación final antes de desplegar en mainnet.

### 6.2 Revisión de Código
- Revisión obligatoria de cada Pull Request.
- Checklist de seguridad en validaciones de entradas y manejo de fondos.
- Uso de herramientas como Slither y MythX.

### 6.3 Liberación
1. Auditoría final de contratos.
2. Pruebas de regresión en testnet.
3. Validación de métricas de calidad.
4. Despliegue en mainnet.

## 7. Roles y Responsabilidades
- **QA Engineer:** ejecución de pruebas y reporte de errores.
- **Desarrollador:** implementación de funciones y corrección de incidencias.
- **Auditor de Smart Contracts:** verificación de seguridad y lógica de contratos.
- **Product Owner / Community Manager:** validación de experiencia de usuario y objetivos del proyecto.

---

## 8. Herramientas
- **Frontend:** React + Web3.js / Ethers.js.
- **Backend:** Node.js / Firebase (opcional).
- **Testing:** Hardhat, Truffle, Mocha, Chai.
- **Seguridad:** Slither, MythX.
- **Gestión de incidencias:** Jira o GitHub Projects.

## 9. Mejora Continua
El proceso de aseguramiento de calidad se mantendrá en mejora continua mediante:
- Retroalimentación de donantes y gestores de proyectos.
- Monitoreo constante de transacciones y errores en la plataforma.
- Actualizaciones periódicas de contratos y frontend según resultados de auditorías y recomendaciones de la comunidad.

## Conclusión
El Plan de Calidad de Software del proyecto Giveth establece lineamientos claros para garantizar la seguridad, confiabilidad y experiencia de usuario en la plataforma. Su implementación permitirá minimizar riesgos, asegurar la correcta gestión de fondos y fortalecer la confianza de la comunidad en la adopción de esta solución Web3.
