# SI4IoT User Manual

## Introduction
`SI4IoT` (Service Integration for IoT) is a graphical development environment designed to integrate heterogeneous IoT systems using a **Model-Driven Engineering (MDE)** methodology. This manual provides detailed steps to set up, model, and generate code for IoT systems using SI4IoT.

## Prerequisites
Before starting, ensure the following tools are installed:

1. **Eclipse IDE**: Download and install **Eclipse IDE for Java and DSL Developers**.
2. **Java Development Kit (JDK)**: Install JDK 8 or a compatible version.
3. **Git**: Install Git for version control.
4. **Required Eclipse Plugins**:
   - **EMF (Eclipse Modeling Framework)**: For metamodel and model creation.
   - **Sirius**: To create graphical editors for the DSL models.
   - **Acceleo**: For code generation using Model-to-Text transformations (M2T).

### Video Tutorials
Refer to the following tutorials for a detailed guide:
- [System Setup Video](https://www.youtube.com/watch?v=_KkkUdqSMsU)
- [Installation Tutorial](https://www.youtube.com/watch?v=MoC2mjMp_Aw)
- [Tool Example Tutorial](https://www.youtube.com/watch?v=3VVa3Ib7ZLE)

## Installation Steps
1. **Install the Required Plugins**:
   - Open Eclipse IDE.
   - Navigate to `Help` > `Eclipse Marketplace`.
   - Search for **EMF**, **Sirius**, and **Acceleo**, and install each plugin.
   - Restart Eclipse when prompted.

2. **Clone the SI4IoT Repository**:
   - Open a terminal or Eclipse Git interface.
   - Run:
     ```bash
     git clone https://github.com/acgtic211/si4iot
     ```
   - Or use `File` > `Import` > `Git` to import into Eclipse.

3. **Import the Project into Eclipse**:
   - Go to `File` > `Import`.
   - Choose `Existing Projects into Workspace`.
   - Select the repository directory and import the project.

4. **Launch the Sirius Editor**:
   - Open the `.aird` file within the project structure.
   - Start modeling the Physical, Logical, and Application layers using the graphical editor.

## Modeling a New IoT System
### Step-by-Step Guide
1. **Physical Layer**:
   - Model the hardware components: sensors, actuators, and controllers.
   - Specify the connectivity and communication protocols.

2. **Logical Layer**:
   - Define the control logic for each device.
   - Implement rules for data processing and decision-making.

3. **Application Layer**:
   - Model the user interfaces for DTV, mobile, and web applications.
   - Ensure proper integration with the logical and physical layers.

## Code Generation and Deployment
1. **Run Acceleo Code Generation**:
   - Right-click on the `.mtl` files and select `Run As` > `Acceleo Application`.
   - Choose the input models and output directory.

2. **Compile the Generated Code**:
   - For Arduino, use the Arduino IDE to upload the `.ino` files.
   - For Android, import the generated code in Android Studio.

3. **Deploy the Solution**:
   - Deploy on target IoT devices and test system functionalities.

## Troubleshooting
### Common Issues:
1. **Plugin Installation Issues**:
   - Verify that all necessary plugins are correctly installed.

2. **Code Generation Errors**:
   - Ensure the models are consistent and correctly linked.

3. **Deployment Problems**:
   - Confirm network configurations and device connectivity.

With this guide and the linked tutorials, you should be able to successfully model, generate, and deploy IoT systems using the SI4IoT environment.
