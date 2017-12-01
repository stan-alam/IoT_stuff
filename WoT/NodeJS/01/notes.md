## Web Of Things using NodeJS!

**Some background on 'IoT'**

"The vision of a world where tiny computer structures
with sensors and communication interfaces are embedded
in the infrastructure  of cities, cars, offices..etc

**The Web of Things** is a specialization of IoT that
uses what made the web so sucessful and it applies it 
to embedded devices in order to make the latest developments
of IoT available to devs. 

## 1.1 Defining the Internet of Things

The vision of IoT is where the world is much 
more than the collection of multimedia content
: it extends into the physical, real-time-world
using small/tiny computers.

# Definition :

	The IoT is a system of physical objects that can be
	discovered, monitored, controlled, or interacted with
	by electronic devices that communicate over various
	networking interfaces and eventually can be connected
	to the wider internet.
	
A *smart thing* is a physical object that's digitally
autgemented with one or more of the following :

	* Sensors (temp, light, motion..etc)
	
	* Actuators (displays, sound, motors..etc)
	
	* Computation ( can run progs and logic )
	
	* Communcication interfaces (wired or wireless)
	
	Tags: NFC/RFID, QR 
	
	Devices: iBeacon/BLE, Arduino rPI
	
	Machines: Hue lights 

      The most profound technologies are those that disappear. They weave themselves into the
      fabric of everyday life until they are indistinguishable from it.…Silicon-based information
      technology, in contrast, is far from having become part of the environment. More
      than 50 million personal computers have been sold, and nonetheless the computer
      remains largely in a world of its own. It is approachable only through complex jargon
      that has nothing to do with the tasks for which people actually use computers.
      **Mark Weiser, “The Computer for the Twenty-First Century,” 1991**




Things in the IoT can range from simple tagged products such as FedEx with auto-ID tag,
QR codes, NFC, RFID tags for real time tracking. Communication method can be wifi, bluetooth, Zigbee

**There is no unique protocol for IoT**

The point of WoT is not to recreate the wheel.

## 1.2 Web of Things

IoT is limmited to physical device protocols, WoT already uses the web which is scalable.

**WoT is only concerned with the highest level of OSI layer - 7**
(which handles applications, services and data) This high level of abstraction allows for the possibility to connect data and services from many devices regardless of the actual transport
protocols they use.)

In contrast, the **Internet of Things** works on a single Application-level protocol and usually **focuses on the lower layers of the OSI stack**

cross-layer TCP/HTTP optimizations allow devices to run on 8KB of ram. JS community has allowed massive developments in shifting the workload from devices to client apps and to the cloud.

**The essence of REST** -- is an architectural style for developing for developing distributed apps and is the basis upon which the modern web is built. Focus on creating loosely using URIs, HTTP, and standardized media types. Abstracting the services from their application-specific semantics thanks to a **uniform interface** (HTTP verbs and response codes) makes it easy to build
loosely coupled services because it provides a simple mechanisms for clients to select the best possible representations for interactions.

This means you can interact with Things via web browser and explore the web of things as you would when surfing the web, via links ...or to other devices(Things). **Real Time Data** can be streamed to the browser, such as pollution sensors etc.

## 1.2.3

 "Sir Tim Berners-Lee developed the web (HTTP and HTML)"

**Smart Homes and WoT**

Wot is an alternative to where web languages are the baseline, the minimal API that devices should offer either directly or indirectly through gateways.

## 1.3.4 Smart cities build on Rock 'n Roll

and energy grids ... and such...


  1. Deploy wireless sensor nodes.

  2. Collect data

  3. Analyze data in the lab.

  4. Write reports

  6. Create Actions on reports


## 1.3.5 Smart Manufacturing and industry 4.0

**Germany has been** at the forefront of this change driven by companies -- Bosch, Siemens, SAP.

The two main aspects of this is ... 1. Access to unparalleled amounts of data. Connecting machines to the Internet and feeding them real-time data in one step toward more transparent and efficient industrial systems.

1.3.6-7 **Industry and the Web of Things, and Marketing 2.0**

1.4 **Web of things is just internet of things on steroids**

1.4.1 **Easy programming**

Wot protocol can easily be used to read and write data from to devices and are much simpler to use and faster to learn than the complex IoT protocols. The devices will offer a web API interface for devs.

## 1.4.2

**The reason web standards have reached such popularity is that they're entirely open and free**
Hardly any risk for changing overnight. This ensures that data can be rapidly and easily moved across systems, hence HTTP and REST are a good choice.

1.4.3 **Fast and easy to deploy, maintain, and integrate**

WoT there's no risk that web will suddenly stop working and require an upgrade unlike IoT stuff, IoT = spaghetti.

1.4.4 **Loose coupling between elements**

Http is loosely coupled by design because of the API specification which is essentially a contract between actors on the web and leaves little room for ambiguity.

1.4.5 **Widely used security and privacy mechanisms**

Security - to ensure that no one can access data or a device they  aren't supposed to use.

Privacy -- personal information must be kept safe

**Advantage of using web over IoT is that the standards/protocols have and are being tested, vs where IoT, the protocols are custom.**

1.4.6 There are still shortcomings, exposing a device to the web also allows risk for DDos attacks, hostile nation attacks and unauthorized data mining.

## Summary
WoT does not care about underlying networking protocols or standards, or how to integrate many devices to one protocol. The ecosystem is based on the HTTP standdards/specs

Using simple and ubiquitous web standards such as HTTP, Web Socket, and
JSON to integrate all sorts of devices and applications makes it much easier to
rapidly prototype all sorts of applications and then scale them for enterprise grade
solutions.
