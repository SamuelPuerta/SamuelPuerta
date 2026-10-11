<h1 align="center">Samuel Puerta</h1>
<p align="center">
  Estudiante de Ingeniería de Sistemas (9.º sem., UdeA) · Backend, Cloud y Machine Learning
</p>

<p align="center">
  <a href="https://samuel-puerta.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/samuelpuerta-softwaredev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://instagram.com/samuel.puerta"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
  <a href="mailto:puertasamuel04@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <img src="https://img.shields.io/badge/Abierto%20a-Pr%C3%A1cticas%202027--1-2ea44f?style=for-the-badge">
</p>

## Sobre mí

Auxiliar de Programación en la **SIU – UdeA** (desde jul. 2025). Construyo software que se pueda mantener, probar y desplegar, y me interesa llevar modelos de machine learning a servicios reales.

| Backend | Cloud y DevOps | Machine Learning |
|---|---|---|
| APIs REST, autenticación JWT, bases de datos, migraciones y mensajería | Docker, CI/CD con GitHub Actions y arquitecturas serverless en AWS | Modelos de clasificación, validación rigurosa y despliegue como microservicio |

## Stack

| | |
|---|---|
| **Lenguajes** | <img src="https://skillicons.dev/icons?i=java,python,go,c,kotlin,bash&theme=dark"> |
| **Backend** | <img src="https://skillicons.dev/icons?i=spring,fastapi,maven,gradle&theme=dark"> |
| **Bases de Datos** | <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis&theme=dark"> |
| **ML y datos** | <img src="https://skillicons.dev/icons?i=python,sklearn&theme=dark"> ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square) ![Optuna](https://img.shields.io/badge/Optuna-3F6DB5?style=flat-square) |
| **Cloud y DevOps** | <img src="https://skillicons.dev/icons?i=aws,docker,githubactions,git,github,linux&theme=dark"> |
| **Testing y calidad** | ![JUnit5](https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-78A641?style=flat-square) ![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white) ![Serenity BDD](https://img.shields.io/badge/Serenity%20BDD-0B7285?style=flat-square) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![JaCoCo](https://img.shields.io/badge/JaCoCo-C21325?style=flat-square) ![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white) |

## Proyectos destacados

### Backend y cloud

| Proyecto | Descripción |
|---|---|
| [**CITASalud**](https://github.com/SamuelPuerta/CITASalud-Agendamiento) | Microservicio de agendamiento médico: registro y login con JWT, control de acceso por roles, gestión de horarios y citas, notificaciones por correo, mensajería con RabbitMQ y migraciones con Flyway. Incluye REST, GraphQL, Swagger, métricas con Prometheus, cobertura con JaCoCo y pipeline CI/CD con SonarCloud y Snyk.<br>*Java 17 · Spring Boot · PostgreSQL · RabbitMQ · Docker* |
| [**Cronos**](https://github.com/SamuelPuerta/cronos) · [demo](https://cronos-frontend.s3.us-east-1.amazonaws.com/index.html) | Cápsula del tiempo digital serverless con el patrón dead man's switch: el mensaje se envía al destinatario solo si el dueño deja de hacer check-in. API de 7 endpoints, tarea programada cada 15 minutos que revisa vencimientos y entrega por correo, frontend estático y pruebas con moto.<br>*Python · Lambda · API Gateway · DynamoDB · EventBridge · SES · S3 · Serverless Framework* |
| [**Transcription Service**](https://github.com/SamuelPuerta/Transcription-service) | Servicio backend con pruebas automatizadas, contenedor y análisis de calidad.<br>*Python · FastAPI · MongoDB · Docker · SonarQube* |

### Machine learning

| Proyecto | Descripción |
|---|---|
| [**TriageFlow ML Service**](https://github.com/SamuelPuerta/triageflow-ml-service) | Microservicio de triaje de urgencias: un RandomForest asigna el nivel (crítico, urgente o estable) a partir de signos vitales y la API expone KPIs de saturación. Imagen Docker multi-stage con usuario no-root y healthcheck, y pruebas de los endpoints.<br>*Python · FastAPI · scikit-learn · Docker* |
| [**Fraud Detection**](https://github.com/SamuelPuerta/FinancialTransactions-FraudDetection-Model) | Detección de fraude con clases muy desbalanceadas (~1,3 %). Compara regresión logística, KNN, Random Forest, MLP y SVM con validación cruzada estratificada, PR-AUC como métrica principal, y evalúa PCA y UMAP.<br>*Python · pandas · scikit-learn* |
| [**Modelos IA Saber Pro**](https://github.com/SamuelPuerta/ModelosIASaberProColombia) | Análisis y modelado predictivo sobre datos de Saber Pro: limpieza, feature engineering, optimización de hiperparámetros y pseudo-etiquetado.<br>*Python · pandas · scikit-learn · XGBoost · Optuna* |

### Calidad, móvil y juegos

| Proyecto | Descripción |
|---|---|
| [**Paycore ScreenPlay**](https://github.com/SamuelPuerta/PaycoreScreenPlay) | Pruebas E2E con patrón Screenplay sobre una plataforma de pagos: autenticación, gestión y operaciones. 14 de 14 escenarios en verde.<br>*Java · Serenity BDD · Cucumber · Gradle* |
| [**RutaUdeA**](https://github.com/maikol0629/rutaUdea) | App Android para preparar el examen de admisión de la UdeA (razonamiento lógico y lectura crítica). Contribuidor.<br>*Kotlin · Firebase* |
| [**NeoPoker**](https://github.com/SamuelPuerta/neopoker) | Juego móvil de póker con temática cyberpunk, modos Classic y Neon, y arquitectura offline-first.<br>*Flutter · Flame · Firebase* |

## Sistemas y concurrencia

Proyectos de la carrera sobre cómo funcionan las cosas por debajo:

- [Concurrency Web Server](https://github.com/SamuelPuerta/concurrency-webserver): comparación experimental de estrategias de planificación de solicitudes en C con sockets
- [Matrix Multiplication](https://github.com/SamuelPuerta/matrix-multiplication-processes): paralelismo con procesos e IPC, con análisis de rendimiento
- [Synchronization Mechanisms](https://github.com/SamuelPuerta/Synchronization-Mechanisms-SO): mecanismos de sincronización de sistemas operativos
- [SO Monitor](https://github.com/SamuelPuerta/System-Operative-Monitor-Bash): monitor del sistema en Bash
- [CCTV TCP/UDP](https://github.com/SamuelPuerta/CCTV-SOCKETS-TCP-UDP): comunicación con sockets TCP y UDP

## Actualmente

- Backend y desarrollo de software como eje, con ML aplicado como segundo foco
- Profundizando en cloud, contenedores y automatización de calidad
- Finalizando Ingeniería de Sistemas y buscando práctica empresarial para 2027-1

## Estadísticas

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=SamuelPuerta&show_icons=true&theme=tokyonight&hide_border=true&count_private=true">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SamuelPuerta&layout=donut&langs_count=8&theme=tokyonight&hide_border=true">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=SamuelPuerta&theme=tokyonight&hide_border=true">
</p>


