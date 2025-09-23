# Lista de Verificación de Auditoría – Proyecto Giveth

**Propósito:** Este documento sirve como guía para auditar el código, la seguridad y la documentación del proyecto Giveth, garantizando el cumplimiento de los estándares de calidad definidos en el Plan de SQA.  

**Estado de la Auditoría:**
- En Progreso
- Completado
- Aprobado por el Revisor: [Nombre del Revisor]

---

## Sección 1: Auditoría de Código y Seguridad en la Plataforma
El objetivo es garantizar que los smart contracts, el backend y las transacciones de Giveth sean seguras, transparentes y confiables.

| ID    | Criterio de Verificación             | Descripción                                                                                     | Estado     |
|-------|--------------------------------------|-------------------------------------------------------------------------------------------------|------------|
| C-1.1 | Cobertura de Pruebas                 | ¿Se alcanzó ≥ 85% de cobertura en pruebas unitarias de smart contracts?                        | [ ] Pendiente |
| C-1.2 | Validación de Flujos de Donación     | ¿Se verificó el flujo completo (donación, seguimiento, retiro) en testnet?                    | [ ] Pendiente |
| C-1.3 | Transacciones Exitosas                | ¿Se asegura ≥ 98% de éxito en transacciones?                                                  | [ ] Pendiente |
| C-1.4 | Latencia de Confirmación              | ¿Las transacciones se confirman en ≤ 5 segundos?                                              | [ ] Pendiente |
| C-1.5 | Seguridad en Smart Contracts          | ¿Se realizaron auditorías contra ataques comunes (reentrancy, overflow, phishing) y no se detectaron vulnerabilidades críticas? | [ ] Pendiente |
| C-1.6 | Manejo de Claves Privadas            | ¿Las claves privadas están protegidas y nunca almacenadas en el servidor?                      | [ ] Pendiente |
| C-1.7 | Validación de Firmas                  | ¿La validación de firmas digitales es ≥ 99%?                                                  | [ ] Pendiente |
| C-1.8 | Herramientas de Seguridad             | ¿Se usaron herramientas de análisis (Slither, MythX) para auditar los contratos?              | [ ] Pendiente |

---

## Sección 2: Auditoría de Documentación y Usabilidad
La documentación y la experiencia de usuario son clave para la adopción.

| ID    | Criterio de Verificación             | Descripción                                                                                     | Estado     |
|-------|--------------------------------------|-------------------------------------------------------------------------------------------------|------------|
| D-2.1 | Guía de Configuración                | ¿Existen pasos claros para configurar el entorno y ejecutar el proyecto en testnet?           | [ ] Pendiente |
| D-2.2 | Diagramas de Arquitectura            | ¿Se documenta la interacción frontend → smart contracts → blockchain?                         | [ ] Pendiente |
| D-2.3 | Documentación de la API              | ¿Se describe el uso de las funciones principales y protocolos implementados?                   | [ ] Pendiente |
| D-2.4 | Manual de Usuario                    | ¿Hay un manual para donantes y gestores de proyectos que explique funciones básicas?          | [ ] Pendiente |
| D-2.5 | Usabilidad del Frontend              | ¿El panel Web3 es intuitivo y recibió ≥ 80% de satisfacción en pruebas piloto?                | [ ] Pendiente |
| D-2.6 | Compatibilidad Multinavegador        | ¿La interfaz funciona en distintos navegadores y dispositivos?                                 | [ ] Pendiente |

---

## Sección 3: Auditoría del Backend y Seguridad de Datos
Se revisa la integración, la disponibilidad y la protección de la información.

| ID    | Criterio de Verificación             | Descripción                                                                                     | Estado     |
|-------|--------------------------------------|-------------------------------------------------------------------------------------------------|------------|
| B-3.1 | Seguridad de Datos                   | ¿El almacenamiento de información y transacciones está encriptado y protegido?                | [ ] Pendiente |
| B-3.2 | Integración con Blockchain           | ¿El backend conecta correctamente frontend y contratos?                                        | [ ] Pendiente |
| B-3.3 | Disponibilidad del Sistema           | ¿Se cumple con ≥ 99% de disponibilidad?                                                        | [ ] Pendiente |
| B-3.4 | Escalabilidad                       | ¿El sistema soporta el crecimiento de usuarios y proyectos?                                    | [ ] Pendiente |

---

## Sección 4: Cumplimiento y Ecosistema de la SCF / Giveth
Se asegura que el proyecto esté alineado con las buenas prácticas y los objetivos de Giveth y Stellar.

| ID    | Criterio de Verificación             | Descripción                                                                                     | Estado     |
|-------|--------------------------------------|-------------------------------------------------------------------------------------------------|------------|
| E-4.1 | Licencia de Código Abierto           | ¿El repositorio incluye una licencia de código abierto (MIT, Apache 2.0)?                     | [ ] Pendiente |
| E-4.2 | Política de Privacidad               | ¿Se han redactado términos de servicio y política de privacidad para manejo de datos?         | [ ] Pendiente |
| E-4.3 | Canales de Comunicación              | ¿La documentación incluye los canales de soporte (Discord, Telegram, GitHub)?                 | [ ] Pendiente |
| E-4.4 | Objetivos del Proyecto               | ¿Se refleja la contribución de Giveth a la transparencia y a la inclusión financiera?         | [ ] Pendiente |
---
## Proceso de Verificación:
Se aprueba la auditoria al cumplirse lo siguiente:

- Completar todos los puntos de la lista.

- Validación final por un revisor externo.

- Se confirma que el proyecto cumple con las métricas de seguridad, funcionalidad y documentación.

- Se autoriza el despliegue en mainnet.

