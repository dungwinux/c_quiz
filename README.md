C++ Quiz 
==============================

## _Created by Nguyen Tuan Dung_

> __*Description:*__ This is a project in my class so go see other repos if you don't understand what is this. [Report](/Báo-cáo-Project-A0-No.4.docx)


## **Trắc nghiệm**

1. Chương trình sau gây ra lỗi gì ?
```c++
int main(){
    for ( ; ; );
}
```

|**a. Compiler Error**|**b. Infinite Loop**|
|---|---|
|**c. Stack Overflow**|**d. Không có lỗi**|

2. Tác dụng của hàm `atoi()` trong thư viện "stdlib.h"?

|**a. Chuyển từ xâu (string) sang số**|**b. Tính tổng các phần tử của mảng**|
|---|---|
|**c. Chuyển từ xâu (char) sang số**|**d. Trả về số phần tử của mảng**|

3. Dùng hàm nào sau đây (trong thư viện ctype.h) để kiểm tra xem một ký tự (char) có phải là chữ cái hay không?

|**a. `isalnum()`**|**b. `isalpha()`**|
|---|---|
|**c. `isdigit()`**|**d. `isprint()`**|

4. Nhập đoạn code sau vào một tệp 'test.cpp', chương trình có chạy hay không?
```c++
main(){main();}
```
|**a. Có**|**b. Không**|
|---|---|

5. Ý nghĩa câu lệnh `s = 1 << 5` là gì:

|**a. Gán độ chênh lệch giữa 1 và 5**|**b. Gán `s = 1` rồi `s = 5`**|
|:---|:---|
|**c. Gán `s = ` 2 mũ 5**|**d. Gán `s =` 1 mũ 5**|

6. Ý nghĩa câu lệnh `freopen("123.inp", "r", stdin);` là gì:

|**a. Mở lại tệp `stdin`**|**Mở tệp "123.inp" để đọc**|
|:---|:---|
|**c. Đọc tệp "123.inp" như là input**|**d. Mở tệp "123.inp" để xem**|

## **Bài tập**

1. Hàm sau in ra gì?

```c++
void f(){
    printf("Hello World");
}
```

2. Bạn A đang lập trình tìm ước nhỏ nhất của n mà bé hơn n, nhưng chương trình không in ra kết quả đúng. Hãy tìm ra lỗi sai.

```c++
#include <stdio.h>
int main(){
    int i, n;
    scanf("%d", &n);
    while (i < n && i++);
    printf("%d", i);
}
```

3. Tìm **tất cả** lỗi sai trong code sau:

```c++
#include <stdio.h>
int main(){
    int n;
    scanf("%d", &n);
    for (int i = 1; i <= n; i++){
        printf("%d", i);
    }
}
```

4. Xóa 1 dòng để chương trình không in ra kết quả với mọi input:

```c++
#include <stdio.h>
int main(){
    int n;
    scanf("%d", &n);
    for (int i = 0; i < n; i++){
        if (i % 2)
            printf("%d\n", i);
    }
}
```

5. Tìm ra **1** lỗi sai:

```c++
#include <iostream>
int main(){
    int i = 20;
    while (i --> 4)
        cout << i << endl; 
}
```

6. Dự đoán output:

```c++
#include <stdio.h>
int main(){
    int c = 5;
    c=++c+c++;
    printf("%d", c);
}
```

7. Dự đoán output:

```c++
#include <stdio.h>
bool isInt(float f){
    return f == (int)f;
}
int main(){
    int f = 3.14;
    printf("%d", isInt(f));
}
```

8. Dự đoán output:

```c++
#include <stdio.h>
int main(){
    long n,d;
    int h,m,s;
    scanf("%ld",&n);
    d=n/86400;
    n%=86400;
    h=n/3600;
    n%=3600;
    m=n/60;
    n%=60;
    s = n;
    printf("%ld:%02d:%02d:%02d",d,h,m,s);
}
```

9. Dự đoán output:

```c++
#include <iostream>
using namespace std;
int main(){
    string s;
    getline (cin, s);
    for (int i = 0; i < 1000; i++){
        cout << s << endl;
    }
```

10. Dự đoán output:

```c++
#include <stdio.h>
int main(){
    int a, b, c, s;
    float p;
    scanf("%d %d %d", &a, &b, &c);
	p = (a + b + c) / 2;
    s = sqrt(p * (p - a) * (p - b) * (p - c));
    printf("%d", s);
}
```

