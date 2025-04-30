<img src="https://heladosbon.com/wp-content/uploads/2023/10/logo-header-bon-1.svg" alt="Logo Helados Bon" width="400"/>

# Helados Bon

## Descripción General
Bienvenido al repositorio central de Helados Bon, el fabricante y distribuidor líder de helados en la República Dominicana. Fundada con pasión por crear productos congelados excepcionales, Helados Bon se ha establecido como un símbolo de calidad, innovación y tradición en la industria heladera del Caribe.

## Misión
Deleitar a nuestros clientes con productos de helado excepcionales elaborados con ingredientes de la más alta calidad, fomentando prácticas sostenibles y celebrando la cultura y sabores dominicanos.

## Flujo de Trabajo de Desarrollo
1. **Seguimiento de Issues**: Todo trabajo de desarrollo comienza con un issue en nuestro sistema de gestión de proyectos
2. **Estrategia de Ramificación**: 
   - `main`: Código listo para producción
   - `develop`: Rama de integración
   - `feature/*`: Nuevas funcionalidades
   - `hotfix/*`: Correcciones urgentes
3. **Revisión de Código**: Todos los PRs requieren al menos dos aprobaciones
4. **CI/CD**: Pipelines automatizados de pruebas y despliegue
5. **Estrategia de Entornos**:
   - Desarrollo
   - Pruebas/QA
   - Staging
   - Producción

## Primeros Pasos
1. Clonar el repositorio:
   ```
   git clone https://github.com/helados-bon/main.git
   ```
2. Instalar dependencias:
   ```
   cd helados-bon && npm install
   ```
3. Configurar variables de entorno:
   ```
   cp .env.example .env
   ```
4. Iniciar el entorno de desarrollo:
   ```
   docker-compose up -d
   ```

## Documentación
Las documentaciones pertinentes de los proyectos se encuentran en su debido repositorio con readme, en el caso de los proyectos de Google AppScript existe un repositorio centralizado que brinda la documentación de cada proyecto.

## Contribución
1. Asegúrate de tener los derechos de acceso necesarios
2. Crea una rama de funcionalidad desde `develop`
3. Implementa tus cambios siguiendo nuestros estándares de codificación
4. Incluye pruebas para la nueva funcionalidad
5. Actualiza la documentación según sea necesario
6. Envía un pull request con una descripción clara de los cambios

## Contacto
- Gerente de TI: [Kelvin Acosta](mailto:kacosta@bon.com.do)
- Ingenierio de Aplicaciones y Analítica: [Alejandro Beltre](mailto:aaquiles@bon.com.do)

## Sitio Web
Para más información sobre nuestros productos y servicios, visita nuestro [sitio web oficial](https://heladosbon.com/)

---

© 2025 Helados Bon. Todos los derechos reservados.
