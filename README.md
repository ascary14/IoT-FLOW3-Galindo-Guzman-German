# IoT-FLOW3-Galindo-Guzman-German
En este repositorio se subira el flow 3 Creado en IoT

//Este es un mensaje de pub de json para flow 3 mosquitto_pub -h 3.66.119.222 -i ascary142169 -q 2 -t codigoIoT/SIC/flow3/temp -m "{\"ID\":\"German Ascary\",\"Temp\":\"23.4\",\"mnsg\":\"prueba flow 3\"}"

//Para subscribirse 
mosquitto_sub -h 3.66.119.222 -i ascary-14-5134 -t codigoIoT/SIC/flow3/temp

//Encender node red
 node-red

//Ver direccion ip de node
nslookup broker.hivemq.com

//si tienes teclado rgb XD
xset led on