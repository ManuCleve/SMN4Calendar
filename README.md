# SMN4Calendar

El objetivo es poder visualizar el pronóstico de distintas maneras en google calendar utilizando la fuente más confiable que existe en la Argentina: El Glorioso Servicio Meteorológico Nacional.

- El primer paso será estudiar la [API del SMN](https://github.com/gastonpereyra/smnQL/tree/master/docs/api)
- El segundo paso, hacer lo propio con la [API de Google Calendar](https://developers.google.com/calendar/api/guides/overview)
- Luego redactaremos el script que creará y actualizará los pronósticos en un calendar.
- Deberemos también construir un archivo de configuración donde se almacenará la ciudad de donde se quieren conocer los datos, el tipo de pronóstico que se quiere conocer (diario, extendido, otro) y la cantidad de datos que se quieren conocer (viento, clima, humedad, etc).
