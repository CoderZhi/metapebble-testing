# Meta Pebble Testing
*Network: IoTeX Testnet*

**1. Download/Install**
- iOS Testflight
- ioPay: build > 21
- Android https://iopay-app.s3.amazonaws.com/metapebble-alpha.apk 


**2. Create Meta Pebble**
- If you initialize the APP for the first time, you need to create a new meta pebble with an IMEI and an SN. The IMEI and SN are tied to the mobile, never changed after creation.<br/>

<img src="https://user-images.githubusercontent.com/83109624/179713956-af0a0b93-a7d6-4f6f-98d6-5a364f0337b2.png" width="300" height="550" /><br/>

**3. Connect wallet**
- Click `Activate Device` to connect to ioPay wallet (if you use Android for testing and cannot jump to ioPay, you need to go to the settings center to cancel the original "default" wallet).


**4. Claim the NFT (if your wallet doesn't have NFTs yet)**
uj
If your wallet owns no NFT, the NFT list will be empty. Click the claim button to open the ioPay, and then claim the NFT in dapp presented.

*Tip: Only for the IoTeX testnet.*

<img src="https://user-images.githubusercontent.com/83109624/179714088-1a0117de-c8bb-4e87-808c-a46ac4de16bb.png" width="300" height="580" /><br/>
<img src="https://user-images.githubusercontent.com/83109624/179714126-a0cb9cc6-d8a2-4c8b-baec-faefec68b3a2.png" width="300" height="580" /><br/>

**5. Select NFT**
- Select an available NFT, then click the `Activate` button
- The pebble will open the ioPay to excute the relevant contract methods.\
<img src="https://user-images.githubusercontent.com/83109624/179714188-76a073ef-7491-43f3-ba87-ee3624d9fe9c.png" width="300" height="580" /><br/>
<img src="https://user-images.githubusercontent.com/83109624/179714206-d0ac320a-603a-4cde-98b7-8c4131873ed7.png" width="300" height="580" /><br/>

**6. Register**

After completing the registration, the pebble app will query the status of device, which may be slow.<br/>

**7. Upload Data to Server**
- Go to settings, toggle the GPS and select an interval
- Click `Turn on` button
- Open the pebble in the home screen, the GPS data will be uploaded to the server repeatedly\
<img src="https://user-images.githubusercontent.com/83109624/179714275-d2674e77-d648-4089-8b2b-783bf25dd61e.png" width="300" height="550" /><br/>
<img src="https://user-images.githubusercontent.com/83109624/179714309-6e2f9d79-dfcf-4c13-a631-8a69d7c9e561.png" width="300" height="550" /><br/>

**8. Check GPS**\
Pebble will upload your GPS data to the portal and you can check your GPS data on the web and map.\
https://w3w3bstream-example.onrender.com/
