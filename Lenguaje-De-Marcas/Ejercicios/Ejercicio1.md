Ejercicio1
Lenguaje de Marcas
Práctica 2: Gestión colaborativa de
material académico con Git y GitHub
UT4 Optimización y Documentación
Grupos de 2 a 4 personas máximo
Entrega antes del 15/03/2026 23:55h
Objetivos de aprendizaje
El alumnado aprenderá a:
• Utilizar Git como sistema de control de versiones.
• Trabajar de forma colaborativa mediante GitHub.
• Organizar proyectos mediante ramas, issues y pull requests.
• Documentar proyectos software correctamente.
• Visualizar la evolución del trabajo mediante commits.
• Resolver conflictos de fusión.
• Aplicar buenas prácticas profesionales reales.
Organización
• Grupos de mínimo 2 y máximo 4 personas.
• Todos los integrantes deben participar activamente.
• Se deberá poder identificar el trabajo individual.
Descripción de la práctica
Se deberá crear un repositorio que contenga todo el material de clase de:
• Lenguaje de Marcas
• Entornos de Desarrollo
Contenido:
1.- Apuntes de teoría
• Resúmenes propios.
• Esquemas o mapas conceptuales.
2.- Ejercicios
• Actividades realizadas.
• Soluciones documentadas.
3️.- Prácticas
• Código fuente.
• Explicaciones.
4️.- Software necesario
• Listado.
• Enlaces.
• Guía básica de instalación.
5.- Documentación
README con:
• Descripción del proyecto.
• Integrantes.
• Estructura.
• Instrucciones de uso.
Requisitos obligatorios de Git
Commits
• Frecuentes y pequeños.
• Mensajes descriptivos.
• Debe verse la evolución del trabajo.
Ejemplo:
docs: añadidos apuntes tema 1 LM
feat: ejercicios XML completados
fix: corrección errores práctica 2
Ramas
Cada integrante deberá:
• Crear una rama propia.
• Trabajar en ella.
• Fusionarla mediante Pull Request.
Ejemplo:
rama-ana
rama-carlos
rama-maria
Pull Requests
• Crear Pull Request para integrar cambios.
• Revisar el trabajo de compañeros.
• Añadir comentarios.
Issues (gestión de tareas)
El equipo deberá:
• Crear issues para organizar tareas.
• Asignar responsables.
• Marcar tareas completadas.
Archivo .gitignore
Debe incluir archivos innecesarios como:
• Configuración del IDE.
• Temporales.
• Binarios.
Conflicto de fusión
El equipo deberá experimentar al menos un conflicto y resolverlo.
(Se puede provocar modificando el mismo archivo entre dos ramas).
Versión final
Crear una versión etiquetada: v1.0-entrega
Entrega
• Enlace al repositorio.
• Documento breve (1–2 páginas):
• Organización del equipo.
• Problemas encontrados.
• Aprendizaje individual.
Exposición del trabajo
Cada grupo deberá realizar una presentación en clase donde muestre el repositorio y
demuestre el uso correcto de Git y la organización del proyecto.
La presentación tendrá una duración aproximada de 10–15 minutos por grupo.
Durante la exposición el grupo deberá mostrar en directo:
1.- Repositorio en GitHub
• Estructura de carpetas.
• README.
• Contenido de las asignaturas.
• Organización general.
2.- Evidencias de trabajo con Git
Se deberá enseñar:
• Historial de commits.
• Participación de cada integrante.
• Ramas utilizadas.
• Pull Requests realizados.
• Issues creados y cerrados.
El profesorado podrá hacer preguntas sobre cualquier parte del repositorio.
3.- Demostración práctica (pruebas de funcionamiento)
El grupo deberá demostrar:
• Cómo clonar el repositorio.
• Cómo cambiar de rama.
• Cómo ver el historial de commits.
• Cómo crear un commit.
• Cómo subir cambios.
• Cómo ver una Pull Request.
Ejemplo de comandos que pueden mostrar:
git clone
git checkout
git log
git add
git commit
git push
No es necesario que todo el grupo ejecute comandos, pero todos deben saber
explicarlo.
4.- Explicación del trabajo en equipo
Cada integrante deberá explicar:
• Qué parte ha realizado.
• Problemas encontrados.
• Qué ha aprendido sobre Git.
• Dificultades del trabajo en equipo.
Criterios de evaluación de la presentación
Se valorará:
1) Claridad en la explicación
2) Evidencias reales del uso de Git
3) Participación de todos los miembros
4) Demostración práctica correcta
5) Capacidad para responder preguntas
GUÍA PASO A PASO PARA EL ALUMNADO
Paso 1: Crear cuenta en GitHub
1. Acceder a GitHub.
2. Crear cuenta gratuita.
Paso 2: Instalar Git
Comprobar instalación:
git --version
Paso 3: Crear repositorio
1. Crear repositorio en GitHub.
2. Nombre: Repositorio-DAW.
3. Público o privado.
Paso 4: Clonar repositorio
git clone URL_DEL_REPOSITORIO
Paso 5: Configurar usuario
git config --global user.name "Tu Nombre"
git config --global user.email "correo@email.com"
Paso 6: Crear estructura de carpetas
Crear carpetas de asignaturas y contenido.
Paso 7: Primer commit
git add .
git commit -m "estructura inicial del repositorio"
git push
Paso 8: Crear ramas individuales
git checkout -b rama-tu-nombre
Subirla:
git push -u origin rama-tu-nombre
Paso 9: Trabajar con commits
Cada vez que hagas cambios:
git add .
git commit -m "mensaje descriptivo"
git push
Paso 10: Crear Issues
En GitHub:
• Crear tareas.
• Asignarlas.
• Cerrarlas al terminar.
Paso 11: Pull Request
Cuando termines:
1. Crear Pull Request.
2. Otro compañero revisa.
3. Aceptar cambios.
Paso 12: Resolver conflictos (si aparecen)
Git indicará archivos en conflicto.
Editar → guardar → commit.
Paso 13: Versión final
git tag v1.0-entrega
git push –tags
RÚBRICA DE EVALUACIÓN
Competencias que se trabajan
• Control de versiones.
• Trabajo colaborativo.
• Organización de proyectos.
• Documentación técnica.
• Metodologías profesionales reales.
Opcional (para subir nota)
• Uso de Wiki.
• Uso de GitHub Projects.
• Automatización básica.
• Buen diseño del README.
Resultado esperado
Al finalizar, el alumnado habrá trabajado con Git de una forma muy similar a un entorno
profesional real.
Criterio Excelente (10–9) Puntos
Muy organizado y completo Correcto Básico Desordenado 2
Uso de commits Frecuentes y claros Adecuados Pocos Incorrectos 2
Uso de ramas Correcto y completo Adecuado Básico Incorrecto 2
Completo y colaborativo Correcto Básico No usado 1
Muy bien gestionado Correcto Básico No usado 1
Documentación Excelente README Correcto Básico Deficiente 1
Equilibrado Aceptable Desigual Individual 0,5
Correcta Parcial Básica No realizada 0,5
Notable
(8–7)
Aprobado
(6–5)
Insuficiente
(<5)
Repositorio y
estructura
Pull Requests y
revisión
Issues y
organización
Trabajo en
equipo
Resolución de
conflictos
