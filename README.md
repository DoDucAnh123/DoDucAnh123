# sample-21080300
<html>
<head>
<title>21080300-Do Duc Anh</title>
<meta name="viewport" content="initial-scale:1.0;width=device-width">
<style>
* {
  box-sizing: border-box;
}
body {
  margin: 0;
}

.header {
  background-color: pink;
  padding: 20px;
  text-align: center;
}

.topnav {
  overflow: hidden;
  background-color: black;
}


.topnav a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 20px 30px;
  text-decoration: none;
}
</style>
</head>
<body>
<body style = "background-color:pink" >
<div class="header">
  <img style="border-radius:50%;object-fit:cover" src= "hobby.jpg" width="200" height="200"  alt="error"/>
  <h1>Đỗ Đức Anh</h1>
  <p>MAS 1 - 21080300</p>

</div>
<br>
<br>
<br>
<br>

<p>
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

labels=["North","East","West","South"]
yvals=[10,1,2,7]

nbars=len(labels)
y=np.arange(nbars)

plt.bar(labels,yvals, color='r')
plt.plot()

plt.xlabel("Region")
plt.yticks(ticks=y)
plt.ylabel("Number of transactions")
plt.title("Company performance")
plt.show()
</p>

</body>
</html>

