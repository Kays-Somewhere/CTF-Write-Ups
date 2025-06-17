# Packet Whisperer
Category: Networking

Points: 75

[Question](#Question)

[Solve](#Solve)

[Flag](#Flag)

## Question 
Missing the question but it was asking you to find the a username within a packet capture.

# Solve
Downloaded the provided login.pcap file and opened it in Wireshark. I then found a POST /login packet and right clicked on it. I chose "Follow" then "http stream" to follow all the data related to the login prossess.

![Screenshot 2025-06-17 124001](https://github.com/user-attachments/assets/33002a60-143e-4bf8-b11d-85086e1666f2)

I found username line and coverted it to the flag.

“username=ironpotatoadmin&password=C1%7Bmaybe_TLS_would_be_nice%7D” 

![Screenshot 2025-06-14 110918](https://github.com/user-attachments/assets/dc34aeb4-96df-4560-bf4f-6d8c3f82350c)

# Flag
C1{maybe_TLS_would_be_nice}
