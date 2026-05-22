# Automotive & Autonomous Systems Frameworks

*Frameworks for autonomous driving, vehicle control, sensor fusion, In-Vehicle Infotainment (IVI), AUTOSAR standards, and vehicle simulation.*

## Contents

- [Autonomous Driving & Control Planes (AD/ADAS)](#autonomous-driving-control-planes-ad-adas)
- [In-Vehicle Infotainment (IVI) & HMI](#in-vehicle-infotainment-ivi-hmi)
- [Automotive Ethernet & CAN Bus Tools](#automotive-ethernet-can-bus-tools)
- [Sensor Fusion & Object Detection](#sensor-fusion-object-detection)
- [Vehicle-to-Everything (V2X) Communication](#vehicle-to-everything-v2x-communication)
- [Telematics & Fleet Management](#telematics-fleet-management)
- [Simulation & Virtual Validation](#simulation-virtual-validation)
- [AUTOSAR & Classic Automotive Frameworks](#autosar-classic-automotive-frameworks)
- [Connected Car APIs & Cloud Integration](#connected-car-apis-cloud-integration)
- [Battery Management Systems (BMS) Software](#battery-management-systems-bms-software)

---

## Autonomous Driving & Control Planes (AD/ADAS)

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Apollo | Enterprise-grade autonomous driving platform open sourced by Baidu | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/ApolloAuto/apollo) • [Website](https://apollo.auto) |
| Autoware.Universe | The leading open-source software stack for autonomous driving | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/autowarefoundation/autoware.universe) • [Website](https://autoware.org) |
| openpilot | Open source driver assistance system from comma.ai | <kbd>🏷️ Python/C++</kbd> | [GitHub](https://github.com/commaai/openpilot) • [Website](https://comma.ai) |
| ROS2 Autonomous | Autonomous driving plugins and navigation nodes for ROS2 | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/ros-navigation/navigation2) • [Website](https://navigation.ros.org) |
| Aslan | Open-source autonomous driving software for low-speed vehicles | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/ProjectAslan/Aslan) • [Website](https://projectaslan.org) |
| GoAD | Go framework for high-level autonomous routing and mission planning | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goad/goad) • [Website](https://goad.dev) |
| RustAD | Safe Rust control loop framework for steering and throttle actuation | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustad/rustad) • [Website](https://rustad.dev) |
| AdasKit C# | C# ADAS simulation controller and virtual radar visualizer | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/adaskit/adas-kit) • [Website](https://adaskit.org) |
| PyAD | Python prototyping framework for autonomous path search and control | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyad/pyad) • [Website](https://pyad.net) |
| ControlFlow | C++ framework for high-rate vehicle state machines and safety checks | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/controlflow/controlflow) • [Website](https://controlflow.io) |
| OpenDR | Deep learning toolkit for cognitive robotics and autonomous systems | <kbd>🏷️ Python/C++</kbd> | [GitHub](https://github.com/opendr-eu/opendr) • [Website](https://opendr.eu) |
| Chrono Autonomous | Chronological physics simulation middleware for autonomous vehicles | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/projectchrono/chrono) • [Website](https://projectchrono.org) |
| LocalPath | Go framework for automated vehicle trajectory and collision avoidance | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/localpath/localpath) • [Website](https://localpath.org) |
| SpeedPlanner | Rust library for real-time optimal speed profiling on curved roads | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/speed/speedplanner) • [Website](https://speedplanner.dev) |
| DriveOS | Microservice-based central scheduler for autonomous vehicle computing | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/driveos/driveos) • [Website](https://driveos.io) |

## In-Vehicle Infotainment (IVI) & HMI

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| AGL (Automotive Grade Linux) | Collaborative open source project building a linux-based IVI stack | <kbd>🏷️ C/C++</kbd> | [GitHub](https://github.com/automotive-grade-linux/agl-sbb) • [Website](https://automotivegradelinux.org) |
| Qt for Automotive | Specialized Qt suite for building automotive digital cockpits and HMI | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/qt/qt5) • [Website](https://qt.io/solutions/automotive) |
| Android Automotive SDK | Platform libraries for building native Android Automotive IVI apps | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/android/platform-frameworks-base) • [Website](https://source.android.com/devices/automotive) |
| OpenHMI | TypeScript browser-based framework for electric vehicle dashboards | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/openhmi/openhmi) • [Website](https://openhmi.org) |
| HmiKit C# | C# WPF-based framework for industrial and agricultural HMI designs | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/hmikit/hmi-kit) • [Website](https://hmikit.net) |
| NodeIVI | Node.js bridge connecting car system metrics to HTML5 dashboards | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodeivi/nodeivi) • [Website](https://nodeivi.github.io) |
| RustHMI | Rust embedded graphical library for low-power instrument clusters | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rusthmi/rusthmi) • [Website](https://rusthmi.dev) |
| GoCarPlay | Go utility for interacting with smartphone integration signaling | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gocar/gocarplay) • [Website](https://gocarplay.dev) |
| PyIVI | Python simulation mock server for in-vehicle infotainment displays | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyivi/pyivi) • [Website](https://pyivi.org) |
| SmartDeviceLink (SDL) | Connects smartphone apps with in-vehicle infotainment systems | <kbd>🏷️ C++/Java</kbd> | [GitHub](https://github.com/smartdevicelink/sdl_core) • [Website](https://smartdevicelink.com) |
| Flutter Automotive | Flutter extensions for building sleek cross-platform automotive UIs | <kbd>🏷️ Dart</kbd> | [GitHub](https://github.com/flutter/flutter) • [Website](https://flutter.dev) |
| IVI-Control | C++ framework for controlling car climate, volume, and ambient lights | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/ivi/ivicontrol) • [Website](https://ivicontrol.net) |
| CockpitJS | HTML5 canvas rendering library for EV battery and speedometer dials | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/cockpitjs/cockpitjs) • [Website](https://cockpitjs.io) |
| DashboardOS | Kotlin-based automotive grade head unit operating dashboard | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/dash/dashboardos) • [Website](https://dashboardos.org) |
| AuraHMI | High-performance vector rendering HMI framework | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/aurahmi/aura) • [Website](https://aurahmi.io) |

## Automotive Ethernet & CAN Bus Tools

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| SocketCAN | Official Linux kernel subsystem for Controller Area Network (CAN) drivers | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/linux/kernel) • [Website](https://kernel.org) |
| python-can | Python library providing controller area network support for developers | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/hardbyte/python-can) • [Website](https://python-can.readthedocs.io) |
| SavvyCAN | QT-based cross-platform CAN bus reverse engineering tool | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/collin80/SavvyCAN) • [Website](https://savvycan.com) |
| CanFestival | Open-source CANopen framework for embedded controllers | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/canfestival/canfestival) • [Website](https://canfestival.org) |
| GoCAN | Go network parser for real-time CAN bus trace decoding | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gocan/gocan) • [Website](https://gocan.dev) |
| RustCAN | Rust safe interface for manipulating embedded CAN frames | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustcan/rustcan) • [Website](https://rustcan.dev) |
| CanKit C# | C# desktop tool library for interfacing with USB-to-CAN hardware | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/cankit/can-kit) • [Website](https://cankit.org) |
| SomeIP-JS | Node.js implementation of the SOME/IP automotive ethernet protocol | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/someip/someip-js) • [Website](https://someipjs.org) |
| OpenSOMEIP | C++ high-performance implementation of SOME/IP for vehicle networks | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/opensomeip/opensomeip) • [Website](https://opensomeip.org) |
| PySomeIP | Python testing utility for mocking SOME/IP vehicle service endpoints | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pysomeip/pysomeip) • [Website](https://pysomeip.net) |
| Vsomeip | C++ implementation of SOME/IP service-oriented middle ware by BMW | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/COVESA/vsomeip) • [Website](https://github.com/COVESA/vsomeip) |
| CanOpen Go | Go CANopen master and slave implementation library | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/canopen/canopen-go) • [Website](https://canopengo.org) |
| LibUds | C++ library implementing Unified Diagnostic Services (UDS) over CAN | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/uds/libuds) • [Website](https://libuds.net) |
| RustUDS | Rust safe wrapper for vehicle diagnostic query networks | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustuds/rustuds) • [Website](https://rustuds.dev) |
| EtherCar | Go controller framework for TSN (Time-Sensitive Networking) Ethernet | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/ether/ethercar) • [Website](https://ethercar.io) |

## Sensor Fusion & Object Detection

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Lidar-Core | C++ high-performance processing library for 3D LiDAR point clouds | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/lidar/lidar-core) • [Website](https://lidarcore.org) |
| OpenPCDet | PyTorch-based codebase for 3D object detection from point clouds | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/open-mmlab/OpenPCDet) • [Website](https://github.com/open-mmlab/OpenPCDet) |
| FilterPy | Python library implementing Kalman, Extended Kalman, and particle filters | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/rlabbe/filterpy) • [Website](https://github.com/rlabbe/filterpy) |
| GoFusion | Go framework for sensor data alignment and real-time state estimation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gofusion/gofusion) • [Website](https://gofusion.dev) |
| RustFusion | Rust safe multi-sensor track fusion and spatial indexing framework | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustfusion/rustfusion) • [Website](https://rustfusion.dev) |
| PointMatch C# | C# library for matching vehicle camera bounds with radar objects | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/pointmatch/pointmatch) • [Website](https://pointmatch.net) |
| RadarCore | C++ framework for processing raw automotive FMCW radar signals | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/radar/radar-core) • [Website](https://radarcore.org) |
| SensorSync | Node.js framework for timestamp synchronization of camera grids | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/sensorsync/sensorsync) • [Website](https://sensorsync.github.io) |
| Open3D | Modern library for 3D data processing and visualization | <kbd>🏷️ C++/Python</kbd> | [GitHub](https://github.com/isl-org/Open3D) • [Website](https://open3d.org) |
| PCL (Point Cloud Library) | Standalone, large-scale, open-source library for 2D/3D image processing | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/PointCloudLibrary/pcl) • [Website](https://pointclouds.org) |
| NuScenes-devkit | Python devkit for interacting with autonomous vehicle sensor datasets | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/nutonomy/nuscenes-devkit) • [Website](https://nuscenes.org) |
| FusionFlow | Go network framework for routing raw vehicle telemetry to cloud models | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/fusionflow/fusionflow) • [Website](https://fusionflow.dev) |
| TrackFilter | C++ library implementing multi-object tracking (MOT) filter equations | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/track/trackfilter) • [Website](https://trackfilter.net) |
| CamRadar | Rust deep-learning pipeline for 2D image to 3D radar fusion projection | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/camradar/camradar) • [Website](https://camradar.io) |
| SensorNode | Java framework for coordinating distributed smart automotive sensor nodes | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/sensornode/sensornode) • [Website](https://sensornode.org) |

## Vehicle-to-Everything (V2X) Communication

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OpenV2X | Open source Vehicle-to-Everything (V2X) edge computing suite | <kbd>🏷️ Go/Python</kbd> | [GitHub](https://github.com/open-v2x/backend) • [Website](https://openv2x.org) |
| V2x-Kit | Java framework for parsing DSRC, WAVE, and C-V2X message standards | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/v2x/v2x-kit) • [Website](https://v2xkit.org) |
| RustV2X | Rust safe high-frequency message broadcasting server for roadside units | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustv2x/rustv2x) • [Website](https://rustv2x.dev) |
| GoV2X | Go routing engine for distributing localized hazard warning messages | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gov2x/gov2x) • [Website](https://gov2x.dev) |
| V2xSim C# | C# framework for simulating vehicle-to-infrastructure network topologies | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/v2xsim/v2x-sim) • [Website](https://v2xsim.net) |
| NodeV2X | Node.js package for mocking V2X basic safety messages (BSM) | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodev2x/nodev2x) • [Website](https://nodev2x.github.io) |
| PyV2X | Python library for parsing SPaT (Signal Phase and Timing) traffic lights | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyv2x/pyv2x) • [Website](https://pyv2x.org) |
| RoadsideOS | C++ real-time operating control software for road-side units (RSUs) | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/roadside/roadsideos) • [Website](https://roadsideos.net) |
| Asn1Codec | C++ encoder and decoder for J2735 and ISO V2X ASN.1 specifications | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/asn1/asn1codec) • [Website](https://asn1codec.org) |
| O-V2X Client | Go client library for connecting autonomous cars with smart intersections | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/openv2x/client) • [Website](https://openv2x.org) |
| V2xGtw | Kotlin gateway for converting V2X telemetry into MQTT cloud messages | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/v2x/gateway) • [Website](https://v2xgateway.io) |
| DsrcCodec | Rust parser and builder for Dedicated Short-Range Communications data | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/dsrc/dsrccodec) • [Website](https://dsrccodec.dev) |
| TransitV2X | C# system for prioritizing public transit vehicle signal preemption | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/transit/transitv2x) • [Website](https://transitv2x.com) |
| SmartCross | Python simulator for modeling pedestrian alerts to connected cars | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/cross/smartcross) • [Website](https://smartcross.org) |
| SafetyAlerts | Java server for high-volume geographical distribution of road hazards | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/safety/safetyalerts) • [Website](https://safetyalerts.org) |

## Telematics & Fleet Management

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Traccar | Open source GPS tracking system with support for 170+ protocols | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/traccar/traccar) • [Website](https://traccar.org) |
| OpenTelematics | Standard API and middleware specification for fleet telemetry | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/opentele/opentelematics) • [Website](https://opentelematics.org) |
| FMS-Parser | Go library for parsing FMS (Fleet Management System) truck standards | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/fms/fms-parser) • [Website](https://fmsparser.dev) |
| RustTelematics | Rust high-performance ingestion pipeline for GPS and OBD-II logs | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rusttele/rusttelematics) • [Website](https://rusttelematics.dev) |
| PyTelematics | Python package for calculating vehicle harsh braking and driver scores | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pytele/pytelematics) • [Website](https://pytelematics.org) |
| Telematics C# | C# desktop tracker client for vehicle fleet visualization maps | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/tele/telematics) • [Website](https://telematics.net) |
| NodeGPS | Node.js server for parsing raw NMEA-0183 GPS receiver protocol streams | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodegps/nodegps) • [Website](https://nodegps.github.io) |
| ObdClient | C++ embedded library for querying OBD-II diagnostic parameters over ELM327 | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/obd/obdclient) • [Website](https://obdclient.org) |
| GpsGateway | Kotlin microservice for routing mobile GPS coordinates to fleet backends | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/gps/gpsgateway) • [Website](https://gpsgateway.io) |
| FleetEngine | TypeScript framework for routing and vehicle scheduling optimization | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/fleet/fleetengine) • [Website](https://fleetengine.org) |
| ObdII-Py | Python library for parsing vehicle PID codes and engine trouble diagnostics | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/obd2/obd2py) • [Website](https://obd2py.net) |
| RustOBD | Rust package for talking with car diagnostic ports over serial lines | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustobd/rustobd) • [Website](https://rustobd.dev) |
| FleetRoute | C# framework for resolving Capacitated Vehicle Routing Problems (CVRP) | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/fleet/fleetroute) • [Website](https://fleetroute.com) |
| FuelLog | Go ledger server for tracking vehicle mileage and fuel consumption efficiency | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/fuel/fuellog) • [Website](https://fuellog.io) |
| SmartFleet | Java enterprise resource scheduler for dispatching fleet vehicles | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/smart/smartfleet) • [Website](https://smartfleet.org) |

## Simulation & Virtual Validation

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| CARLA | Open-source simulator for autonomous driving research and validation | <kbd>🏷️ C++/Python</kbd> | [GitHub](https://github.com/carla-simulator/carla) • [Website](https://carla.org) |
| LG SVL Simulator | Multi-sensor simulator for autonomous driving development (archived) | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/lgsvl/simulator) • [Website](https://svlsimulator.com) |
| SUMO (Simulation of Urban MObility) | Open source, highly portable traffic simulation suite | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/eclipse-sumo/sumo) • [Website](https://eclipse.org/sumo) |
| Webots | Open-source robot simulator providing a complete automotive environment | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/cyberbotics/webots) • [Website](https://cyberbotics.com) |
| Gazebo | Multi-robot simulator for outdoor and indoor environments with vehicle dynamics | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/gazebosim/gz-sim) • [Website](https://gazebosim.org) |
| AirSim | Open-source simulator for autonomous vehicles based on Unreal Engine | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/microsoft/AirSim) • [Website](https://github.com/microsoft/AirSim) |
| GoSimAuto | Go utility for mocking vehicle agent routes and traffic light states | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gosim/gosimauto) • [Website](https://gosimauto.dev) |
| RustSimVehicle | Rust kinematics library for simulating 2D and 3D vehicle physics | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustsim/rustsimvehicle) • [Website](https://rustsimvehicle.dev) |
| PySimTraffic | Python traffic flow generator based on the Intelligent Driver Model (IDM) | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pysim/pysimtraffic) • [Website](https://pysimtraffic.org) |
| SimHIL C# | C# framework for Hardware-in-the-Loop (HIL) automation and test grids | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/simhil/simhil) • [Website](https://simhil.net) |
| NodeScenario | TypeScript parser for ASAM OpenSCENARIO dynamic traffic scripts | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodescen/nodescenario) • [Website](https://nodescenario.org) |
| OpenDRIVE-Parser | C++ library for parsing ASAM OpenDRIVE road geometry files | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/opendrive/opendrive-parser) • [Website](https://opendriveparser.net) |
| PyOpenDrive | Python package for rendering OpenDRIVE XML highway networks | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyod/pyopendrive) • [Website](https://pyopendrive.io) |
| RustDRIVE | Rust library for verifying autonomous path plans against OpenDRIVE maps | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustdrive/rustdrive) • [Website](https://rustdrive.dev) |
| TrafficFlow | Java visual tool for generating random urban intersection traffic | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/traffic/trafficflow) • [Website](https://trafficflow.org) |

## AUTOSAR & Classic Automotive Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Arccore | Open-source platform implementing classic AUTOSAR software standards | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/arccore/arccore) • [Website](https://arccore.com) |
| Comas | C++ open-source framework for automotive diagnostic communication | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/comas/comas) • [Website](https://comas.org) |
| GoAutosar | Go parsing toolkit for AUTOSAR XML (ARXML) system templates | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goauto/goautosar) • [Website](https://goautosar.dev) |
| RustAutosar | Rust library for safe parsing and validation of AUTOSAR system data | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustauto/rustautosar) • [Website](https://rustautosar.dev) |
| ArxmlParser C# | C# desktop tool library for editing and compiling ARXML databases | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/arxml/arxmlparser) • [Website](https://arxmlparser.net) |
| PyAutosar | Python script collection for automating AUTOSAR software configuration generation | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyauto/pyautosar) • [Website](https://pyautosar.org) |
| OpenECU | C library framework for building standard electronic control unit software | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/openecu/openecu) • [Website](https://openecu.org) |
| EcuMock | Go simulator for mocking automotive ECUs over virtual CAN buses | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/ecumock/ecumock) • [Website](https://ecumock.io) |
| NodeArxml | Node.js framework for exporting vehicle bus definitions to ARXML files | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodearxml/nodearxml) • [Website](https://nodearxml.github.io) |
| OsekOS | C++ implementation of the OSEK/VDX automotive operating system standard | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/osek/osekos) • [Website](https://osekos.org) |
| Trampoline RTOS | RTOS implementing OSEK/VDX and AUTOSAR OS specifications | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/trampoline-rtos/trampoline) • [Website](https://trampoline.rts-software.org) |
| EcuBuilder | Java developer environment for AUTOSAR basic software config | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/ecubuild/ecubuilder) • [Website](https://ecubuilder.org) |
| AutosarCom | C++ library for classic AUTOSAR COM communication stack | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/autosar/autosarcom) • [Website](https://autosarcom.net) |
| EcuState | Rust framework for implementing automotive ECU power and sleep state controllers | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/ecustate/ecustate) • [Website](https://ecustate.dev) |
| AutoDiagnostics | C# framework for writing automotive dealer scan tools | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/autodiag/autodiagnostics) • [Website](https://autodiagnostics.com) |

## Connected Car APIs & Cloud Integration

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| CarAPI | Open-source dashboard interface connecting standard car clouds | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/carapi/carapi) • [Website](https://carapi.org) |
| GoVehicleAPI | Go API client for retrieving vehicle telemetry from OEM platforms | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/govehicle/govehicleapi) • [Website](https://govehicleapi.dev) |
| SmartCar SDK | Python interface for interacting with Smartcar connected car APIs | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/smartcar/smartcar-python) • [Website](https://smartcar.com) |
| TeslaSDK | Rust library wrapping Tesla vehicle owners JSON Web APIs | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/teslasdk/teslasdk) • [Website](https://teslasdk.org) |
| FleetCloud C# | C# framework for uploading telematics logs to Azure IoT Hub | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/fleetcloud/fleet-cloud) • [Website](https://fleetcloud.net) |
| NodeCarCloud | Node.js backend for orchestrating connected vehicle subscriptions | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodecar/nodecarcloud) • [Website](https://nodecarcloud.github.io) |
| JavaConnectedCar | Java microservice for aggregating telemetry from multi-OEM clouds | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javacar/javaconnectedcar) • [Website](https://javaconnectedcar.org) |
| CarMQTT | C++ embedded client for publishing vehicle signals to brokers | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/carmqtt/carmqtt) • [Website](https://carmqtt.net) |
| VehicleDataFlow | Go network engine for transforming vehicle telemetry to standard JSON | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/vehicledata/vehicedataflow) • [Website](https://vehicedataflow.dev) |
| AutoCloud | Python serverless framework for handling vehicle lock/unlock alerts | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/autocloud/autocloud) • [Website](https://autocloud.io) |
| VinDecoder | Rust library for parsing and decoding Vehicle Identification Numbers (VIN) | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/vin/vindecoder) • [Website](https://vindecoder.dev) |
| CarSync SDK | Kotlin mobile SDK for reading local vehicle Wi-Fi hotspots state | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/carsync/carsyncsdk) • [Website](https://carsyncsdk.com) |
| FordSync SDK | Java framework for deploying applications onto Ford SYNC systems | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/fordsync/fordsync) • [Website](https://developer.ford.com) |
| MyCar API | C# framework for building consumer mobile apps for car remote start | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/mycar/mycarapi) • [Website](https://mycarapi.com) |
| OemConnector | Go routing engine for synchronizing vehicle status with manufacturer APIs | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/oem/oemconnector) • [Website](https://oemconnector.org) |

## Battery Management Systems (BMS) Software

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OpenBMS | Open-source control software for EV battery cell balancing | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/openbms/openbms) • [Website](https://openbms.org) |
| BmsMonitor | Python UI utility for visualizing battery cell state of charge (SoC) | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bmsmon/bmsmonitor) • [Website](https://bmsmonitor.dev) |
| GoBMS | Go telematics parser for recording EV battery temperature logs | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gobms/gobms) • [Website](https://gobms.dev) |
| RustBMS | Rust real-time safety critical monitoring loop for lithium-ion packs | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustbms/rustbms) • [Website](https://rustbms.dev) |
| CellBalance C# | C# simulator for modeling battery passive and active cell balancing | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/cell/cellbalance) • [Website](https://cellbalance.net) |
| NodeBMS | Node.js dashboard framework for monitoring electric home battery walls | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodebms/nodebms) • [Website](https://nodebms.github.io) |
| JavaBMS | Java database pipeline for long-term battery degradation statistics | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javabms/javabms) • [Website](https://javabms.org) |
| BmsSimulator | C++ physical modeling framework for pack temperature and current profiles | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/bms/bmssimulator) • [Website](https://bmssimulator.net) |
| SocCalc | Go library implementing Coulomb counting and Kalman battery state estimators | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/soc/soccalc) • [Website](https://soccalc.org) |
| BmsAlerts | Python alert routing engine for high-temperature EV cell warnings | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bms/bmsalerts) • [Website](https://bmsalerts.io) |
| EmbeddedBms | C++ software library for modular master-slave hardware BMS setups | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/emb/embeddedbms) • [Website](https://embeddedbms.net) |
| PackConfig | TypeScript configuration builder for setting pack over-voltage thresholds | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/pack/packconfig) • [Website](https://packconfig.org) |
| BatteryLife | Rust library for predicting battery State of Health (SoH) via models | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/batlife/batterylife) • [Website](https://batterylife.dev) |
| BmsDiagnostics | C# framework for writing battery test stand diagnostic automation | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/bmsdiag/bmsdiagnostics) • [Website](https://bmsdiagnostics.com) |
| PowerManager | Java framework for coordinating charging speed with grid battery status | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/power/powermanager) • [Website](https://powermanager.org) |
