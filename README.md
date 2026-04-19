# 🖥️ Aplicación Fullstack — Spring Boot + Frontend Web

Aplicación web fullstack que integra un backend **Spring Boot** con un frontend desarrollado en HTML, CSS y JavaScript. Expone una API REST consumida directamente desde el navegador, con toda la aplicación containerizada en Docker.

## 🛠️ Tecnologías

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Stack:** Spring Boot · Spring Data JPA · H2 · HTML/CSS/JS · Docker · Gradle

## 📋 Funcionalidades

- API REST en Java con Spring Boot
- Frontend web que consume la API mediante `fetch`
- Interfaz de usuario para visualizar y gestionar datos
- Base de datos embebida H2
- Aplicación completa containerizada con Docker

## 🚀 Cómo ejecutar

### Con Docker
```bash
git clone https://github.com/MannMatias/spring-boot-fullstack
cd TP-6
docker build -t tp6-app .
docker run -p 8080:8080 tp6-app
```

### Sin Docker
**Requisitos:** Java 17, Gradle

```bash
git clone https://github.com/MannMatias/spring-boot-fullstack
cd TP-6
./gradlew bootRun
```

Acceder desde el navegador en `http://localhost:8080`

## 📁 Estructura del proyecto

```
src/
├── main/
│   ├── java/com/example/inicial1/   # Backend Spring Boot
│   └── resources/
│       └── static/                  # Frontend (HTML, CSS, JS)
Dockerfile
build.gradle
```

## 📚 Contexto

Proyecto desarrollado para la materia **Desarrollo de Software** — UTN FRM.
