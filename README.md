
# SI4IoT: Integration Methodology for IoT Systems
Visit the official project page for more details: [SI4IoT Project Page](https://acg.ual.es/repo/si4iot/).

## Description
`SI4IoT` (Service Integration for IoT) is a development environment that allows the graphical modeling of IoT systems using a Model-Driven Engineering (MDE) methodology. It provides an editor where users can design and integrate IoT systems, both software and hardware, and generate executable code automatically for various platforms. This approach helps developers focus on the application’s business logic without dealing with the complexity of underlying technologies. The tool is part of the [Applied Computing Group](https://acg.ual.es/).

## Project Structure
The project is structured into three main layers:

1. **Physical Layer**: Models the hardware components, such as sensors and actuators.
   - **Infrastructure Sublevel**: Specifies network characteristics and device connectivity.
   - **Hardware Sublevel**: Defines sensors, actuators, and controllers.

2. **Logical Layer**: Specifies control logic and communication between devices.
   - **Control Sublevel**: Includes logic for REST services and event management.
   - **Interaction Sublevel**: Manages communication between Physical and Application layers.

3. **Application Layer**: Offers user interfaces for system interaction.
   - **DTV Level**: Models the interface for digital television.
   - **Mobile Level**: Defines interfaces for mobile devices.

## Key Features
- **Graphical Modeling**: Enables graphical definition of IoT systems through a custom DSL.
- **M2T Transformations**: Automates code generation from models using Acceleo.
- **Platform Integration**: Supports multiple platforms such as Arduino, Node-Red, Android, and Ballerina.
- **Multiplatform Code Generation**: Generates code for sensors, REST services, and mobile interfaces.
- **Extensive Documentation**: Provides detailed guidance for users.

## Installation
1. Download and install **Eclipse IDE** with the following plugins:
   - **EMF (Eclipse Modeling Framework)** for metamodel management.
   - **Sirius** for graphical model visualization.
   - **Acceleo** for M2T transformations.
2. Clone this repository:
```bash
git clone https://github.com/acgtic211/si4iot
```
3. Import the project into Eclipse (`File` -> `Import` -> `Existing Projects into Workspace`).
4. Open the `.aird` file for the Sirius editor and start defining the project models.

## Related Articles
- **"A DSL for the Development of Heterogeneous Applications"**: [DOI: 10.1109/FiCloudW.2017.108](https://doi.org/10.1109/FiCloudW.2017.108)
- **"A Cross-Device Architecture for Modelling Authentication Features in IoT Applications"**: [DOI: 10.3217/jucs-024-12-1758](https://doi.org/10.3217/jucs-024-12-1758)
- **"IoTV: Merging DTV and MDE Technologies on the Internet of Things"**: [DOI: 10.1007/978-3-030-11890-7-25](https://doi.org/10.1007/978-3-030-11890-7-25)

## Video Demonstrations
- [System Setup Video](https://www.youtube.com/watch?v=_KkkUdqSMsU)
- [Installation Tutorial](https://www.youtube.com/watch?v=MoC2mjMp_Aw)
- [Tool Tutorial](https://www.youtube.com/watch?v=3VVa3Ib7ZLE)

For more information, visit the official [SI4IoT Project Page](https://acg.ual.es/repo/si4iot/).

## License
Distributed under the MIT License. See `LICENSE` for more information.
