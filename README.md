# Sistema de Consulta Vehicular (Arquitectura C4)

Este repositorio contiene la implementación técnica del diseño C4 realizado en IcePanel.

## Arquitectura
- **Backend:** Java Spring Boot con patrón Cache-Aside (Redis) para resiliencia ante fallos de la ANT.
- **Frontend:** React (Vite) para la interacción con el usuario.
- **Integraciones:** SRI (REST) y ANT (Simulación Web Scraping).

## Estructura
- `/vehiculos`: Código fuente del Backend Java.
- `/frontend`: (Dentro de vehiculos) Código fuente de la interfaz React.

## Ejecución
1. Backend: Ejecutar `VehiculosApplication.java` (Puerto 8080).
2. Frontend: `npm run dev` (Puerto 5173).
