# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.

## PROGRAM - ARP
![image](https://github.com/user-attachments/assets/f4cdc0b0-8e0f-40dc-9a76-82162c05ad08)

## OUPUT - ARP
![image](https://github.com/user-attachments/assets/92ef80ea-4b36-416a-8f59-1f6a6fb56d34)

## PROGRAM - RARP
![image](https://github.com/user-attachments/assets/54e801b4-f7a9-48f2-ba49-4ab24bd6f592)

## OUPUT -RARP
![image](https://github.com/user-attachments/assets/ac4a908a-4760-430c-a7b8-0268868ec833)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
