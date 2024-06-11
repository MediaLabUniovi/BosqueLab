Proyecto para deteccion de incendios tanto en exteriores como interiores desarollado por el MediaLab.

Objetivos de este proyecto: 
* Deteccion de gases producidos por el fuego: Carbonos (CO2, CO) Nitrogenos(NOx) Sulfuros (SOx) [MQ135,MQ7,SCD30]
* Deteccion de contaminacion acustica: Sensor (Microfono) para medir decibelios [KY038]
* Deteccion de temperatura y humedad [BME280]
* Deteccion de particulas en suspension PM10 y PM2.5 [SDS011]
  
Enlaces a los sensores que se usan en este proyecto se pueden encontrar en el EXCEL "SENSORES INCENDIOS"

Nota: A la hora de la conexion de los sensores ir probando que funcionan 1 por 1, empezando por el SDS011

ACCESO A TTN: https://eu1.cloud.thethings.network/console/applications/sensor-incendios/devices/incendiolab24/data

ACCESO BALENA: https://dashboard.balena-cloud.com/login

GRAFANA: http://4f566df1fed52c6e7fd5f661f64ae3eb.balena-devices.com:8080/d/LeuF06mRz/sensor-incendios?orgId=1&from=now-3h&to=now

![incendios](https://github.com/MediaLabUniovi/bosquelab/assets/159242374/b6bb0664-3aca-4ea0-b097-660a4a702bfe)
