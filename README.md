# deauth_attack
How safe are wifi networks?

When a client wants to break its connection with the wireless network it is connected to, it terminates the relationship between them by pressing the disconnect button. Looking at the back of the job, the client sends a deauthentication packet to the wireless network and the connection is terminated.

However, these termination packets can be spoofed by other devices. This will not only interrupt the wifi connections of all devices connected to the wifi network, but also allow malicious users to capture 3Handshake packets from the next connection packets. This is a very popular way to get wifi password. So how is a deauthentication packet sent? How does a simple attack cause an unstoppable problem?

<img class="fit-picture"
     src="/pics/eviltwin2-1024x626%20-%20Kopya.png">
     
     
We are using a Wemos d1 mini for a simple experiment


<img class="fit-picture"
     src="/pics/WhatsApp%20Image%202023-01-05%20at%2015.46.25%20-%20Kopya.jpeg">
     

     
 <img class="fit-picture"
     src="/pics/WhatsApp%20Image%202023-01-05%20at%2022.33.03%20(1).jpeg">
 
 <img class="fit-picture"
     src="/pics/WhatsApp%20Image%202023-01-05%20at%2022.33.03%20(2).jpeg">
 <img class="fit-picture"
     src="/pics/WhatsApp%20Image%202023-01-05%20at%2022.33.03.jpeg">
 
 After a quick scan and target wifi network selection, we initiate a Deauth attack.
 
 
 <img class="fit-picture"
     src="/pics/atak2%20-%20Kopya.png">
 
 <img class="fit-picture"
     src="/pics/deauth-1024x337%20-%20Kopya.png">
 <img class="fit-picture"
     src="/pics/deauthattack%20-%20Kopya.png">
     
  <img class="fit-picture"
     src="/pics/dis%20-%20Kopya.png">
     

  
     
    
<img class="fit-picture"
     src="/pics/1_eXBh6RIhggabcQU0d0L9qA%20-%20Kopya.jpg">
     
When we scan with Wireshark, it is seen that the outgoing deauthentication packets and the router connection are disconnect.     

