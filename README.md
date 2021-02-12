# Pictionary
En este proyecto, vamos a implementar una red neuronal recurrente para la clasificación de dibujos (representados como trazos almacenados con coordenadas X e Y) del juego Pictionary.
Para importar los atchivos npz que representan los dibujos para cada categoría se pueden importar desde un terminal utilizando la siguiente instrucción:

gtsutil -m cp -r 'gs://quickdraw_dtaset/sketchrnn/*.npz' <<Fichero destino>>
