# Cattle-Health-Monitoring-System---IoT-Security

The 21st century has witnessed a remarkable trans- formation driven by the Internet of Things (IoT) and smart computing. Just a decade ago, the data-powered services they offer seemed like science fiction. Today, these technologies are woven into the fabric of our lives, influencing everything from our homes (smart homes) to our commutes (autonomous vehicles) and healthcare (wearable health trackers). Agriculture is no exception. Farmers and entrepreneurs alike are adopting a range of smart devices, from sensors that monitor crop health and soil moisture to drones that automate tasks like pesticide application. As an integral part of smart farming arises the livestock health management where the parties involved remotely monitor the cattle health with the use of sensors and other devices. However, this interconnectedness comes with a risk: increased vulnerability to cyberattacks. These attacks could have a devastating impact on economies heavily reliant on agriculture. To address this challenge, this work delves into the critical issues of security and privacy within the smart farming’s livestock health ecosystem. We also proceed to obtain a comprehensive understanding on how a particular attack can affect the entire system.

Shown below is the block diagram of our system. It comprises of - 
1. A toy smart farm scenario equipped with Zigbee device on that acquire the cattle data
2. A Zigbee edge device that communicates the acquired data to the RaspberryPi
3. Network Packet Broker that monitors the traffic flow in the entire network. The entire data is recorded and observed on Wireshark (on the cloud).
4. A CISCO switch that interconnects the RaspberryPi, Server, Network Packet Broker and the other devices that are to be connected in the network


<img width="1641" alt="Screenshot 2024-05-08 at 2 41 30 PM" src="https://github.com/AishwaryaKoushik/Cattle-Health-Monitoring-System---IoT-Security/assets/161193220/91f621eb-ff85-4644-9374-4048cd9e16ee">


Among the various attacks that can be performed on the network, one of them that poses a serious threat and also tends to have a devastating impact on the system is the Denial of Service attack. The overall strategy is to carry out a Denial of Service (DoS) attack specifically targeting the Raspberry Pi device in the network. By successfully executing a DoS attack on the Raspberry Pi, the attacker aims to overwhelm and incapacitate this device, preventing it from performing its intended function of data transmission. This would effectively disrupt the entire data collection and monitoring process, as the server would no longer receive the sensor data from the field.



