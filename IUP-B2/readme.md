## Step 1: How we Design our Low Pass Filter

Our specification of LPF ;  	1. Cut off 2.4GHz
2. ATTN 3GHz > 30dB
#### 1.We are choosing n = 7 from this graph

<img width="502" src="table.png">

<img width="502" src="order.png">
 

#### 2. From criteria given ATTN 3GHz > 30dB so from the graph above we are choosing n = 7 we will get (w/wc)-1 = 1 Calculation :
f = 4.8 GHz, fc = 2.4 GHz, (w/wc) - 1 = 1	

#### 3. From 1) and 2) we calculate the value as shown below.
<img width="502" src="excel.png">
 

## Step 2: Graph
We decide to use Zh = 100 ZL = 25 and R0 = 50 and we can calculate the length and width of the LPF 

<img width="502" src="graph.png">





## Step 3: designed LPF

<img width="502" src="2dsonnet.png">




## Step 4: design PCB by using EasyEDA


<img width="502" src="2deasyeda.png">

<img width="502" src="3deasyeda.png">



EasyEda Link : https://oshwlab.com/natthapon.r/TheFinalProject


## Members
Krittapas 6410551037
Natthapon 6410551053
Thunwarach 6410554206
Machaphat 6410554231
Wiyadarat 6410551100
