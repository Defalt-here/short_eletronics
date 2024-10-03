<h1>Forked from Elecrow-RD/short_eletronics</h1>
<p>A new way to control your OLED Games on ESP8266</p>
<h1>How to use</h1>
<h2>Basic Idea</h2>
Copy the code below for your Node MCU 1.0 ESP 8266 module then download the RoboRemo App on your mobile<br>
Using the RoboRemo's UI creator you can now configure buttons to send a packet with your desired content
i.e. you can set the value of what a button sends when pressed as a UDP packet
<h2>Connecting to Robo Remo</h2>
<p>When you run the sketch for the first time you will find the Local IP and the port your Node MCU is workin on</p>
<p>Connect to UDP using the address and Port</p>
<p>Make 4 buttons on your UI and configure them as follows in the pressed field under the edit menu</p>
<ol>
  <li>Up = 1</li>
  <li>Right = 2</li>
  <li>Down = 3</li>
  <li>Left = 4</li>
</ol>
