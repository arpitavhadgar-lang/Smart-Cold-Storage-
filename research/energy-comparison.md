# Energy Comparison

## Objective

The objective of the proposed energy-management approach is to reduce
unnecessary operation of the active cooling system and make better use
of available solar energy.

## Conventional Approach

In a conventional refrigeration-based system, active cooling is the
primary method used to remove heat from the storage chamber.

The refrigeration load can vary depending on factors such as ambient
conditions, the temperature of incoming produce, the desired storage
temperature and the characteristics of the storage facility.

## Proposed Approach

The proposed system uses a combination of:

- Thermal insulation
- Passive cooling
- Solar PV generation
- MPPT charge control
- Battery storage
- ESP32-based monitoring
- Temperature-based active cooling

The active cooling system is activated only when the measured
temperature exceeds the defined control threshold.

This approach can reduce unnecessary cooling operation and allow the
available battery energy to be used more efficiently.

## Energy Flow

Solar PV
→ MPPT Charge Controller
→ Battery
→ DC Loads / Cooling System
→ ESP32 Monitoring & Control

## Energy-Management Principle

The proposed control strategy follows:

**Passive Cooling First → Monitor Temperature → Activate Cooling Only
When Required → Stop Cooling When the Required Condition is Restored**

## Expected Benefits

The proposed energy-management strategy is intended to:

- Reduce unnecessary active cooling operation
- Improve utilization of solar-generated energy
- Extend useful battery operation
- Reduce dependence on grid electricity
- Support decentralized cold-storage operation

## Important Note

Actual energy savings depend on the final chamber size, insulation,
ambient temperature, quantity and temperature of incoming produce,
cooling-system efficiency, solar capacity, battery capacity and
operating conditions.

Therefore, percentage energy savings should only be reported after
experimental testing and measurement.
