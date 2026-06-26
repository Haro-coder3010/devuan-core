# Devuan Core

Un sistema base Devuan Excalibur desplegado utilizando OpenRC, diseñado para ser mínimo, reproducible, auditable y endurecido. Este proyecto elimina por completo las dependencias de systemd para reducir la superficie de ataque y mitigar riesgos de ciberseguridad o escaladas de malware.

> ### 📝 Nota del Autor
> No soy un programador profesional; soy un entusiasta de la programación y del mundillo de las distribuciones Linux. Me encanta la investigación y la experimentación en hardware antiguo, utilizando mi propia computadora como laboratorio. 

> Mi investigación y mis pruebas están orientadas a la educación y el aprendizaje. Posiblemente mi nivel actual no sea el suficiente para llevar este proyecto más allá por mí mismo, pero con el apoyo de las nuevas tecnologías (IA), la documentación y las investigaciones existentes, lograré mi objetivo de aprendizaje. ¡Toda crítica y guía es bienvenida!


## 🎯 Filosofía del Proyecto
Devuan es una distribución de Linux basada en Debian sin systemd; una base sólida y libre sobre la cual trabajar. El objetivo es brindar:

* **Para el usuario común:** Una estación de trabajo funcional, estable y segura. Un sistema compatible con la mayoría del software libre usando la librería `glibc` y el gestor `apt` purgado de la forma más limpia posible, donde no tenga que aprender a levantar un firmware o verificar logs para saber que su red, su kernel y sus datos están seguros.
* **Para el usuario avanzado:** El lienzo perfecto y la libertad de tener a su disposición un init perfectamente auditable y controlable, permitiendo hardenizar aún más un estándar de seguridad que ya es muy superior al que ofrecen otras distribuciones.

## 🔬 Bitácora de Experimentos y Laboratorios
Aquí iré subiendo el control de mis prácticas:
* **[DevuanCore1.0](./DevuanCore1.0):** Primer intento de instalar por debootstrap DevuanCore Minimal. 
* **[Log de Errores](./Log-de-Errores):** Historial de errores, recopilación de errores del DevuanCore1.0
* **[Resultado](./Esqueleto):** Esqueleto, log de los comandos, códigos y configuraciones que sí funcionaron.
* **[DevuanCore2.0](./DevuanCore2.0) :** Guía técnica a seguir resultado del analisis y corrección de errores de la DevuanCore 1.0.
* **[DevuanCore2.0(documentación)](./DevuanCore2.0(documentacion)** Documentación de la DevuanCore2.0 y sus resultados.


## 💬 Contribuciones y Críticas
Este repositorio es público para que cualquiera pueda revisar la documentación, auditar las configuraciones, proponer mejoras o criticar constructivamente los experimentos. ¡Toda retroalimentación es bienvenida!
