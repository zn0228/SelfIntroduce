# 자기소개

* 학번/이름   
1학년 4반 20번/홍아연

* 출신   
 __목포__ 

 * c
```c
int main() {
	
	int i,num,sum=0;
	scanf("%d", &num);
	for (i = 2; i <= num; i=i+2)
	{

		sum = i + sum;

	}
	
	printf("%d", sum);

    int a, b, i,sum=0;
	scanf("%d %d", &a, &b);
	for (i = a; i <= b; i++) {

		if (i % 3 == 0) {
			sum = sum + i;
		}
	}

	printf("%d", sum);

    int num, max=0, i,n;
	scanf("%d", &n);
	for (i = 1; i <= n; i++) {

		scanf("%d ", &num);
		if (num > max)
		{
			max = num;
		}
	}

	printf("%d", max);

	return 0;
	
} 
```
