# Análisis de tiempos de pago

**Proyecto final de Ciencia de Datos**  
**Estudiante:** Sergio Morales  
**Video:** https://drive.google.com/file/d/1nANemakyWt-yIAFxCLHUwmIBwpjG6JHi/view?usp=drive_link

## ¿De qué trata?

Escogí este tema porque trabajo con procesos de pagos y quería hacer el proyecto sobre algo que me resultara familiar. La idea fue revisar si los lotes con más operaciones tardan más tiempo en procesarse.

Para el ejercicio usé datos simulados. No hay información real de bancos ni de clientes.

## ¿Qué hice?

Empecé con 123 registros. Revisé si había datos repetidos, vacíos o tiempos incorrectos y, después de la limpieza, quedaron 120.

Luego calculé algunas estadísticas básicas e hice gráficos para comparar los tiempos. El promedio de procesamiento fue de unos 63,8 minutos.

Por último, probé una regresión lineal usando la cantidad de operaciones para estimar el tiempo. Para un lote de 100 operaciones, el resultado fue cercano a 56,8 minutos, con un error promedio de 7,8 minutos en los datos de prueba.

## ¿Qué aprendí?

En esta base, los lotes con más operaciones generalmente tardan más. También vi que es importante revisar la información antes de sacar conclusiones y que un modelo puede servir para tener una estimación, aunque no siempre acierte.

## Archivos

- `datos/`: archivo CSV utilizado.
- `notebook/`: análisis hecho en Google Colab.
- `graficos/`: gráficos del ejercicio.
- `presentacion/`: diapositivas de apoyo.
- `video/`: material de la presentación y enlace al video.

## Para revisar el análisis

El cuaderno está en la carpeta notebook y los datos están en pagos_siulados.csv.
