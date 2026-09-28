# Working Methodology

The Climate-Adaptive Solar Smart Mini Cold Storage operates by
maintaining suitable temperature and humidity conditions inside an
insulated storage chamber while minimizing energy consumption.

The system follows a smart control approach in which passive cooling
and thermal insulation are utilized first, and active cooling is
activated only when the internal temperature exceeds the defined
threshold.

## Working Process

### 1. Solar Power Generation

Solar PV panels generate electrical energy from sunlight. The generated
power is supplied to the MPPT charge controller for efficient charging
of the battery.

### 2. Battery Storage

The battery stores the solar energy and provides a continuous power
source for the system during periods of low sunlight or at night.

### 3. Environmental Sensing

Temperature and humidity sensors continuously monitor the conditions
inside the storage chamber. The system can also monitor external
temperature and other operating parameters.

### 4. ESP32-Based Monitoring and Control

The ESP32 receives the sensor data and compares the measured
temperature with the predefined temperature threshold.

The controller determines whether active cooling is required based on
the current storage conditions.

### 5. Passive Cooling and Insulation

The insulated chamber minimizes heat transfer from the surrounding
environment. Passive cooling is utilized as the first stage of
temperature management to reduce the requirement for active cooling.

### 6. Active Cooling

When the internal temperature rises above the defined threshold, the
ESP32 activates the energy-efficient DC cooling system.

When the required temperature condition is restored, the cooling
system is switched off to avoid unnecessary energy consumption.

### 7. Temperature and Humidity Regulation

The system continuously monitors temperature and humidity to maintain
suitable storage conditions for the stored vegetables.

Different compartments can be used for vegetables having different
storage requirements.

### 8. Continuous Monitoring

The sensing and control process operates continuously. Sensor readings
are monitored by the ESP32, allowing the system to respond to changes
in the storage environment.

### 9. Protection and Alerts

If the storage temperature remains above the predefined safe limit for
a specified duration, the system can generate an alert to indicate
abnormal storage conditions.

## Overall Working Flow

Solar Panel
→ MPPT Charge Controller
→ Battery
→ ESP32 & Sensors
→ Temperature/Humidity Monitoring
→ Passive
