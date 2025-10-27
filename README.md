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
Name: Bakkiyalakshmi E
Reg No: 212223220012
```
 ```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
marks=[30,15,62,81]
student=['Bakki','Raji','Malar','Gokki']
plt.plot(marks,student)
plt.title("My Line Plot!")
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()

 ```
<img width="833" height="593" alt="image" src="https://github.com/user-attachments/assets/1e20df95-d2d8-4ace-9b8f-259909ce6fcb" />

 ```
 student=['Bak','Raj','Mal','Gok']
 attendence=[60,85,73,99]
 plt.plot(attendence,student)
 plt.title("My Line Plot!")
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
 ```
<img width="821" height="592" alt="image" src="https://github.com/user-attachments/assets/9948a427-1e05-4a44-bffe-8bcaf7e01b77" />

 ```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='blue',marker='*',s=30)
 plt.title("My Scatter Plot!")
 plt.show()
 ```
<img width="800" height="567" alt="image" src="https://github.com/user-attachments/assets/76b52b61-725f-47e7-aa0e-6cc4396621af" />

 ```
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='purple')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
 ```
<img width="813" height="589" alt="image" src="https://github.com/user-attachments/assets/d678584b-e37a-48ce-9128-7094dd5b55db" />

 ```
 act=['bak','raj','mal','gok']
 slices=[3,7,6,8]
 color=['pink','y','g','skyblue']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.title("My Pie Chart!")
 plt.legend()
 plt.show()
 ```
<img width="680" height="565" alt="image" src="https://github.com/user-attachments/assets/4ba656b3-e7b7-43df-b046-2f3d198ffbc9" />

 ```
 feedback=['Good R','excellent G','Perfect M','Ok B']
 slices=[4,10,3,8]
 color=['y','aqua','g','pink']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.title("My Pie Chart!")
 plt.legend()
 plt.show()
 ```
<img width="697" height="538" alt="image" src="https://github.com/user-attachments/assets/9b606839-cba8-40d6-80b6-c784885fe6d6" />

 ```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='pink')
 plt.fill_between(x, y2, color='skyblue')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.title("My Area Chart!")
 plt.legend(['y1','y2'])
 plt.show()
 ```
<img width="808" height="570" alt="image" src="https://github.com/user-attachments/assets/9a32ee3a-5c96-4f55-953b-5e1db1fa1627" />

 ```
 height = [25, 42, 30, 38, 28]
 names = ['bak', 'gok', 'mal', 'kum', 'raj']
 c1=['pink', 'skyblue'] 
c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.title("My Bar Chart!")
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
 ```
<img width="813" height="594" alt="image" src="https://github.com/user-attachments/assets/36a33520-45a9-41cd-8dd9-cf39bc1a1ae8" />

 ```
 plt.title('My Histogram chart!')
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='purple', alpha=0.5)
 plt.show()
 ```
<img width="786" height="570" alt="image" src="https://github.com/user-attachments/assets/47b5057c-0220-43e1-aee8-5c5703120ff9" />
```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
<img width="832" height="456" alt="image" src="https://github.com/user-attachments/assets/b4cfd279-1acb-46fe-ba77-0163882862f3" />
```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('My Box Plot!')
```
<img width="831" height="615" alt="image" src="https://github.com/user-attachments/assets/2d2c0010-14ea-4b6e-8a76-4149238bef55" />

# Result:
 Thus,the Experiment was executed Successfully.
