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

Active contracts from https://github.com/bokkypoobah/FindGNTTokenTrader/blob/master/findGNTTokenTraderOutput_20161116_005815UTC.csv:

    \#,TokenTraderAddress,SellsTokens,EtherPer1000Tokens,TokenBalance
    26,0x4b17f65fc6450cbcced9e893dd84123a5fc13362,TRUE,1.45,110624.7596
    27,0x1e00980cb7b109d290fcf6c4e579debb8c836c39,TRUE,1.45,164700.3448
    24,0x1a22bb6827dbb7df60a6de726519c2a509271695,TRUE,1.5,499660.2167
    6,0xc0081f0e16cbceec6df8e63986212a52ee493540,TRUE,1.88,102821.2909
    23,0x406a65de7a2e94ef19597a79296e269fada85a71,TRUE,1.9,136166.8742
    15,0x5eb860c816789bb52300a0675300701eca203cf8,TRUE,1.95,158854.1026
    0,0x399156ee3339f4b29a53e307b98cce09fda3bac7,TRUE,2,5430.015
    10,0xa7f8da2594eaf1e8573a5974be6028f64157cd7a,TRUE,2,713516
    22,0xf31057bc0ff5e3e3b32652b29c0451624392567c,TRUE,2,100050
    25,0xffd41efe3d3c073f4c7dbf2cec7c19111fc7523e,TRUE,2,4250
    17,0x6e3f7ad4d9accb12452744fb2785ecac31ea8026,TRUE,2.05,50000
    18,0x4b34da26bfb35d3089c455cb483a5fff8695d447,TRUE,2.11,200000
    11,0x42be3b481f25b0148cd1a144d8ca22cda5b677e7,TRUE,2.33,9.00E-12
    2,0x4104e4b12e73bc99dd4f20a39525d07aa395c0d4,TRUE,3,1794.833333
    19,0x593fd4a14f64282891a1369442462361a1908b01,TRUE,3.75,900


Enjoy. (c) BokkyPooBah 2016. The MIT licence.
