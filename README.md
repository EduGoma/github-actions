# Ejercicios de GitHub Actions

Este repositorio contiene ejercicios para aprender a usar GitHub Actions como parte de tus flujos de trabajo de integración y entrega continua (CI/CD).

## Pregunta 1: Configurar una acción para compilar y probar una aplicación cada vez que se envié una confinación de código

En este ejercicio, aprenderás a configurar un flujo de trabajo de GitHub Actions que se ejecutará cada vez que realices una confirmación de código en la rama principal. Este flujo de trabajo compilará y probará tu aplicación utilizando un contenedor Docker local. Para obtener más detalles y un ejemplo de cómo configurar este flujo de trabajo, consulta el archivo `.github/workflows/docker-build-test.yml`.

## Pregunta 2: Implementar un flujo de trabajo de implementación continua para una aplicación web utilizando GitHub Actions

En este ejercicio, aprenderás a implementar un flujo de trabajo de CI/CD utilizando GitHub Actions. El flujo de trabajo se activará cada vez que realices una confirmación de código en la rama principal, construirá y probará tu aplicación y, si todas las pruebas pasan, la implementará en un servidor de producción. Para obtener más detalles y un ejemplo de cómo configurar este flujo de trabajo, consulta el archivo `.github/workflows/ci-cd.yml`.

## Requisitos

- Una cuenta de GitHub
- Un repositorio de GitHub para almacenar tu código y configuración de flujos de trabajo
- Conocimientos básicos de YAML, el lenguaje de marcado utilizado para definir flujos de trabajo de GitHub Actions
- Conocimientos básicos de Docker (opcional, solo para el ejercicio 1)

## Recursos adicionales

- [Documentación oficial de GitHub Actions](https://docs.github.com/en/actions)
- [Tutorial de implementación en AWS con GitHub Actions](https://aws.amazon.com/es/blogs/containers/create-a-ci-cd-pipeline-for-amazon-ecs-with-github-actions-and-aws-codebuild-tests/)
