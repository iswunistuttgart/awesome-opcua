# Awesome OPC UA [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Open Platform Communications Unified Architecture (OPC UA) libraries, tools and resources. Inspired by awesome-... stuff.

Including the information from [traversaro/awesome-opcua](https://github.com/traversaro/awesome-opcua)

Open Platform Communications Unified Architecture (OPC UA) is the data exchange standard for  safe, reliable, manufacturer- and platform-independent industrial communication.

For a brief introduction to OPC UA, check the [What is OPC? UA in a Minute](https://www.youtube.com/watch?v=-tDGzwsBokY).

See the [official OPC Foundation site](https://opcfoundation.org/about/opc-technologies/opc-ua/) for the official specifications and more information about the OPC UA standard.

## Contents

- [Awesome OPC UA](#awesome-opcua)
  - [OPC UA Standards Documents](#opc-ua-standards-documents)
    - [Resources](#resources)
      - [Online Resources](#online-resources)
      - [Books](#books)
      - [Articles](#Articles)
      - [Videos](#Videos)
    - [Software](#software)
      - [SDKs and Libraries](#sdks-and-libraries)
        - [C](#c)
        - [C++](#c-1)
        - [C#](#c-2)
        - [JavaScript/TypeScript](#javascript--typescript)
        - [Java](#java)
        - [MATLAB](#matlab)
        - [NuGet Packages](#nuget-packages)
        - [Python](#python)
        - [Rust](#rust)
        - [Golang](#golang)
        - [Delphi](#delphi)
      - [Cloud](#cloud)
      - [Test Clients](#test-clients)
      - [Modelling Tools](#modelling-tools)
      - [Online Tools](#online-tools)
      - [SimulationServer](#server-simulations)
      - [Server and Client examples](#server-and-client-applications)
    - [Gateways (OPC Classic)](#gateways (OPC Classic))
    - [Community](#community)
    - [Related Lists](#related-lists)
    - [Tutorials](#tutorials)
    - [Contribute](#contribute)
    - [License](#license)

## OPC UA Standards Documents

_Released OPC UA Specifications._

- [OPC Foundation Documents Overview](https://opcfoundation.org/developer-tools/documents/) - All Documents (Specification, Templates, Guidelines) published by the OPC Foundation
- [OPC Unified Architecture Specification](https://opcfoundation.org/developer-tools/specifications-unified-architecture) - OPC UA Specification published by the OPC Foundation. Needs registration for download.
- [OPC UA Information Models](https://opcfoundation.org/developer-tools/specifications-opc-ua-information-models) - OPC UA Companion Specifications released by the OPC Foundation. Needs registration for download.
- [OPC Foundation Git repository of NodeSets](https://github.com/OPCFoundation/UA-Nodeset) - easy way to get the nodeset files without registration
- [OPC UA Online Reference](https://reference.opcfoundation.org/) - Online versions of OPC UA specifications and information models. Harder to read than the PDF versions due to each chapter being a separate site. Search function over all parts of the standard and the information models.

## Resources

_Information material apart from the standards documents._

### Online Resources

_Information material available online._

- [OPC Foundation Online Reference](https://reference.opcfoundation.org/)
- [OPC UA Profile Reporting Application
](https://profiles.opcfoundation.org/) - UA 1.05 forward
- `deprecated` [OPC Foundation UA Profile Reporting Visualization Tool](https://profiles-old.opcfoundation.org/) - Overview of OPC UA Profiles.
- `deprecated` [OPC Foundation UA Profile Reporting Visualization Tool with drafts](https://profiles-old.opcfoundation.org/v104/reporting/?All=true) - Same as above including (stable) drafts.
- [OPC Foundation Templates](https://opcfoundation.org/developer-tools/documents/) - (select the "Template" filter) Templates for (joint) working groups. Including MS Visio shapes for OPC UA.
- [OPC Foundation OPC UA Wiki](http://wiki.opcfoundation.org/index.php?title=Main_Page) - OPC UA Wiki of the OPC Foundation. **Not up to the latest specification state!**
- [OPC Foundation Information Modelling Best Practices](https://opcfoundation.org/developer-tools/documents/view/312) - Whitepaper intended to provide best practices while creating OPC UA information models.
- [List of Collaborations Groups on Companion Specifications](https://docs.google.com/spreadsheets/d/10SOpad6uu7JA5ZSpccVyqaqkyhYBiIXqNus28-1cJtU/edit#gid=1248333029) - Overview of the different standardization activities
- [https://opcua.rocks/](https://opcua.rocks/) - blog about OPC UA
- [https://sandervandevelde.wordpress.com/](https://sandervandevelde.wordpress.com/) -  IoT Blog (use also OPC UA in some projects)
- [OPCUA CS Graph](https://iswunistuttgart.github.io/opcua-cs-graph/) - Graph that shows the dependencies between Companion Specification
- [GitHub Org of the OPC Foundation](https://github.com/OPCFoundation) - different software projects and reference implementations

### Books

_Books about OPC UA._

- _Wolfgang Mahnke, Stefan-Helmut Leitner, Matthias Damm_, OPC Unified Architecture. _Springer; 2009_, ISBN: 978-3540688983.
- Etienne Rossignon, [node-opcua by example](https://leanpub.com/node-opcuabyexample)  

### Articles

- [A Literature Survey on Open Platform Communications (OPC) Applied to Advanced Industrial Environments](https://www.mdpi.com/2079-9292/8/5/510) A literature Survey for OPC UA in 2019 with Trends and Open Research Issues
- [OPC UA versus ROS, DDS, and MQTT: performance evaluation of industry 4.0 protocols](https://mediatum.ub.tum.de/doc/1470362/file.pdf)
Performance evaluation of differente protocols
- [Benchmarking of existing OPC UA implementations for Industrie  4.0-compliant digitalization solutions](https://ieeexplore.ieee.org/abstract/document/8104838)
Compare different implementations for OPC UA
- [Designentscheidungen für OPC-UA-Informationsmodelle](https://www.ingenieur.de/fachmedien/wt-werkstattstechnik/ausgaben-wt-werkstattstechnik-online/inhalte-der-online-ausgabe-5-2020/) (German) Description of OPC UA Design decisions in OPC UA for Weighing Technology and OPC UA for Machine Tools
- [Der Trend zur branchenorienterten OPC UA Companion Specification und deren Herausforderungen](https://www.der-maschinenbau.de/markt-trends-technik/der-trend-und-seine-herausforderungen/) (German) Descriptes the Trends of OPC UA  Companion Specification

### Videos

- [What is OPC? UA in a Minute](https://www.youtube.com/watch?v=-tDGzwsBokY)
- [Tech-Intro "OPC UA Concepts" by Uwe Steinkrauss (06-2019)](https://www.youtube.com/watch?v=E2XJfmAEdqw) - A 10 minutes technical introduction to OPC UA basic concepts.
- [20200622 02 OPC UA Technology](https://www.youtube.com/watch?v=OQC_kVYisS8)  - 20 min Introduction into OPC UA (OPC UA Day 2020)
- [OPC UA Security Deep Dive by Randy Armstrong (Chair of OPC UA Security Working Group), Dec 2020](https://www.youtube.com/watch?v=pa82WydVtPY)
- [Creating Information Model and OPC UA Server Using NET - Industry40tv](https://www.youtube.com/watch?v=gxA7SDNLHgc)
- [YouTube Channel of the OPC Foundation](https://www.youtube.com/user/TheOPCFoundation)
- [OPC UA for Machine Tools YT Channel](https://youtube.com/playlist?list=PLkiLpeY1YPH1gEtEV7jmX9D8XPUEfS5EF)
- [OPC UA PubSub Explained, Jouni Aro (Prosys OPC), OPC Day Finland 2021](https://www.youtube.com/watch?v=FWtrruzOvr4&list=PL98upRG1ESZSMFf18NK-OMFxNYWrIdHDU&index=14)

## Software

_Software for creating OPC UA Servers, Clients, Publishers, Subscribers or Information Models._

### SDKs and Libraries

_SDKs to create OPC UA components._

#### C

- [open62541](https://open62541.org/) - Open Source C (C99) implementation for Server/Client and Pub/Sub licensed under the Mozilla Public License v2.0. [MPL-2.0]
- [OpenOpcUA](http://www.openopcua.org/)  - Server/Client
- [OpenScadaUA Interface](http://oscada.org/websvn/filedetails.php?repname=OpenSCADA&path=%2Ftrunk%2FOpenSCADA%2Fsrc%2Fmoduls%2Fdaq%2FOPC_UA%2FlibOPC_UA%2FlibOPC_UA.h) - only Server
- [ASNeG](https://github.com/ASNeG/OpcUaStack)  - Server/Client
- [uaf](https://github.com/uaf/uaf)  - Client (wrapper over proprietary sdk)
- [UACL/CPP -](https://gitlab.com/falko.wiese/uacl_cpp) Server (wrapper over proprietary sdk)
- [S2OPC](https://gitlab.com/systerel/S2OPC) - Client/Server
- [dataFeed OPC UA](https://data-intelligence.softing.com/de/produkte/datafeed-opc-sdks/datafeed-opc-ua-c-server-client-sdk-for-windows/) - Server/Client proprietary (Softing) [Commercial]
- [OPC UA SDK/Toolkit für Embedded-Geräte](https://industrial.softing.com/de/produkte/opc-ua-and-opc-classic-sdks/uatoolkit-embedded.html) - C implementation for Server/Client and Pub/Sub [Commercial]
- [Prosys OPC UA C/C++ SDKs](https://www.prosysopc.com/products/opc-ua-cplusplus-sdk/) - Server/Client proprietary [Commercial]
- [Unified Automation C/C++ SDKs](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html)  - Server/Client proprietary [Commercial]
- [NodesetLoader](https://github.com/matkonnerth/nodesetLoader) - Library for importing nodesets in xml schema, add nodeset import to open62541 [MPL-2.0]

#### C++

- [freeopcua](https://github.com/FreeOpcUa/freeopcua) - Open Source C++ OPC-UA Server and Client Library. [LGPL-3.0]
- [QtOPCUA](https://doc.qt.io/QtOPCUA/index.html) - Qt module that implements a Qt API to interact with OPC UA. [LGPL-3.0]
- [QUaServer](https://github.com/juangburgos/QUaServer) -  Qt C++ wrapper for open62541 server stack. [MIT]
- [ASNeG OPC UA Stack](https://asneg.github.io/projects/opcuastack) - Open source C++ framework for development and distribution of OPC UA client\server applications. [Apache-2.0]

#### C\#

- [UA.NET Standard](https://github.com/OPCFoundation/UA-.NETStandard) - Server/Client - Official OPC UA .NET Standard Stack from the OPC Foundation. [GPL-2.0 / RCL dual licensed]
- [UACL/CS](Client/Server (wrapper over proprietary sdk)) - Client/Server (wrapper over proprietary sdk)
- [opc-ua-client](https://github.com/convertersystems/opc-ua-client)-  only Client
- [LibUA](https://github.com/nauful/LibUA) - Server/Client
- [h-opc](https://github.com/hylasoft-usa/h-opc) - OPC client made simpler, for UA and DA
- [Träger](https://opcua.traeger.de/) - Server/Client [Commercial]
- [dataFeed OPC UA](https://data-intelligence.softing.com/de/produkte/datafeed-opc-sdks/datafeed-opc-ua-net-standard-sdks/) - Server/Client (Softing) [Commercial]
- [QuickOPC](https://www.opclabs.com/products/quickopc) - Client (OPC Labs)
- [OPC UA .NET SDK](https://www.prosysopc.com/products/opc-ua-dotnet-sdk/) - Server/Client (Prosys) [Commercial]
- [PicoOPC](https://www.opclabs.com/products/picoopc/for-dotnet) - OPC UA client library [Commercial]
- [Unified Automation .NET SDK](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html)  - Server/Client [Commercial]

#### JavaScript / TypeScript

- [node-opcua](http://node-opcua.github.io/) - Server/Client - NodeOPCUA is a OPC UA stack fully written in TypeScript for Node.js. [MIT]
- [node-red-contrib-opcua](https://flows.nodered.org/node/node-red-contrib-opcua) - Node-Red Plugin for OPC UA (Server/Client)
- [HBM/opcua](https://github.com/HBM/opcua) - only Client

#### Java

- [Eclipse Milo™](https://github.com/eclipse/milo) - Server/Client - Java open source implementation of OPC UA (IEC 62541).  [EPL-2.0]
- [opcua4j](https://code.google.com/p/opcua4j/)  - only Server
- [Prosys OPC UA](https://www.prosysopc.com/products/opc-ua-java-sdk/) - Server/Client proprietary

#### MATLAB

- [OPC Toolbox](https://www.mathworks.com/help/opc/index.html) - MATLAB official toolbox that supports OPC UA. See [Mathworks site](https://www.mathworks.com/discovery/opc-ua.html) for more details. [Commercial]

#### NuGet Packages

- [OPCFoundation.NetStandard.Opc.Ua](https://www.nuget.org/packages/OPCFoundation.NetStandard.Opc.Ua/) - NuGet Package of the Reference Implementation [[OPC-F redistributables license]](https://opcfoundation.org/license/redistributables/1.3/)
- [PicoOPC](https://www.opclabs.com/products/picoopc/for-dotnet) - OPC UA client library (OPC Labs) [Commercial]

#### Python

- [uaf](https://github.com/uaf/uaf) - Client (wrapper over proprietary sdk)
- `deprecated`[Python FreeOpcUa](https://github.com/FreeOpcUa/python-opcua) - Server /Client
- [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio) - OPC UA / IEC 62541 Client and Server for Python >= 3.7 and pypy3. [LGPL-3.0]

#### Rust

- [locka99/opcua](https://github.com/locka99/opcua) - OPC UA server / client API implementation for Rust. [MPL-2.0]

#### Golang

- [gopcua/opcua](https://github.com/gopcua/opcua) - Server/Client - A native Go implementation of the OPC/UA Binary Protocol.
- [awcullen/opcua](https://github.com/awcullen/opcua) - Server/Client. [MIT]

#### Delphi

- [Sentrol SDK for Delphi](https://www.prosysopc.com/products/opc-ua-sentrol-sdk/) - Server/Client proprietary (Prosys) [Commercial]
- [Unified Automation Delphi SDK](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html)  - Server/Client proprietary [Commercial]

### Cloud

- [OPC UA with Akri](https://docs.akri.sh/discovery-handlers/opc-ua) - A Kubernetes Resource Interface for OPC UA [Apache-2.0]

### Test Clients

_Test Clients to check server implementations manually._

- [UaExpert](https://www.unified-automation.com/products/development-tools/uaexpert.html) - General purpose graphical test client supporting OPC UA features like DataAccess, Alarms & Conditions, Historical Access and calling of UA Methods by Unified Automation [Commercial] (free evaluation license).
- [dataFEED](https://data-intelligence.softing.com/de/produkte/opc-software-plattform/opc-ua-demo-client/) - Demo Client developed by Softing (free)
- [FreeOpcUA](https://github.com/FreeOpcUa/opcua-client-gui) - OpenSource Client based on python
- [Prosys OPC UA Monitor](https://www.prosysopc.com/products/opc-ua-monitor/) - HMI Tool  (Evaluation for Free)
- [OPC UA Browser](https://www.prosysopc.com/products/opc-ua-browser/) - Demo Client developed by Prosys (free evaluation license).
- [OPC UA Test tool](https://github.com/matkonnerth/opcuatesttool) - Automate OPC UA server performance testing

### Modelling Tools

_Tools to create OPC UA Information Models._

- [UAModeler](https://www.unified-automation.com/products/development-tools/uamodeler.html) - Modeling Tool by Unified Automation. [Commercial]
- [OPC UA Modeler](https://www.prosysopc.com/products/opc-ua-modeler/) - Modeling Tool by Prosys [Commercial]
- [SiOME](https://support.industry.siemens.com/cs/document/109755133/siemens-opc-ua-modeling-editor-%28siome%29-for-implementing-opc-ua-companion-specifications?dti=0&lc=en-WW) - Modeling Tool by Siemens [Commercial]
- [UA-ModelCompiler](https://github.com/OPCFoundation/UA-ModelCompiler) - Tool to convert OPC UA Information models in Model.xml format to NodeSet2.xml Format. [MIT]
- [UML2OPCUA](https://github.com/model-UA/papyrus-opcua-plugin) - Papyrus plugin to model OPC UA Information models with Papyrus
- `deprecated` [FreeOpcUa/opcua-modeler](https://github.com/FreeOpcUa/opcua-modeler) - Free OPC UA Modeler is a tool for designing OPC UA address spaces [GPL-3.0]

### Online Tools

_Tools available online to help with OPC UA components or Information Models._

- [OPC UA NodeSet Validator](https://apps.opcfoundation.org/NodeSetValidator/) - Check NodeSet XML Files against Word Documents following the OPC Foundation Specification Template.
- [OPC UA CloudViewer](https://cloudviewer.umati.app/) - Make the XML NodeSets browsable, by DigitalTwinConsortium ([Source](https://github.com/digitaltwinconsortium/UA-CloudViewer)).
- [OPC UA for Cloud Library](https://uacloudlibrary.opcfoundation.org/) - OPC UA Information Model database with a REST and GraphQL interface ([Source](https://github.com/OPCFoundation/UA-CloudLibrary))

## Server Simulations

_Implementations of Example, Simulation and SampleServer that are running on the internet or can be run local._

- [OPC UA Player](https://github.com/MileBuurmeijer/OPCUA-Player) -  supports replaying OPC UA data from a data file
- [OPC UA Simulation Server](https://www.prosysopc.com/products/opc-ua-simulation-server/) - free (professional Edition can import own information model)
- `opc.tcp://opcua.rocks:4840` - Demo Server based on open62541
- `opc.tcp://opcua.umati.app:4840` - [umati Demo Server](https://github.com/umati/Sample-Server) implementing different umati endorsed companion specifications
- `opc.tcp://opcua2.umati.app:4840` - [umati Demo Server 2](https://github.com/umati/Sample-Server-asyncio) implementing different umati endorsed companion specifications
- `opc.tcp://milo.digitalpetri.com:62541/milo` - [Demo Server](https://github.com/eclipse/milo#public-demo-server) based on eclipse/milo
- [Azure OPC UA Sample](https://github.com/Azure-Samples/iot-edge-opc-plc) - sample server in c# 
- [List of publicly availavle OPC UA Servers and Clients](https://github.com/node-opcua/node-opcua/wiki/publicly-available-OPC-UA-Servers-and-Clients)

## Server and client applications

_Implementations of server and client applications and other examples._

- [UA-CloudDashboard](https://github.com/barnstee/UA-CloudDashboard) - A cloud-based, dockerized dashboard for displaying OPC UA PubSub telemetry data, read directly from an Azure IoT Hub. [MIT]
- [UA-CloudLibrary](https://github.com/OPCFoundation/UA-CloudLibrary) - The reference implementation of the UA Cloud Library [MIT]
- [CloudLib GraphQL](https://github.com/cesmii/CloudLib) - CloudLib GraphQL Prototype by CESMII for the OPC UA for Cloud Library OPC-Foundation JWG [proprietary]
- [OPCUA2AAS](https://github.com/barnstee/OPCUA2AAS) - OPC UA Server that can generate an Industry 4.0 Asset Admin Shell from its info model. [MIT]
- [MQTTPublisherMVP](https://github.com/barnstee/MQTTPublisherMVP) - Minimum Viable Product for an MQTT-based OPC UA PubSub Publisher for industrial cloud telemetry. [MIT]
- [umati Dashboard](https://umati.app) - umati community online dashboard - [Specification](https://showcase.umati.org)
- [umati Sample Server](https://github.com/umati/Sample-Server) based on [open62541](https://github.com/open62541/open62541) [MPL-2.0]
- [umati Sample Server 2](https://github.com/umati/Sample-Server-asyncio) based on [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio) [APL-2.0]
- [umati Sample Server 3](https://github.com/umati/SampleServer-node-opcua) based on [node-opcua](http://node-opcua.github.io/) [APL-2.0]
- [OPCModbusUAServer](https://github.com/BoBiene/OPCModbusUAServer) - An open source OPC UA server for Modbus TCP devices [MIT]
- [OPC Router Docker Sample](https://github.com/OPC-Router/opc-ua-umati-mssql-grafana) - A very easy to use sample showcasing data transfers from a umati server to a SQL database.
- [OPC UA Thermometer with Akri](https://docs.akri.sh/demos/opc-thermometer-demo) - A demo of Akri - Discovering and Using OPC UA Thermometers [APL-2.0]
- [OPC UA Transformer](https://github.com/alw-iwu/opcua-transformer) - Transforms OPC UA Server address space into RDF data structure [APL-2.0]
- [OPC UA for Joining Systems](https://github.com/umati/UA-for-Industrial-Joining-Technologies) - Test clients and servers based on OPC UA for Joining Systems developed by VDMA Industrial Joining Technologies working group. [APL-2.0]
- [OPC UA primer](https://github.com/ntd/opcua-primer) - A sample OPC UA server based on `open62541` and on a model design XML. [MIT]
- [opcua-skills/plug-and-produce](https://github.com/opcua-skills/plug-and-produce) - Plug-and-Produce System Architecture for Robotic Applications using OPC UA [proprietary]
- [convertersystems/opc-ua-samples](https://github.com/convertersystems/opc-ua-samples) - Sample HMIs using OPC Unified Architecture (OPC UA) and Visual Studio. [MIT]

## Gateways (OPC Classic)

coming soon

## Community

- [Stack Overflow](https://stackoverflow.com/tags/opc-ua) - Questions related to OPC UA in Stack Overflow.
- [OPC Foundation Twitter](https://twitter.com/OPCFoundation) - Official OPC Foundation account that shares update about the OPC UA standard.
- [OPC Foundation Podcast](https://opcfoundation.org/resources/podcast/) - Official OPC Foundation podcast that gives insight into the OPC UA technology, applications in different industries and answers questions from the audience.
- [OPC Foundation Ebooks](https://opcfoundation.org/resources/ebooks/) - Information about OPC UA technology and applications in different industries as contributions by various authors.

## Related Lists

- [open62541's List of Open Source OPC UA Implementations](https://github.com/open62541/open62541/wiki/List-of-Open-Source-OPC-UA-Implementations) - List of open source OPC UA implementations.
- [Agile-IoT/awesome-open-iot](https://github.com/Agile-IoT/awesome-open-iot) - A curated list of awesome open source IoT frameworks, libraries and software.

## Tutorials

- [From modelling to execution – OPC UA Information Model Tutorial](https://opcua.rocks/from-modelling-to-execution-opc-ua-information-model-tutorial/) - Complete walkthrough from creating a custom OPC UA information model, compiling this model into an OPC UA `NodeSet2.xml` file, and then using the `open62541` OPC UA stack to create a running OPC UA server.
- [Visualizing OPC UA Information Model using Graphviz](https://opcua.rocks/visualizing-opc-ua-information-model-using-graphviz/) - Tutorial on how to use Graphviz to visualize OPC UA Information Models.
- (WIP) [OPC UA Tutorials](https://github.com/AndreasHeine/opcua-tutorial) - Tutorial for [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio)

## Contribute

Contributions are welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[CC0 1.0 Universal](LICENSE)
