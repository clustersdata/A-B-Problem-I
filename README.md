# A-B-Problem-I

Problem Description

Calculate A + B.

Input

Each line will contain two integers A and B. Process to end of file. 

Output

For each case, output A + B in one line.

Sample Input

1 1 

Sample Output

2 

代码：

#include<stdio.h>

int main()

{

    int a,b;
	
    while(scanf("%d %d",&a,&b)!=EOF)
	
        printf("%d\n",a+b);
		

}
