
Let a member of the admin team know that you want access to the dedicated VPN and provide them your HTB handle. If there are spots available you will be added, once added you should see the `Dedicated Labs` in the lower left hand corner.
<img width="1523" alt="image" src="https://user-images.githubusercontent.com/84935721/123170974-c8652780-d440-11eb-83de-74b527c967ea.png">

<br>

The `Dedicated Labs` tab provides the IP address of the machines we are doing for the meetup. If you are able to see the machine that means you have access to the dedicated VPN.
<img width="1259" alt="image" src="https://user-images.githubusercontent.com/84935721/123207613-48ac7c80-d483-11eb-8d38-494e24e8a629.png">

<br>

Go to the `Access` tab on the left hand side.
<img width="1259" alt="image" src="https://user-images.githubusercontent.com/84935721/123207873-b2c52180-d483-11eb-9baa-ea9cbd603fbb.png">

<br>

Switch to the dedicated VPN.
<img width="1259" alt="image" src="https://user-images.githubusercontent.com/84935721/123171826-e2ebd080-d441-11eb-91de-018d48d325cb.png">

<br>

Refresh the server to get the new VPN profile
<img width="1259" alt="image" src="https://user-images.githubusercontent.com/84935721/123171969-0ca4f780-d442-11eb-98ca-a1f063b15fce.png">

<br>

Download the file to your Kali machine.
<img width="1259" alt="image" src="https://user-images.githubusercontent.com/84935721/123207760-83161980-d483-11eb-949b-4453aac6079b.png">

<br>

Navigate to the OpenVPN file on your Kali machine and run the following cmd.

`sudo openvpn --config FILENAME.ovpn`

<img width="1259" alt="image" src="https://user-images.githubusercontent.com/84935721/123208752-43503180-d485-11eb-80a1-5ae1fab8c708.png">

<br>

If the profile is working then you should be able to successfully ping the machine.
<img width="1259" alt="image" src="https://user-images.githubusercontent.com/27873299/124331196-86309a00-db54-11eb-80aa-bade9e9d5a01.png">

<br>

The server should also show you being connected.
<img width="1259" alt="image" src="https://user-images.githubusercontent.com/27873299/124331452-d6a7f780-db54-11eb-90db-4d3e9026c32a.png">



