## Design Low Pass Filter

by using frequency cutoff at 2 GHz and attenuation 3 GHz > 30 dB.

#### We chosse 0.5 dB ripple Table

<img width="800" src="Photo/0.5 dB.jpg">

We get abs(W/Wc) - 1 = 0.5 and then we gonna get N = 7

#### Calculate L and C from g 7-order that we got from table and then use Impedance High or Zh = 105 and Impedance Low or Zh = 25  in excel.

<img width="800" src="Photo/CLexcel.png">

#### Put the value L, C, R0, Zh, and Zl in Sonet to see a graph that cutoff at 2 GHz or not.

<img width="800" src="Photo/CLR.jpg">

<img width="800" src="Photo/graph.png">

## Using Txline to find width and length of C, L, and R

<img width="800" src="Photo/105a.png">
<img width="800" src="Photo/105b.png">
<img width="800" src="Photo/25a.png">
<img width="800" src="Photo/25b.png">
<img width="800" src="Photo/50.png">
