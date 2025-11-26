<img width="1619" height="587" alt="image" src="https://github.com/user-attachments/assets/2ec92c59-3f52-487c-875c-f3ca42d861b9" /># Sistema de Consulta Vehicular (Arquitectura C4)

Este repositorio contiene la implementación técnica del diseño C4 realizado en IcePanel.
LINK DE ICEPNALE: 
- https://s.icepanel.io/3k50yQxNP70jaO/ga0e

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
