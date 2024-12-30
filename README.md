# akinportscanner

![akinportscanner](https://github.com/user-attachments/assets/47ba16cc-03d2-47b2-b5d7-1f214764ebbd)


Port scanner is a tool used to detect open ports and services on a networked device. It helps identify available communication endpoints and is commonly used in network security assessments, troubleshooting, and penetration testing.




How Ports Work:

In computer networking, ports are logical endpoints for communication between devices. They are managed by the Transmission Control Protocol (TCP) and User Datagram Protocol (UDP). Each port is associated with a specific service or application, such as:

Port 80: HTTP (web traffic)

Port 443: HTTPS (secure web traffic)

Port 25: SMTP (email)

Port 22: SSH (secure shell)




Ports can exist in three states:

Open: Actively accepting connections.

Closed: Not accepting connections, but reachable.

Filtered: Blocked by a firewall or security rules, with no response or a "destination unreachable" reply.






Installation Steps:

Clone the repository into a specific directory:

git clone https://github.com/AkinlawonDMentor/akinportscanner.git

Navigate to the directory:

cd akinportscanner

Usage:

python akinportscanner.py  target(e.g testphp.vulnweb.com)






Ethical Considerations:

Using a port scanner on a network without permission is illegal in many jurisdictions. Always ensure that you have proper authorization before conducting port scans.
