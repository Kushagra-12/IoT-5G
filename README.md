# IoT-5G

### 5G Architecture
5G is effectively a dynamic, coherent and flexible framework of multiple advanced technologies supporting a variety of applications. 5G utilizes a more intelligent architecture, with Radio Access Networks (RANs) no longer constrained by base station proximity or complex infrastructure. 5G leads the way towards disaggregated, flexible and virtual RAN with new interfaces creating additional data access points.
![image](https://user-images.githubusercontent.com/49092108/184804759-1fa304a6-1950-4c93-91e2-65a92cd2249a.png)

### 3GPP
![image](https://user-images.githubusercontent.com/49092108/184804989-dc683f4b-e40d-4d56-a53d-ec252b156531.png)
3GPP, or the 3rd Generation Partnership Project, was initially formed in December 1998 when the European Telecommunications Standards Institute (ETSI) partnered with other standard development organizations (SDOs) from around the world to develop new technologies

What is 3GPP 5G NR?
5G NR (New Radio) is a new radio access technology (RAT) developed by 3GPP for the 5G (fifth generation) mobile network. It was designed to be the global standard for the air interface of 5G networks.

### 5G Architecture 3GPP 
- The 3rd Generation Partnership Project (3GPP) covers telecommunication technologies including RAN, core transport networks and service capabilities. 3GPP has provided complete system specifications for 5G network architecture which is much more service oriented than previous generations
- Services are provided via a common framework to network functions that are permitted to make use of these services. Modularity, reusability and self-containment of network functions are additional design considerations for a 5G network architecture described by the 3GPP specifications.

### 5G Spectrum and Frequency
- Multiple frequency ranges are now being dedicated to 5G new radio (NR). The portion of the radio spectrum with frequencies between 30 GHz and 300 GHz is known as the millimeter wave, since wavelengths range from 1-10 mm. Frequencies between 24 GHz and 100 GHz are now being allocated to 5G in multiple regions worldwide. 
- In addition to the millimeter wave, underutilized UHF frequencies between 300 MHz and 3 GHz are also being repurposed for 5G. The diversity of frequencies employed can be tailored to the unique applications considering the higher frequencies are characterized by higher bandwidth, albeit shorter range. The millimeter wave frequencies are ideal for densely populated areas, but ineffective for long distance communication. 

### 5G NR / 4G LTE
![image](https://user-images.githubusercontent.com/49092108/184805187-16b65aa6-6452-4b68-bcaf-480ec86d0c7d.png)
- NR has a radio structure that makes it compatible with LTE but better prepared for future technology solutions and use cases such as higher spectral efficiency, traffic capacity and shorter user plane latency.
- An important goal of 5G NR is to support the growth of wireless communication by enhancing electromagnetic radiation spectrum efficiency for mobile broadband.
- networks can move vast amounts of data more efficiently than with 4G LTE.

### MEC
- Multi-Access Edge Computing (MEC) is an important element of 5G architecture. MEC is an evolution in cloud computing that brings the applications from centralized data centers to the network edge, and therefore closer to the end users and their devices. 
- This technology is not exclusive to 5G but is certainly integral to its efficiency. Characteristics of the MEC include the low latency, high bandwidth and real time access to RAN information that distinguish 5G architecture from its predecessors.
- The 5G specifications define the enablers for edge computing, allowing MEC and 5G to collaboratively route traffic. In addition to the latency and bandwidth benefits of the MEC architecture, the distribution of computing power will better enable the high volume of connected devices inherent to 5G deployment and the rise of the Internet of Things (IoT). 

### NFV and 5G
- Network function virtualization (NFV) decouples software from hardware by replacing various network functions such as firewalls, load balancers and routers with virtualized instances running as software. This eliminates the need to invest in many expensive hardware elements and can also accelerate installation times, thereby providing revenue generating services to the customer faster. 
- NFV enables the 5G infrastructure by virtualizing appliances within the 5G network. This includes the network slicing technology that enables multiple virtual networks to run simultaneously. 

### 5G RAN Architecture
- The concept of NFV extends to the RAN through for example network dis-aggregation promoted by alliances such as O-RAN. This enables flexibility and creates new opportunities for competition, provides open interfaces and open source development, ultimately to ease the deployment of new features and technology with scale. Network dis-aggregation also allows components of the network to be virtualized, providing a means to scale and improve user experience as capacity grows. The benefits of virtualizing components of the RAN provide a means to be more cost effective from a hardware and software viewpoint especially for IoT applications where the number of devices is in the millions.
### eCPRI
- RF interfaces are not cost effective when testing large numbers of 5G carriers as the RF costs rapidly increase. The introduction of eCPRI interfaces presents a more cost-effective solution as fewer interfaces can be used to test multiple 5G carriers. eCPRI is aimed to be a standardized interface for 5G used for instance in the O-RAN front haul interface such as the DU. 

### 5G Core Architecture

![image](https://user-images.githubusercontent.com/49092108/184805746-f983938b-37d2-4d14-892d-0c8696827e2b.png)

- The 5G core network architecture is at the heart of the new 5G specification and enables the increased throughput demand that 5G must support. The new 5G core, as defined by 3GPP, utilizes cloud-aligned, service-based architecture (SBA) that spans across all 5G functions and interactions including authentication, security, session management and aggregation of traffic from end devices. 

### Security in 5G Architecture
- 5G is building on the security practices of past mobile technology generations, yet the trust model has become much more expansive with more players involved in the service delivery process. The IoT and user propagation create an exponentially higher number of endpoints with many of these traffic inputs no longer supervised by human hands. 
- Among the improved 5G security features detailed by the 3GPP standards are unified authentication to decouple authentication from access points, extensible authentication protocols to accommodate secure transactions, flexible security policies to address more use cases and subscriber permanent identifiers (SUPI) to ensure privacy on the network. 
- As 5G deployment continues and critical performance nodes become increasingly virtualized, operators will need to continually monitor and assess security performance. 
- Undoubtedly, 5G will deliver the exponential speed enhancement users have grown accustomed to with each new generation of mobile networks, but speed is just the beginning. The expected changes to industries ranging from personal transportation to manufacturing and farming will be so significant that many have dubbed 5G the next Industrial Revolution. At the heart of this paradigm shift is the multi-faceted 5G architecture, with MEC, NFV massive MIMO and a cloud-aligned, service-based core architecture working in concert to deliver the new wave of services. 

### 5G Air Interface

![image](https://user-images.githubusercontent.com/49092108/184805973-57c66f6b-b89d-4e6d-9d2e-a58e4889be19.png)

5G NR is a new air interface being developed for 5G. An air interface is the radio frequency portion of the circuit between the mobile device and the active base station. The active base station can change as the user is on the move, with each changeover known as a handoff.
The 5G NR is being designed to significantly improve the performance, flexibility, scalability and efficiency of current mobile networks, and to get the most out of the available spectrum, be that licensed, shared or unlicensed, across a wide variety of spectrum bands.
Furthermore, the 5G NR air interface is just one component of the future 5G network so it must also be designed to work as part of a wider flexible network architecture.

### m-MIMO / Beamforming

![image](https://user-images.githubusercontent.com/49092108/184806072-37473211-9bb7-46f6-96fa-3f084fc738c9.png)

- MIMO is between two devices (e.g. base station and mobile station or AP and client), while Massive MIMO is simultaneous communication between a base station and multiple clients. It essentially merges the concept of beamforming with MIMO to minimize interference between devices.
- Massive MIMO or m-MIMO typically requires at least 64 antennas at both the transmitter and receiver end. In this light, you can think of MIMO as something that is a normal MIMO at present which has a fewer number of antennas or less than 64.

### MM -Wave

![image](https://user-images.githubusercontent.com/49092108/184806175-20601390-1cc3-46f0-9e18-c5cc80d9e762.png)

- Millimetre wave (MM wave), also known as millimetre band, is the band of spectrum with wavelengths between 10 millimetres (30 GHz) and 1 millimetre (300 GHz). It is also known as the extremely high frequency (EHF) band.
- It's a radio frequency that would allow transmission frequencies between 30 GHz and 300 GHz
- Sub-6GHz 5G is essential for blanket coverage and bandwidth, while mm Wave offers higher speeds over shorter distances. As such, mm Wave deployments are limited to short distances, such as a few streets, and areas that benefit most from extreme high bandwidth, such as stadiums and city centres.

### Network Slicing

![image](https://user-images.githubusercontent.com/49092108/184806289-a899185f-879a-4bc0-8922-781a6a113753.png)

Network slicing is a method of creating multiple unique logical and virtualized networks over a common multi-domain infrastructure. Using Software-Defined Networking (SDN), Network Functions Virtualization (NFV), orchestration, analytics, and automation, Mobile Network Operators (MNOs) can quickly create network slices that can support a specific application, service, set of users, or network.

The use cases identified for 5G and network slicing fall into three major categories:
- Extreme (or enhanced) Mobile Broadband (eMBB). These applications are very video-centric and consume a lot of bandwidth and will generate the most traffic on the mobile network.
- Massive Machine-Type Communications (mMTC). This is more commonly known today as the Internet of Things, but at a much larger scale, with billions of devices being connected to the network. These devices will generate far less traffic than eMBB applications, but there will be many magnitudes more of them.
- Ultra-reliable Low-Latency Communications (urLLC). These will allow for things like remote surgery or vehicle-to-X (v2x) communications and require MNOs to have mobile edge computing capacity in place.

### Small Cell

![image](https://user-images.githubusercontent.com/49092108/184806405-5f9e55ab-9a60-4efd-8ae0-97fb1fc37739.png)

### How important is small cell technology for 5G?
At their core, small cells are wireless transmitters and receivers designed to provide network coverage to smaller areas. So while tall, high-power “macro” towers keep the network signal strong across large distances, small cells suit more densely developed environments like cities.

### How small is small?
Building a network capable of delivering 5G may be complex, but small cell technology is a straightforward idea. Whereas most of today’s cellular data travels between towers and antennas that may rise hundreds of feet, small cells are about the size of a picnic cooler or mini-fridge.

### 4G vs 5G

![image](https://user-images.githubusercontent.com/49092108/184806532-2be9f9ce-531c-4a0e-a285-0053d754bbb5.png)
