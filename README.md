## Design and Implementation of Smart Cart using Labview 
<p align="center" >
 <b>
  <span style="color:red"> Welcome to the Smart Cart Using LabVIEW project !</span> 
 </b>
 </p>
<p align="justify" >    
This major project focuses on the design and implementation of a Smart Cart using LabVIEW.
In this present generation most of the people prefer to visit supermarkets and hypermarkets to buy the products of their needs right from the food products to the household usage items. In general these hypermarkets and supermarkets provide trolleys to their customers to have a hand free convenient shopping. Though the entire shopping goes well most of the customers get stressed out by seeing those long queues and hours of waiting near the bill counters. Even after coming up with some temporary solutions for this highly time consuming problem like increasing the man power in bill counters it didn’t bring a big difference. The aim of the paper is to overcome this problem with a permanent solution. Here we introduce a new system called <b>“SMART CART”</b> where we can most probably eliminate the time taking process at the counters. This ultimately leads to the customer satisfaction from the starting of the shopping till the end point. And also adds benefits like reduction of man power requirement and high efficiency with low expenses. In this competitive world of technology this brings a drastic change benefiting both customers and also retail industries by the usage of automated devices. The idea is implemented using <b>"LabVIEW software"</b> and <b>"hardware MyRIO"</b>. </p>

 # Introduction
 <p align="justify" >
 In an era where technology continuously evolves to simplify daily tasks and enhance efficiency, the development of smart systems has become increasingly prominent. The project <b>'Design and Implementation of Smart Cart using LabVIEW'</b> aims to integrate advanced technologies into the realm of shopping carts, transforming traditional carts into intelligent, automated assistants. Leveraging the capabilities of LabVIEW, a powerful graphical programming platform, this project endeavors to create a seamless shopping experience by incorporating features such as obstacle detection, automated navigation, and real-time data analysis. By merging cutting-edge hardware with sophisticated software, this endeavor seeks to revolutionize the shopping landscape, offering consumers a glimpse into the future of retail convenience and automation.</p>

# Purpose
The purpose of the smart cart is as shown in below picture.

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/8090ec69-c3d6-442b-9ec0-5043a6109b26)

<p align="justify" >
The motivation behind this venture is to actualize a programmed shopping basket that gives awesome accommodation and proficiency to clients, Help clients effectively find the coveted items. Our objective incorporates keeping away from impacts with obstructions and distinguishing available courses, gathering client input and upgrading the way required to oblige the shopping rundown, and educating client when the truck is blocked.</p>

# Proposed System
<p align="justify"> 
The proposed system aims to revolutionize the shopping experience by introducing a high-tech, cost-effective solution tailored for supermarkets and malls. The Smart Shopping Cart, which has meticulously designed to enhance convenience and security while minimizing theft risks. Leveraging hardware components such as <b>Bluetooth (HC-05), MyRio, and PIR sensor</b>, the system ensures robust performance and seamless integration. MyRio serves as the bridge between hardware and software, facilitating efficient communication. The inclusion of a PIR sensor acts as a deterrent against theft, enhancing the safety of goods within the cart. The software application is developed using Android Studio, offering a user-friendly interface for seamless interaction. Upon scanning a unique QR code assigned to each cart, customers initiate the shopping process. Subsequently, the application establishes a connection between the customer's device and the shopkeeper's MyRio via Bluetooth. This connection enables real-time updates, allowing customers to add or remove items by scanning their barcodes. Upon completion of shopping, customers can signal completion through the app, generating a detailed bill that includes itemized costs and total expenses. Finally, the system streamlines the payment process, offering a hassle-free checkout experience. Through this comprehensive system, the proposed solution aims to elevate the shopping experience, ensuring efficiency, convenience, and security for all stakeholders involved.</p>

# Module Description
<p align="justify">
The design and implementation of the Smart Cart using LabVIEW combines advanced hardware integration with sophisticated software programming. Leveraging LabVIEW's graphical programming environment, the project aims to create a seamless shopping experience by integrating features such as obstacle detection, automated navigation, and real-time data analysis. Through meticulous design and implementation, this endeavor seeks to revolutionize traditional shopping carts, offering a glimpse into the future of retail convenience and automation. The following sections discusses the block diagram and required components for this project.</p>

