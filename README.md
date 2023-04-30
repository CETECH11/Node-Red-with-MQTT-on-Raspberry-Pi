# Node-Red-with-MQTT-on-Raspberry-Pi

![alt text](https://hackster.imgix.net/uploads/attachments/1584103/_YdmtJRhaG5.blob?auto=compress%2Cformat&w=900&h=675&fit=min)

Node-RED is a flow-based development tool for visual programming of hardware devices, and it is widely used for the Internet of Things. In addition, Node-RED provides a web browser-based flow editor, which can be used to create JavaScript functions. So, in this tutorial, I'll teach you how to integrate Qubitro with Raspberry Pi via Node-RED.

What is MQTT?
MQTT stands for Message Queuing Telemetry Transport. MQTT is a machine-to-machine connectivity protocol. It is useful for connections with remote locations where we want to send just a few bytes of data or our sensor values. It is a system where you can publish and receive messages as a client.

By using MQTT you can send commands to control outputs, read and publish data from sensors and much more. Therefore, by using MQTT you can establish communication between multiple devices. Using MQTT you can send a command to a client to control output, or you can read data from a sensor and publish it to a client. There are two main terms in MQTT i.e. Client and Broker. Let’s discuss what client and broker are.

MQTT Client: An MQTT client is any device that runs an MQTT library and connects to an MQTT broker over a network. Both publisher and subscriber are MQTT clients. The publisher and subscriber refer that whether the client is publishing messages or subscribing to messages.

MQTT Broker: The broker receives all messages, filters the messages, determines who is subscribed to each message, and sends the message to these subscribed clients.


![alt text](https://hackster.imgix.net/uploads/attachments/1583915/image_vXXOTm1Dts.png?auto=compress%2Cformat&w=740&h=555&fit=max)

Node-RED is an effective open-source platform for developing Internet of Things (IoT) applications that aim to make the programming part simpler.

Node-RED is a web-based application that employs visual programming to let you link code fragments, or "nodes, " together to carry out a task. When the nodes are connected, they form flows.
IBM created open-source Node-RED software.
The Raspberry Pi flawlessly runs Node-RED.
Because it is a visual programming tool, a wider spectrum of users can use it.
Node-RED allows you to spend less time writing code and more time creating exciting things.


![alt text](https://hackster.imgix.net/uploads/attachments/1583909/171_image.png?auto=compress%2Cformat&w=740&h=555&fit=max)

Node-RED forms it easy to:

access the GPIOs on your RPi;
connect to other devices via MQTT;
For your projects, develop a responsive graphical user interface;
Interact with outside services.
Get information from the internet, such as stock prices, emails, and weather forecasts;
Organize time-based events;
Keeping and getting information from a database.
Now that we are aware of Node-Red, okay. We need a physical medium to install Node-Red, and the Raspberry Pi will serve that purpose.

![alt text](https://hackster.imgix.net/uploads/attachments/1544797/pcbway_55Vl7NMRFG.JPG?auto=compress%2Cformat&w=740&h=555&fit=max)

You must check out [PCBWAY](https://www.pcbway.com/) for ordering PCBs online for cheap!

You get 10 good-quality PCBs manufactured and shipped to your doorstep for cheap. You will also get a discount on shipping on your first order. Upload your Gerber files onto PCBWAY to get them manufactured with good quality and quick turnaround time. [PCBWay](https://www.pcbway.com/) now could provide a complete product solution, from design to enclosure production. Check out their online Gerber viewer function. With reward points, you can get free stuff from their gift shop.
