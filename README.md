# Power Management Tool

In the era of 5G and edge computing, the proliferation of devices across diverse locations has led to a notable increase in power consumption. This surge underscores the critical need for corporations and governments globally to implement strategies aimed at achieving net-zero power consumption. With escalating electricity prices, managing and understanding total power consumption has become increasingly vital for both economic and environmental reasons.

## Project Objectives

This project seeks to tackle the challenges associated with power management by focusing on the following goals:

1. **Research Open-Source Tools**: Identify and assess available open-source tools for precise power measurement.
2. **Document System Knobs**: Catalog the various configurable parameters within a system that influence power consumption metrics.
3. **Telemetry Data Collection**: Collect telemetry data from essential components such as the CPU, memory, Network Interface Card (NIC), and Thermal Design Power (TDP).
4. **Power Utilization Measurement**: Measure and record system power utilization, particularly focusing on CPU, NIC, and TDP based on varying system utilization percentages.

## Team Member

Sreevankumar R

## College Mentor

Dr. Chitra

## Key Features

- **CPU Metrics Monitoring**: Provides real-time monitoring of CPU utilization, including usage percentages for each core. It also visualizes C-states, representing different CPU idle modes, to help identify energy-saving opportunities.
- **Memory Usage Insights**: Tracks system RAM usage, comparing memory in use versus available memory. This assists in identifying memory-intensive applications and potential bottlenecks, along with monitoring disk usage statistics.
- **Temperature and Power Mode Switching**: Continuously monitors temperatures of critical components (CPU, GPU, etc.) to ensure safe operation. Users can switch between various power modes (performance, balanced, power-saving) to optimize power consumption based on current needs.
- **Battery and NIC Power Consumption**: Provides detailed battery statistics (percentage, time remaining, power state) for better battery management. Also monitors NIC power consumption to understand the energy impact of network activities.
- **GPU Metrics Tracking**: Tracks GPU metrics such as power consumption, supply voltage, and temperature, offering insights into the power efficiency of graphics-related tasks.

## Docker Integration

Using Docker for containerization ensures a consistent and portable environment for running the Python GUI application, mitigating dependency issues and easing deployment across different systems.

### Steps to Use Docker

1. **Create a Dockerfile**: This file outlines the environment needed for your application.
2. **Build the Docker Image**: Use the Dockerfile to create an image that contains your application and its dependencies.
3. **Run the Container**: Start a container from your image, specifying parameters like CPU loading percentage and test duration.

## Installation Steps

1. **Install System Dependencies**:
   - Download the `install_dependencies.sh` script from the repository and run the following commands in your terminal:
     ```bash
     chmod +x install_dependencies.sh
     ./install_dependencies.sh
     ```

2. **Install Docker**:
   - Download the `Step1-install_docker.sh` script and execute:
     ```bash
     chmod +x Step1-install_docker.sh
     ./Step1-install_docker.sh
     ```

3. **Create Dockerfile**:
   - Create a Dockerfile with:
     ```bash
     vi Dockerfile
     ```
   - Copy the contents from `Step2-Create Dockerfile` into your new Dockerfile.

4. **Download Application Code**:
   - Access the `GUI_code` folder in the repository, download the files, and run the application.

## Tools Utilized

The Power Management Tool incorporates several powerful libraries and tools to provide accurate real-time data through intuitive visualizations:

- **psutil**: A cross-platform library for retrieving information on running processes and system utilization metrics, including CPU, memory, and disk.
- **tkinter**: Python's standard GUI toolkit, providing components for interactive applications.
- **turbostat**: A command-line tool reporting processor frequency and power statistics, offering insights into CPU performance.
- **Docker**: A platform for developing and deploying applications in isolated containers, ensuring consistency across different environments.
- **matplotlib**: A versatile plotting library for creating various visualizations, from static graphs to interactive charts.
- **lm-sensors**: A suite of tools for monitoring hardware sensor data, useful for temperature and fan speed monitoring.
- **upower**: A daemon providing information about power devices and managing power-related operations.

## Conclusion

The Power Management Tool is designed to equip users with real-time insights into system performance and energy consumption. By leveraging detailed monitoring capabilities, users can optimize their systems for greater efficiency and sustainability. This tool not only helps individual users manage power consumption but also supports broader eco-friendly computing practices.

Explore the repository for more detailed information and usage instructions, and start optimizing your system today!
# Power Management Tool

