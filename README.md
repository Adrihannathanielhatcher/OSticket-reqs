<h2>VPN & The Networks Around Us<h2>
  
  
  ![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/1522d3f7-3b1f-47b6-a4e0-f4648db710f6) ![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/24acb663-5c4b-489e-8e90-8a14db30cd43)![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/683237a6-2aff-4ef8-8087-952835981e17)


 <h2>*This tutorial is an outline for researching and
        using virtual machines to access VPN Networks*<h2>
<h2>Video Demonstration</h2>
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN Program

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Proton VPN Program 
- Microsoft Azure Account
- Need to Know how to get a free Microosoft Azure Account? Here's a link to find out https://www.youtube.com/watch?v=-0mL7rA8nhM
<h2>Installation Steps</h2>
<h2>1. Creating a Virtual Machine in Azure<h2>

![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/6d0d9610-c0e5-43d4-b2a0-1a517bad9300)

 
- For this lab we will use Microsoft Azure, in your homepage you will find the Virtual Machine tab (an example of this will be on the image above) make sure in the box that says (Region) you choose a different country then where you currently reside, this will allow us to access VPN's from distinct areas. The goal is to deploy your virtual machine so this does not require configuration other then the basics just outlined. You can name the virtual machine how you like and take note to save a username and password you can remember in case you lose access to your virtual machine. 
 
 Example/
 Username: vpnexplorer 
 Password: Virtualinternet1!




<h2>2. Startup Remote Desktop<h2> 

![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/c5244bd3-5555-488d-9d33-d1d811fefa62) ![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/4e0a9610-beaf-4225-9511-b406d5efc056)![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/8a9059b9-602d-47a3-b68d-03bb350c2fd7)




- Once you have deployed your virtual lab you can access remote desktop from your devices start menu (example above left image). It will ask for your created username and password to start up the enviornment. The virtual area is recognizable by the blue bar above the screen in the middle, this will ensure the actions inside your virtual machine are safe. If you need to exit out, pressing the minus button will allow you to access your original screen. You now have your very own Virtual Machine to play with. 
</p>



<h2> 3. Access Whatismyipaddress.com in your new country<h2> 

  
![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/d4d54467-1b3e-4c93-b4a1-f55b134d7e07)




- Here is the fun part. Go to Whatismyipaddress.com inside the virtual machine. You can do this by opening a browser window and pasting this address. Depending on the region you entered the IP Adress will be vastly different from your current location. If you want to make sure, exit out of your Virtual Machine and type in the same URL into you computer's browser. Now that we can see the difference in Address let's take it up a notch. 
<br />


<h2> 4. Downloading Proton VPN and observe your enviornment<h2> 

![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/782be18a-550e-4503-8b14-5776182bcdfc)
[i![image](https://github.com/Adrihannathanielhatcher/OSticket-reqs/assets/172681359/31c8af13-d871-4d88-8669-e49fdfde5518)





- Now inside your Virtual Machine download Proton VPN it is a fairly easy process (Link Below for sign up) . You are looking for the free version and it will ask you for an email address and a password during the process. After you have completed the installation depending on your region when you open Proton VPN you will be able to connect to a private Network in that area (Example Image Above). The coolest feature is based off the area you select you can get a cool diagram as well as addresses from anywhere, this lab does great job of highlighting the inner workings of a Virtual Private Network at work. If you want to mess around inside of the lab make sure to delete your currnt Virtual Machine and create a new one in a diffrent area. Then make sure to repeat the steps outlined above. Enjoy

https://protonvpn.com/download-windows

