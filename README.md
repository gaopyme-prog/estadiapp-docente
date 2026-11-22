# EstadiApp – Docente

**Abrir la aplicación:** https://gaopyme-prog.github.io/estadiapp-docente/

## ¿Qué es?
Una aplicación web para **recoger datos en campo y analizarlos estadísticamente**, construida para el proyecto de aula de **Estadística (840601)** del programa de Ingeniería de Producción, 5.º semestre, UNIPAZ, 2026. El caso de estudio es el **consumo de agua en los dispensadores del edificio de aulas** de UNIPAZ.

## ¿Para qué sirve? (finalidad)
Que el estudiante viva el ciclo completo de una investigación estadística en un problema real de su institución: **recolectar → organizar → analizar → interpretar → recomendar**. La versión "Docente" sirve como modelo de referencia para que los estudiantes construyan y comparen la suya, y para entregar a la dependencia encargada un informe con recomendaciones sobre la reposición de botellones.

**Dirigido a:** docentes y estudiantes de estadística; el esquema se puede adaptar a otros estudios (asistencia, residuos, uso de espacios, encuestas).

## Funciones (cuatro pestañas)
1. **Registrar:** formulario de recolección por piso y dispensador: fecha, horas de observación, jornada, capacidad del botellón, niveles inicial y final, botellones reemplazados, agua remanente, estado del dispensador y usuarios estimados. Calcula automáticamente el **consumo estimado** con la fórmula:
   *Consumo = nivel inicial + (botellones reemplazados × capacidad) − nivel final − agua remanente retirada.*
   Incluye resumen, base de datos de registros y **exportación a Excel (CSV)**.
2. **Análisis:** elige una variable cuantitativa o cualitativa (con filtro opcional por categoría, por ejemplo solo la jornada de la mañana) y obtiene medidas estadísticas, tabla de frecuencias y gráficos.
3. **Probabilidad:** define eventos A y B para calcular probabilidades simples, conjuntas y condicionales, y genera **tablas de contingencia** entre variables cualitativas.
4. **Informe:** ficha técnica (objetivo, población, tipo de muestreo censal, tamaño de muestra), variables del estudio, resultados de todas las variables, y espacios para interpretación, conclusiones y recomendaciones. Se **imprime o guarda en PDF**.

## ¿Cómo se usa?
1. Abra el enlace (funciona en computador y en celular, útil para registrar en el sitio).
2. En **Registrar**, diligencie una observación por dispensador y pulse **Guardar registro**. Repita durante el periodo de estudio.
3. En **Análisis** y **Probabilidad**, elija variables y pulse calcular.
4. En **Informe**, escriba la interpretación, conclusiones y recomendaciones, y pulse **Imprimir / Guardar PDF**.
5. Use **Exportar datos a Excel (CSV)** para respaldar la base de datos.

## Datos y privacidad
Los registros se guardan en el **almacenamiento del navegador** del equipo donde se diligencian; no se envían a ningún servidor. Exporte el CSV periódicamente como copia de seguridad y para unir los datos de varios equipos.

## Archivos del repositorio
- `index.html`: toda la aplicación en un solo archivo.

## Créditos
Proyecto de Aula · Estadística · Ingeniería de Producción · UNIPAZ, 2026.
Docente: **Omar Guerrero Avilés** (omar.guerreroav@unipaz.edu.co). Desarrollado con apoyo de inteligencia artificial.
