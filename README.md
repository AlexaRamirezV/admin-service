# 👨‍⚕️ Admin Service (Paso 4)

**Puerto:** `9090`

Servidor de monitoreo visual que permite visualizar el estado (`Health`), métricas, logs y detalles técnicos de todos los microservicios registrados.

## 🚀 Ejecución
1.  Iniciar este servicio al final, o después del Gateway.
2.  **Verificación:** Acceder a `http://localhost:9090` para ver el estado.

---
**Nota:** Si se accede al final se vería algo como:

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/1588a529-c15e-48c3-b434-83b54f2e23b7" />

---
### 🔗 Mapa de Arquitectura
0. [Config data](https://github.com/AlexaRamirezV/config-data.git)
1. [Config Server](https://github.com/AlexaRamirezV/config-service.git)
2. [Registry Service (Eureka)](https://github.com/AlexaRamirezV/registry-service.git)
3. [Gateway Service](https://github.com/AlexaRamirezV/gateway-service.git)
4. ➡️ **[Admin Service]**
5.  APIs del sistema:
   * [Auth](https://github.com/AlexaRamirezV/DWB-auth.git)
   * [Customer](https://github.com/AlexaRamirezV/DWB-customer.git)
   * [Product](https://github.com/xEriis/Backend.git)
   * [Invoice](https://github.com/AlexaRamirezV/DWB-invoice.git)
