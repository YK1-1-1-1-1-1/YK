# YK
能正确统计导入的纯英文txt文本中的字符数，单词数，句子数。
具体命令行界面如下：
please input your filename:
文件路径、文件名
characters: 
words:
lines:

例：
//200以内能被7整除的数
#include <iostream.h>
int main()
{
 int i;
for(i=1;i<=200;i++)
{if (i%7==0)
{
 cout<<"两百以内能被7整除的数"<<i<<endl;
}
}
return 0;

}
please input your filename:
C:\Users\vcc\Desktop\\1.txt
characters: 63
words:8
lines:8
请按任意键继续. . .

//三个数比较大小
#include<iostream>
using namespace std;
int main()
{
int result,max( int x ,int y, int z);//对max函数做声明
int a,b,c;
cout<<"a="<<endl;
cin>>a;
cout<<"b="<<endl;
cin>>b;
cout<<"c="<<endl;
cin>>c;
result=max(a,b,c);
cout<<"max="<<result<<endl;
return 0;
}
int max(int x,int y, int z)//定义max函数
{
 int m;
 if (x>=y)
 {
   if (x>=z)
	   m=x;
   else 
	   m=z;
 }
 else
 {
   if(y>=z)
	   m=y;
   else
	   m=z;
 }
 return m;
}
please input your filename:
C:\Users\vcc\Desktop\\2.txt
characters: 211
words:63
lines:27
请按任意键继续. . .


#include <iostream>
using namespace std;
int main()
{
  int max(int a,int b,int c);
  int a,b,c;
  cout<<"输入三个数"<<endl;
  cin>>a>>b>>c;
  cout<<"最大的数字是"<<max(a,b,c)<<endl;

}
int max(int a,int b,int c)
{
   if(a>=b)
	   b=a;
   if(c>=b)
	   b=c;
   return b;

}

please input your filename:
C:\Users\vcc\Desktop\\3.txt
characters: 128
words:47
lines:14
请按任意键继续. . .
