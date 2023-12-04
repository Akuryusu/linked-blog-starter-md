### Requirements

- All sources linked
- Ten slides
- Script (nah)

# Slides
---
### **Intro Slide**
---
#### **Point 1: Introduction to Tor**
- Briefly introduce Tor, its acronym, and its primary goal of providing anonymous communication.
- Developers
---
#### **Point 2: How Tor Works**
- Explain the process of onion routing and the use of multiple layers of encryption.
- Include a simple diagram to illustrate the flow of data through the Tor network.
---
#### **Point 3: Tor Browser Security**
- Introduce Tor Browser as a modified version of Mozilla Firefox.
- Highlight key features like NoScript, security levels, etc.
- Include a screenshot of the Tor Browser interface.
---
#### **Point 4: Use Cases**
- Discuss use cases: protection against surveillance, avoiding censorship, and accessing .onion websites.
- Use real-world examples or scenarios to illustrate each use case.
---
#### **Point 5: Challenges
- Acknowledge challenges and criticisms.
- Address the responsible use of Tor.
---
### **Outro Slide**



# Loose Script
---
### Point 1
- TOR stands for The Onion Routing (Browser)
- A project created by Naval Research Lab Scientists (Учени от лаборатория за военноморски изследвания) (Names in presentation)
- Initial goal is anonymous browsing
- Development is continued by various volunteers around the world


### Point 2
- Onion Routing encrypts data in layers, routing it through volunteer-operated nodes. Each node peels back one layer, obscuring the sender's identity. (Recreate image in PP)
![[Pasted image 20231122003222.png]]

- First node (server) is the **entry** node through which the data enters. The data gets transferred to the second node, called **relay** node. The destination (server/website) receives the data from the third and last node, the **exit** node. The data get encrypted until the last connection where it gets decrypted to the destination by the exit node


### Point 3
- Tor is based on Mozilla Firefox. The primary reason is that Mozilla focuses on privacy and is open-source
- Mention security levels
- Has integrated NoScript extension which blocks JS by default


### Point 4
- Anonymous browsing
- Avoiding censorship and restrictions (ограничения). For example accessing social media or news sites in countries like Iran and China. Regional restrictions. For example Netflix's content restrictions. school restrictions. For example blocked sites.
- Protection against surveillance (from government)
- Secure communication 

### Point 5 
- End node has no encryption which can lead to vulnerability
- Painfully low speed
- Criminals and illegal activity
# Sources
---
https://www.geeksforgeeks.org/
https://www.torproject.org/