<h3> Components Required </h3>

<table>
  <tr>
    <th>Hardware Components</th>
    <th>Software Components</th>
  </tr>
  <tr>
    <td><ul>
  <li>Bluetooth Module (HC-05) </li>
  <li>PIR Sensor</li>
  <li>NI-MyRIO</li>
</ul></td>
    <td><ul>
  <li>LabVIEW </li>
  <li>Android Studio</li>
</ul></td>
  </tr> 
</table>

<h3> Hardware Components </h3>

 <ul>
  <li> <p align="justify">
   <b> Bluetooth Sensor:</b> The Bluetooth sensor, specifically the HC-05 module, facilitates wireless communication between the smart cart and external devices such as smartphones or tablets. It enables seamless data transfer and interaction, allowing users to control the cart remotely and receive real-time updates on their mobile devices.</p>
  </li>
  <li><p align="justify">
   <b>PIR Sensor:</b> The Passive Infrared (PIR) sensor serves as a motion detection device, detecting heat emitted by nearby objects or individuals. In the context of the smart cart, the PIR sensor enhances security by detecting unauthorized movements or potential theft within the vicinity of the cart.</p>
  </li>
  <li><p align="justify">
   <b>NI-MyRIO:</b> The National Instruments MyRIO is a versatile embedded hardware platform designed for real-time control and data acquisition applications. It serves as the central processing unit of the smart cart, facilitating integration between various hardware components and enabling efficient communication with the software interface.</p>
  </li>
 </ul>

<h3> Software Components </h3>
  <ul>
  <li> <p align="justify">
  <b>LabVIEW:</b> LabVIEW is a graphical programming environment developed by National Instruments, commonly used for data acquisition, instrument control, and industrial automation. In the context of the smart cart project, LabVIEW is utilized to develop the software interface, incorporating features such as obstacle detection, automated navigation, and real-time data analysis.</p>
  </li>
   <li> <p align="justify">
<b>Android Studio:</b> Android Studio is the official Integrated Development Environment (IDE) for Android app development, providing a comprehensive suite of tools for designing, building, and testing Android applications. In this project, Android Studio is used to develop the mobile application that interfaces with the smart cart, allowing users to control the cart, scan products, and view real-time updates on their Android devices.</p>
   </li>
  </ul>
<h3> System Design and Architecture  </h3>
<p align="justify">
 The system design and architecture of the Smart Cart project form the backbone of its functionality and performance. It encompasses the interconnection and interaction between various hardware and software components, ensuring seamless operation and efficient communication.</p>
 <p align="justify">
 In the proposed, Smart Cart (Fig.1) shows the block diagram and it consists of MyRIO, Sensor, Bluetooth module, and power supply as the major blocks. All these blocks are connected as shown in fig 2. </p>

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/eef36e47-08a5-4ea5-a163-42bf6fe7f103)

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/7aa44adf-db56-45b9-9713-cd4f6b955406)

## Methodology
<p align="justify">
The first part of the module is to store trolley ID, so the Bluetooth module is set to read state and when Bluetooth is connected to the application it receives a message <b>“Trolley”</b>, with that shopping starts and whenever item is added using app, MyRIO receives ID’s to store the items added to the cart by comparing ID’s. Best part is security whenever the item is added; MyRio gives a chance to put a hand in it.</p> 
<p align="justify">
PIR detects the motion of the object where the access will be granted only when the barcode of the item is scanned either for adding item or deleting item and for all other cases access will be denied to add item or delete item. So, when the shopping is done, for verification, the checkout phase starts where the customer removes all the items from the basket by using PIR. Finally at the end of the shopping, Billing is automatically done and the bill is stored in the database.</p>

## Working Principle
<b> Working Module using LabVIEW Tool</b> 

This project creates a central bill and the software used for the creation of the bill and displaying of data is by using LabVIEW. Interestingly, LabVIEW is consisted of Front panel and Block Diagram Window. 
<h3> Front Panel </h3>
  <ul>
  <li> 
  The front panel window is the user interface for the VI. It has controls and indicators, which are the interactive input and output terminals, respectively, of the VI.</li>
   <li>
   Controls and indicators placed on the front panel are automatically placed on the block diagram.</li>



