# RPG Game Maker MV-Free-Cryptocurrency-Algo-Payment-Gateway<br>
## Algo Crypto Blockchian Plugin.

## Free Plugin!
## Recieve ETH,BNB,FTM,Matic,Moonriver.. cryptocurrencies in your RPGMaker MV Games!

<img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/icon/eth.png" width="25" height="25" alt="eth"> <img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/icon/bnb.png" width="25" height="25" alt="bnb"> <img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/icon/ftm.png" width="25" height="25" alt="ftm"> <img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/icon/matic.png" width="25" height="25" alt="matic"> <img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/icon/movr.png" width="25" height="25" alt="movr"><br>
RPGMaker Free Cryptocurrency Payment Gateway<br>
due to reduce the big size of project zip file ,"audio" and "img" folder are deleted,<br>
you just need create a new RPG Maker Project, then copy "audio" and "img" folder to this project. <br>
and then launch the Game.rpgproject. <br>
 <br>
 
*This plugin now support Ethereum,Binance,Polygon,Fantom,Moonriver,and Ropsten Test network. <br>
### How To Use<br>
1.Copy the "AlgoCryptoPayment.js" and "RS_InputDialog.js" files into your project's /js/plugins/ folder.<br>
2.Activate plugin using the 'Plugin Manager'.<br>


## Script command <br>
<img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/script.png" alt="RPGmaker crypto payment1">


### Create New wallet
CreateWallet()<br>

### Show Player's wallet
ShowMyWallet()<br>

### Show Infomation of ERC20 token
InfoOfERC20("0xFA9A0930D919657b00e208631c836B404B2da729")<br>

### Check if Player is the owner of this NFT.
ownerOf(3,"0x8210be23eC496ABEbb55eD9243FEd11687Fc37d1")<br>
3 is tokenID, "0x8210be23eC496ABEbb55eD9243FEd11687Fc37d1" is ERC721 token address<br>

### Send ETH/BNB... to Game Owner,and recive game coins
SendBaseCoin(  "0x7B70921a415eF9cCea9EFAA19EAB8E9860734c2f",0.01,1000 ) <br>
Send 0.01 ETH/BNB/matic to  "0x7B70921a415eF9cCea9EFAA19EAB8E9860734c2f",and get 1000 Game Coins. <br>

### Send ERC20 Token... to Game Owner,and recive game coins
SendERC20( "0xFA9A0930D919657b00e208631c836B404B2da729",18,1,"0x7B70921a415eF9cCea9EFAA19EAB8E9860734c2f",1000 )<br>
Send 1 token (token address:"0xFA9A0930D919657b00e208631c836B404B2da729") to "0x7B70921a415eF9cCea9EFAA19EAB8E9860734c2f" ,and get 1000 Game Coins.<br>

### Transfer NFT
safeTransferFrom(NFTAddress,FromAddress,ToAddress,TokenID)<br>
safeTransferFrom( "0x8210be23eC496ABEbb55eD9243FEd11687Fc37d1","0xb6A4c1C0af091aFFff0E7d4D8E09f2e400286e34","0x7B70921a415eF9cCea9EFAA19EAB8E9860734c2f",2 )<br>












 
Video tutorial:https://www.youtube.com/watch?v=DL4XKOE8eN8
 
 
<img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/algoPayment.png" alt="algoPayment">
 <br>
<img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/2.png" alt="RPGmaker crypto payment1">
<img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/1.png" alt="RPGmaker crypto payment2">
<img src="https://github.com/AlgoNetwork/RPGMaker-Free-Cryptocurrency-Algo-Payment-Gateway/blob/main/3.png" alt="RPGmaker crypto payment3">
