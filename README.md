---
page_type: sample
languages:
- csharp
- javascript
products:
- azure
- azure-maps
- azure-function
- azure-ad
description: "Track and capture relevant events that occur in space and time using Azure Maps spatial analytics services."
urlFragment: "iothub-to-azure-maps-geofencing"
---

# Implement IoT spatial analytics using Azure Maps

Tracking and capturing relevant events that occur in space and time is a common IoT scenario. For example, in fleet management, asset tracking, mobility, and smart city applications. This repo contains resources necessary to develop a solution pattern for using Azure Maps API against relevant events captured by IoT hub, using the event subscription model provided by Event Grid.

This repo contains the data and code files required to build an IoT system to [implement IoT spatial analytics using Azure Maps](https://docs.microsoft.com/azure/azure-maps/tutorial-iot-hub-maps). Following are the resources in this repo:

  * c# code to create an Azure Function, implementing business logic based on Azure Maps spatial analytics.
  * A Json file representing the geofence area, that you can upload in the Azure Maps, Data service using the Data Upload API.
  * A c# application that simulates an in-vehicle IoT Plug and Play device.


## Getting Started

To get started follow the tutorial [here](https://docs.microsoft.com/azure/azure-maps/tutorial-iot-hub-maps)


## Resources

To explore what Azure Maps has to offer, see:

* [Azure Maps Documentation](https://docs.microsoft.com/azure/azure-maps/)

To learn more about IoT-Hub, see:

* [IoT Hub Documentation](https://docs.microsoft.com/azure/iot-hub/)

To learn more about IoT Plug and Play, see:

* [IoT Plug and Play](https://aka.ms/iotpnpdocs)
