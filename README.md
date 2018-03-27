# StellarSwap 
Stellarswap is a global exchange board for all Stellar token and cryptocurrencies (coins). Easy sign up, easy trading.
developed by Graichi Younes.
Contact me : jonasess@gmail.com or younes.graichi.93@gmail.com

### Requirements

This library requires the 'gmp', and cURL extensions for PHP. To enable these extensions, see:
   
   [GMP Installation Guide](http://php.net/manual/en/gmp.installation.php)

   [cURL Installation Guide](http://php.net/manual/en/curl.installation.php)
   
[Also check Block.io on how for more information.](https://github.com/BlockIo/block_io-php)


### Installation

Clone the project or download it and copy it to your main direction(Example: /var/www/html/).
git clone https://github.com/jonasess/Stellarswap

### Usage:

Sent up the data base tables ...

Set up your database connection in this directory include/dbconnection.php

Run ..
### Add new Stellar token:
1. Add the logo of the asset in the direction logo/

2. Add the information of your asset in the file stellarSwap-assetTokens.js
* Example:
```
[
  'Asset-website',
  'Asset-logo-direction example: logo/myaaset.png',
  'Asset code',
  'Asset issuer'
],
```

3. Do the same step in the file stellarSwap-assetTokens.php , add your asset information in the $asset_tokes array .
* Example
```
array("domain"=>"your-domain-name","logo"=>"Asset-logo-direction","code"=>"Asset code","issuer"=>"Asset issuer id"),
```

And congratulations your asset has been added to the board for the trading.

### Add new cryptocurrency (coin):
Details soon.
Hint you need to use api or daemons.

### Note:
Stellarswap use the api from block.io to support 3 coins (BTC, LTC and DOGE).
Giving the ability to create wallet, send and receive payments, exchange vs coins or tokens (stellar tokens) ... etc .

### Goals:
1. block.io api is limited, one of the goals is to change it and connect the board to daemon file of BTC or any other coin to give more control and unlimited usage.
2. Support more coins and tokens.
3. Add more security to the board.

### Warning:
1. For stellarswap account reset the password function is not working (under maintenance).
2. History of Stellar trades is under maintenance.
3. There's no History exchanges of coins yet, i will add it soon.

### Support me:
If you like the project and you want to support me . You can donate:
* Stellar wallet:``` GDI4HFEIZIPUGMXL7MM5BXRAJKC76XU2EDSS6GML2PL7MBTG6GICUYS3 ```
* BTC wallet:``` 1PD1UBxTajiHEa4oDZex6QN6UT4aRxCDsM ```
* ETH wallet:``` 0x083c01b98810e17b0b6cce27cb1cb37a6a40e4eb ```
* LTC wallet:``` LQ3fQoLJkW7hwuPdWtcPa5YYtAvmsp7UCs ```

You can contact me on GitHub or on my email address jonasess@gmail.com / younes.graichi.93@gmail.com .