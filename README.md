C++ Quiz
==============================

> __*Description:*__ This is a project in my class so go see other repos if you don't understand what is this.

## Trắc nghiệm

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

## Bài tập

<!-- Hàm sau in ra gì / trả về kết quả gì ? -->

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
