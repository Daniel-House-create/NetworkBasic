# NetworkBasic

<h1>Building a basic network</h1>
This tutorial outlines the basics of building and configuring a simple network<br />

<h2>Environments and Technologies Used</h2>

- Cisco Packet Tracer

<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>Checklist</h2>

- Build and organize network diagram
- Configure IPs in the router
- Ping tests to show PCs can communicate within their network and with those outside network (ie different switches and the server)
- Ensure that HTTP/HTTPS is on in the server and run a test to ensure the PCs are connected to the Internet

<h2>Installation Steps</h2>

<p> 

![Screenshot 2025-04-25 100154](https://github.com/user-attachments/assets/c793bfb2-17f1-4f15-906a-ad713d731f0f)
</p>
<p>
Since this is a simple network diagram, I decided to create three small sections of the network: IT, HR, and Sales. Each section has two PCs and a switch. All are conncected to one router. The router is connected to another switch and the switch is connected to the server.
</p>
<br />

<p>
<img width="867" alt="Screenshot 2025-04-28 at 10 44 13 AM" src="https://github.com/user-attachments/assets/f8814732-8aa3-4314-8c0b-87d534dcc21b"/>
</p>
<p>
<img width="849" alt="Screenshot 2025-04-28 at 10 45 54 AM" src="https://github.com/user-attachments/assets/d5b2b31c-5fbe-42ae-b13f-044df879ff33" />
</p>
<p>
I configure the router to allow traffic between the different switches and the router using the default gateway of each local network. I then show the ip interface to ensure that all of the IP addresses are configured and working properly.
</p>
<br />

<p>
<img <img width="765" alt="Screenshot 2025-04-28 at 10 51 01 AM" src="https://github.com/user-attachments/assets/1780885b-8ba1-4dc4-bdba-133af38a4dd2" />
</p>
<p>
I did a ping test from PC0, or the first PC in the IT department, to the server and it was successful. All PCs can contact the server.
</p>
<br />

<p>
<img <img width="734" alt="Screenshot 2025-04-28 at 10 55 03 AM" src="https://github.com/user-attachments/assets/f75ba541-55c9-4266-b7e9-cdda994c9682" />
</p>
<p>
With the same PC, I did a ping test to see if it can contact the other PC within the IT department and outside to HR and Sales. All were successful.
</p>
<br />

<p>
<img width="763" alt="Screenshot 2025-04-28 at 10 55 51 AM" src="https://github.com/user-attachments/assets/cf665d60-313c-4a96-ae9b-14db79a0bfa8" />
</p>
<p>
<img width="765" alt="Screenshot 2025-04-28 at 10 56 00 AM" src="https://github.com/user-attachments/assets/a6261935-5383-4601-bf21-577d89cbec0a" />
</p>
To test Internet connectivity, I headed into the server and made sure the HTTP/HTTPS protocol is turned on. I went into the index and clicked on edit. I left what was there because it was on default and wanted to keep the project simple. But then I went into a PC and accessed the Internet. The second screenshot is the successful test.
</p>
<br />

<p>
<img <img width="1168" alt="Screenshot 2025-04-28 at 10 56 21 AM" src="https://github.com/user-attachments/assets/9057ed18-9053-41eb-8169-7dd8cf2c1842" />
</p>
<p>
This is the updated topology of the network. Every PC and department can contact the server and every PC in the entire network. Traffic can pass between the router and the different switches. The network is ready and configured for the business.
</p>
<br />
