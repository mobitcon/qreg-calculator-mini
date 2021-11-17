# qreg 11 calculator
This is the git repository for the calculator for the [qreg 11](https://qreg.tech/product/qreg-11/).
The calculator is used to give an easy way to see what parts of the qreg card have to be ejected from the qreg 11 metal card.
The qreg 11 calculator is hosted on the [here](https://qreg.tech/qreg-calculator-11/) but it can be run on local machine too. This can be achieved by either downloading or  cloning this repository. After downloading/cloning, open the index.html via webbrowser and enter the bip 39 word number or the word itself, the bits will be calculated automaticaly.
The calculator uses the [bip 0039 words](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt) as base for the calculation of the bits. The logic is written in the app.js file. 
The word *abandon* (The first line of the bip 39 file) will translate to number 1, which than will be translated to "00000000001". *ability* -> 2 -> "000000000010". This continues upto *zone* -> 2047 -> "11111111111". As the qreg 11 card onlyfeatures 11 "bits" the word zoo is mapped to "00000000000".  


