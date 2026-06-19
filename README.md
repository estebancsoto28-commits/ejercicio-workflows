# Landing Page Política - Integración Continua

[![CI Landing Page Politica](https://github.com/TU_USUARIO/TU_REPOSITORIO/actions/workflows/ci.yml/badge.svg)](https://github.com/TU_USUARIO/TU_REPOSITORIO/actions)

## 📝 Documentación Técnica del Workflow
Este repositorio utiliza **GitHub Actions** para ejecutar un flujo de integración continua (`ci.yml`). Cada vez que se realiza un `push` o un `pull_request` hacia la rama `main`, un entorno virtual automatizado (Ubuntu) verifica que el proyecto mantenga la estructura limpia obligatoria: `index.html`, `css/style.css`, `js/script.js` y `README.md`.

---

## 🧠 Reflexión Final
1. **¿Qué beneficios aporta la Integración Continua?**  
   Permite detectar errores de forma temprana antes de desplegar a producción, asegura que el código de todos los desarrolladores mantenga un estándar de calidad y automatiza tareas repetitivas.
   
2. **¿Qué errores detecta GitHub Actions?**  
   Falta de archivos obligatorios, errores de sintaxis, fallas en pruebas unitarias y problemas de compilación o dependencias rotas.
   
3. **¿Por qué automatizar validaciones?**  
   Porque elimina el error humano. Garantiza de forma estricta que ningún código defectuoso o incompleto se integre a la rama principal.
   
4. **¿Cómo mejorarías el workflow?**  
   Implementando validaciones de código (Linters como ESLint o Stylelint) para asegurar buenas prácticas de escritura, minimizando las imágenes automáticamente o agregando pruebas de accesibilidad web.