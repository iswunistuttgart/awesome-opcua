# Awesome OPC UA

A curated list of awesome OPC UA resources. Inspired by awesome-... stuff.

- [Awesome OPC UA](#awesome-opcua)
  - [OPC UA Standards Documents](#opc-ua-standards-documents)
    - [Resources](#resources)
      - [Online Resources](#online-resources)
      - [Books](#books)
      - [Articles](#Articles)
      - [Videos](#Videos)
    - [Software](#software)
      - [SDKs](#sdks)
      - [Test Clients](#test-clients)
      - [Modelling Tools](#modelling-tools)
      - [Online Tools](#online-tools)
      - [SimulationServer](#SimulationServer)
      - [Sever and Client examples](#Server-and-client-applications)
    - [Gateways  (OPC Classic)](#Gateways (OPC Classic))

## OPC UA Standards Documents

_Released OPC UA Specifications._

- [OPC Unified Architecture Specification](https://opcfoundation.org/developer-tools/specifications-unified-architecture) - OPC UA Specification published by the OPC Foundation. Needs registration for download.
- [OPC UA Information Models](https://opcfoundation.org/developer-tools/specifications-opc-ua-information-models) - OPC UA Companion Specifications released by the OPC Foundation. Needs registration for download.
- [Git Repos containing the most of the nodsets](https://github.com/OPCFoundation/UA-Nodeset) - easy way to get the nodeset files without registration 
- [OPC UA Online Reference](https://reference.opcfoundation.org/v104/) - Online versions of OPC UA specifications and information models. Harder to read than the pdf versions due to each chapter being a separate site. Search function over all parts of the standard and the information models.

## Resources

*Information material apart from the standards documents.*

### Online Resources

*Information material available online.*

- [OPC Foundation Online Reference](https://reference.opcfoundation.org/v104/)
- [OPC Foundation UA Profile Reporting Visualization Tool](https://apps.opcfoundation.org/ProfileReporting/index.htm) - Overview of OPC UA Profiles.
- [OPC Foundation UA Profile Reporting Visualization Tool with drafts](https://apps.opcfoundation.org/ProfileReporting/index.htm?All=true) - Same as above including (stable) drafts.
- [OPC Foundation Templates](https://opcfoundation.org/Guidelines-And-Templates/) - Templates for (joint) working groups. Including MS Visio shapes for OPC UA.
- [OPC Foundation OPC UA Wiki](http://wiki.opcfoundation.org/index.php?title=Main_Page) - OPC UA Wiki of the OPC Foundation. **Not up to the latest specification state!**
- [OPC Foundation Information Modelling Best Practices](https://opcfoundation.org/wp-content/uploads/2020/09/OPC-11030-Whitepaper-UA-Modeling-Best-Practices-1.00.00.pdf) - Whitepaper intended to provide best practices while creating OPC UA information models. 
- [List of Collaborations Groups on Companion Specifications](https://docs.google.com/spreadsheets/d/10SOpad6uu7JA5ZSpccVyqaqkyhYBiIXqNus28-1cJtU/edit#gid=1248333029) - Overview of the different standardization activities
- [https://opcua.rocks/](https://opcua.rocks/) - blog about OPC UA
- [https://sandervandevelde.wordpress.com/](https://sandervandevelde.wordpress.com/) -  IoT Blog (use also OPC UA in some projects)
- [OPCUA CS Graph](https://iswunistuttgart.github.io/opcua-cs-graph/) - Graph that shows the dependencies zwischen Companion Specification
- [Github Orga of the OPC Foundation](https://github.com/OPCFoundation) - different software projects and reference implementations

### Books

*Books about OPC UA.*

- *Wolfgang Mahnke, Stefan-Helmut Leitner, Matthias Damm*, OPC Unified Architecture. *Springer; 2009*, ISBN: 978-3540688983.


### Articles

[PROFANTER, Stefan, et al. OPC UA versus ROS, DDS, and MQTT: performance evaluation of industry 4.0 protocols. In: Proceedings of the IEEE International Conference on Industrial Technology (ICIT). 2019.](https://mediatum.ub.tum.de/doc/1470362/file.pdf)

Performance evaluation

[H. Haskamp, M. Meyer, R. Möllmann, F. Orth and A. W. Colombo,  "Benchmarking of existing OPC UA implementations for Industrie  4.0-compliant digitalization solutions," *2017 IEEE 15th International Conference on Industrial Informatics (INDIN)*, Emden, 2017, pp. 589-594, doi: 10.1109/INDIN.2017.8104838](https://ieeexplore.ieee.org/abstract/document/8104838)

Compare implementations for OPC UA

[S. Friedl, T. Heinemann, A. Lechler  "Designentscheidungen für OPC-UA-Informationsmodelle" *WT online 5-2020 , 2020, pp. 589-594](https://www.ingenieur.de/fachmedien/wt-werkstattstechnik/ausgaben-wt-werkstattstechnik-online/inhalte-der-online-ausgabe-5-2020/)

(German) Description of OPC UA Design decisions in OPC UA for Weighing Technology and OPC UA for Machine Tools

[F. Kretschmer, C. Dripke, and A. Wohlfeld “Der Trend zur branchenorienterten OPC UA Companion Specification und deren Herausforderungen,” Marburg, 2018](https://www.der-maschinenbau.de/markt-trends-technik/der-trend-und-seine-herausforderungen/)

(German) Descriptes the Trends of OPC UA  Companion Specification

### Videos

- [What is OPC? UA in a Minute](https://www.youtube.com/watch?v=-tDGzwsBokY)
- [20200622 02 OPC UA Technology](https://www.youtube.com/watch?v=OQC_kVYisS8)  - 20 min Introduction into OPC UA (OPC UA Day 2020)
- [OPC UA Security Deep Dive by Randy Armstrong (Chair of OPC UA Security Working Group), Dec 2020](https://www.youtube.com/watch?v=pa82WydVtPY)


## Software

*Software for creating OPC UA Servers, Clients, Publishers, Subscribers or Information Models.*

### SDKs

*SDKs to create OPC UA components.*

#### C / C++

- [open62541](https://open62541.org/) - Open Source C implementation for Server/Client and Pub/Sub.
- [FreeOpcUA](http://freeopcua.github.io/) - Server/Client
- [OpenOpcUA](http://www.openopcua.org/)  - Server/Client
- [OpenScadaUA Interface](http://oscada.org/websvn/filedetails.php?repname=OpenSCADA&path=%2Ftrunk%2FOpenSCADA%2Fsrc%2Fmoduls%2Fdaq%2FOPC_UA%2FlibOPC_UA%2FlibOPC_UA.h) - only Server
- [ASNeG](https://github.com/ASNeG/OpcUaStack)  - Server/Client
- [uaf](https://github.com/uaf/uaf)  - Client (wrapper over proprietary sdk)
- [UACL/CPP -](https://gitlab.com/falko.wiese/uacl_cpp) Server (wrapper over proprietary sdk)
- [S2OPC](https://gitlab.com/systerel/S2OPC) - Client/Server
- [dataFeed OPC UA](https://data-intelligence.softing.com/de/produkte/datafeed-opc-sdks/datafeed-opc-ua-c-server-client-sdk-for-windows/) - Server/Client proprietary (Softing)
- [OPC UA SDK/Toolkit für Embedded-Geräte](https://industrial.softing.com/de/produkte/opc-ua-and-opc-classic-sdks/uatoolkit-embedded.html) - C implementation for Server/Client and Pub/Sub
- [Prosys OPC UA C/C++ SDKs](https://www.prosysopc.com/products/opc-ua-cplusplus-sdk/) - Server/Client proprietary
- [Unified Automation C/C++ SDKs](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html)  - Server/Client proprietary

#### C\#

- [UA.NET Standard](https://github.com/OPCFoundation/UA-.NETStandard) - Server/Client
- [UACL/CS](Client/Server (wrapper over proprietary sdk)) - Client/Server (wrapper over proprietary sdk)
- [opc-ua-client](https://github.com/convertersystems/opc-ua-client)-  only Client
- [LibUA](https://github.com/nauful/LibUA) - Server/Client
- [Träger](https://opcua.traeger.de/) - Server/Client proprietary
- [dataFeed OPC UA](https://data-intelligence.softing.com/de/produkte/datafeed-opc-sdks/datafeed-opc-ua-net-standard-sdks/) - Server/Client proprietary (Softing)
- [QuickOPC](https://www.opclabs.com/products/quickopc) - Client proprietary (OPC Labs)
- [OPC UA .NET SDK](https://www.prosysopc.com/products/opc-ua-dotnet-sdk/) - Server/Client proprietary (Prosys)
- [PicoOPC](https://www.opclabs.com/products/picoopc/for-dotnet) - OPC UA client library proprietary; NuGet pkg (OPC Labs) 
- [Unified Automation .NET SDK](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html)  - Server/Client proprietary

#### Java

- [Eclipse Milo](https://github.com/eclipse/milo) - Server/Client
- [opcua4j](https://code.google.com/p/opcua4j/)  - only Server
- [Prosys OPC UA](https://www.prosysopc.com/products/opc-ua-java-sdk/) -Server/Client proprietary

#### Python

- [uaf](https://github.com/uaf/uaf) - Client (wrapper over proprietary sdk)
- [Python FreeOpcUa](https://github.com/FreeOpcUa/python-opcua)  - Server /Client

#### JavaScript / TypeScript

- [node-opcua](http://node-opcua.github.io/) - Server/Client
- [node-red-contrib-opcua](https://flows.nodered.org/node/node-red-contrib-opcua) - Node-Red Plugin for OPC UA (Server/Client)
- [opcua](https://github.com/HBM/opcua) - only Client

#### Rust

- [opcua](https://github.com/locka99/opcua) - Server/Client

#### Golang

- [opcua](https://github.com/gopcua/opcua) - Server/Client

#### Delphi

- [Sentrol SDK for Delphi](https://www.prosysopc.com/products/opc-ua-sentrol-sdk/) - Server/Client proprietary (Prosys)
- [Unified Automation Delphi SDK](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html)  - Server/Client proprietary

### Test Clients

*Test Clients to check server implementations manually.*

- [UAExpert](https://www.unified-automation.com/products/development-tools/uaexpert.html) - Demo Client developed by Unified Automation (free evaluation license).
- [dataFEED](https://data-intelligence.softing.com/de/produkte/opc-software-plattform/opc-ua-demo-client/) - Demo Client developed by Softing (free)
- [FreeOpcUA](https://github.com/FreeOpcUa/opcua-client-gui) - OpenSource Client based on python
- [Prosys OPC UA Monitor](https://www.prosysopc.com/products/opc-ua-monitor/) - HMI Tool  (Evaluation for Free)
- [OPC UA Browser](https://www.prosysopc.com/products/opc-ua-browser/) - Demo Client developed by Prosys (free evaluation license).

### Modelling Tools

*Tools to create OPC UA Information Models.*

- [UAModeler](https://www.unified-automation.com/products/development-tools/uamodeler.html) - Modeling Tool by Unified Automation.
- [OPC UA Modeler](https://www.prosysopc.com/products/opc-ua-modeler/) - Modeling Tool by Prosys
- [SiOME](https://support.industry.siemens.com/cs/document/109755133/siemens-opc-ua-modeling-editor-%28siome%29-for-implementing-opc-ua-companion-specifications?dti=0&lc=en-WW) - Modeling Tool by Siemens

### Online Tools

*Tools available online to help with OPC UA components or Information Models.*

- [OPC UA NodeSet Validator](https://apps.opcfoundation.org/NodeSetValidator/) - Check NodeSet XML Files against Word Documents following the OPC Foundation Specification Template.
- [OPC UANodeSet WebViewer](https://github.com/barnstee/UANodesetWebViewer) - Make the XML NodeSets browsable.

## Server Simulations

*Implementations of Example, Simulation and SampleServer that are running on the Internet or can be run local.*

- [OPC UA Player](https://github.com/MileBuurmeijer/OPCUA-Player) -  supports replaying OPC UA data from a data file
- [OPC UA Simulation Server](https://www.prosysopc.com/products/opc-ua-simulation-server/) - free (professional Edition can import own information model)
- `opc.tcp://opcua.rocks:4840` - Demo Server based on open62541
- `opc.tcp://opcua.umati.app:4840`- [umati Demo Server](https://github.com/umati/Sample-Server) based on open62541, implementing different umati endorsed companion specifications
- `opc.tcp://milo.digitalpetri.com:62541/milo` - [Demo Server](https://github.com/eclipse/milo#public-demo-server) based on eclipse/milo
- [List of publicly availavle OPC UA Servers and Clients](https://github.com/node-opcua/node-opcua/wiki/publicly-available-OPC-UA-Servers-and-Clients)

## Server and client applications

*Implementations of server and client applications and other examples*

- [OpcUaWebDashboard](https://github.com/barnstee/OpcUaWebDashboard) - A cloud-based, dockerized dashboard for displaying OPC UA PubSub telemetry data, read directly from an Azure IoT Hub. 
- [UA-CloudLibrary](https://github.com/barnstee/UA-CloudLibrary) - Swagger prototype by @branstee for the OPC UA for Cloud Library OPC-Foundation JWG
- [CloudLib GraphQL](https://github.com/cesmii/CloudLib) - CloudLib GraphQL Prototype by CESMII for the OPC UA for Cloud Library OPC-Foundation JWG
- [UA-CloudLibrary](https://github.com/OPCF-Members/UA-CloudLibrary) - Reference implememtation UA-CloudLibrary **REMARK: OPC-F members only for now**
- [OPCUA2AAS](https://github.com/barnstee/OPCUA2AAS) - OPC UA Server that can generate an Industry 4.0 Asset Admin Shell from its info model.
- [MQTTPublisherMVP](https://github.com/barnstee/MQTTPublisherMVP) - Minimum Viable Product for an MQTT-based OPC UA PubSub Publisher for industrial cloud telemetry.
- [umati Dashboard](https://umati.app) - umati community online dashboard - [Specification](https://showcase.umati.org)

## Gateways (OPC Classic)

coming soon
