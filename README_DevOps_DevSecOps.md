#  Introducción a DevOps y DevSecOps

¿Alguna vez te has preguntado cómo las grandes empresas lanzan software rápido, sin errores y manteniendo la seguridad? La respuesta está en dos prácticas clave: **DevOps** y **DevSecOps**. En esta guía, aprenderás de forma sencilla qué son, cómo funcionan y por qué son tan importantes, ¡aunque no tengas conocimientos técnicos previos!

---

##  ¿Qué es DevOps?

**DevOps** es una metodología que une a los equipos de desarrollo (Dev) y operaciones (Ops) con un objetivo común: **entregar software de forma rápida, continua y confiable**.

###  Objetivo principal
- Automatizar procesos.
- Mejorar la colaboración entre equipos.
- Entregar valor continuo al usuario final.

###  Ciclo de vida DevOps

1. **Planificación**: definir qué se va a construir.
2. **Desarrollo**: escribir el código.
3. **Integración continua (CI)**: integrar cambios frecuentemente.
4. **Entrega continua (CD)**: desplegar el software automáticamente.
5. **Monitoreo y operación**: asegurar que todo funcione correctamente.

![Diagrama DevOps](images/DevOps.png)

---

##  ¿Qué es DevSecOps?

**DevSecOps** es una evolución de DevOps que incorpora la **seguridad desde el inicio** del ciclo de vida del software.

###  ¿Qué agrega DevSecOps?

- Seguridad integrada en todas las etapas.
- Evaluación de riesgos desde el diseño.
- Automatización de pruebas de seguridad.

###  Fases adicionales del ciclo DevSecOps

1. **Evaluación de riesgos**
2. **Pruebas de seguridad (automatizadas y manuales)**
3. **Monitoreo de vulnerabilidades**
4. **Respuesta ante incidentes**

![Diagrama DevSecOps](images/DevSecOps.webp)

---

##  DevOps vs DevSecOps

| Característica           | DevOps                         | DevSecOps                          |
|--------------------------|--------------------------------|------------------------------------|
| Enfoque principal        | Entrega rápida y continua      | Entrega rápida y segura            |
| Seguridad                | Se considera al final          | Se incorpora desde el inicio       |
| Automatización           | CI/CD                          | CI/CD + pruebas de seguridad       |
| Herramientas             | Jenkins, Docker, Git           | Jenkins, Docker, Git, SAST, DAST   |
| Cultura                  | Colaboración Dev + Ops         | Colaboración Dev + Ops + Sec       |
