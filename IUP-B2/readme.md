## Step 1: How we Design our Low Pass Filter

Our specification of LPF ;  	1. Cut off 2GHz
2. ATTN 3GHz > 30dB
#### 1.We are choosing n = 5 from this graph

<img width="502" src="image077777777.jpg">
 

#### 2. From criteria given ATTN 3GHz > 30dB so from the graph above we are choosing n = 5 we will get (w/wc)-1 = 0.5 Calculation :
f = 3 GHz, fc = 2 GHz, (w/wc) - 1 = 0.5	

#### 3. From 1) and 2) we calculate the value as shown below.
<img width="502" src="image8888888.png">
 

## Step 2: Graph
We decide to use Zh = 110 ZL = 25 and R0 = 50 and we can calculate the length and width of the LPF 

<img width="502" src="project555555556666666.png">




## Step 3: designed LPF

<img width="502" src="sonnetboard.png">



## Step 4: design PCB by using EasyEDA

<img width="502" src="2dpicture.png">

<img width="502" src="3dpicture.png">



EasyEda Link : https://oshwlab.com/natthapon.r/finalproject

## Members
Krittapas 6410551037
Natthapon 6410551053
Thunwarach 6410554206
Machaphat 6410554231
Wiyadarat 6410551100
