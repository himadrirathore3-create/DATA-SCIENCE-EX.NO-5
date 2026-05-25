# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

```
import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
```
# Line Plot:

```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
```

```
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```

# Output:
<img width="1101" height="450" alt="image" src="https://github.com/user-attachments/assets/383e3e55-47f6-49e0-bd87-082fc918e340" />
<img width="804" height="738" alt="image" src="https://github.com/user-attachments/assets/368b09cf-bf40-465d-b4d9-90c3fddadb43" />

# Scatter Plot:

```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
```

```
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

# Output:

<img width="640" height="225" alt="image" src="https://github.com/user-attachments/assets/d25eb5a4-d3bb-42d3-b465-47fa9e502726" />
<img width="793" height="735" alt="image" src="https://github.com/user-attachments/assets/6b61033a-7a68-402c-a3d4-60c682881837" />

# Pie Chart:

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

```
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

# Output:

<img width="934" height="207" alt="image" src="https://github.com/user-attachments/assets/79e72770-398d-4c83-bc3d-2600ac631f1b" />
<img width="703" height="696" alt="image" src="https://github.com/user-attachments/assets/5a05e969-8a97-4c91-88a5-60271b50163a" />

# Area Chart:

```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

# Output:

<img width="785" height="539" alt="image" src="https://github.com/user-attachments/assets/250bc730-441b-4e7b-a358-c7b068649647" />

# Bar Chart:

```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show() 
```

# Output:

<img width="814" height="558" alt="image" src="https://github.com/user-attachments/assets/3113b94a-3c0e-4cc6-9010-a3b38b7c8dad" />

# Histogram:

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

# Output:

<img width="944" height="425" alt="image" src="https://github.com/user-attachments/assets/5ce54f52-556d-494a-9f98-296b8827b6af" />

# Box Plot:

```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```

# Output:

<img width="595" height="369" alt="image" src="https://github.com/user-attachments/assets/b2a8da5a-a65c-44ff-bff4-75ad0142f2ea" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```

# Output:

<img width="778" height="504" alt="image" src="https://github.com/user-attachments/assets/5e7f6bd0-d637-4f90-a747-914a337af7a5" />





















# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
