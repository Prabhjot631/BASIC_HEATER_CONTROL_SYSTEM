# BASIC_HEATER_CONTROL_SYSTEM

WOKWI SIMULATION:   https://wokwi.com/projects/438007957425787905

The Arduino code performs the following key tasks:

- **Initializes** the DHT22 sensor and required pins (LED, relay, buzzer).
- **Reads temperature** from the DHT22 sensor using the DHT library.
- **Compares temperature** with a user-defined threshold.
  - If the temperature is below the threshold:
    - Turns ON the LED and relay (activates heater).
  - If the temperature exceeds the overheat limit:
    - Activates the buzzer (overheat warning).
- **Loop** function continuously monitors and updates the system state.
