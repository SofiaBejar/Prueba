# Prueba

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.16.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# Nidhu - Gestión de Hogares Compartidos

## Autores
- **Sergio Gámez Ortega**  
- **Sofía Béjar Rimoldi**

## Descripción
Nidhu es una aplicación web pensada para facilitar la vida en pisos compartidos. Permite organizar tareas del hogar, controlar los gastos comunes y compartir listas de la compra entre los miembros de la vivienda de forma sencilla y visual.

## Objetivos del Proyecto
- Fomentar la responsabilidad compartida y la organización entre compañeros de piso.  
- Facilitar la comunicación y el reparto equitativo de tareas y gastos.  
- Ofrecer una experiencia de usuario clara, accesible y atractiva.

## 🛠️ Tecnologías Utilizadas
### Frontend
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
</p>

### Base de Datos
<p>
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

### Control de Versiones
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

### Despliegue en AWS
<p>
  <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/CloudFormation-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Route%2053-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>
<blockquote>
  Despliegue en 3 instancias EC2 (Frontend, Backend y BBDD), con infraestructura definida mediante CloudFormation y enrutamiento gestionado con Route 53.
</blockquote>

### Diseño
<p>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
  <img src="https://img.shields.io/badge/FigJam-8E44AD?style=for-the-badge&logo=figma&logoColor=white"/>
</p>

## Esquema E/R de la Base de Datos
(Coloca aquí una imagen del diagrama o un enlace al mismo si está en Figma, Draw.io o Lucidchart)

![Esquema E/R](enlace-a-diagrama.png)

## Tutorial de Uso
1. Regístrate en la aplicación con tu nombre y correo.  
2. Accede a tu espacio compartido.  
3. Crea y asigna tareas domésticas.  
4. Añade gastos comunes y selecciona quiénes participan.  
5. Consulta el saldo individual y colectivo.

### Capturas de pantalla

![Captura de inicio](img/captura-home.png)  
![Captura gastos](img/captura-gastos.png)

## Bitácora de Tareas

### Semana 1 (7/04/2025 - 13/04/2025)
| Tarea realizada                                                | Miembro responsable   |
|---------------------------------------------------------------|-----------------------|
| Crear estructura básica de Backend y frontend                 | Sergio                |
| Crear la base de datos, factorías, semilleros y modelos en el backend | Sergio            |
| Investigar funcionamiento de Laravel Sanctum para crear una API Rest para servir al Frontend | Sergio            |
| Planteamiento inicial del proyecto, investigación sobre la competencia y análisis de necesidades | Sofía             |
| Crear el Notion para organización de tareas y planificación general | Sofía                 |
| Diseño inicial: elección de colores, estilo visual, User Flow, Wireframe de baja fidelidad | Sofía            |

### Semana 2 (14/04/2025 - 20/04/2025)
| Tarea realizada                                                | Miembro responsable   |
|---------------------------------------------------------------|-----------------------|
| Crear endpoints para autenticación (login, logout, registro)  | Sergio                |
| Crear servicio de Autenticación en el frontend para consumir los endpoints de autenticación de la API | Sergio       |
| Crear Landing Page                                           | Sergio                |
| Continuar con el diseño visual y ajustes finales de la Landing Page | Sofía             |
| Revisión y ajustes de diseño de la interfaz de usuario        | Sofía                 |
| Desarrollo de wireframes de alta fidelidad | Sofía  |

### Semana 3 (21/04/2025 - 27/04/2025)
| Tarea realizada                                                | Miembro responsable   |
|---------------------------------------------------------------|-----------------------|
| Crear Login Page y Register Page                               | Sergio                |
| Investigar cómo crear validaciones de formularios en Angular   | Sergio                |
| Implementar las validaciones tanto en el formulario de Login y Registro | Sergio           |
| Diseño de la estructura para separar el Frontend, Backend y BBDD | Sofía  |
| Configuración de Route 53 para facilitar la conexión a la base de datos desde la instancia EC2 | Sofía          |


### Semana 4 (28/04/2025 - 4/05/2025)
| Tarea realizada                                                | Miembro responsable   |
|---------------------------------------------------------------|-----------------------|
| Crear List Page                                               | Sergio                |
| Implementar endpoints y servicios en el backend para resumen de la Home Page y la lista de la compra | Sergio       |
| Crear servicio de Usuario y Piso en el frontend para consumir los endpoints creados | Sergio   |
| Trabajando en el despliegue de la estructura final | Sofía                 |
| Investigación sobre cómo configurar Laravel para utilizar una base de datos ya existente en lugar de crear una nueva durante la configuración del proyecto | Sofía |

## Bibliografía
- [Documentación oficial de Laravel](https://laravel.com/docs)  
- [TailwindCSS Docs](https://tailwindcss.com/docs)  
- [Guía Figma para diseño UI](https://help.figma.com/)  
- [Laravel Sanctum Documentation](https://laravel.com/docs/9.x/sanctum)  
- [Route 53 - Amazon Web Services](https://aws.amazon.com/route53/)  
- [Laravel Database Configuration](https://laravel.com/docs/9.x/database#configuration)  
- [Configurar conexiones remotas de MySQL en Laravel](https://laravel.com/docs/9.x/database#mysql) 
- [Wireframe.cc - Herramienta de wireframes](https://wireframe.cc/)  


## Vídeo de Presentación
[Ver en YouTube](https://www.youtube.com/watch?v=-OSdt3XvKfE&ab_channel=Serzh)

