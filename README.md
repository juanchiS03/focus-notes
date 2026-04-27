# 🎨 FocusNotes - Frontend

Interfaz de usuario moderna y de alto rendimiento para FocusNotes. Desarrollada con **Astro**, esta aplicación consume de forma asíncrona la API de Spring Boot para ofrecer una gestión de notas fluida y reactiva.

## 🛠️ Stack Tecnológico
* **Framework:** Astro 4.x
* **Estilos:** Tailwind CSS
* **Lógica:** JavaScript (ES6+) / Fetch API
* **Despliegue:** Vercel

## 📋 Funcionalidades de la Interfaz
* **Consumo de API:** Integración total con el backend mediante variables de entorno para una comunicación segura.
* **Sistema de Filtros:** Filtrado dinámico por categorías (Trabajo, Personal, Idea, Urgente) y buscador por título.
* **UI/UX:**
    * **Sticky Footer:** Layout flexible que mantiene el pie de página en la base de la ventana.
    * **Modales:** Formularios interactivos para la creación de nuevas notas.
    * **Feedback Visual:** Actualización de iconos y estados (favoritos) sin recargar la página.
* **Diseño Responsive:** Adaptabilidad completa a dispositivos móviles y escritorio.

## 🔌 Configuración de Conectividad
Para que el frontend funcione, es necesario configurar la variable de entorno `PUBLIC_API_URL` apuntando a la instancia de Render:
```env
PUBLIC_API_URL=[https://notes-app-backend-fbri.onrender.com/api]
