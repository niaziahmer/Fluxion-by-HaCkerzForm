# Hackerz.
## :pen:Usage
* chmod +x ./Installer  
* ./Installer
After installing.
* chmod +x ./fluxion
* ./fluxion
#Fluxion is the future 
#Fluxion is a remake of linset by vk496 with less bugs and more features. It's compatible with the latest release of Kali (Rolling)
## :octocat: How to contribute
All contributions are welcome, from code to documentation, to graphics, to design suggestions, to bug reports.  Please use GitHub to its fullest-- contribute Pull Requests, contribute tutorials or other wiki content-- whatever you have to offer, we can use it!
## :book: How it works

* Scan the networks.
* Capture handshake (can't be used without a valid handshake, it's necessary to verify the password)
* Use WEB Interface
	* Some standard pages
	* Some real pages of routers 
* Launches a FakeAP instance imitating the original access point
* Spawns a MDK3 processs, which deauthentificates all of the users connected to the target network, so they can be lured to connect to FakeAP network and enter the WPA password.
* A DHCP server is launched in FakeAP network
* A fake DNS server is launched in order to capture all of the DNS requests and redirect them to the host running the script
* A captive portal is launched in order to serve a page, which prompts the user to enter their WPA password
	* Real pages simulate a firmware update 
* Each submitted password is verified against the handshake captured earlier
* The attack will automatically terminate once correct password is submitted
## Disclaimer

***Note: Fluxion is intended to be used for legal security purposes only, and you should only use it to protect networks/hosts you own or have permission to test. Any other use is not the responsibility of the developer(s).  Be sure that you understand and are complying with the Fluxion licenses and laws in your area.  In other words, don't be stupid, don't be an asshole, and use this tool responsibly and legally.***