In the era of 5G and edge computing, the proliferation of devices across diverse locations has led to a notable increase in power consumption. This surge underscores the critical need for corporations and governments globally to implement strategies aimed at achieving net-zero power consumption. With escalating electricity prices, managing and understanding total power consumption has become increasingly vital for both economic and environmental reasons.

## Project Objectives

This project seeks to tackle the challenges associated with power management by focusing on the following goals:

1. **Research Open-Source Tools**: Identify and assess available open-source tools for precise power measurement.
2. **Document System Knobs**: Catalog the various configurable parameters within a system that influence power consumption metrics.
3. **Telemetry Data Collection**: Collect telemetry data from essential components such as the CPU, memory, Network Interface Card (NIC), and Thermal Design Power (TDP).
4. **Power Utilization Measurement**: Measure and record system power utilization, particularly focusing on CPU, NIC, and TDP based on varying system utilization percentages.

## Team Member

Sreevankumar R

## College Mentor

Dr. Chitra

## Demonstration

For a practical overview of the tool's functionality, watch the demonstration screencast here: [Watch the Screencast](#).

## Key Features

- **CPU Metrics Monitoring**: Provides real-time monitoring of CPU utilization, including usage percentages for each core. It also visualizes C-states, representing different CPU idle modes, to help identify energy-saving opportunities.
- **Memory Usage Insights**: Tracks system RAM usage, comparing memory in use versus available memory. This assists in identifying memory-intensive applications and potential bottlenecks, along with monitoring disk usage statistics.
- **Temperature and Power Mode Switching**: Continuously monitors temperatures of critical components (CPU, GPU, etc.) to ensure safe operation. Users can switch between various power modes (performance, balanced, power-saving) to optimize power consumption based on current needs.
- **Battery and NIC Power Consumption**: Provides detailed battery statistics (percentage, time remaining, power state) for better battery management. Also monitors NIC power consumption to understand the energy impact of network activities.
- **GPU Metrics Tracking**: Tracks GPU metrics such as power consumption, supply voltage, and temperature, offering insights into the power efficiency of graphics-related tasks.

## Docker Integration

Using Docker for containerization ensures a consistent and portable environment for running the Python GUI application, mitigating dependency issues and easing deployment across different systems.

### Steps to Use Docker

1. **Create a Dockerfile**: This file outlines the environment needed for your application.
2. **Build the Docker Image**: Use the Dockerfile to create an image that contains your application and its dependencies.
3. **Run the Container**: Start a container from your image, specifying parameters like CPU loading percentage and test duration.

## Installation Steps

1. **Install System Dependencies**:
   - Download the `install_dependencies.sh` script from the repository and run the following commands in your terminal:
     ```bash
     chmod +x install_dependencies.sh
     ./install_dependencies.sh
     ```

2. **Install Docker**:
   - Download the `Step1-install_docker.sh` script and execute:
     ```bash
     chmod +x Step1-install_docker.sh
     ./Step1-install_docker.sh
     ```

3. **Create Dockerfile**:
   - Create a Dockerfile with:
     ```bash
     vi Dockerfile
     ```
   - Copy the contents from `Step2-Create Dockerfile` into your new Dockerfile.

4. **Download Application Code**:
   - Access the `GUI_code` folder in the repository, download the files, and run the application.

## Tools Utilized

The Power Management Tool incorporates several powerful libraries and tools to provide accurate real-time data through intuitive visualizations:

- **psutil**: A cross-platform library for retrieving information on running processes and system utilization metrics, including CPU, memory, and disk.
- **tkinter**: Python's standard GUI toolkit, providing components for interactive applications.
- **turbostat**: A command-line tool reporting processor frequency and power statistics, offering insights into CPU performance.
- **Docker**: A platform for developing and deploying applications in isolated containers, ensuring consistency across different environments.
- **matplotlib**: A versatile plotting library for creating various visualizations, from static graphs to interactive charts.
- **lm-sensors**: A suite of tools for monitoring hardware sensor data, useful for temperature and fan speed monitoring.
- **upower**: A daemon providing information about power devices and managing power-related operations.

## Conclusion

The Power Management Tool is designed to equip users with real-time insights into system performance and energy consumption. By leveraging detailed monitoring capabilities, users can optimize their systems for greater efficiency and sustainability. This tool not only helps individual users manage power consumption but also supports broader eco-friendly computing practices.

Explore the repository for more detailed information and usage instructions, and start optimizing your system today!
