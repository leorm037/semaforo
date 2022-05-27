# Semáforo (Traffic Light)
Python script to turn on Traffic Light, Raspberry PI 3 or higher, using GPIO pins 16, 20 and 21.

## Screenshots
![Raspberry PI 4](https://user-images.githubusercontent.com/4519186/170693153-67655aa6-c043-45e9-8e8c-f30f0ce55e07.jpg)

![Raspberry PI 3](https://user-images.githubusercontent.com/4519186/170693166-d1042af8-3c23-471f-869e-b5fac9bd960b.jpg)

## Instructions
```
  Enter color and status
    Example:
      semaforo red on
      semaforo red off
      semaforo yellow on
      semaforo yellow off
      semaforo green on
      semaforo green off
      semaforo all on
      semaforo all off
```

## Required
- Python 3
- python3-pigpio
- pigpio
- raspi-gpio

```
sudo apt install raspi-gpio pigpio python3-pigpio python3
```

## Install
```
sudo cp semaforo /usr/local/bin/semaforo
```
