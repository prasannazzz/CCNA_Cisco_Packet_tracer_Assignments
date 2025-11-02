## Two switch Topology
<img width="807" height="441" alt="image" src="https://github.com/user-attachments/assets/66a8b661-ec5f-41b2-a905-25b0f4cf0446" />
<img width="808" height="431" alt="image" src="https://github.com/user-attachments/assets/87e12a87-806d-4759-8845-73e918f6cba9" />

<img width="721" height="440" alt="image" src="https://github.com/user-attachments/assets/48d520fb-35b0-4d5f-8f25-e8eedf790f9b" />

## 10.3.5 Packet Tracer – Troubleshoot Default Gateway Issues – ILM
<img width="451" height="468" alt="image" src="https://github.com/user-attachments/assets/fc05988a-8012-4308-9de1-9daa14334d21" />
<img width="385" height="259" alt="image" src="https://github.com/user-attachments/assets/ea68aa6e-4348-419d-8bb0-d4b2085feb57" />
<img width="512" height="354" alt="image" src="https://github.com/user-attachments/assets/d49a6418-39ad-4d4f-95b5-3912368e4103" />
S1>enable
S1#configure terminal
S1(config)#ip default-gateway 192.168.10.1

S2>enable
S2#conf terminal
S2(config)#interface vlan 1
S2(config-if)#ip address 192.168.11.2 255.255.255.0
S2(config-if)#no shutdown


