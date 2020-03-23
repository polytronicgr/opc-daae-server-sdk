## OPC DA/AE Server SDK

### Introduction
The OPC DA/AE Server SDK offers a fast and easy access to the OPC Data Access (DA) and OPC Alarms&Events (AE) technology. Develop OPC DA 2.05a, 3.00 00 and OPC AE 1.00, 1.10 compliant Servers with any compiler capable of either

- generating a Windows DLL (OPC DA/AE Server SDK DLL). This results in a generic server executable plus a Windows DLL.
- generating a .NET 4.8 assembly (OPC DA/AE Server SDK .NET). This results in a generic server executable plus a .NET 4.8 assembly.
- generating one server executable without the use of any DLLs (Source code version required).

The developer can concentrate on his application and servers can be developed fast and easily without the need to spend a lot of time learning how to implement the OPC specifications. The server API is easy to use and many OPC specific functions, e.g. creating a group or adding an item to a group are handled by the framework. Even the complex asynchronous read/write handling is handled by the framework.

The “Framework” includes all OPC DA 2.05a, 3.00 and OPC AE 1.00, 1.10 handling and ensures the OPC compliance. It is implemented as a generic C++ based executable.

The “Server API” defines easy to use interface functions required for developing OPC DA/AE compliant servers. The OPC server is supplied as an EXE file with full C++ source code and the application adaptation part in 1 file. This imposes some limitations on the adaptation possibilities but makes the adaptation much easier and quicker. By using this API OPC servers can be easily implemented by adapting just a few functions, e.g. there are only 5 functions that have to be implemented for an OPC DA Server. The functions handle the configuration of the server and the read/write functionality of items.

The OPC DA/AE Server SDK offers unique features for performance and functionality improvements of the developed OPC Server like Event Driven Mode for Device Access; Dynamic address space with items added when they are first accessed by a client and removed when they are no longer in use; Item browsing can be implemented to browse the cache or the device/database.

### Licenses & Pricing
The OPC DA/AE Server SDK follows a dual-license: 

#### Binaries
The OPC DA/AE Server SDK is licensed under the MIT License. A very liberal license that encourages both commercial and non-commercial use. This version features:

- Can be used for commercial purposes.
- Full featured without limitations or restrictions.
- There are no separate runtime fees or royalties needed.

Not available for this version are:

- Warranty of any kind. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
- Technical Support. See section Commercial Support for more information on how to get support.
- Updates and fixes.

#### Source Code
The OPC DA/AE Server SDK source code is available under a commercial source code license. There are no separate runtime fees or royalties.

Our Source Code License Agreement (https://technosoftware.com/documents/Source_License_Agreement.pdf) allows the use of the OPC DA/AE Server SDK source code to develop software on and for all supported operating system and hardware platforms.

### Commercial Support
Purchase commercial suppourt via https://technosoftware.com/product/standard-support/ for a single Standard Support request (two hours support time budget, five business days maximum initial response time, although we usually answer within one to two business days) for EUR 390,00 from Technosoftware GmbH.

By purchasing support, you agree to our Support Service Agreement at https://technosoftware.com/documents/Support_Services_Agreement.pdf