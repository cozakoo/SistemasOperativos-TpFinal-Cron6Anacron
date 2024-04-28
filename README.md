# Cron y Anacron para tareas programadas en Linux


Cron y Anacron son herramientas utilizadas en sistemas operativos Linux para la ejecución programada de tareas, permitiendo automatizar acciones de forma síncrona y asíncrona respectivamente. Ambas herramientas son fundamentales en la administración de sistemas Linux y se encuentran disponibles por defecto en la mayoría de las distribuciones GNU/Linux.

Si bien Cron y Anacron permiten agendar tareas, su funcionamiento no es igual y en lugar de ser productos alternativos, son necesariamente complementarios.

## Cron
Cron es un sistema de programación de tareas que permite ejecutar comandos de forma periódica en el sistema. Funciona mediante la configuración de archivos especiales llamados crontabs, que contienen las instrucciones para ejecutar tareas en momentos específicos. Las tareas pueden ser programas, scripts o comandos simples.

## Anacron
Anacron es una herramienta similar a Cron pero diseñada para ejecutar tareas programadas de forma asíncrona en sistemas Linux. Está especialmente diseñada para sistemas que no están siempre encendidos, como computadoras portátiles o servidores que se apagan regularmente.

## Ejemplos prácticos
Para mostrar el funcionamiento de Cron y Anacron, se proporcionan ejemplos prácticos en forma de scripts en bash que pueden ser agendados como tareas programadas. Estos ejemplos demostrarán cómo configurar y ejecutar tareas utilizando ambas herramientas.