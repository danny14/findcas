# 🌴 FindCas - Sistema de Reservas de Fincas

**FindCas** es un sistema especializado en la reserva de fincas para vacaciones o eventos. Facilita tanto a los propietarios como a los usuarios la gestión eficiente de reservas, proporcionando una experiencia sencilla, rápida y segura.

## 🚀 Características Principales

-   🏡 **Gestión de Fincas**: Los propietarios pueden añadir fincas con nombre, ubicación, descripción, capacidad, fotos y tarifas.
-   📅 **Sistema de Tarifas**: Tarifas personalizadas según temporada alta, baja, fines de semana y festivos.
-   👥 **Roles de Usuarios**: Interfaz diferente para clientes, propietarios y administradores.
-   🔐 **Reservas Seguras**: Permite a los usuarios hacer reservas y añadir los nombres de los acompañantes. Las reservas no se pueden cancelar.
-   💳 **Pagos en Línea**: Integración con todos los métodos de pago disponibles en Colombia.
-   ⭐ **Calificaciones y Comentarios**: Los usuarios pueden calificar las fincas (1 a 5 estrellas), dejar comentarios y dar "likes" a sus fincas favoritas.
-   📆 **Calendario de Disponibilidad**: Cada finca puede gestionar sus tiempos disponibles mediante un calendario interactivo.
-   🎁 **Códigos de Descuento**: Posibilidad de aplicar códigos de descuento en promociones o temporadas especiales.
-   ❌ **Políticas de Cancelación**: Políticas de cancelación generales para todas las fincas, configurables para nuevas etapas.

## 🛠️ Tecnologías Utilizadas

-   **Backend**: Laravel
-   **Frontend**: Vue.js
-   **Base de Datos**: MySQL/PostgreSQL
-   **Autenticación**: JWT (JSON Web Token)
-   **Pagos**: Integración con pasarelas de pago nacionales

## 📋 Requisitos

-   PHP 8.1 o superior
-   Composer
-   Node.js (para el frontend con Vue.js)
-   MySQL o PostgreSQL
-   Docker (opcional, para contenedores)

## 🚧 Instalación y Ejecución

Sigue estos pasos para ejecutar el proyecto localmente:

1. Clona el repositorio:

    ```bash
    git clone https://github.com/tu_usuario/findcas.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd findcas
    ```

3. Instala las dependencias de PHP:

    ```bash
    composer install
    ```

4. Instala las dependencias de Node.js:

    ```bash
    npm install
    ```

5. Configura el archivo `.env` con la información de tu base de datos y otros parámetros necesarios:

    ```bash
    cp .env.example .env
    ```

6. Genera la clave de la aplicación:

    ```bash
    php artisan key:generate
    ```

7. Ejecuta las migraciones de la base de datos:

    ```bash
    php artisan migrate
    ```

8. Levanta el servidor de desarrollo:
    ```bash
    php artisan serve
    npm run dev
    ```

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

---

¡Gracias por visitar **FindCas**! Si tienes alguna pregunta o sugerencia, no dudes en abrir un [issue](https://github.com/tu_usuario/findcas/issues).
