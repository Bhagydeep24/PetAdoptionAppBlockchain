# Pet Adoption App Blockchain

---

#### Steps for executing the application:

1. Download/clone the project from the GitHub repository: https://github.com/Bhagydeep24/PetAdoptionAppBlockchain
Note: For TA this README will be in the code submission so downloading code from repository won’t be required.

2. Once project is downloaded Execute <b>npm intstall</b> CLI command (make sure node is installed and working) in the terminal making sure current directory is the project downloaded. This step will install all the required node modules.

3. Download [Ganache]: https://www.trufflesuite.com/ganache and make the application running.

![](ss/ganache.png)

4. Next step we need to check if the Ganache connection details with the project is set properly. For that we have <b>truffle-config.js</b> file in the project and we just need to confirm. And those host and port is available Ganache application on top. Both code and details in Ganache would look something like below:

<img src="https://github.com/Bhagydeep24/PetAdoptionAppBlockchain/blob/master/ss/truffle-config.png" width="400" height="350">

![](ss/connection_details.png)

5. Once connection is confirmed then we will execute 2 CLI commands <b>truffle compile</b> and then <b>truffle migrate</b>. (if there is no truffle installed you can install by CLI command <b>npm install -g truffle@5.0.2</b>)

6. Once both the commands are executed without any error we will run the project using CLI command <b>npm run dev</b> which open our project in browser and it will look something like below

![](ss/thumbnail.png)

7.  Next we will need Metamask extension install on our browser for the transaction. And after we are logged in our Metamask account we need to set up private network. So click on network dropdown button on top right and select <b>custom RPC</b>. This whole process will look like below figure on browser extension.

<img src="https://github.com/Bhagydeep24/PetAdoptionAppBlockchain/blob/master/ss/customRPC.png" width="600" height="500">

8. Once we click on custom RPC we will need to fill in details. Below 2 figures are before filling details and after filling those details.

![](ss/before_details.png)

![](ss/after_details.png)

9. Now our private network is set. And it will look something like figure below when we click on Metamask extension icon. Make sure private network is selected.

![](ss/connect1.png)

10. Next step, we need to import address from running Ganache application to this private network. For that click on circle icon next to private network written drop down on right top. Which will look like below figure.

![](ss/connect2.png)

11. Next we will select import account which will open below figure dialog. And here we need to paste the private key of the address we want to connect to the private network.

![](ss/connect3.png)

12. We can get that private key from Ganache application. Open the running Ganache window and select the key icon on the right and we can pick any address we want. Here we are going to select key icon for top most address (0x74b4…).

![](ss/connect4.png)

13. Once we click on key icon it will open dialog box given in below figure just copy that private key. (Here to avoid any misuse I have hidden the private key).

![](ss/connect5.png)

14. Once we copy the key, paste that in dialog box opened in step 11. And click import. We can see in below figure after successful import our Ganache address(0x74b4..) is now available here.

![](ss/connect6.png)

15.  We can see that not connected text on top left corner it means our running localhost website is not connected with this account. For that click on three dot icon next to Account 6 and select Connected sites which will ask to Manually connect to current site. 

![](ss/connect7.png)

![](ss/connect8.png)

16. Then it will ask to select manually which account to connect make sure account we imported is selected. Then press next and finally click confirm.

![](ss/connect9.png)

![](ss/connect10.png)

17. Next we can see now it shows Connected.

![](ss/connect11.png)

18. Now all setup is completed finally and we can test our application. Now make sure you see figure similar to one in step 6. Here click on adopt button on any pet you want to adopt. And once we click on that it will open a popup asking for the transaction confirmation just like below figure.

![](ss/connect12.png)

19. And once we confirm the transaction that pet you clicked is adopted by you and the adopt button is no longer available for that pet and it is replaced by success button.

![](ss/connect13.png)

##### Or you can see the youtube demo of how to execute the project:

<a href="https://www.youtube.com/watch?v=UY-DFtYRFgM&feature=youtu.be" target="_blank"><img src="ss/thumbnail.png" alt="IMAGE ALT TEXT HERE" width="800" height="500" border="10" /></a>

___

## References:

* https://www.trufflesuite.com/tutorials/pet-shop
* https://www.youtube.com/watch?v=coQ5dg8wM2o
* https://github.com/Alexintosh/Adopt-a-Pet-dapp
* corgi image: https://favim.com/image/7073677/
* retriver image: https://hypeauditor.com/preview/tuckerbudzyn/ 
* rest of the animals’ photo was taken from: https://www.goodhousekeeping.com/life/pets/advice/g1236/animal-instagrams/?slide=19

