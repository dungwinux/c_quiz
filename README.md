C Quiz
==============================

> __*Description:*__ This is a project in my class so go see other repos if you don't understand what is this.

## Cấu trúc thuật toán

### Trắc nghiệm

1. Câu lệnh  `while(1);`  gây ra lỗi gì ?

|**a. Máy tính hỏng**|**b. Infinite Loop**|
|---|---|
|**c. Stack Overflow**|**d. Không có lỗi**|

2. 

```c++
int main(){
    
}
```
## Bài tập

<!-- Hàm sau in ra gì / trả về kết quả gì ? -->

1. Hàm sau in ra gì?

```c++
void f(){
    printf("Hello World");
}
```

2. Bạn A đang lập trình tìm ước nhỏ nhất của n mà bé hơn n, nhưng chương trình không in ra kết quả đúng. Hãy tìm ra lỗi sai

```c++
#include <stdio.h>
int main(){
    int i, n;
    scanf("%d", &n);
    while (i < n && i++);
    printf("%d", i);
}
```

3. Tìm tất cả lỗi sai trong code sau:

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

4. Dự đoán Output:
> Đây là câu khó, để đây cho vui. **ĐỪNG LÀM**

```c++
#include <stdio.h>
int i;f(char*s){for(i=64;*s;putchar(*s^i?32:*s++))i+=i^90?1:puts("")-26;}
int main(){
	f("HELLOWORLD");
}
```

5. T