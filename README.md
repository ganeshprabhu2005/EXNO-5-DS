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
NAME: HEMANATH S
REG NO : 212224230094
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
````
#  Line Plot:
```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```

 <img width="603" height="853" alt="Screenshot 2025-10-27 101859" src="https://github.com/user-attachments/assets/f7822526-63a3-4cf9-8e77-7ad189d0b950" />

#  Scatter Plot:
```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
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
 <img width="562" height="841" alt="Screenshot 2025-10-27 101912" src="https://github.com/user-attachments/assets/bae80a7c-0ce5-498a-add0-4593ca802dbb" />

# Pie Chart:
```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```
<img width="521" height="813" alt="Screenshot 2025-10-27 101921" src="https://github.com/user-attachments/assets/21498bf9-af65-49f7-8990-65267a9f3e4d" />


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
 
<img width="766" height="431" alt="Screenshot 2025-10-27 101928" src="https://github.com/user-attachments/assets/82e9b763-a8b3-48a4-aae1-d938c271c98d" />


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
<img width="601" height="468" alt="Screenshot 2025-10-27 101934" src="https://github.com/user-attachments/assets/5c4ffc32-2ed2-42cd-9ee9-a8e4009bf6d6" />
 
# Histogram:
```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
 <img width="710" height="427" alt="Screenshot 2025-10-27 101941" src="https://github.com/user-attachments/assets/70983725-2851-4fa9-a1d0-cdcd4a9e9030" />


# Box Plot:
```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```
<img width="748" height="361" alt="Screenshot 2025-10-27 101949" src="https://github.com/user-attachments/assets/fefc5448-b36d-43fd-a221-417a47aff170" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="864" height="492" alt="Screenshot 2025-10-27 101956" src="https://github.com/user-attachments/assets/47fa09fb-e1e5-4708-828a-b756406c8076" />

# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
