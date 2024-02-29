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
<b> 1. Working Module using LabVIEW Tool</b> 

This project creates a central bill and the software used for the creation of the bill and displaying of data is by using LabVIEW. Interestingly, LabVIEW is consisted of Front panel and Block Diagram Window. 
<h3> Front Panel </h3>
  <ul>
  <li> 
  The front panel window is the user interface for the VI. It has controls and indicators, which are the interactive input and output terminals, respectively, of the VI.</li>
   <li>
   The controls and indicators placed on the front panel are automatically placed on the block diagram. Front panel indicators pass data from the user to their corresponding terminals on the block diagram</li>
  </ul>

The following figure depicts the front panel of the code in LabVIEW.

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/c9341247-6ece-46d0-b159-d2d5a2efda66)
<p align="justify">
When you open a new or existing VI, the front panel window of the VI appears. The front panel
window is the user interface for the VI. The above shown figure is an example of a front panel window.</p>
<p align="justify">
The front panel shows the status of the PIR sensor whether the access is granted or denied by using the Boolean indicators and the increment of the items in the list when added and the decrement of the item from the list when deleted can be seen in the numerical indicators and Read buffer is used to see the trolley name which is scanned and error in and error out are used to indicate whether there is any error present in the code or not.</p>
<h3> Block Diagram </h3>
<ul>
  <li> A block diagram is a graphical representation of a system, project, or scenario. It provides a functional view of a system and illustrates how the different elements of that system interlink.</li>
  <li>It contains the graphical source code of a LabVIEW program that defines the functionality of the VI. The blocks are interconnected, using wires to indicate the dataflow.</li></ul>
  
 In the below shown block diagram panel, different icons and programming structures are used to develop codes as shown in below figures.

  ![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/68d155bb-f200-46f1-9b15-9583faaa6b9c)

  ![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/0569213e-97c5-4e76-87b5-72385bcb01dd)

  ![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/2af2a745-ae12-46e1-9c4e-3994129a08dc)

<h3>Creation of the File Path using MyRIO</h3>
The following sections discusses the how to create File path using MyRIO.
<ul>
  <li> Initially for the creation of the file path we have to know the myRIO IP address. </li>
<li> Now, open any browser and type the IP address in http format i.e http://172.22.11.2/files/ and press ENTER.</li>
<li>Now it will ask the credentials like USER NAME and PASSWORD.<br>User name: admin </br>
<br>Password: (press enter)</br></li>
<li> Now Browser displays the below figure and contents of the file will be displayed and here
we have chosen the tmp file. </li></ul>

 ![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/dba44c25-2c84-4f5f-9226-5bff2eae72f5)

<ul>
<li> Now go to THIS PC on desktop and right click on it and there will be an option named MAP
NETWORK DRIVE click on it.</li>
<li> There we can create any local drive. Here, we have chosen R drive letter and next we need
to select the checkbox with Connect using different credentials and uncheck the Reconnect
at Sign-in.</li>
<li> In this we need to give the folder path i.e ip address/file/tmp and then click on ok.Then it will create the local folder.</li>
<li> In this we need to create new excel sheet file which can be used for billing purpose.</li>
<li>This file path is given in the block diagram figure in order to store the billing amount and the following figure depicts the central billing excel sheet.</li></ul>

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/38c1da4e-8968-476c-80c2-95cc41947e36)

<b> 2. Working Module using Mobile Application </b> 
<ul>
<li>Initially, We need to store the unique trolley ID’s and these ID’s are assigned to their respective trolleys.</li>
<li>There must be a inbuilt scanner or you need to download an application to support the barcode and QR code.</li>
<li>Secondly, We need to download the SMART CART application in order to proceed further shopping.</li>
<li>As shown in the below figure, Press the scan trolley button and scan the unique QR code which is assigned to their respective trolley.</li></ul>

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/f818c534-7c8a-4617-8316-db292bbe2108)

<ul>
<li>When the trolley id and QR code of the trolley are matched then, then the dialog box will open with text as <b>“The Trolley Is Assigned Successfully”</b> otherwise there will get an text as <b>“The Trolley Is Not Assigned”.</b></li>
<li>Next after trolley id are matched then it goes to next screen and there we need to connect the Bluetooth.</li>
<li>After connecting to the Bluetooth only we can do the shopping otherwise, there will a dialog box raised with a text <b>“ERROR connecting”</b>.</li>
<li>Next after trolley id are matched then it goes to next screen and there we need to connect the Bluetooth.</li>
<li>As shown in the below figure, the available paired devices will be shown on the display. The Bluetooth module we used is HC-05 Bluetooth module.</li></ul>

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/dbf333a9-56de-4a99-a151-4565aae5ecc4)

<ul>
 <li>After connecting to Bluetooth only we can continue with the further shopping otherwise, there will a dialog box raised with a text “ERROR connecting” and we cannot proceed with our shopping.</li>
</ul>

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/e4cf5249-757d-417e-91f9-799109a766bd)

<ul>
 <li>After Bluetooth is connected, As shown in the above figure there will be two options i.e ADD or DELETE.</li>
 <li>When we press on the add or delete button, we need to scan the product barcode to add or delete the item from the list.</li>
 <li>Whenever a product is added or deleted using an app, myRIO receives IDs to store the added or deleted products to the cart by comparing IDs.</li>
 <li>The best part is security, whenever the product is added or subtracted, myRIO gives access to put a hand in it for some time, to add the product or to take the product from the Cart.</li>
 <li>PIR detects the motion of the object where the access will be granted only when the barcode of the item is scanned either for adding product or deleting product and for all other cases access will be denied adding product or deleting product.</li>
</ul>

The following figures shows the screens of the mobile application which shows the shopping bill and total number of items in the cart.

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/871dface-2240-4677-b79b-03b4d44b72a7)

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/ac54f8c0-e6d2-4df9-9662-86f0290802af)

![image](https://github.com/imsvreddy1998/Design-and-Implementation-of-Smart-Cart-using-Labview/assets/124395648/68f32c68-7b3c-4793-8834-69872079d408)

<ul>
 <li>After the addition and deletion of the items, Press I’m done, and the total amount and the items quantity will be displayed to check the items.</li>
<li> Once the shopping is done and the items are checked press End shopping, and the bill will be generated automatically in the central billing system.</li>
<li>Because of the central bill we don’t need to wait in the long queues to scan the products, we need to just pay the bill and unfill the cart.</li>
</ul>



 



  


