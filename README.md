# Actividad 3
**Estudiante:** Ernesto Cordova Arreola
**Materia:** Fundamentos Devops

## Descripción
Esta actividad implementa una aplicación Flask contenerizada con Docker, lista para ser integrada en un pipeline de CI/CD en AWS utilizando CodePipeline, CodeBuild y CodeDeploy.

## Estructura
- `/app`: Contiene el código fuente y el Dockerfile.
- `docker-compose.yml`: Para el despliegue local.
- `buildspec.yml` & `appspec.yml`: Configuraciones para la automatización en la nube.
