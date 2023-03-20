# Sensor System for Self-Driven In-Home Climate Control
This is an Oregon State University Computer Science Capstone Project.

## Personnel:
### Students:
- Daniel Piper
- Jacob Redfern
- Marcelo Salas
- Ryan Zimmerman

### Project Partners:
- Lyubo Gankov
- Faaiq Waqar
- Kiernan Canavan

## About the Project
The purpose of this project is to empower homeowners to make optimal use of their windows to cool and heat their homes, using sensors placed throughout their home.

Annually, the cost of air conditioning and heating equipment rises in cost anywhere from 5% - 9%. Coupled with the growing costs of electricity and natural gas, in-house climate control can amass enormous utility bills. Effective use of the windows in one’s home can help, but knowing how best to use the windows in your home is a non-trivial problem.

Compared to the competition, the benefits of using our project are that it is free and open-source, highly configurable, and not locked into any ecosystem. You can use any kind of sensor, and can easily self-host the web server if you don't want to be tied into our cloud server. It may not be as polished or feature-rich than commercially available projects, but it is very accessible and adaptable to your needs.

## Using the Project
### Hardware requirements
You must have at least one sensor module that can get temperature and humidity data and send that data over the network. When developing the project, we used an [Arduino Nano RP2040 Connect](https://store.arduino.cc/products/arduino-nano-rp2040-connect) with a [DHT11 Sensor](https://www.adafruit.com/product/386).

To set up a sensor module, follow the instructions [here](https://github.com/sensor-climate-control/scc-sensor).

### Software setup
You can either use our cloud-hosted web server at [osuscc.azurewebsites.net](https://osuscc.azurewebsites.net) (recommended), or self-host a web server using the instructions [here](https://github.com/sensor-climate-control/scc-web).

Additionally, our recommended configuration is for your sensors to directly communicate with the web server, but we also support a configuration with a local server that handles the web server communication ([setup instructions](https://github.com/sensor-climate-control/scc-local-server)).

## Repositories and Documentation
All documentation can be found in the respective repositories:
- [Web Server](https://github.com/sensor-climate-control/scc-web)
- [Sensors](https://github.com/sensor-climate-control/scc-sensor)
- [Local Server](https://github.com/sensor-climate-control/scc-local-server)

## Contact or Get Assistance
If you have any difficulties setting up and running the project, please open a GitHub issue in the appropriate repository.

If you want to contact us for any other reason, you can open a GitHub issue or [Start a GitHub discussion](https://github.com/orgs/sensor-climate-control/discussions/new/choose)