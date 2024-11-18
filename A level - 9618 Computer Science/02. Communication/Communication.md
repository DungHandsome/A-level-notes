---
tags:
  - Communication
  - Network
cssclasses:
  - center-images
---


# Networking
## Networking devices
- **Networking devices**: Interconnected devices that enable fast data transmission within a network
- **Networking benefits**:
	- **Devices sharing**: such as share printers to reduce cost.
	- **File sharing**
	- **Data back up**: data can be backed up centrally at the end of each day
	- **Access to reliable data**: that comes from a central source, such as a ==file server==.

|                         | LAN (Local Area Network)                                                                         | WAN (Wide Area Network)                                                                                 |
| :---------------------- | :----------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------ |
| **Definition**          | A network that connects devices within a small geographical area, often within the same building | A network that connects devices within a larger geographical area, such as a city, country, or globally |
| **Ownership**           | Only private ownership                                                                           | Private or public ownership                                                                             |
| **Transmission medium** | Transmission medium: Twisted Pair Cables , Coaxial Cables or Wi-Fi                               | Transmission medium: PSTN or Satlink                                                                    |
| **Transfer rate**       | Higher data transfer rate                                                                        | Lower data transfer rate                                                                                |
| **Bottleneck**          | Less congestion                                                                                  | More congestion                                                                                         |

> [!NOTE] Additional information - wLAN
> **wLAN** is similar to LAN but no wires or cables. They provide wireless network communications over fairly short distances (up to 100m). We usually call this Wi-fi

## Networking models
- Consider 2 types of networking models: **client-server** and **peer-to-peer**.

### Client-server
![[Client-server-model.svg.png|400]]

- **Definition**: **Server-based network**: A dedicated server provides applications (administration of users, security, and resources) for the client computer to utilize.
- The server dictates which users are able to access which file

> [!tip] Most important aspect of each model
> **Client-server model**: Sharing of data
> **Peer-to-peer**: Connectivity

- **Application**:
	- **Printer**: Manages print jobs from client computers
	- **File sharing**: User's data is stored on the server
	- **Proxy server**
	- **Email server**: For sending, receiving, storing emails
	- **Database server**: Manage DBMS (database management system)

- The client-server model offers thin clients and thick clients:

|                | Thin client (Works rely on client)                                              | Thick client (Works rely on server)                                |
| :------------- | :------------------------------------------------------------------------------ | :----------------------------------------------------------------- |
| **Definition** | Activity are processed mostly on **server side**                                | Activity are processed mostly on **client slide**                  |
| **Activity**   | Only **provides input and receives output**, processing is done by the server   | **processes most of the application** locally on the client slide  |
| **Hardware**   | Required good hardware on the client slide                                      | Required good hardware on the server side                          |
| **On/Offline** | Cannot function without connected to the server                                 | Can function without connected to the server (offline)             |
| **Security**   | Better security because the client have less right to modify the data on server | Less secured because the client can modify the data sent to server |
| **Problems**   | Can get bottlenecked                                                            | Less secured                                                       |
| **Example**    | Most website and cloud software                                                 | fps games or offline application                                   |
### Peer-to-pear
- **Definition**: A decentralized network where each connected computer stores data and operates independently as a 'peer', acting as both a client and a server.
- **Application**: the **internet** is a large peer-to-peer model
- 