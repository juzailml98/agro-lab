# agro-lab
<p>an agricultural monitoring project </p>
<p>This project is intend to collect soil data and display the data collected in a website</p>
# application scenario
<ol>
  <li>Collection of data in sensor nodes</li>
  <liTransmission of data collected in nodes to gateway.</li>
<li>Transmission of data collected in gateway to the server.</li>
<li>Visualization of data in website.</li>
  </ol>

Following data to be collected for soil monitoring purpose
  <ol>
<li>Soil PH</li>
<li>NPK</li>
<li>Soil Temperature</li>
<li>Humidity</li>
<li>Soil conductivity</li>
  </ol>

# sensors to be used
  <ol>
<li>Soil NPK:npk sensor rs485</li>
<li>Arduino Soil Moisture Sensor</li>
<li>AM2302 DHT22 Digital Temperature & Humidity 
<li>Sensor</li>
<li>Nodemcu esp8266</li>
<li>Arduino uno</li>
<li>SX1278 Lora Module</li>
<li>Raspberry pi3b+</li>
  </ol>

# technologies to be used
  <ol>
<li>LoraWAN: for interconnecting sensor nodes</li>
<li>Wifi: for connecting Arduino</li>
<li>FLoRa - Framework for Lora: based on the OMNeT++ simulator and and INET framework</li>
<li>Google firebase</li>
  </ol>


# deliverables
  <ol>
<li>Developing a basic soil data collecting device using Arduino,DHT22 temperature sensor, soil moisture sensor</li>
 <li>simple Lora based network using 2 Arduinos</li>
  
<li>Data visualization in google firebase collected from sensors Demonstration </li>
<li>Simulation of Lora network using FloRa</li>
</ol>

# why lora
The IoT industry is bringing lots of technology and solutions to the market with chip manufacturers investing heavily in the market growing the industry exponentially. It isn’t however without its challenges. One of the key challenges in building out the internet of things is ensuring that those “things” or end nodes are in fact able to communicate with the internet. The sheer number of current internet devices is massive and is expected to hit 25 billion by 2020. Any network that supports such an infrastructure needs to have the ability to handle the traffic. These issues don’t include the fact that nodes need to run on some sort of battery power, have weak radios and also are limited in memory and processing power.

IoT devices today use a number of different technologies to support their communications, but none of them are really ideal for the purpose and application of today. Wi-Fi is everywhere at the moment but it uses a lot of energy and transmits lots of data, whilst this is great it isn’t such a perfect solution for IoT devices that don’t have as much energy at their disposal or wish to send small amounts of data. There are also limitations in the modulation techniques used and as such access points can only handle a handful of devices at once.

Bluetooth devices allow local communication but has very limited range in version 4.0. They also require too much power. Even newer Bluetooth Low Energy devices still consume much more power than is necessary. Up to recently the best available technology on the market was considered to be ZigBee low power modules that transmit over greater distances and at low transfer rates, usually a few kilometers in clear path.


LoRa technology was developed by a company called Semtech and it is a new wireless protocol designed specifically for long-range, low-power communications. LoRa stands for Long Range Radio and is mainly targeted for M2M and IoT networks. This technology will enable public or multi-tenant networks to connect a number of applications running on the same network.

LoRa Alliance was formed to standardize LPWAN (Low Power Wide Area Networks) for IoT and is a non-profit association which features membership from a number of key market shareholders such as CISCO, actility, MicroChip, IBM, STMicro, SEMTECH, Orange mobile and many more. This alliance is key to providing interoperability among multiple nationwide networks.

Each LoRa gateway has the ability to handle up to millions of nodes. The signals can span a significant distance, which means that there is less infrastructure required, making constructing a network much cheaper and faster to implement.

LoRa also features an adaptive data rate algorithm to help maximize the nodes battery life and network capacity. The LoRa protocol includes a number of different layers including encryption at the network, application and device level for secure communications.



