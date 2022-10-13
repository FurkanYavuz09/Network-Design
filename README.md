# Network-Design
Network Design project for CENG422
CENG422 Final Project

Design the network for a company... Assume that the following is true:
1.	There are two buildings next to each other: A factory and an office building. There is also a remote branch office located in another town.
2.	The main factory building has 3 floors; each floor needs at least 8 Ethernet ports to connect their devices. Use a router at each floor.
3.	The office building has 2 floors. Each floor has 2 offices, and each office needs at least 
2 Ethernet ports. Use a router at each floor.
4.	The branch itself has a modem, a router, and needs 4 Ethernet ports for the personnel working there.
5.	The company also has a leased line from one of the offices, to the branch office, connected via a router, a leased line and a modem. (for our simulation, connect the branch to the office via two routers with serial ports, and have the two “talk” to each other via PPP or another protocol of your liking).

Do the following:
1.	Make a diagram of the entire network. You may use any tool , including paper and pencil.
2.	Assign IP address groups to each group, marking them on the diagram.
3.	Decide where each switch and router should be.
4.	Assume all devices are CISCO.
5.	Using GNS3, create the network on your computer,
6.	Configure each router, add at least 1 virtual PC to each office.
7.	Verify that each section of the network can “see” all other sections by pinging from one PC to another from every PC.
8.	Submit all proof: diagram(s), gns3 diagram(s), router/switch configurations (gns3 has an Export Config option), and a blog-like paper describing what you did, and why you chose those devices and configurations, how it went, what you did first, then what else.. etc..