11. Dự đoán giá trị trả về của câu lệnh `fun(1230);`:

```c++
#include<math.h>
//...
int isSqr(int x){
    return (sqrt(x) = (int) sqrt(x));
}
int fun(int x){
    int n;
    x *= x;
    return (isSqr(x + 4) || isSqr(x - 4));
}
//...
```

12. Dự đoán output:

```c++
#include<math.h>
int main(){
    int n, s = 1;
    scanf("%d", &n);
    for (int i = 0; i ++< n; s *= i);
    printf("%d", s - n);
    return 0;
}
```

13. Dự đoán output:

```c++
#include <stdio.h>
int main(){
	long a, b, n, k, mod;
	scanf("%ld %ld %ld", &n, &a, &b);
	k = a / b;
	mod = a % b;
	for (long i = 0; i < n; i++){
		k = (mod * 10);
		mod = k % b;
		k /= b;
	}
	printf("%ld", k);
}
```

14. Dự đoán output:

```c++
#include <stdio.h>
#include <string.h>
//...
int main(){
    char z[200];
    // scanf("%s",&z);
    z = "Hello";
    int len = strlen(z);
    for (int i = len; i --> 0; ){
        printf("%c", z[i]);
    }
}
//...
```

15. Dự đoán output:

```c++
#include <stdio.h>
#define m(a, b) (a > b ? a : b)
//...
int main(){
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d", m(a, b));
}
//...
```

16. Dự đoán output:

```c++
#include <iostream>
using namespace std;
//...
int plus(int a, int b){
    return (a+b); 
}
int time(int a, int b){
    return (a*b);
}
int op(int x, int y, int (*p)(int,int))
{
    return (*p)(x,y);
}
int main(){
    int m, n;
    m = op(7, 15, plus);
    n = op(10, m, time);
    cout << n;
    return 0;
}
//...
```

17. Dự đoán output:

```c++
#include <stdio.h>
//...
int main(){
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d", a & b);
}
//...
```

18. Dự đoán output:

```c++
#include <stdio.h>
//...
int main(){
    bool a, b;
    scanf("%d %d", &a, &b);
    printf(a ^ b ? "true" : "false");
}
//...
```

19. Dự đoán output:

```c++
#include <stdio.h>
//...
int main(){
    bool a, b;
    scanf("%d %d", &a, &b);
    printf(a ^ b ? "true" : "false");
}
//...
```

20. Dự đoán output:

```c++
#include <iostream>
//...
int main(int argc, char* argv[]){
	for (int i = 0; i < argc; i++){
		std::cout << argv[i] << std::endl;
	}
}
//...
```

21. Dự đoán output:

```c++
#include <stdio.h>
int main(){
    long n;
    long long s = 0, k;
    scanf("%ld", &n);
    for (long i = 0; i < n; i++){
    	scanf("%lli", &k);
    	s+=k;
    }
    printf("%lli", s/n);
}
```

22. Dự đoán output:

```c++
#include <stdio.h>
int main(){
	long n, m, k, s = 0;
	scanf("%ld %ld", &n, &m);
	for (long i = 0; i < n; i++){
		for (long j = 0; j < m; j++){
			scanf("%ld", &k);
			if ((i+j) % 2 == 0) s += k;
		}
	}
	printf("%ld", s);
}
```

23. Dự đoán output:

```c++
#include <stdio.h>
long a[1000];
int main(){
	long n;
	scanf("%ld", &n);
	for (long i = 0; i < n; i++){
        scanf("%ld", &a[i]);
    }
	for (long i = 0; i < n; i++){
        for (long j = i + 1; j < n; j++){
            if (a[i] > a[j]){
                long tmp = a[i];
                a[i] = a[j];
                a[j] = tmp;
            }
        }
    }
	for (long i = 0; i < n; i++){
        printf("%ld ", a[i]);
    }
}
```

24. Dự đoán output:

```c++
#include <stdio.h>
int main(){
	long n, a[100000];
	scanf("%ld", &n);
	bool boo = true;
	for (long i = 0; i < n; i++){
		scanf("%ld", &a[i]);
	}
	for (long i = 0; i < (n / 2) && boo; i++){
		boo = (a[i] == a[n-i-1]);
	}
	printf(boo ? "YES" : "NO");
}
```
