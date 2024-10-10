# UML Diagram
# Wind Turbine Class

This project implements a `WindTurbine` class in C++ based on the provided UML diagram. The `WindTurbine` class models the properties and behavior of a wind turbine, including its model, blade length, power output, rotor speed, and methods to calculate energy generation and display details.

## UML Diagram


```plantuml
@startuml
class WindTurbine {
    - model: string
    - bladeLength: double
    - powerOutput: double
    - rotorSpeed: double

    + getModel(): string
    + setModel(string): void
    + getBladeLength(): double
    + setBladeLength(double): void
    + getPowerOutput(): double
    + setPowerOutput(double): void
    + getRotorSpeed(): double
    + setRotorSpeed(double): void
    + calculateEnergyGenerated(hours: double, windSpeed: double): double
    + printDetails(): void
}
@enduml
