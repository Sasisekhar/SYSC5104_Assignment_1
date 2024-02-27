# Assignment 1

## Repository structure
This repository has 3 folders. The Comms_Top_Example contains the first model whose simulation outputs are shown in the report (Table 3.1).
The Traffic_Light_rx and Traffic_Light_tx folders contain the models to be implemented on the 2 microcontrollers.

The assignment report was written using LateX. The source code is available in Sasisekhar_DEVS_Assignment1.zip, and Sasisekhar_DEVS_Assignment1.pdf in the report itself.

## Running the Simulation

```
cd Comms_Top_Example
make all
```

## Executing the model

The makefiles have been configured to flash an ESP32S3 microcontroller. Kindly ensure that you have installed ESP-IDF per the instructions provided [here](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/)

After following the steps to install ESP-IDF, run the following command to flash the devices:
```
make setup && make embedded
```
