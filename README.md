# jTechTEXAS
# e-Calculator
[jTech<sup>TM</sup> TEXAS](https://kietpawpan.github.io/jTechTEXAS)

<img src="https://kietpawpan.github.io/jTechTEXAS/img/Body.svg" width="200">

## Contents
- [Use](https://github.com/Kietpawpan/jTechTEXAS/blob/main/README.md#utility)
- [Credits](https://github.com/Kietpawpan/jTechTEXAS/blob/main/README.md#credits)
- [Users' Guide](https://github.com/Kietpawpan/jTechTEXAS/blob/main/README.md#users-guide--j-2305)
  - Warning
  - Use
  - Financial calculation rules
 - [License](https://github.com/Kietpawpan/jTechTEXAS/blob/main/README.md#license)

## Utility
An analytical device for financial freedom planner & intelligent investor, with the following functions:  

- Future Value (FV) 
- Present Value (PV)
- Interest Rate (I)
- Investment period (N)
- Financial Freedom Goal (FX)
- Expected Interest Rate with Monthly Saving (IM)
- Common Stock Target Price (TP)
- Desired Stock Target Price (PX) 
- Earning Per Share Dynamics (E1 & E2)
- Financial condition (FN)
- Moderate P/E Ratio (PE)
- Product of P/E and Price to Book Value (BV)
- Desired Percent Growth Rate of Earning Per Share (PG)
- Observed Mean Percent Growth Rate of Earning Per Share (GR)
- Lifestyle Simplifying Goal (S)

## Credits
- Device body was modified from the electronic calculator designed and coded by [Justin Woodward](https://codepen.io/jwoo) at [https://codepen.io/freeCodeCamp/pen/MeQyjB](https://codepen.io/freeCodeCamp/pen/MeQyjB), with the internal functions removed and new keypad, buttons, and display panel designed.   
- Javascript functions for currency formatting were modified from https://aguidehub.com/codesandbox/?code=gallant-water-pg5t9e

## Users' Guide | J-2305

***Warning!***
- jTech<sup>TM</sup> makes no guarantees of the accuracy of this Users' Guide or its suitability for any purposes or the accuracy of calculation results produced by the e-calculator. For more information, see [License](https://github.com/Kietpawpan/jTechTEXAS/blob/main/README.md#license). jTech is not a broker/dealer, nor an investment advisor. No content in this repository should be understood as a recommendation to engage in any of the investment strategies presented in our repository content. We do not provide recommendations or views as to whether a stock or investment approach is suited to the financial needs of other people. We made this device for programming practice only.

### About this Manual  
- This Users' Guide covers use and calculation rules of the jTech<sup>TM</sup> TEXAS JT-2305.  
- The ==> sumbol indicates where the value for each input variable should enter (PV, FV, N, or I).  
  >Example: PE ==> PV indicates that you must input the value for PE at the PV cell on the display panel.
- On the whole display panel, there are four input cells. The top one is PV, the second top FV, the third N, and the fourth I.

To use this device,
1. Click the display panel, not the buttons on the keypad, to input the value for each input variable. 
2. Use the keypad on your mobile device (or the keyboard) to key the value (number) for each input variable of the function you apply. You can input only positive number. 
4. Click the function button to compute its value.
5. Check the calculation result on the bottom of the display panel. The default answer is 0.

### Step 1: Determine FX  
The first step in doing anything is to know exactly the results to be expected from what you are doing. In the money game, the first step is to set your **financial freedom goal** (FX)&mdash;the amount of money in your invesment account that generates the passive income at the rate of I (% per year) without you needing to work for money. FX depends on your designed lifestyle&mdash;the amount of money you have to expense per month (EX).

If you want to expense $15,000 per month for your designed lifestyle without having to work for it and if you will be able to gain passive income at the interest rate of 5% per year from your investment. Then, you input the following values (**Fig. 2a**):

```
EX ==> PV = 15,000
IX ==> I = 5
```   
Then, you click the **`FX`** button, and will get the answer of $3,600,000 (**Fig. 2b**), which means you should have at least $3.6 million in your investment account so that your financial freedom goal will be achieved; you can live without having to work for money, because the investment is working for you.

<img src="https://kietpawpan.github.io/jTechTEXAS/img/FX1.svg" width="200">

**Fig. 2a FX function input**

<img src="https://kietpawpan.github.io/jTechTEXAS/img/FX2.svg" width="200">

**Fig. 2b FX function output**


### Step 2 Determine I and IM  
I is the expected interest rate from your investment to achieve the financial freedom goal (FX). IM is I, given you will put the same amount of money in your saving account every month (m) for investment after your retirement .

Assume, for example, that
1. You will be working for money during the next 12 years before your retirement.
2. You know from step 1 that your FX is $3.6 million.
3. At present, your have $1,000,000 in your investment account.

So, you input the following values:  

```
PV ==> PV = 1,000,000;
FX ==> FV = 3,600,000;
N ==> N = 12;
```

Then, you click the **`I`** button, and will get the value of 11.265%/y as the answer (**Fig. 3**), which means your expected interest rate should be 11.265% per year so that you will have $3.6 million in your investment account, for your financial freedom after retirement.

<img src="https://kietpawpan.github.io/jTechTEXAS/img/I.svg" width="200">  

**Fig. 3 I function**

However, if you also save the money from other sources of income, say totally $10,000 per month, or m = $10,000 per month, then you input the following values:
```
PV = 1,000,000;
FX ==> FV = 3,600,000;
N = 12;
m ==> I = 10000;
```
Then, you press the **`IM`** button, and will get the answer of 6.628%/y (**Fig. 4a 4b**), which means your expected interest rate should be 6.628% per year so that you will have $3.6 million in your saving account for your financial freedom after retirement.

<img src="https://kietpawpan.github.io/jTechTEXAS/img/IM1.svg" width="200">  

**Fig. 4a IM function input**

<img src="https://kietpawpan.github.io/jTechTEXAS/img/IM2.svg" width="200">  

**Fig. 4b IM function output**

### Step 3 Determine TP and PX  
A way to make passive income is to have investments working for you. If you invest in common stocks, you need to buy the stocks of a few good companies, of which the stock prices will possibly reach your desired target prices (PX).

Assume, for example, that
1. Today stock price of company A (P) is $22 per share.
2. You would like to buy some shares of this stock, and held them for 5 years.
3. You know from step 2 that your required interest rate (IM) is 6.628% per share per year.
4. This company makes no dividend payment (d = $0 per year).

You input the values as follows:
```
P ==> PV = 22;
N = 5;
IM ==> I = 6.628;
```
Then, you press the **`TP`** buttton, and will get the answer of $30.32/s (**Fig. 5a 5b**), which is the expected target price of that stock ($/share), to give the interest rate equivalent of 6.628%.

<img src="https://kietpawpan.github.io/jTechTEXAS/img/TP1.svg" width="200">  

**Fig. 5a TP input**

<img src="https://kietpawpan.github.io/jTechTEXAS/img/TP2.svg" width="200">  

**Fig. 5b TP output**

However, if the company pay you dividend of $0.35 per share per year, so you input the values as follows:
```
TP ==> FV = 30.32;
N = 5;
d ==> I = 0.35;
```
Then, you press the **`PX`** button, and will get the answer of $28.57/s (**Fig. 6**), which is your desired target price of this stock ($/share). This price will give you 6.628% interest rate equivalent, including dividend.     

<img src="https://kietpawpan.github.io/jTechTEXAS/img/PX.svg" width="200">  

**Fig. 6 PX inputs and answer**

### Step 4 Determine PE and PG
PE is Moderate P/E ratio&mdash;current stock price divided by average earnings over the past three years (P/E). If, for example, the earning per share (E) of this stock over the past three years are $0.99, $0.98, and $0.86, and the current price (P) of this stock is $22.20, then you input the values as follows:
```
E1 ==> PV = 0.99;
E2 ==> FV = 0.98;
E3 ==> N = 0.86;
P ==> I = 22.2;
```
Then, you press the **`PE`** button, and will get the answer of 23.53 (**Fig. 7a 7b**), which means the average P/E ratio of this stock is 23.53, preferably rounded down to 23 for greater margin of safety. 

<img src="https://kietpawpan.github.io/jTechTEXAS/img/PE1.svg" width="200">  

**Fig. 7a PE function input**

<img src="https://kietpawpan.github.io/jTechTEXAS/img/PE2.svg" width="200">  

**Fig. 7b PE function output**

You know from step 3 that the target price (PX) is $28.57 per share. You also know from step 4 that PE is 23.53. If, for example, the average earning per share (EPS) over the past 3 years of this stock is $0.94, then you input the values as follows:
```
PE ==> PV = 23.53;
PX ==> FV = 28.57;
N = 5;
EPS ==> I = 0.94;
```
Then, you press the **`PG`** button, and will get the answer of 25.83%/y (**Fig. 8**), which means that if the earning per share of this stock grow at 25.83% per year, you will achieve 6.628% desired interest rate from capital gain and dividend yield during the next 5 years. You still need to assess whether this EPS growth rate is plausible or not, based on the actual perfomance and potential of this company. This calculation is based on the assumption that the earning per share of this stock will increase in the future, preferably to double its earning per share in ten years (I > 7.1% per year).

<img src="https://kietpawpan.github.io/jTechTEXAS/img/PG.svg" width="200">  

**Fig. 8 PG function**

### Step 5 Determine GR  

If the earning per share of this stock in the past ten years at the end four years are 1.21, 0.98, 0.99, and 0.86, then you input the values as follows:
```
eps7 ==> PV = 1.21;
eps8 ==> FV = 0.98;
eps9 ==> N = 0.99;
eps10 ==> I = 0.86;
```
Then, you press the **`GR`** button, and will get the answer of -10.37%/y (**Fig. 9**), which means the actual performace of this stock, represented by EPS, is declining at 10.37% per year, much lower than your expected growth rate (PG = 29.42%). You can decide whether to buy this stock or not, if there is no plausible theory to support the story that the EPS of this this stock will grow as you want (GR >= PG).


<img src="https://kietpawpan.github.io/jTechTEXAS/img/GR.svg" width="200">  

**Fig. 9 GR function**

### Step 6 Determine E1
E1 is the average earning per share (EPS) over the past ten years at the beginning (year 1 to year 3). If EPSs at year 1, 2 , and 3 are 1.21, 0.98, and 0.99 dollars per share, respectively, then you input the values as follows (**Fig. 10a**):
```
eps8 ==> PV = 1.21;
eps9 ==> FV = 0.98;
eps10 ==> N = 0.99;
```

<img src="https://kietpawpan.github.io/jTechTEXAS/img/E1.svg" width="200">  

**Fig. 10a E1 input**

Then, you press the **`E1`** button, and will get the answer of $1.06/s (**Fig. 10b**), which means the base EPS of this stock is $1.06 per share.

<img src="https://kietpawpan.github.io/jTechTEXAS/img/E12.svg" width="200">  

**Fig. 10b E1 output**

### Step 7 Determine E2
E2 is the average earning per share (EPS) over the past ten years at the end (year 8 to year 10). If EPSs at year 8, 9 , and 10 are 0.98, 0.99, and 0.86 dollars per share, respectively, and you know from step 6 that E1 = $1.06 per share, so you input the values as follows:
```
eps8 ==> PV = 1.21;
eps9 ==> FV = 0.98;
eps10 ==> N = 0.99;
```
Then, you press the **`E2`** button, and will get the answer of 67%<100! (**Fig. 11**), which means the current EPS of this stock is less than the expected EPS growth (100%), or a minimum increase of at least one-third in per share earnings in the past ten years. This stock is not a growth stock.

<img src="https://kietpawpan.github.io/jTechTEXAS/img/E2.svg" width="200">  

**Fig. 11 E2 input and output**

### Step 8 Determine PE
PE is the moderate price/earnings ratio, or current price divided by earning per share of year 8 to year 10. If EPSs at year 8, 9 , and 10 are 0.98, 0.99, and 0.86 dollars per share, respectively, and the current price of this stock (P) is $22.20 per share, so you input the values as follows (**Fig. 12a**):
```
eps8 ==> PV = 1.21;
eps9 ==> FV = 0.98;
eps10 ==> N = 0.99;
P ==> I = 22.20;
```
<img src="https://kietpawpan.github.io/jTechTEXAS/img/PE1.svg" width="200">  

**Fig. 12a PE input**

Then, you press the **`PE`** button, and will get the answer of 23.53>15! (**Fig. 13**), which means the price is greater than the average earnings more than 15 times&mdash;this stock is not a defensive stock. 

<img src="https://kietpawpan.github.io/jTechTEXAS/img/PE2.svg" width="200">  

**Fig. 13 PE output**

### Step 9 Determine BV
BV is the the product of PE miltiplied by price-to-book ratio (PB). If PB = 2.57, and you know from step 8 that PE = 23.53, so you input the values as follows:
```
PE ==> PV = 23.53;
PB ==> FV = 2.57;
```

Then, you press the **`BV`** button, and will get the answer of 60.5>22.5! (**Fig. 14**), which means the ratio of price to assets is more than 1.5 in recent years, given PE is 15&mdash;This stock is not a defensive stock. 

<img src="https://kietpawpan.github.io/jTechTEXAS/img/BV2.svg" width="200">  

**Fig. 14 BV inout and output**

### Step 10 Determine FN
FN is financial condition of this stock. If the current assets (CA), the current liabilities (CL), the long term debt (LTD), and the equity (EQ) are $135,552.48, $68,660.05, 24,488.40, 103,760.82 million, respectively, so you input the values as follows:
```
CA ==> PV = 135,552.48;
CL ==> FV = 68,660.05;
LTD ==> N = 24,488.40;
EQ ==> I = 103,760.82;
```

Then, you press the **`FN`** button, and will get the answer of 2>2l!Dy<2Ey (**Fig. 15**), which means the the current assets is less than twice the current liabilities, but the long term debt does not exceed the net current assets and does not exceed twice the stock equity. This stock has too much current liabilities or too low net current assets.

<img src="https://kietpawpan.github.io/jTechTEXAS/img/FN.svg" width="200">  

**Fig. 15 FN inout and output**

## Financial Calulation Rules
 
PV = FV / (1 + I)<sup>N</sup>;  
FV = PV * (1 + I)<sup>N</sup>;  
N = ln(FV/PV) / ln(1 + I);  
I = (FV/PV)<sup>1/N</sup> - 1;  
```
FX(EX, IX) {
  FX = 12 * EX/IX;
  }
I(PV, FX, N) {
  I = ([(FX/PV)^1/N] - 1) * 100;
  }
IM(PV, FX, N, m) {
  IM = ([(((FX - (m * 12 * N))/PV)^1/N] - 1) * 100;
  }
TP(P, N, IM) {
  TP = (P * ((1 + IM/100)^N);
  }
PX(P, TP, N, d) {
  PX = TP - (d * N);
  }
PG(PE, PX, N, EPS) {
  PG = [(PX / PE) / (100 / N)] * 100;
  }
GR(eps1, eps2, eps3, eps4) {
  GR = (((eps2 - eps1) / eps1) * 100) + 
       (eps3 - eps2) / eps2) * 100) +
       ((eps4- eps3) / eps3) * 100)) / 3;
       }
 BV(P, BV) {
   P ==> PV;
   BV ==> FV;
   P/BV < 15: y;}
 E1(eps1, eps2, eps3){
  eps1 ==> PV;
  eps2 ==> FV;
  eps3 ==> N;
  E1 = (eps1 + eps2 + eps3)/3; ==> I}
 E2(eps8, eps9, eps10, E1) {
  eps8 ==> PV;
  eps9 ==> FV;
  eps10 ==> N;
  E1 ==> I
  E2 = (eps8 + eps9 + eps10)/3;
  E2 > E1 + E1/3: y;
   }
 PE(eps8, eps9, eps10, P) {
  eps8 ==> PV;
  eps9 ==> FV;
  eps10 ==> N;
  P ==> I 
  P/E2 > 15: y;
   }
 BV(PE, BV) {
   PE ==> PV;
   BV ==> FV;
   PE * BV < 22.5: y
   }
 FN(CA, CL, LTD, EQ) {
   CA ==> PV;
   CL ==> FV;
   LTD ==> N;
   EQ ==> I;
   CA > 2CL: y;
   LTD < (CA - CL): y;
   LTD < 2EQ: y;
   }
```
### Assumption
1. Current assets are not diffcult to liquidate.
2. Data in the financial sheets are accurate.
3. Current ratios of 2 or greater indicate ample liquidity.
4. If the long-term debt is less than the net current assets, the company can liquidate the assets to repay its long-term debt.
5. A higher long-term debt-to-equity ratio makes the company more prone to financial risk.




## LICENSE
This code of jTech<sup>TM</sup> TEXAS calculator relies on the following codes: bootstrap.min.css and filestack.min.js. The calculator body was modified from the code at https://codepen.io/freeCodeCamp/pen/MeQyjB, designed and coded by Justin Woodward. which are all MIT Licensed, as noted at https://blog.codepen.io/documentation/terms-of-service/: 

> By submitting, posting or displaying Content on the CodePen Site, 
you grant CodePen and other users of the Services a worldwide, 
non-exclusive, royalty-free license (with the right to sublicense) 
to use, copy, reproduce, process, adapt, modify, publish, transmit, 
display and distribute such Content in any and all media or 
distribution methods (now known or later developed). 
Specifically, the MIT license. If you specifically save a Pen as 
private in CodePen, and that Pen has never been public on 
CodePen or anywhere else, the code in that particular Pen 
is unlicensed.

The filestack.min.js was taken from Filestack
>MIT License
>Copyright (c) 2020 Filestack
>Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

>The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.   

Aside from the above, the license for all other contents in 
this repository is as follows:

```
Copyright © 2023 Monte Kietpawpan ("jTech")
All rights reserved.

You may not copy, download, modify, publish, republish, transmit, 
distribute, perform, participate in the transfer or sale, create 
derivative works of, or in any other way exploit (including but 
not limited to for commercial use), any of the content in this 
repository, in whole or in part without our prior written consent.

THE SOFTWARE IS PUBLISHED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
