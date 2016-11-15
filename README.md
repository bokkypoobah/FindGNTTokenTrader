# FindGNTTokenTrader
Find Golem Network Token (GNT) TokenTrader Information

This script will list the TokenTrade contracts created by the TokenTraderFactory contract deployed to https://etherscan.io/address/0xc4af56cd5254aef959d4bce2f75874007808b701 .

## Background
For further information on the TokenTrader and TokenTraderFactory contracts, see:
* https://www.bokconsulting.com.au/blog/trustless-token-selling-contract/
* https://www.reddit.com/r/ethtrader/comments/5cnl58/trustless_gnt_selling_contract/

## Notes
* This scripts list all deployed TokenTrader, even those deployed with some errors. The Sell price and Units fields for the TokenTrade deployed with errors is normally crazily incorrect.
* If you do want to try purchasing GNTs from these contracts, test with  a small amount first.
* This is just a tool for finding the contracts. Your use of the contracts is your own responsibility!

## Download
To use this script, download https://github.com/bokkypoobah/FindGNTTokenTrader/blob/master/findGNTTokenTrader and read the instructions at the top of the file.

## Sample Output

See the list above for the latest files with the name 'findGNTTokenTraderOutput_yyyymmdd_hhmmssUTC.csv'.

Sample output :

    Listing generated at Tue, 15 Nov 2016 12:28:53 UTC
    0 TokenTrader Address: 0x399156ee3339f4b29a53e307b98cce09fda3bac7
      Deployed                         : #2615921 at Sat, 12 Nov 2016 23:17:56 UTC
      TxHash                           : 0x6a7f83c93837f4ab11e1bc9dae2a34df4b4610b0d87512e451a36b5f53fb9661
      Owner                            : 0x0020dba1d308339182239056a00fcc146d2e26e0
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 200
      Units                            : 100000
      Ethers per 1,000 tokens          : 2
      Current TokenTrader token balance: 185495
      Current TokenTrader ether balance: 524.012902
      Current Owner ether balance      : 458.69492270873582333
    1 TokenTrader Address: 0xb362bba1c7c5c857e3ac74d740c0007c48db7362
      Deployed                         : #2617375 at Sun, 13 Nov 2016 05:05:53 UTC
      TxHash                           : 0xb7ef581cd0e6597525e254add6f820ac6ecf860d89d01656035dfd880dac2747
      Owner                            : 0x0020dba1d308339182239056a00fcc146d2e26e0
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 150
      Units                            : 100000
      Ethers per 1,000 tokens          : 1.5
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 2.5e-16
      Current Owner ether balance      : 458.69492270873582333
    2 TokenTrader Address: 0x4104e4b12e73bc99dd4f20a39525d07aa395c0d4
      Deployed                         : #2618103 at Sun, 13 Nov 2016 07:57:29 UTC
      TxHash                           : 0x3cf847a7087dd02ae2c1ac76c7c498ca3f4ca4b10a7cf1fc00cad4b5c178c531
      Owner                            : 0x0020dba1d308339182239056a00fcc146d2e26e0
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 300
      Units                            : 100000
      Ethers per 1,000 tokens          : 3
      Current TokenTrader token balance: 1794.8333333333342
      Current TokenTrader ether balance: 34.6155000000000019
      Current Owner ether balance      : 458.69492270873582333
    3 TokenTrader Address: 0xec323cff33a717aa88ce0c6ad97de5b3eba1ca1e
      Deployed                         : #2618686 at Sun, 13 Nov 2016 10:08:44 UTC
      TxHash                           : 0x60eaae62ffbdd56cc922e738a0f3e1301c3178e90f3a31af504e7b3b12cf2251
      Owner                            : 0xcd68762eb52324f4d83040e2c85d8aea51ec0d31
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : false
      Sell price                       : 200
      Units                            : 25000
      Ethers per 1,000 tokens          : 8
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 0
    4 TokenTrader Address: 0x3243f7f0c5ef59fa430f41b08ab356902573d274
      Deployed                         : #2618757 at Sun, 13 Nov 2016 10:28:47 UTC
      TxHash                           : 0x0f13a7c339006ca2110ef70b6146073c924bb7e727a19befe937a4fdd318d65c
      Owner                            : 0xcd68762eb52324f4d83040e2c85d8aea51ec0d31
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : false
      Sell price                       : 200
      Units                            : 100000
      Ethers per 1,000 tokens          : 2
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 0
    5 TokenTrader Address: 0x54b0ad2e694f234e01822b4f24b6c2ab126a577f
      Deployed                         : #2619148 at Sun, 13 Nov 2016 11:59:35 UTC
      TxHash                           : 0xbb6f14368be8412afd9e1746938997fc26bdbae94f7ca8657f155d5bf701898b
      Owner                            : 0xcd68762eb52324f4d83040e2c85d8aea51ec0d31
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : false
      Sell price                       : 300
      Units                            : 100000
      Ethers per 1,000 tokens          : 3
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 0
    6 TokenTrader Address: 0x9fd7e3743dadde6d954f840c598c9b20abef0793
      Deployed                         : #2619229 at Sun, 13 Nov 2016 12:15:38 UTC
      TxHash                           : 0x0b6d4a83e2813010dd2e4f6e226b9322ec0975d583c9ff2d29fb197fa04b7727
      Owner                            : 0x16efbb80e246b61e42e0d8bd6496cefb9d40867b
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 0
      Units                            : 1000000
      Ethers per 1,000 tokens          : 0
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 1085.347925203083825378
    7 TokenTrader Address: 0xc0081f0e16cbceec6df8e63986212a52ee493540
      Deployed                         : #2619428 at Sun, 13 Nov 2016 13:04:24 UTC
      TxHash                           : 0x03418089251eaae28626c733fc6eb5a1255e80d9ba98e62b178646a987cb514a
      Owner                            : 0x16efbb80e246b61e42e0d8bd6496cefb9d40867b
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 188
      Units                            : 100000
      Ethers per 1,000 tokens          : 1.88
      Current TokenTrader token balance: 102829.2696557392019
      Current TokenTrader ether balance: 1.17800000000000124
      Current Owner ether balance      : 1085.347925203083825378
    8 TokenTrader Address: 0xe743e923850b8aa0c101684e0abf389d21e4e623
      Deployed                         : #2619497 at Sun, 13 Nov 2016 13:18:41 UTC
      TxHash                           : 0xef511d0ddb520edef04c9d91870d5d8f63069c69d3fe961c8fc050c679fbddd7
      Owner                            : 0x16efbb80e246b61e42e0d8bd6496cefb9d40867b
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 178
      Units                            : 100000
      Ethers per 1,000 tokens          : 1.78
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 1085.347925203083825378
    9 TokenTrader Address: 0xdec557f3b3c0e8f46f67a9a3097507d5a764dbc6
      Deployed                         : #2619704 at Sun, 13 Nov 2016 14:12:00 UTC
      TxHash                           : 0x8761b6ea8ecfb177d7d76badc75eba276eec9dbcb616a59312316c7ffcd27c5e
      Owner                            : 0xc0bd5afc3dbd7affef40a8d6a7921bbefb3bcdb2
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 400
      Units                            : 100000
      Ethers per 1,000 tokens          : 4
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 5.406221640758317507
    10 TokenTrader Address: 0x8881e10321f36fe893db67d388ad1d4727ad899d
      Deployed                         : #2620228 at Sun, 13 Nov 2016 16:07:02 UTC
      TxHash                           : 0x037552e00ee84c5f6d1ce976ac55b0145544bc5ddfa61a4ec2b2213929ad732f
      Owner                            : 0x65be7973aefa378fc4b41b7ada858b709b393178
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 200
      Units                            : 100000
      Ethers per 1,000 tokens          : 2
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 2.1147433353600001
    11 TokenTrader Address: 0x213f1e6e515978d98dab33a2e58a721c9baa0f19
      Deployed                         : #2620247 at Sun, 13 Nov 2016 16:11:11 UTC
      TxHash                           : 0x9db1ef6dea4a4045a9814567764dc81b49d4033b6614769c6acf52b1114111fb
      Owner                            : 0x4a4716db9800dc20a3975e4fe562fa70448487dc
      Asset address                    : 0x00a74476443119a942de498590fe1f2454d7d4ac ???
      Sells tokens                     : true
      Sell price                       : 5.880067031582463048853214082472432820673866408802059892628705437901838614528e+75
      Units                            : 5.300541194335152988749892502228755547482451690626856874364818603877859328e+74
      Ethers per 1,000 tokens          : 11093.33333333333333333
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 0.136507538
    12 TokenTrader Address: 0xa7f8da2594eaf1e8573a5974be6028f64157cd7a
      Deployed                         : #2620364 at Sun, 13 Nov 2016 16:37:01 UTC
      TxHash                           : 0xb1476af7d8f727082e0844799223e8b25bfb285ed3eb26bc0b32cf4a539ab874
      Owner                            : 0x65be7973aefa378fc4b41b7ada858b709b393178
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 200
      Units                            : 100000
      Ethers per 1,000 tokens          : 2
      Current TokenTrader token balance: 713516
      Current TokenTrader ether balance: 1.9679999999999999
      Current Owner ether balance      : 2.1147433353600001
    13 TokenTrader Address: 0x42be3b481f25b0148cd1a144d8ca22cda5b677e7
      Deployed                         : #2620449 at Sun, 13 Nov 2016 16:54:25 UTC
      TxHash                           : 0x1d01cc09fb0482bb406ceda6a173985c9879144c0c875eafb7bc66a3b1d108ed
      Owner                            : 0x16efbb80e246b61e42e0d8bd6496cefb9d40867b
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 233
      Units                            : 100000
      Ethers per 1,000 tokens          : 2.33
      Current TokenTrader token balance: 205296.1965953052123
      Current TokenTrader ether balance: 4.489861932938856016
      Current Owner ether balance      : 1085.347925203083825378
    14 TokenTrader Address: 0xe0a1c26c65deef0316762ebc8f3734d703664947
      Deployed                         : #2620618 at Sun, 13 Nov 2016 17:35:15 UTC
      TxHash                           : 0x60227ae1206edacbe3b622ef30476c721292e4bf7d6df97949333a862faed3e1
      Owner                            : 0x16efbb80e246b61e42e0d8bd6496cefb9d40867b
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT
      Sells tokens                     : true
      Sell price                       : 150
      Units                            : 100000
      Ethers per 1,000 tokens          : 1.5
      Current TokenTrader token balance: 0
      Current TokenTrader ether balance: 0
      Current Owner ether balance      : 1085.347925203083825378
    15 TokenTrader Address: 0x7ea06cf742bf823d8b711c35795859445f3181c1
      Deployed                         : #2620623 at Sun, 13 Nov 2016 17:37:09 UTC
      TxHash                           : 0xea9a0aff2df1ae2bc66686616df55185098bb6fff07dd4cca81073bad28e6fbe
      Owner                            : 0x16efbb80e246b61e42e0d8bd6496cefb9d40867b
      Asset address                    : 0xa74476443119a942de498590fe1f2454d7d4ac0d GNT





Enjoy. (c) BokkyPooBah 2016. The MIT licence.
