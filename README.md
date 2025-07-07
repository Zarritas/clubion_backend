# Clubion Backend

**Backend para Clubion — Plataforma de gestión integral para clubes deportivos, centros de atletismo y equipos.**

Este repositorio contiene el backend desarrollado sobre **Odoo Community Edition**, personalizado para cubrir las necesidades específicas de academias deportivas, equipos y centros de entrenamiento.

---

## 🚀 Funcionalidades clave

- Gestión de miembros, deportistas y entrenadores  
- Planificación y seguimiento de entrenamientos y competiciones  
- Gestión de cuotas, pagos y facturación  
- Control de asistencia y estadísticas deportivas  
- Integración con frontend y APIs REST para una experiencia completa  

---

## 🛠 Tecnologías usadas

- Odoo Community Edition (versión 17 recomendada)  
- Python 3.x  
- PostgreSQL  
- Docker para entorno de desarrollo y despliegue  

---

## 📦 Instalación y configuración

### Requisitos previos

- Docker & Docker Compose instalados  
- Git  

### Clonar el repositorio

```bash
git clone https://github.com/Zarritas/clubion_backend.git
cd clubion_backend
```

### Levantar el entorno con Docker

```bash
docker-compose up -d
```

Esto levantará los servicios de Odoo y PostgreSQL.
Acceder a Odoo

Abre tu navegador en http://localhost:8069 y sigue la configuración inicial.

### 🧪 Desarrollo

- Para instalar módulos personalizados, ponlos dentro de la carpeta addons

- Usa el comando Odoo shell para desarrollo y debugging:
```bash
docker exec -it clubion_backend_odoo_1 /bin/bash
odoo shell -d your_database
```
---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Para contribuir:

1. Haz un fork del repositorio
2. Crea una rama nueva para tu feature o fix (feature/nombre-feature)
3. Realiza commits claros y descriptivos
4. Envía un Pull Request explicando tus cambios

Por favor, lee el archivo `CONTRIBUTING.md` para más detalles.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

---

## 📞 Contacto

Si tienes dudas o quieres colaborar, puedes contactarme vía GitHub o por email: jlorenzolimon@gmail.com

---

## ¡Gracias por formar parte de Clubion!

