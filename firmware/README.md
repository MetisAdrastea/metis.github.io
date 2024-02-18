Esta carpeta es una prueba para alojar firmwares precompilados, para que un ESP32 pueda venir a buscarlos y auto actualizarse.
La idea es que el ESP32 vaya a buscar el fichero "version.md" que contiene UNICAMENTE el número de versión y, si es superior a la versión de firmware que tiene instalada, se descargue e instale automáticamente el fichero firmware.bin
