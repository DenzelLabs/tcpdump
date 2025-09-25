# tcpdump packet capture

## Lab Tasks
<ul>
  <li>Identify available network interfaces</li>
  <li>Use tcpdump to capture live network traffic</li>
  <li>Save network traffic to a packet capture file</li>
  <li>Filter the packet capture data</li>
</ul>

<br><br>

<p>used ifconfig to check available network interfaces</p>
<img width="683" height="374" alt="image" src="https://github.com/user-attachments/assets/ee0ac546-7ec8-4d6b-9ee9-06a340fbf987" />

<br><br>

<p>used tcpdump -D to view available capture interfaces</p>
<img width="646" height="193" alt="image" src="https://github.com/user-attachments/assets/4504c355-0739-462e-aac5-7e40c75f1b4a" />

<br><br>

<p>captured 5 packets on eth0 with tcpdump in verbose mode</p>
<img width="784" height="493" alt="image" src="https://github.com/user-attachments/assets/f2f6318f-7f7d-46cc-86a3-5e1602c851fc" />

<br><br>

<p>captured 9 port 80 packets on eth0 into capture.pcap</p>
<img width="785" height="76" alt="image" src="https://github.com/user-attachments/assets/63666734-8872-48b1-b4a0-74fbcd1ea229" />

<br><br>

<p>used curl to make an HTTP request to opensource.google.com, creating port 80 traffic</p>
<img width="763" height="255" alt="image" src="https://github.com/user-attachments/assets/947d3ffc-385a-4d81-b078-6ecc6e68b79a" />

<br><br>

<p>verified capture.pcap file was created and contains packet data</p>
<img width="545" height="90" alt="image" src="https://github.com/user-attachments/assets/4846992c-4aa7-457d-ac49-5aee789bb5d3" />

<br><br>

<p>reviewed packet headers from saved capture file using tcpdump</p>
<img width="783" height="432" alt="image" src="https://github.com/user-attachments/assets/0aa19f18-e977-41b0-9ce9-8b3527d7ec89" />
<img width="779" height="664" alt="image" src="https://github.com/user-attachments/assets/b4387fc5-10c2-41bc-89e5-7b02899dbb4e" />
<img width="779" height="100" alt="image" src="https://github.com/user-attachments/assets/25ed5b53-f73a-4d29-a14c-f75e0353b437" />

<br><br>

<p>viewed extended packet payloads from saved capture file using tcpdump</p>
<img width="783" height="407" alt="image" src="https://github.com/user-attachments/assets/a7aaeba8-5cd3-4803-985a-800d8cd97c57" />
<img width="780" height="667" alt="image" src="https://github.com/user-attachments/assets/b94c9fc1-6d83-46f3-abaf-a6ede5f7d241" />
<img width="789" height="688" alt="image" src="https://github.com/user-attachments/assets/ad2632af-5cd7-49cf-81a3-9b3a132fcdcf" />
















