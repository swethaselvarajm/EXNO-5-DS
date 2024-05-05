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
Line
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
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/45bd220b-eae0-45db-8f88-c456bb26e0b2)
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/bc0e58fe-02b4-48e4-b442-0c6234017abf)

Bar graph
```
x=[10,20,30,40,50]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()

x=[14,30,25,6,20]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()
```
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/96847c7e-289d-4e09-8058-6ab1300abd96)
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/63368202-7307-444d-b4ce-45831bca0d0c)

Scatterplot
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
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/d535c555-a09a-45e3-a7a1-260ee173722d)
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/fdbe06fc-3573-4522-bbfc-1de52da48443)

Histogram
```
ages=[2,5,70,40,30,45,50,45,43,40]
range=(0,80)
bin=10
plt.hist(ages,bin,range,color='green',histtype='bar',rwidht=0.8)
plt.xlabel('ages')
plt.ylabel('No of people')
plt.legend()
plt.title('Histogram')
plt.show()

x=[2,1,6,4,2,4,8,9,4,2,10]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/ea94eff6-143d-4b13-9d9d-89a5dc962bb0)
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/33f86c38-33ca-42bd-ac8d-9b02149238f1)

Pie chart
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
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/e0cb61b9-0386-4d99-9d52-d2ec79be30f6)
![image](https://github.com/swethaselvarajm/EXNO-5-DS/assets/119525603/eca58623-3775-451f-a295-f2c1176ec8c2)

# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
