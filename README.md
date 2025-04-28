# Práctica Final DevOps: CI/CD + GitHub Pages (Apache)

Este proyecto demuestra:

- Página web simple en HTML
- Prueba unitaria usando Jest
- Servidor web local con Docker y Apache
- Automatización de pruebas con GitHub Actions
- Publicación en GitHub Pages

## Comandos principales

```bash
npm install
npm test
docker build -t practica-devops-apache .
docker run -d -p 8080:80 practica-devops-apache
```
