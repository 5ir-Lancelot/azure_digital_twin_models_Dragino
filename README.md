# azure_digital_twin_models_Dragino
Here I post the digital twin model from Dragino Soil pH Sensor (LSPH01) and Dragino Soil Conductivity model (LSE01) 

In Azure Iot Central you can upload these .json models written in The Digital Twins Definition Language (DTDL).
https://learn.microsoft.com/en-us/azure/digital-twins/concepts-models

It tells the application how to deal with the incoming telemetry. The goal is to pick just the variables of interest out of the telememtry .json message that is send.
Nobody wants to have all the metadata. The important variables are then correctly taken out and can be displayed with the dashboards and data explorer in Azure IoT Central.

The files give you a starting point for the model. You can rename variables according to your needs.
I highly recommend publishing the template and then check the raw data from one testing device and click 'Add capabilites automatically'. That will make your life much easier.
This will take the important variables out of your incoming raw telemetry message.

some keywords : Dragino Sensors, Microsoft Azure IoT Central, Dragino Digital Twin Models,  
