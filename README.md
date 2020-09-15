### Hi there 👋

<!--
**wang123-lxq/wang123-lxq** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on 计算机
- 🌱 I’m currently learning 软件工程与文档写作
- 👯 I’m looking to collaborate 完成一项大工程
- 🤔 I’m looking for help with 做一次活动
- 💬 Ask me about 大学的问题
- 📫 How to reach me: 2845519538
- 😄 Pronouns: 
- ⚡ Fun fact: 
-->
 
  
  
   
    
     
     
         
1 
/* 
2*冒泡排序 
3 
*/ 
4 
public class BubbleSort{ 
5 
public static void main(String[]args）{ 
int[] arr={6,3,8,2,9,1}; 
System.out.println("排序前数组为:"); 
7 
8 
for(int num:arr){ 
System.out.print(num+" "); 
10 
for(int i-;i<arr.length-1;i++){//外层循环控制排序趟数 
11 
for(intj=;j<arr.length-1-i;j++){//内层循环控制每一趟排序多少次 
12 
if(arr[j]>arr[j+1]{ 
13 
int temp=arr[j; 
14 
arr[j]=arr[j+1]; 
15 
arr[j+1]=temp; 
16 
17 
} 
18 
19 
} 
20 
System.out.println(; 
System.out.println("排序后的数组为:"); 
21 
22 
for(int num:arr){ 
System.out.print(num+" "); 
23 
24 
25 
} 
26}
