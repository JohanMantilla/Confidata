
## 🛡️ Confidata 🛡️

Confidata es una plataforma de última generación que permite a las organizaciones gestionar de manera eficiente el cumplimiento de las regulaciones de protección de datos personales en Ecuador. Combina tecnología moderna con interfaces intuitivas para simplificar procesos complejos de privacidad.

## ✨ Características Principales

- **Gestión de Consentimientos**: Registro y seguimiento de consentimientos de usuarios
- **Administración de Datos Personales**: Control centralizado de información personal
- **Sistema de Notificaciones**: Alertas automáticas para cumplimiento normativo
- **Auditoría y Trazabilidad**: Registro completo de operaciones y accesos
- **API RESTful**: Integración sencilla con sistemas existentes

## 🛠️ Stack Tecnológico

### Frontend
- **React** - Interfaz de usuario
- **TypeScript** - Tipado estático
- **React Query** - Gestión de estado del servidor

### Backend
- **NestJS** - Framework Node.js
- **PostgreSQL** - Base de datos principal
- **Redis** - Cache y sesiones
- **Docker** - Contenedorización
- **JWT** - Autenticación

## 🚀 Inicio Rápido

### Prerrequisitos

- Node.js >= 18
- Docker y Docker Compose
- PostgreSQL >= 14
- Redis >= 6

### Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/Confidata.git
   cd privaceto
   ```

2. **Configurar variables de entorno**
   ```bash
   cp .env.example .env
   # Editar .env con tus configuraciones
   ```

3. **Instalar dependencias**
   ```bash
   # Backend
   npm install
   
   # Frontend
   cd frontend
   npm install
   cd ..
   ```

4. **Iniciar servicios con Docker**
   ```bash
   docker-compose up -d
   ```

5. **Ejecutar migraciones**
   ```bash
   npm run db:migrate
   npm run db:seed
   ```

6. **Iniciar la aplicación**
   ```bash
   # Backend (microservicios)
   npm run start:dev
   
   # Frontend
   cd frontend
   npm run dev
   ```

La aplicación estará disponible en:
- Frontend: http://localhost:3000
- API Gateway: http://localhost:4000
- Documentación API: http://localhost:4000/api/docs

## 📁 Estructura del Proyecto

```
Confidata/
├── api-gateway/          # Gateway principal
├── auth-service/         # Microservicio de autenticación
├── user-service/         # Gestión de usuarios
├── consent-service/      # Manejo de consentimientos
├── data-service/         # Datos personales
├── notification-service/ # Sistema de notificaciones
├── audit-service/        # Auditoría y logs
├── frontend/             # Aplicación React
├── docker-compose.yml
```

## 🔧 Configuración

### Variables de Entorno

Crear un archivo `.env` basado en `.env.example`:

```env
# Base de datos
DATABASE_URL="postgresql://usuario:password@localhost:5432/confidata"
REDIS_URL="redis://localhost:6379"

# JWT
JWT_SECRET="tu-secreto-super-seguro"
JWT_EXPIRES_IN="24h"

# SMTP
SMTP_HOST="smtp.gmail.com"
SMTP_PORT=587
SMTP_USER="tu-email@gmail.com"
SMTP_PASS="tu-password"

# Aplicación
FRONTEND_URL="http://localhost:3000"
API_BASE_URL="http://localhost:4000"
```

## 🧪 Testing

```bash
# Tests unitarios
npm run test

# Tests e2e
npm run test:e2e

# Cobertura
npm run test:cov
```

## 📊 Base Legal

Este sistema está diseñado para cumplir con:

- **Ley Orgánica de Protección de Datos Personales del Ecuador**
- **Decreto Ejecutivo No. 410** (Reglamento de aplicación)
- **Resoluciones de la Autoridad de Protección de Datos**
- Mejores prácticas internacionales (GDPR como referencia)

## 🔒 Características de Seguridad

- Cifrado de datos en reposo y en tránsito
- Autenticación multifactor (2FA)
- Control de acceso basado en roles (RBAC)
- Auditoría completa de operaciones
- Monitoreo de seguridad en tiempo real

## 📈 Monitoreo y Métricas

El sistema incluye dashboards para:
- Estado de cumplimiento normativo
- Métricas de consentimientos
- Actividad de usuarios
- Rendimiento del sistema
- Alertas de seguridad

### Estándares de Código

- Usar ESLint y Prettier para formato
- Escribir tests para nuevas funcionalidades
- Documentar APIs con Swagger/OpenAPI
- Seguir convenciones de commit conventional

## 📋 Roadmap

- [x] Sistema de autenticación
- [x] Gestión de usuarios
- [x] Módulo de consentimientos
- [ ] Dashboard avanzado de métricas
- [ ] Integración con sistemas externos
- [ ] Módulo de capacitación
- [ ] API pública para terceros
- [ ] App móvil para administradores


---

**Confidata Ecuador** - Protegiendo datos, cumpliendo normativas 🇪🇨
