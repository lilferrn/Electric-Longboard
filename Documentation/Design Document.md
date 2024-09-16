**Design Document**

**Major Moving Parts of Your Design**

* **Motors**: Dual 1000W hub motors located in the rear wheels.  
* **Battery Pack**: A 10,000mAh lithium-ion battery.  
* **Wheels**: 85mm wheels with a soft polyurethane coating for smooth rides.  
* **Deck**: A flexible 7-layer bamboo and carbon fiber deck.  
* **Braking System**: Regenerative braking that feeds energy back into the battery.

**Sections / Block Diagram** Create a block diagram showing the main sections of your system:

* **Power Supply**: Battery, Charger  
* **Motor Controllers**: Electronic Speed Controller (ESC) connected to the motors  
* **User Interface**: Bluetooth connection to mobile app, remote control  
* **Braking System**: Integrated into the motor control  
* **Sensors**: Speed sensor, battery level sensor

**Priorities and Dependencies**

* **Priority 1**: Power supply design (battery capacity, charging system).  
  * Dependency: The motors depend on an adequate power supply.  
* **Priority 2**: Motor control (ESC selection and configuration).  
  * Dependency: Motor control is linked to the battery and throttle input.  
* **Priority 3**: User interface design (app integration, remote).  
  * Dependency: UI depends on the motor and ESC functioning properly.  
* **Priority 4**: Braking system integration (regenerative braking).  
  * Dependency: Depends on the motor control system being operational.

**Design Approaches for Major Moving Parts**

* **Motors**: Select hub motors for a compact, efficient design without belts.  
* **Battery**: Lithium-ion, offering long ride times with quick charging.  
* **Wheels**: Soft wheels for grip on urban terrain, improving rider comfort.  
* **Braking**: Regenerative braking system that reduces energy waste.  
* **User Interface**: Use Bluetooth for easy app-based speed control and diagnostics.

**Major Component Selection**

* **Motors**: Dual 1000W hub motors.  
* **Battery**: 10,000mAh lithium-ion pack.  
* **ESC**: Choose a VESC-compatible controller for maximum customization.
* **Wheels**: 85mm polyurethane wheels.  
* **Bluetooth Module**: Low-energy Bluetooth 5.0 module.
