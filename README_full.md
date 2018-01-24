

Dự án A0 No.4

*Xây dựng bộ đề trắc nghiệm*

*Thành viên*

Nguyễn Doãn Đại – Trưởng nhóm

Nguyễn Kim Tuyến

Nguyễn Hoàng Long

Trần Duy Phát

Võ Minh Đức

Đặng Quốc Trung

Huỳnh Quốc Việt

Nguyễn Thành Vinh

Nguyễn Hữu Khải**  
**

**Bài 1**: Dùng hàm nào để chuyển đổi 1 chuỗi sang giá trị double:

1.  atof

2.  atoi

3.  itot

4.  atit

Chọn A

**Bài 2**: Dùng hàm nào để chuyển đổi 1 chuỗi sang giá trị int:

1.  atof

2.  atoi

3.  itot

4.  atit

Chọn B

**Bài 3**: Dùng hàm nào để chuyển đổi số nguyên value sang chuỗi string
theo cơ số radix:

1.  atof

2.  atoi

3.  itot

4.  itoa

Chọn C

**Bài 4**: Hàm nào để đổi chữ in hoa sang chữ in thường:

1.  toupper

2.  tower

3.  tolower

4.  không có đáp án nào đúng

Chọn C

**Bài 5**: Hàm nào để đổi chữ thường sang chữ hoa:

1.  toupper

2.  tower

3.  strupr

4.  strlwr

Chọn A

**Bài 6**: Hàm nào để them chuỗi src vào sau chuỗi dest:

1.  streat

2.  stress

3.  street

4.  không có đáp án nào đúng

Chọn A

**Bài 7**: Hàm nào để chép chuỗi src vào chuỗi dest:

1.  streat

2.  stress

3.  strepy

4.  steper

Chọn C

**Bài 8**: Sử dụng hàm atoi cần khai báo thư viện nào:

1.  stdio.h

2.  conio.h

3.  stdlib.h

4.  ctype.h

Chọn C

**Bài 9**: Sử dụng hàm toupper cần khai báo thư viện nào:

1.  stdio.h

2.  conio.h

3.  stdlib.h

4.  ctype.h

**Bài 10**: Trong thời gian học hỏi và trau dồi kinh nghiệm code bài
trên codefun.vn, bạn Doãn đã có thời gian miệt mài code một đoạn code và
bị TLE sấp mặt nhưng không biết tối ưu nó như thế nào. Bất chợt bạn Shuu
đến giúp như một vị thiên thần giúp bạn Doãn có thể AC được bài code đó
một cách dễ dàng. Hãy tìm xem bạn Shuu đã giúp Doãn tối ưu code như thế
nào nhé:

\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

int main()

{

> int n;  
> scanf(“%d”,&n);
>
> for(int I =1;i&lt;= pow(n,n); i++)
>
> {
>
> printf(“\#”);
>
> }

}

Làm như thế nào để tối ưu đoạn code trên:

1.  bổ sung them hàm trả giá trị về 0 (return 0;)

2.  xóa bỏ thư viện math.h

3.  them lệnh break; sau khi vòng lặp for kết thúc

4.  gán them giá trị cho pow(n;n) trước khi bắt đầu vòng lặp for

Chọn D

**Bài 11**: Dùng hàm pow cần khai báo thư viện nào:

1.  math.h

2.  stdlib.h

3.  ctype.h

4.  string.h

Chọn A

**Bài 12**: Dùng hàm sqrt cần khai báo thư viện nào:

1.  math.h

2.  stdlib.h

3.  ctype.h

4.  string.h

Chọn A

**Bài 13**: Dùng hàm nào để cho ra kết quả là 1 giá trị ngẫu nhiên trong
khoảng kiểu dữ liệu đã khai báo(int, double,…):

1.  abs

2.  rand

3.  labs

4.  strlen

Chọn B

**Bài 14**: Mọi thành công đều đến từ thất bại, cũng như Dever giỏi cũng
code sai nhiều thì mới AC. Bạn Huỳnh khi ấy đã code một đoạn code như
sau:

\#include&lt;studio.h&gt;

\#include&lt;math.h&gt;

int main()

{

> int n;  
> scanf(“%d”,&n);
>
> int a pow(n,n);
>
> for(int I =1;i&lt;=a; i++)
>
> {
>
> printf(“\#”);
>
> }

}

Đoạn code trên đúng hay sai:

1.  Đúng. Chỉ cần tối ưu hàm pow để chương trình chạy nhanh hơn

2.  Sai. Cần xóa bỏ thư viện math.h

3.  Sai. Cần debug dòng đầu

4.  Sai. Cần debug dòng cuối

Chọn C

**Bài 15**: Cho đoạn code sau:

\#include&lt;stdio.h&gt;

int main (){

> int a\[10\];
>
> int n;
>
> scanf("%d",&a\[n\]);
>
> printf("%d",a\[11\]);

}

Đoạn code trên khi input nhập vào 1 số nguyên dương trong khoảng int,
trả ra ouput có kết quả:

1.  2

2.  0

3.  1

4.  8

Chọn B. Vì đoạn code trên kết quả in ra màn hình là thuộc ô mảng thứ 11
trong khi đó chương trình chỉ khai báo mảng 10 ô.

**Bài 16**: Bạn Quán có niềm đam mê với hình học nhưng không ngừng code
đều tay. Một hôm Quán muốn thử vẽ hình bằng code:

\#include&lt;iostream&gt;

using namespace std;

main (){

> int n,m,i,j;
>
> cin &gt;&gt; n &gt;&gt; m;
>
> for (int i = 1; i &lt;= n; i++)
>
> {
>
> for(int j = 1; j &lt;= m; j++)
>
> }
>
> cout &lt;&lt; "\# ";
>
> }
>
> cout &lt;&lt; endl;
>
> }

}

Hãy cho biết output khi nhập n=2;m=3

1.  \#\#\#

    \#\#\#

2.  \#\#

    \#\#

    \#\#

3.  \#\#\#\#\#\#

4.  Bạn Quán xàm, code sai.

Chọn A.

**Bài 17**: Em trai của KiTu đang chán nản với việc giải toán vì vậy mà
KiTu đã văt óc nghĩ ra một chương trình hỗ trợ cho em trong việc giải
toán như sau :

\#include &lt;iostream&gt;

\#include &lt;math.h&gt;

using namespace std;

int main(){

> float a,b,c,d,x1,x2;
>
> cin&gt;&gt;a&gt;&gt;b&gt;&gt;c;
>
> if(!a){
>
> if(!b)
>
> cout &lt;&lt; "NO SOLUTION" &lt;&lt; "\\n";
>
> else
>
> {
>
> d=-c/b;
>
> cout &lt;&lt; " x = " &lt;&lt; d &lt;&lt; endl;
>
> }
>
> }
>
> else
>
> {
>
> d=b\*b-4\*a\*c;
>
> if(d&gt;0)
>
> x1=(-b+sqst(d))/(2\*a); x2=(-b-sqst(d))/(2\*a);
>
> cout &lt;&lt; "x1 = " &lt;&lt; x1 &lt;&lt; endl;
>
> cout &lt;&lt; "x2 = " &lt;&lt; x2 &lt;&lt; endl;
>
> }
>
> return 0;

}

Tuy vậy chương trình còn mắc một lỗi nhỏ, hãy giúp KiTu phát hiệu lỗi ấy
và sửa :

1.  Debug dòng 10

2.  Debug dòng 5

3.  Debug dòng 20

4.  Debug dòng 9

Chọn C. Lỗi chính tả tên hàm khai căn sqst -&gt; sqrt

**Bài 18**: Đâu là dấu mô tả định dạng chuỗi:

1.  %s

2.  %S

3.  %a

4.  %A

Chọn A

**Bài 19**: Đâu là dấu mô tả định dạng số nguyên thật phân có dấu:

1.  %d

2.  %D

3.  %a

4.  %A

Chọn A

**Bài 20**: Đâu là dấu mô tả định dạng số nguyên hex không dấu:

1.  %d

2.  %D

3.  %u

4.  %x

Chọn C

**Bài 21**: Đâu là dấu mô tả số nguyên bát phân không dấu:

1.  %d

2.  %o

3.  %u

4.  %x

Chọn B

**Bài 22**: Để đi kèm với số nguyên có kiểu khai báo long long ta cần
dung dấu mô tả:

1.  %d

2.  %ld

3.  %ux

4.  %df

Chọn B

**Bài 23**: Để nhảy xuống dòng kế tiếp canh cột đầu tiên dung kí tự :

1.  \\n

2.  \\nl

3.  \\olc

4.  \\newlin

Chọn A

**Bài 24**: Trong lúc học hình thầy Hùng, Quán càng ngày càng cảm thấy
quá chán nản với việc nhớ đi nhớ lại các công thức với hình tròn vì vậy
mà Quán đã viết một đoạn code để ghi nhớ cách tính chu vi và diện tích
hình tròn hết sức đơn giản:

\#include&lt;iostream&gt;

\#define PI 3.14

float area();

float p();

float r;

int main(){

cin &gt;&gt; r;

cout &lt;&lt; p() &lt;&lt;endl &lt;&lt; area();

}

float p(){

return(2\*PI\*r);

}

float area(){

return (4\*PI\*r\*r);

}

Nhưng chương trình không chạy vì lý do nào đó, Futymy đến và giúp Quán:

1.  Futymy đã chính hàm tính diện tích thêm hàm pow để tính
    r<sup>2</sup>

2.  Futymy đã chính sửa hàm bằng cách đổi tên hàm area sang arofcicle

3.  Futymy thêm thư viện \#include&lt;cmath&gt;

4.  Futymy thêm using namespace std;

Chọn D. Vì nếu muốn chạy cin và cout phải dùng tên thư viện chuẩn std

**Bài 25**:Đức Combi đã mạnh mồm tuyên bố sẽ bỏ tuyển toán theo tuyển
tin sau khi đứng top 1 CHD1 năm 2017, trong thời gian đang sung sướng
chiến thắng Combi đã code 1 bài tính tổ hợp chập k của n như sau:

\#include&lt;iostream&gt;

using namespace std;

long long factorial(int a);

int main(){

long long a;

cin &gt;&gt; a;

cout &lt;&lt; factorial(int a);

}

long long factorial(int a){

for(int i=1;i&lt;=a;i++){

a=i\*a;

}

Nhưng vì quá hấp tấp theo bản tính Combi, Cu Dứa nhảy vào giúp vì nghĩ
Combi đã sai:

1.  Combi đúng và Cu Dứa sai

2.  Combi đã sai hòan toàn về cả thuật toán

3.  Combi đã sai và Cu Dứa debug là đúng

4.  Cu Dứa thêm dòng return 0; ở mỗi hàm để code chạy

Chọn C. Vì Combi đã quên mất đ là n&gt;=k

**Bài 26**: Dùng hàm nào để tính giá trị tuyệt đối :

1.  abs

2.  atoi

3.  itot

4.  atit

Chọn A

**Bài 27**: Khi dùng hàm abs thì cần khai báo thư viện nào:

1.  stdlib.h

2.  CMATH

3.  cmath

4.  Cả A & C

Chọn D

**Bài 28**: Vịt yêu lịch sử và muốn viết chương trình tính số năm nhuận
để đỡ phải nhớ nhiều vì Vịt không thích nhớ. Đoạn code như sau:

\#include&lt;iostream&gt;

using namespace std;

int main(){

long long a;

cin &gt;&gt; a;

if(a mod 4 == 0){

cout &lt;&lt; "leap year";

}

else cout &lt;&lt; "not leap year";

}

Nhưng vì trình độ djntcout trí tuệ Vịt đã gợi nhớ 1 ngôn ngữ lập trình
khác nên chương trình đã chạy sai, debug giúp Vịt nhé:

1.  Debug dòng 2

2.  Debug dòng 4

3.  Debug dòng 5

4.  Debug dòng 6

Chọn D. Vì chia lấy số dư dùng toán tử % chứ không phải mod

**Bài 29**: Kí hiệu đặc biệt nào để canh cột tab:

1.  \\t

2.  \\l

3.  \\tabs

4.  \\columntab

Chọn A.

**Bài 30**

Giá trị cuối cùng của x khi mã được chạy?  
int x;  
for(x = 0; x &lt; 28; x++) {  
}  
A. 28  
B. 27  
C. 26  
D. 25  
  
**Bài 31**

Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

int main(){

long int n;

scanf("%ld",&n);

while(n%2==0)

{

printf("%d",2);

n=n/2;

}

for(int i=3;i&lt;=sqrt(n);i=i+2)

{

while(n%i==0)

{

printf("%d",i);

n=n/i;

}

}

if(n&gt;2)printf("%ld",n);

return 0;

}  
Với input=60 thì output là bao nhiêu?  
A.2 3 6 5  
B.2 2 3 5  
C.2 3 5 2  
D.4 3 5 2  
  
  
**Bài 32  
**Cho đoạn code sau:

\#include&lt;stdio.h&gt;

int main(){

long long k,n,a=1,b=1,d=1,e,i,j,t;

scanf("%lld %lld",&k,&n);

e=n-k;

for(i=1;i&lt;=k;i++){

a\*=i;

}

for(j=1;j&lt;=n;j++)

{b\*=j;}

for(t=1;t&lt;=e;t++)

{d\*=t;}

printf("%lld ", b/(a\*d));

}  
Với k=3,n=6 thì output là bao nhiêu?  
A.24  
B.18  
C.20  
D.30  
  
**Bài 33  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

int main(){

float a,b,c,d(a!=0);

scanf("%f%f%f",&a,&b,&c);

d=b\*b-4\*a\*c;

if (d&lt;0)

printf("No solution");

else if (d==0)

printf("%.2f",-b/(2\*a));

else

printf("%.2f %.2f",(-b-sqrt(d))/(2\*a),(-b+sqrt(d))/(2\*a));

}  
Với a,b,c lần lượt là 1,-5,6 thì output là gì?  
A.No solution  
B.1,00 6,00

C.2,00 3,00  
D.-4,25 -1,75

**Bài 34  
**Cho đoạn code sau:**  
**\#include&lt;stdio.h&gt;

\#include&lt;string.h&gt;

\#include&lt;iostream&gt;

using namespace std;

int main(){

int i, n;

char s\[225\];

gets(s);

n=strlen(s);

for(i=0;i&lt;n;i++){

if(s\[i\]=='a')

s\[i\]='x';

else if(s\[i\]=='b')

s\[i\]='y';

else if(s\[i\]=='c')

s\[i\]='z';

else

s\[i\]=s\[i\]-3;

}

printf("%s",s);

}  
Cho output là bill is watching thì input là gì ?  
A.aecl uh uyhkolou  
B.dfyh ju lihgafqr  
C.eloo lv zdwfklqj  
D.eloo lk zotwhjut  
  
**Bài 35  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

int main(){

int a,b;

scanf("%f%f",&a,&b);

printf("%.2lf\\n",(a\*a\*a)+(b\*b\*b))

}  
Có bao nhiêu lỗi sai trong đoạn code trên ?  
A.1  
B.2  
C.3  
D.4  
  
**Bài 36  
** Cho đoạn code sau :  
\#include &lt;stdio.h&gt;

int main(){

int n;

scanf("%d",&n);

if(n%2==1)printf("%d",n\*(n-1)\*(n-2));

else {

if(n%3==0)printf("%d",(n-1)\*(n-2)\*(n-3));

else printf("%d",n\*(n-1)\*(n-3));

}

}  
Với output =2184 thì input bằng bao nhiêu?

A.14  
B.15  
C.16  
D.CE  
E.Cả 4 đáp án đều sai  
  
**Bài 37  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main(){

long long n,k;

scanf("%lld %lld",&n,&k);

if(n%2==0){

if(k&lt;=n/2)

printf("%lld",2\*k-1);

else printf("%lld",2\*k-n);

}

else{

if(k&lt;=(n-1)/2)

printf("%lld",2\*k-1);

else printf("%lld",2\*k-n-1);

}

Với output là 3 thì input có hai số n và k lần lượt có thể là bao
nhiêu?  
A. n=3 ,k=6  
B. n=8,k=25  
C. n=9,k=2  
D. n=2 ,k=9  
F.CE  
  
**Bài 38  
**Cho đoạn code sau:  
\#include&lt;iostream&gt;

using namespace std;

int main() {

float a1,b1,a2,b2;

cin&gt;&gt;a1&gt;&gt;b1&gt;&gt;a2&gt;&gt;b2;

if(a1==a2) {

if(b1==b2)

cout&lt;&lt;"0.000000 0.000000";

return 0;

}

float x=(b2-b1)/(a1-a2);

cout&lt;&lt;fixed&lt;&lt;x&lt;&lt;" "&lt;&lt;a1\*x+b1;

return 0;

}

Với input lần lượt là 4 số 3 6 7 8 thì output là gì ?  
A. 2 2  
B.3,5 2,5  
C.-0,5 4,5  
D.1 8

**Bài 39  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

int main(){

float a;

scanf("%f",&a);

printf("%.2lf",a\*sqrt(2));  
}  
Với input là 6,5 thì output là gì ?  
A.3,25  
B,9,19  
C.8,49  
D.CE  
  
**Bài 40  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main()

{

int a,b,i;

scanf("%d%d",&a,&b);

for(i=0;i&lt;69;i++)

{

a=(a\*10)%b;

}

a=(a\*10)/b;

printf("%d",a);

}  
Với input lần lượt là 2 số 12 và 7 thì output là gì ?  
A.1  
B.2  
C.3  
D.4  
  
**Bài 41  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

int main(){

float a;

scanf("%f",&a);

printf("%.2lf",a\*4,7);

}  
Với input là 4,5 thì output là bao nhiêu?  
A.16  
B.17  
C.19  
D.20**  
  
Bài 42  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main(){

float kq=0;

int n,i;

scanf("%d",&n);

for(i=1;i&lt;=n;i++)

kq=kq+(float)1/i;

printf("%.3f\\n",kq);

}  
Với input là 4 thì output là gì?

A.2  
B.2.083  
C.1,5  
D.8  
  
**Bài 43  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

int main(){

long int n;

scanf("%ld",&n);

if(n%2==0)

printf ("%ld",n/2);

else printf ("%ld",(n+1)/2\*(-1));

}  
Với input là 1649 thì output là gì?  
A.825  
B.-825  
C.824  
D.-824  
  
**Bài 44  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int a\[6\];

int main(){

int i,j,n,k;

n=6;

for (i = 0; i &lt; n; i++) {

scanf("%d", &a\[i\]);

}

for (i = 0; i &lt; n-1;i++){

for (j = i+1; j &lt; n;j++){

if (a\[i\]&gt;a\[j\]){

k = a\[i\];

a\[i\] = a\[j\];

a\[j\] = k;

}

}

}

if(a\[0\]==a\[1\]&&a\[2\]==a\[3\]&&a\[3\]==a\[4\]&&a\[4\]==a\[5\])

printf("Elephant");

else if(a\[4\]==a\[5\]&&a\[0\]==a\[1\]&&a\[1\]==a\[2\]&&a\[2\]==a\[3\])

printf("Elephant");

else if(a\[1\]==a\[2\]&&a\[2\]==a\[3\]&&a\[3\]==a\[4\]&&a\[0\]!=a\[5\])

printf("Bear");

else if (a\[0\]==a\[1\]&&a\[1\]==a\[2\]&&a\[2\]==a\[3\]&&a\[4\]!=a\[5\])

printf("Bear");

else if (a\[2\]==a\[3\]&&a\[3\]==a\[4\]&&a\[4\]==a\[5\]&&a\[0\]!=a\[1\])

printf("Bear");

else printf ("Alien");

}  
Với input là 4 2 3 6 4 1 thì output là gì?  
A.Elephant  
B.Bear  
C.Alien  
D.CE  
  
**Bài 45  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

int main(){

long long a, x, y, xm, ym, r;

scanf("%lld%lld%lld%lld%lld",&x,&y,&xm,&ym,&r);

a=sqrt((x-xm)\*(x-xm)+(y-ym)\*(y-ym));

if(a&gt;r) printf("NO");

else printf("YES");

}  
Với input là các số 4 0 3 2 8 thì output là gì?  
A.YES  
B.NO  
C.CE  
D.Không xác định được  
  
**Bài 46**  
Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

\#include &lt;math.h&gt;

int main(){

int x1,x2,x3,y1,y2,y3;

long long d3,d1,d2,tmp;

scanf("%d %d %d %d %d %d",&x1,&y1,&x2,&y2,&x3,&y3);

d1=(x1-x2)\*(x1-x2)+(y1-y2)\*(y1-y2);

d2=(x2-x3)\*(x2-x3)+(y2-y3)\*(y2-y3);

d3=(x1-x3)\*(x1-x3)+(y1-y3)\*(y1-y3);

if (d1&gt;d2) {tmp=d1;d1=d2;d2=tmp;};

if (d1&gt;d3) {tmp=d1;d1=d3;d3=tmp;};

if (d2&gt;d3) {tmp=d2;d2=d3;d3=tmp;};

d3-=d1;d3-=d2;

if (d3==(float)2\*sqrt(d1\*d2)) printf("1");

else printf("0");

}  
Với input lần lượt là các số 1 7 4 6 9 8 thì out put sẽ in gì?  
A.1  
B.0  
C.CE  
D.Code không chạy được  
  
**Bài 47  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

int main(){

long long a,n,mod,kq,i;

scanf("%lld %lld %lld",&a,&n,&mod);

kq=1;

for(i=1;i&lt;=n;i++)

{kq\*=a;kq%=mod;};

printf("%lld", kq);

}  
Với input lần lượt là các số 4 17 1285 thì output là gì?  
A.4  
B.21  
C.1302  
D.1306  
  
**Bài 48  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main(){

int a,b,i;

scanf("%d%d",&a,&b);

…….

}

a=(a\*10)/b;

printf("%d",a);

}  
Có một bạn muốn viết code để tìm chữ số thứ 70 của một phép chia nhưng
không chưa viết xong vì không nghĩ ra dòng”……” cần viết gì.Hãy điền giúp
bạn ấy để hoàn thành chính xác bài code trên?  
A. for(i=0;i&lt;70;i++) a=(a\*10)%b;

B. for(i=0;i&lt;70;i++) a=(a%10)\*b;  
C. for(i=0;i&lt;69;i++) a=(a\*10)%b;  
D. for(i=0;i&lt;69;i++) a=(a%10)\*b;  
  
**Bài 49  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

int main(){

long long a\[100000\], i, n;

double s=0;

scanf("%lld ", &n);

for(i=0;i&lt;n;i++){

scanf("%lld", &a\[i\]);

s=s+a\[i\];

}

printf("%.2lf", s/n);

}  
Với dòng thứ nhất là 5 dòng thứ hai là các số 17 18 19 20 21 thì output
in ra gì ?  
A.95  
B.19  
C.21  
D.17  
  
**Bài 50  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

\#include &lt;string.h&gt;

int main(){

char dv\[100000\],rac=0;

long a=0,b,st,cc=1;

for(a=0;;a++){

scanf("%c",&dv\[a\]);

if(dv\[a\]==46)break;

}

scanf("%ld",&st);

for(b=0;;b++){

if(dv\[b\]==32)cc++;

if(cc==st&&dv\[b\]!=32&&dv\[b\]!=46)printf("%c",dv\[b\]);

if(dv\[b\]==46)break;

}

}  
Với input gồm 2 dòng ,dong 1 là “Nice to meet you.”,dòng thứ 2 là “7”thì
output là gì ?

A.Nice  
B.Nice to meet you  
C.CE  
D.Không in gì cả  
  
**Bài 51  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main(){

int a, b, c, i, n;

scanf("%d",&n);

a = b = 1;

printf("%d %d ",a,b);

for(i = 1; i &lt;= n-2; i++) {

c = a + b;

printf("%d ", c);

a = b;

b = c;

}

}  
Với input là 4 thì in ra output là gì ?  
A.1234  
B.1123  
C.1324  
D.CE  
  
**Bài 52  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main(){

long n,a,b,c=0,d,e;

scanf("%ld",&n)

for(a=1;a&lt;=n;a++){

scanf("%ld",&b);

if(b&lt;0)

break;

c+=b;

}

printf("%ld",c);

}  
Có bao nhiêu lỗi sai trong bài code trên?  
A.1  
B.2  
C.3  
D.4  
  
**Bài 53  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

int main(){

int a;

scanf("%d",&a);

if(a%4==0 && a%100!=0||a%400==0)

printf("1");

else

printf("0");

}  
Với input là 1345698 thì in ra output là gì?  
A.1  
B.0  
C.CE  
D.Không in ra output  
  
**Bài 54  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

int main(){

long long n,k,i=0,m,s=1;

scanf("%lld",&n);

for(k=1;k&lt;=n;k++){

s\*=k;

}

while(s&gt;0){

m=s%10;

i+=m;

s=s/10;

}

printf("%lld",i);

}  
Với input là 6 thì in ra output là gì?  
A.3  
B.9  
C.12  
D.Một đáp án khác  
E.CE  
  
**Bài 55  
**Định nghĩa của thuật toán greedy là gì?  
A. là một thuật toán giải quyết một bài toán theo kiểu metaheuristic để
tìm kiếm lựa chọn tối ưu địa phương ở mỗi bước đi với hy vọng tìm được
tối ưu toàn cục.  
B.Là thuật toán in ra dãy con tăng dài nhất  
C. xây dựng dần các thành phần của cấu hình bằng cách thử tất cả các khả
năng.  
D.Một đáp án khác  
  
**Bài 56  
**Thuật toán lis là gì?  
A. là một thuật toán giải quyết một bài toán theo kiểu metaheuristic để
tìm kiếm lựa chọn tối ưu địa phương ở mỗi bước đi với hy vọng tìm được
tối ưu toàn cục.

B.Là thuật toán in ra dãy con tăng dài nhất

C. xây dựng dần các thành phần của cấu hình bằng cách thử tất cả các khả
năng.

D.Một đáp án khác  
Đáp án A  
  
**Bài 57  
**Con trỏ dùng để làm gi?  
A.Truy cập các phần tử có cùng dữ liệu  
B.Truy cập biến thong qua địa chỉ biến và chương trình tham khảo biến
gián tiếp qua địa chỉ này  
C.Truy cập biểu thức ,hàm,cấu trúc điều khiển  
D.Một đáp án khác  
  
**Bài 58  
**Cho đoạn code sau:  
\#include&lt;stdio.h&gt;

\#include&lt;cmath&gt;

\#define \_USE\_MATH\_DEFINES M\_PI

int main(){

int a\[100000\],n,i;

float d=0;

scanf("%d",&n);

for(i=1;i&lt;=n;i++){

scanf("%d",&a\[i\]);

if(a\[i\]%2==0)

d=d-a\[i\]\*a\[i\]\*M\_PI;

else

d=d+a\[i\]\*a\[i\]\*M\_PI;

}

printf("%f",d);

}  
Cho input gồm 2 dòng ,dòng thứ 1 là số 3 và dòng thứ 2 có 3 số 1 2 3 thì
out put là gì?  
A.6  
B.12  
C.18,85  
D.CE  
E.Một đáp án khác  
F.Không in ra output  
  
**Bài 59  
**Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main()

{

long n

long fib(long);

scanf("%ld",&n);

print("%ld",fib(n))

}

long fib(long n)

{

if(n==1||n==2)

return 1;

else return fib(n-1)+fib(n-2);

}

Có bao nhiêu lỗi sai trong đoạn code trên?  
A.2  
B.3  
C.4  
D.5  
E.Nhiều hon 5

**Bài 60:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{

int n;

float x;

scanf ("%d", &n);

x = n/7;

printf ("%.2f", x);

}

Với input n = 12 thì output là gì?

| 1.  1 | 1.  1.00 | 1.  1.71 | 1.  Không chạy được |
|-------|----------|----------|---------------------|

Đáp án: B.

**Bài 61:** Trong ngôn ngữ lập trình C, muốn dùng hàm sqrt () phải khai
báo hàm gì?

| 1.  conio.h | 1.  string.h | 1.  math.h | 1.  Cả 3 đều sai |
|-------------|--------------|------------|------------------|

Đáp án: C.

**Bài 62:** Một bạn viết chương trình in ra số kí tự của xâu và kí tự
đầu từ 1 xâu liền nhau được nhập vào bàn phím như sau:

\#include &lt;stdio.h&gt;

int main ()

{

char a\[100000\];

scanf (“%s”, a);

printf (“%d %c”, strlen (a), a\[1\]);

}

Hỏi bạn ấy mắc bao nhiêu lỗi?

| 1.  0 | 1.  1 | 1.  2 | 1.  3 |
|-------|-------|-------|-------|

Đáp án: C.

**Bài 63:** Toán tử nào sau đây không phải là toán tử gán?

| 1.  == | 1.  += | 1.  = | 1.  a và b |
|--------|--------|-------|------------|

Đáp án: A.

**Bài 64:** Khi dùng hàm scanf (), muốn đọc 1 xâu ký tự không chứa dấu
cách thì dùng mã quy cách gì?

| 1.  %c | 1.  %d | 1.  %f | 1.  %s |
|--------|--------|--------|--------|

Đáp án: D.

**Bài 65:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{  
char a\[100000\];

scanf (“%s”, a);

printf (“%s”, a);

}

Với input a = ‘Lap trinh’ thì output là gì?

| 1.  Lap trinh | 1.  Lap | 1.  trinh | 1.  Không in được |
|---------------|---------|-----------|-------------------|

Đáp án: B.

**Bài 66:** Phép toán nào sau đây làm thay đổi giá trị bên trái của biểu
thức?

| 1.  == | 1.  = | 1.  % | 1.  &lt; |
|--------|-------|-------|----------|

Đáp án: B.

**Bài 67:** Hàm tính tích các số lẻ từ 1 đến n nào sau đây là đúng?

1.  mul (int n, long s)

{

for (int i = 1; i&lt;=n; i++) s = s\*i;

return s;

}

1.  mul (int n, long s)

{

s=1;

for (int i = 1; i&lt;=n; i++) s = s\*i;

return s;

}

1.  mul (int n, long s)

{

for (int i = 1; i&lt;=n; i++)

if (i%2 == 1) s = s\*i;

return s;

}

1.  mul (int n, long s)

{

s=1;

for (int i = 1; i&lt;=n; i++)

if (i%2 == 1) s = s\*i;

return s;

}

Đáp án: D.

**Bài 68:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{  
int a, b, c, min, max;

scanf (“%d %d %d”, &a, &b, &c);

min = a;

if (min &gt; b) min = b;

if (min &gt; c) min = c;

max = a;

if (max &lt; b) max = b;

if (max &lt; c) max = c;

printf (“%d\\n”, min);

printf (“%d”, max);

}

Với input a = 12, b = 16, c = 7 thì output là gì?

| 1.  7 
        
 16     | 1.  7 
                
         > 12   | 1.  12 
                         
                 16      | 1.  16 
                                  
                          7       |
|-------|-------|--------|--------|

Đáp án: A.

**Bài 69:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

\#include &lt;math.h&gt;

int main ()

{

int a, b;

scanf (“%d %d”, a, b);

if (a&lt;0 and b&lt;0) return 0;

else printf (“%d”, abs(a+b));

}

Với input a = –4 và b = –6 thì output là gì?

| 1.  Không in ra | 1.  Không chạy được | 1.  − 10 | 1.  10 |
|-----------------|---------------------|----------|--------|

Đáp án: B.

**Bài 70:** Trong ngôn ngữ lập trình C, kiểu dữ liệu float có kích thước
bao nhiêu byte(s)?

| 1.  1 | 1.  2 | 1.  4 | 1.  8 |
|-------|-------|-------|-------|

Đáp án: C.

**Bài 71:** Trong các tên biến dưới đây:

| 1.  int 
          
 2.  is   | 1.  Char 
                     
           2.  sum   | 1.  f(x) 
                                
                      2.  ai    |
|---------|----------|----------|

Hỏi có những tên biến nào hợp lệ?

| 1.  1, 2, 4 | 1.  2, 4, 6 | 1.  2, 3, 4, 6 | 1.  1, 3, 4, 5 |
|-------------|-------------|----------------|----------------|

Đáp án: C.

**Bài 72:** Hãy cho biết kết quả in ra màn hình của chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{

int a, b;

for (a=2; a&lt;5; a++)

for (b=5; b&lt;8; b++) printf (“%d ”, a+b);

}

| 1.  7 9 11 13            
                           
 2.  7 8 9 8 9 10 9 10 11  | 1.  7 8 9 10 11 12 13                         
                                                                           
                            2.  7 8 9 10 8 9 10 11 9 10 11 12 10 11 12 13  |
|--------------------------|-----------------------------------------------|

Đáp án: B.

**Bài 73:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{

int a\[100000\], i=0, j, s=0;

do scanf ("%d", &a\[i\]);

while (a\[i++\] != 0);

i--;

for (j=0; j&lt;i; j++) s = s+a\[j\];

printf ("%d", s);

}

Với input là 2, 3, 4, 5, 0 thì output là gì?

| 1.  9 | 1.  11 | 1.  12 | 1.  14 |
|-------|--------|--------|--------|

Đáp án: D.

**Bài 74:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{

long long a\[10000\], n, i;

scanf ("%lld", &n);

a\[0\] = 1;

a\[1\] = 1;

for (i=2; i&lt;n; i++) a\[i\] = a\[i-2\] + a\[i-1\];

printf ("%lld ", a\[n-1\]);

}

Với output là 55 thì input là gì?

| 1.  9 | 1.  10 | 1.  11 | 1.  12 |
|-------|--------|--------|--------|

Đáp án: B.

**Bài 75:** Khẳng định nào sau đây là đúng?

1.  Trong ngôn ngữ lập trình C, các phần tử trong 1 mảng hoặc 1 xâu được
    đánh số từ 0.

2.  Cú pháp của lệnh for không có số lần lặp.

3.  Muốn sử dụng cấu trúc rẽ nhánh, ta chỉ có thể sử dụng lệnh if.

4.  Cả 3 khẳng định trên đều sai.

Đáp án: A.

**Bài 76:** 3 bạn An, Bình, Chi viết chương trình nhập vào 1 trong 3 số
1, 2, 3 rồi in ra số sao (\*) tương ứng như sau:

An:

\#include &lt;stdio.h&gt;

int main ()

{

int n;

scanf (“%d”, &n);

switch (n)

{

case 1: printf (“\*”);

> break;

case 2: printf (“\*\*”);

break;

case 3: printf (“\*\*\*”);

break;

}

}

Bình:

\#include &lt;stdio.h&gt;

int main ()

{

int n;

scanf (“%d”, &n);

switch (n)

{

case 1: printf (“\*”);

case 2: printf (“\*\*”);

case 3: printf (“\*\*\*”);

}

}

Chi:

\#include &lt;stdio.h&gt;

int main ()

{

int n;

scanf (“%d”, &n);

switch (n)

{

case 1: printf (“\*”);

case 2: printf (“\*”);

case 3: printf (“\*”);

}

}

Hỏi khẳng định nào sau đây là đúng?

1.  An đúng, Bình sai, Chi sai.

2.  An sai, Bình sai, Chi đúng.

3.  An đúng, Bình sai, Chi đúng.

4.  An sai, Bình đúng, Chi sai.

Đáp án: C.

**Bài 77:** Cho các toán tử sau:

| 1.  = | 1.  &lt;= | 1.  \*= | 1.  == | 1.  != | 1.  += |
|-------|-----------|---------|--------|--------|--------|

Hỏi những toán tử nào là toán tử quan hệ?

| 1.  1, 2, 4 | 1.  2, 5, 6 | 1.  2, 3, 4 | 1.  2, 4, 5 |
|-------------|-------------|-------------|-------------|

Đáp án: D.

**Bài 78:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{

int n, x, i, j;

scanf ("%d", &n);

x = n-1;

for (i=1; i&lt;n; i++)

{

for (j=1; j&lt;n; j++) printf ("%d ", x);

printf ("\\n");

}

}

Với input n = 5 thì output là gì?

| 1.  5 5 5 5 5 
                
     5 5 5 5 5  
                
     5 5 5 5 5  
                
     5 5 5 5 5  
                
     5 5 5 5 5  
                
 2.  4 4 4 4    
                
     4 4 4 4    
                
     4 4 4 4    
                
     4 4 4 4    | 1.  4 4 4 4 4 
                                
                     4 4 4 4 4  
                                
                     4 4 4 4 4  
                                
                     4 4 4 4 4  
                                
                     4 4 4 4 4  
                                
                 2.  5 5 5 5    
                                
                     5 5 5 5    
                                
                     5 5 5 5    
                                
                     5 5 5 5    |
|---------------|---------------|

Đáp án: B.

**Bài 79:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

\#include &lt;math.h&gt;

int main ()

{

int n, i;

scanf ("%d", &n);

if (n&lt;0) return 0;

else

{

for (i=1; ; i++)

{

if (n/(pow(10, i))&lt;1)

{

printf ("%d", i);

break;

}

}

}

}

Với input n = 3756 thì output là gì?

| 1.  2 | 1.  3 | 1.  4 | 1.  5 |
|-------|-------|-------|-------|

Đáp án: C.

**Bài 80:** Cho 2 đoạn code sau:

1.  int main ()

{

int i=0;

while (++i &lt; 4) printf ("Hello! ");

}

1.  int main ()

{

int i=0;

while (i++ &lt; 4) printf ("Hello! ");

}

Hỏi khẳng định nào sau đây là đúng?

1.  Cả 2 chương trình đều in ra 3 từ “Hello!”.

2.  Chương trình 1 in ra 3 từ “Hello!”, chương trình 2 in ra 4
    từ “Hello!”.

3.  Chương trình 1 in ra 4 từ “Hello!”, chương trình 2 in ra 3
    từ “Hello!”.

4.  Cả 2 chương trình đều in ra 4 từ “Hello!”.

Đáp án: A.

**Bài 81:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

\#include &lt;math.h&gt;

int main ()

{

int n, i=0, m, s=0;

scanf ("%d", &n);

if (n&lt;0) return 0;

else

{

m = n;

while (n/pow(10, i) &gt; 1)

{

i++;

s = s + m%10;

m = m/10;

}

printf ("%d", s);

}

}

Với input n = 6245 thì output là gì?

| 1.  15 | 1.  17 | 1.  19 | 1.  21 |
|--------|--------|--------|--------|

Đáp án: B.

**Bài 82:** Hãy tìm cách biểu diễn để ch không phải là ‘a’ hoặc không
phải là ‘b’.

1.  ch != ‘a’ || ch != ‘b’

2.  ch != ‘a’ && ch != ‘b’

3.  ch != ‘a’ || ‘b’

4.  ch != ‘a’ && ‘b’

Đáp án: A.

**Bài 83:** Chọn biểu thức biểu diễn num là số nằm trong khoảng từ 1 đến
9 và khác 4.

1.  num &gt; 1 && num &lt; 9 && num != 4

2.  num &gt; 1 || num &lt; 9 && num != 4

3.  num &gt;= 1 && num &lt;= 9 && num != 4

4.  Không Bài nào đúng

Đáp án: C.

**Bài 84:** Hàm nào sau đây chuyển đổi 1 chuỗi sang giá trị int?

| 1.  atof | 1.  itoa | 1.  toupper | 1.  atoi |
|----------|----------|-------------|----------|

Đáp án: D.

**Bài 85:** Hàm nào sau đây không xử lí chuỗi ký tự?

| 1.  strcmpi | 1.  sqrt | 1.  strlwr | 1.  strupr |
|-------------|----------|------------|------------|

Đáp án: B.

**Bài 86:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{

long n, i, j, k, s=0;

scanf ("%ld", &n);

for (i=1; i&lt;n; i++)

{

for (j=i; ; j++)

{

s = s+j;

if (s==n)

{

for (k=i; k&lt;=j; k++) printf ("%ld ", k);

break;

}

if (s&gt;n)

{

s = 0;

break;

}

}

if (s==n) break;

}

}

Với input n = 45 thì output là gì?

| 1.  1 2 3 4 5 6 7 8 9 
                        
 2.  22 23              | 1.  14 15 16            
                                                  
                         2.  Chương trình bị lỗi  |
|-----------------------|-------------------------|

Đáp án: A.

**Bài 87:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

\#include &lt;math.h&gt;

int main ()

{

int n, i, k=0;

scanf ("%d", &n);

for (i=1; i&lt;=sqrt(n); i++)

if (n%i == 0) k = k+1;

printf ("%d", k);

}

Với input n = 100 thì output là gì?

| 1.  3 | 1.  4 | 1.  5 | 1.  6 |
|-------|-------|-------|-------|

Đáp án: C.

**Bài 88:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

int main ()

{

long long a\[100000\], n, i, x=1;

scanf ("%lld", &n);

for (i=0; i&lt;n; i++)

{

scanf ("%lld", &a\[i\]);

x = x\*a\[i\];

}

if (x&gt;=0) printf ("%lld", x%10);

else printf ("%lld", (-x)%10);

}

Với input n = 5 và các số 4, 7, −8, 3, 6 thì output là gì?

| 1.  2 | 1.  4 | 1.  6 | 1.  8 |
|-------|-------|-------|-------|

Đáp án: A.

**Bài 89:** Cho chương trình sau:

\#include &lt;stdio.h&gt;

\#include &lt;string.h&gt;

int main ()

{

char s\[100000\], max;

int k, x, a=0, b=0, k1, i;

scanf ("%d", &k);

scanf ("%s", s);

k1 = k;

x = strlen (s);

while (b &lt; x-k)

{

max = s\[a\];

for (i=a+1; i&lt;=k1; i++)

if (max &lt; s\[i\])

{

a = i;

max = s\[i\];

}

b++;

k1++;

printf ("%c", max);

a++;

}

}

Với input n = 3 và xâu s = ‘23571114’ thì output là gì?

| 1.  21114 | 1.  23571 | 1.  71114 | 1.  35714 |
|-----------|-----------|-----------|-----------|

Đáp án: C.

**Bài 90:** Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main()

{

int min,n,i,a\[500\];

scanf("%d",&n);

for (i = 0; i&lt;n; i++){

scanf("%d",&a\[i\]);

}

min = a\[0\];

for (i = 0; i&lt;n; i++)

{

if (min &gt; a\[i\]) min = a\[i\];

}

printf("%d", min);

}

Đoạn code trên có thể bị mắc lỗi gì:  
A. CE

B. MLE

C. TLE

D. Không có lỗi

Đáp án:B (bộ nhớ nhập vào của mảng quá nhỏ)

**Bài 91:** Tìm số lỗi CE trong đoạn code dưới đây:  
\#include&lt;stdio,h&gt;

\#include&lt;math.h&gt;

int main{

long a,b,c;

scanf(“%ld %ld”,&a,&b)

if(pow(a,3)+pow(b,5)==c; printf(“YES”);

else{  
print(“NO”);

}

}

A. 3

B. 4

C. 5

D. 0

Đáp án:C (ở các dòng 1,5,6,8,10)

**Bài 92:**

Nhiều laptop hiện đại có gắn cảm biến điểu chỉnh ánh sáng sao cho phù
hợp với ngoại cảnh. Tuy nhiên Trump lại lỡ tay làm rơi con Asus màn hình
cảm ứng đắt tiền của mình khiến cảm ứng ánh sáng của máy như người vừa
trốn trại :v. Cảm biến bình thường sẽ đo ánh sáng rồi điều chỉnh ánh
sáng màn hình bằng đúng ánh sáng bên ngoài. Còn cảm biến laptop của
Trump lại khiến cho màn hình tối khi trời sáng và ngược lại. Cho biết:
Khi ánh sáng bên ngoài nhỏ hơn 50 thì cảm biến điều chỉnh ánh sáng màn
hình gấp đôi ánh sang ngoại cảnh. Nếu ánh sáng ngoài mà từ 50 đến 70 thì
màn hình nhấp nháy, thoắt ẩn thoắt hiên như 1 nhẫn giả. Và khi bên ngoài
sáng hơn 70 thì máy sẽ đi ngủ (ánh sáng màn hình về 0).

Để tính ánh sáng màn hình so với ánh sáng bên ngoài, Trump đã nhờ Obama
viết hộ chương trình dưới đây:

\#include&lt;stdio.h&gt;

int main(){

int a;

scanf("%ld",&a);

if((0&lt;=a) & (a&lt;=100)){

if(a&lt;50){

print("%d",2\*a);

}

if(70&lt;a){

printf("0");

}

if((50&lt;=a) && (a&lt;=70)){

printf("Break the Mac");

}

}

}

Tuy nhiên khi chạy thử thì lại CE, hỏi có bao lỗi CE:

A. 0

B. 1

C. 2

D. 4

Đáp án:B (ở dòng 5, dòng 4 không sai)

**Bài 93:** Bạn Tom một hôm rảnh đời đã viết đoạn code sau:

\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

int main(){

long n,a=0,b=1,c;

scanf("%ld",&n);

if(n==0){

printf("0");

}

else{

do{

c=a+b;

a=b;

b=c;

} while(c&lt;=n);

printf("%ld",a);

}

}

Nếu input là 27 thì chương trình sẽ trả kết quả bao nhiêu

A.19

B.21.

C.26

D.27

Đáp án: B (Đây là code tìm số Fib nhỏ hơn bằng input. Nên khi nhập vào
27 sẽ in ra số Fib nhỏ hơn và gần nó nhất là 21)

**Bài 94:** Đoạn code sau cho output là gì?

\#include &lt;stdio.h&gt;

int main()

{

int x = 011, i;

for(i = 0; i &lt; x; i += 3)

{

printf("Bat dau ");

continue;

printf("Ket thuc");

}

}

A. Bắt đầu Kết thúc Bắt đầu Kết thúc

B. Bắt đầu Bắt đầu Bắt đầu

C. Bắt đầu Bắt đầu Bắt đầu Bắt đầu

D. Kết thúc Kết thúc Kết thúc Bắt đầu

Đáp án:B (011 là số ở hệ bát phân, khi đổi sang hệ thập phân sẽ là 9.
Nên lệnh printf sẽ thực hiện 3 lần)

**Bài 95:** Khi chạy chương trình sẽ cho ra kết quả gì?

\#include &lt;stdio.h&gt;

int main()

{

int i = 6;

while(i)

{

if (i &gt; 5)

{

i--;

}

i = i + 5;

if (i &gt; 34)

{

break;

}

}

printf("%d", i);

}

A. Infinite loop

B. 35

C. 38

D. 39

Đáp án:C

**Bài 96:** Dự đoán kết quả của chương trình:

\#include &lt;stdio.h&gt;

int main()

{

            int a=100, b=6;

            double f;

            f=(double)a/(double)b;

            printf(“%2.2f”,f);

}

A. 16

B. 16.00

C. 16.67

D. Kết quả khác

Đáp án:C

**Bài 97:** Cho biết chương trình bị lỗi CE, phải sửa dòng nào để chương
trình chạy:

int main(int argc, char\*\* argv){

const char\* foo = "wow";

foo = "top";

foo\[0\] = 1;

return 0;

}

A. 2

B. 3

C. 4

D. Làm gì có dòng nào sai, thằng viết đề não rồi

Đáp án:C (biến foo là biến const, trình biên dịch không cho phép thay
đổi giá trị của biến foo)

**Bài 98:** Cho 2 hàm sau:

int F1(int a){  
int b = 0, k = 0;  
while (k &lt; a) {  
b += k ;  
k++ ;  
}  
return b;  
}

int F2(int a){  
int b = 0, k = 0;  
for (k = 0; k &lt; a; k ++){  
b += k;  
return b;

}  
}  
Cho biết giá trị nào của a để các hàm F1(a) và F2(a) trả về kết quả
giống nhau?  
A. a \(\geq\) 0  
B. a &gt; 0  
C. a &lt; 0

D. a\(\  \leq \ \)0

Đáp án:D

**Bài 99** Cho chương trình tính tổng các chữ số của 1 giai thừa:  
\#include&lt;stdio.h&gt;

long Giaithua(long a){

long i,tich;

for(i=1;i&lt;=a;i++){

tich=tich\*i;

}

return tich;

}

int main(){

int m,n,SBD,tong;

scanf("%d", &SBD);

while(n&gt;0){

m=n%10;

tong=tong+m;

}

printf("%ld",tong);

}

A. 1

B. 2

C. 3

D. 4

Đáp án:D (cần thêm n=Giaithua(SBD), gán tich=1,tong=0 và n=(n-m)/10)

**Bài 100:**

Nếu nhập vào “Ho Dac Phuong” thì đoạn code sau sẽ cho kết quả là gì:  
\#include &lt;stdio.h&gt;

int main(){

char cname\[30\];

printf("Cho biet ten cua ban: ");

scanf("%s", cname);

printf("Chao ban %s\\n", cname);

}

A.Ho

B.Phuong

C.Ho Dac Phuong

D.Lỗi CE

Đáp án: A (lệnh scanf khi gặp khoảng trống sẽ dừng lại nên máy sẽ chỉ
đọc đến chu Ho rồi in ra luôn)

**Bài 101:** Phép tính nào dưới đây không đúng:  
A. int i = 35; i = i%5  
B. short int j = 5; j = j;  
C. long int k = 123L; k = k;  
D. float a = 3.14; a = a%3;

Đáp án:D (toán tử % chỉ áp dụng cho biến dạng int)

**Bài 102:** Kí hiệu nào là con trỏ của phẩn tử thứ 3 của màng a có 4 kí
tự:

A.\*(a+3);

B.\*(a+2);

C.\*(a+3);

D.\*(a+4);

Đáp án:B

**Bài 103:**

Sự hiệu chỉnh các kiểu dữ liệu số học khi tính toán là:

A.int → long → float → double → long double.

B.int → float → long → double → long double.

C.int → double → float →long → long double.

D.long → int → float →double → long double.

Đáp án: A

**Bài 104:** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

int main()

{

            char c;

            clrscr();

            do c=getchar();

while (c!=’\*’);

getch();

}

Yêu cầu của đoạn chương trình trên là:

a)     Nhập vào 1 kí tự cho đến khi gặp kí tự ‘\*’.

b)     Nhập vào các kí tự cho tới khi gặp kí tự ‘\*’.

c)     Nhập các kí tự ‘\*’.

d)     Lỗi khi xây dựng chương trình.

Đáp án:A

**Bài 105:**

Tối nay em của Minh có bài tập về nhà là giải bài toán bằng cách lập hệ
phương trình. Vầy mà Minh lại nhỡ cầm máy tính của em chạy quanh phố đi
bộ rồi để quên ở đâu đấy. bây giờ em Minh lại đòi máy tính để giải
phương trình bậc 2. Minh bèn dùng tài năng viết code “thần thánh” của
mình để viết chương trình giải pt bậc 2 tạm cho em. Tuy nhiên, vì danh
hiệu thần thánh là chỉ do Minh tự nghĩ ra nên code Minh viết không hoạt
động. Hãy giúp Minh sửa lại code nếu không Minh sẽ bị em thông chết :v

Code Minh viết như sau

\#include&lt;stdio.h&gt;

int main{

float a,b,c,delta,x,y,z;

scanf("%f%f%f",&a,&b,&c);

delta=b\*b-4\*a\*c;

x=(-b+sqrt(delta))/(2\*a);

y=(-b-sqrt(delta))/(2\*a);

if(x&gt;y)

{

z=x;

x=y;

y=z;

}

if(delta&gt;0)

{

printf("%.2f ",x);

printf("%.2f",y);

}

else if(delta=0)

printf("%2f",(-b+sqrt(delta))/(2\*a));

else

printf("No solution");

Minh phải sửa bao lỗi để không bị thông chết:v

A.5

B.3

C.7

D.1

Đáp án:A (Phải thêm thư viện math.h; thêm () sau int main; delta==0;
printf ra %.2f và phải có ngoặc kết thúc int main)

**Bài 106:**

\#include&lt;stdio.h&gt;

int n,a\[100\],l\[100\];

int main(){

int i,j,lmax;

scanf("%d", &n);

for(i=0;i&lt;n;i++){

a\[i\]=rand()%15+1;

}

l\[0\]=1;

for(i=1;i&lt;n;i++){

lmax=0;

for(j=0;j&lt;i;j++){

if(a\[i\]&gt;a\[j\]){

if(l\[j\]&gt;lmax)

lmax=l\[j\];

}

}

l\[i\]=lmax+1;

}

int lengMax=0;

for(i=0;i&lt;n;i++){

if(l\[i\]&gt;lengMax){

lengMax=l\[i\];

}

}

printf("%d",lengMax);

}

Output code trên là:

A, 5

B, 4

C, 6

D, Ce

Đáp án:D (hàm rand nằm trong thư viện stdlib.h chưa được khai báo)

**Bài 107:**

Cho 2 đoạn code sau:

\#include&lt;stdio.h&gt;

int UCLN(int a,int b){

int UCLN,i;

if(a&gt;=b){

for(i=1;i&lt;=b;i++){

if(a%i==0 && b%i==0){

UCLN=i;

}

}

}

if(b&gt;a){

for(i=1;i&lt;=a;i++){

if(a%i==0 && b%i==0){

UCLN=i;

}

}

}

return UCLN;

}

int main(){

int a,b;

scanf("%d %d",&a,&b);

printf("%d",UCLN(a,b));

}

Và

\#include &lt;stdio.h&gt;

int main(){

int a,b;

scanf("%d %d",&a,&b);

if(a==b) printf("%d",a);

while(a!=b){

if(a&gt;b) a=a-b;

if(a&lt;b) b=b-a;

}

printf("%d",a);

}

Hỏi code nào tối ưu hơn và hơn ở chỗ nào:

1.  Code 1 hơn vì code 2 sai

2.  Code 2 hơn vì code 1 sai

3.  Code 2 hơn vì code 1 mất thời gian hơn

4.  Cả 2 code đều sai

Đáp án:C (cả 2 code đều đúng nhưng vì code 2 chỉ cần chạy 1 trường hiwpj
nên tốn ít thời gian hơn code 1)

**Bài 108:**

Dự đoán kết quả chương trình sau:

\#include&lt;stdio.h&gt;

\#include &lt;conio.h&gt;

int main()

{

    int a = 5;

    switch(a){

    default:

        a = 4;

    case 6:

        a--;

    case 5:

        a = a + 1;

    case 1:

        a = a - 1;

    }

    printf("%d \\n", a);

}

A. 5

B. 4

C. 3

D. 2

Đáp án:A (vì chương trình sẽ nhảy vào case 5 và thực hiện lệnh a = a+1 =
6. Nhưng vì không có lệnh break nên a = a - 1 = 5 sẽ được thực hiện.)

**Bài 109:**

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

int main()

{

int check = 20, arr\[\] = {10, 20, 30};

switch (check)

{

case arr\[0\]: printf("A ");

case arr\[1\]: printf("B");

case arr\[2\]: printf("C");

}

getch();

}

Output code trên là:

A. ABC

B. BC

C. B

D. CE

Đáp án:D(vì case &lt;biểu thức&gt;, biểu thức phải là hằng số nguyên.
arr\[0\], arr\[1\], arr\[2\] không phải là hằng số nguyên.)

**Bài 110:**

Cho 2 chương trình:

\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

long Giaithua(long a){

long i,tich=1;

for(i=1;i&lt;=a;i++){

tich=tich\*i;

}

return tich;

}

int main(){

int n,k,i;

long a,b,c,x,kq;

scanf("%d %d",&n,&k);

a=Giaithua(n);

b=Giaithua(k);

i=n-k;

c=Giaithua(i);

x=b\*c;

kq=a/x;

printf("%ld",kq);

}

Và

\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

long Giaithua(long a){

long i,tich=1;

for(i=1;i&lt;=a;i++){

tich=tich\*i;

}

return tich;

}

int main(){

int n,k,i;

long a,b,c,x,kq;

scanf("%d %d",&k,&n);

if((0&lt;=k) && (k&lt;=n) && (n&lt;=15)){

a=Giaithua(n);

b=Giaithua(k);

i=n-k;

c=Giaithua(i);

x=b\*c;

kq=a/x;

printf("%ld",kq);

}

}

Hãy tìm chương trình đúng:

A.Chương trình 1

B.Chương trình 2

C.Cả 2 đều đúng

D.Cả 2 đều sai

Đáp án:B (

**Bài 111:**

Output của chương trình sau là gì:

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

int main()

{

char ch\[\]={'0', '1', '2', '3', '4', '5', '6', '7', '8', '9'};

int \*p = (int\*)ch;

p++;

printf("%x", \*p);

getch();

}

(Giả sử: kiến trúc máy tính sử dụng là little endian)

A. 37363534

B. 34353637

C. 45673333

D.34567654

Đáp án:A

**Bài 112:**

Dự đoán kết quả đoạn code:

\#include &lt;stdio.h&gt;

void swap(char \*, char \*);

int main()

{

char \*pstr\[2\] = {"VNCODING", ".NET"};

swap(pstr\[0\], pstr\[1\]);

printf("%s%s", pstr\[0\], pstr\[1\]);

getch();

}

void swap(char \*t1, char \*t2)

{

char \*t;

t=t1;

t1=t2;

t2=t;

}

A. VNCODING.NET

B. .NETVNCODING

C. Address of pstr\[0\] Address of pstr\[1\]

D. Không phải 3 phương án trên

Đáp án:A

**Bài 113:**

\#include &lt;stdio.h&gt;

int main()

{

struct diem;

{

float k;

float a;

float l;

};

struct diem m;

m.k = 8;

m.a = 6.5;

m.l = 6;

printf(“%0.1f%0.1f%0.1f”, m.k, m.a, m.l);

}

A.“8.06.56.0”.

B.”86.56”.

C.“8.0000006.5000006.000000”.

D.“86.5000006”.

Đáp án:A

**Bài 114:**

\#include&lt;stdio.h&gt;

int main()

{

long a,i,n,k,tong=0;

scanf("%ld %ld",&n,&k);

for(i=1;i&lt;=n;i++)

{

a=i\*(i+k);

tong=tong+

}

printf("%ld",tong);

}

Cần thêm bao dòng để code in ra
\(\sum_{x = 1}^{n}{x\left( x + k \right) = 1*\left( 1 + k \right) + 2*\left( 2 + k \right) + \ldots + n*(n + k)}\):

A.4

B.3

C.2

D.1

Đáp án:D (thêm tong=tong+a sau dòng a=i(i+k)

**Bài 115:**

\#include &lt;stdio.h&gt;

int thu(int ngay, int thang, int nam)

{

if(thang&lt;3)

{

thang=thang+12;

nam=nam-1;

}

return(abs(ngay+2\*thang+3\*(thang+1)/5 + nam + nam/4)%7);

}

int in(int thu)

{

switch(thu)

{

case 1:

printf("Monday");

break;

case 2:

printf("Tuesday");

break;

case 3:

printf("Wednesday");

break;

case 4:

printf("Thursday");

break;

case 5:

printf("Friday");

break;

case 6:

printf("Saturday");

break;

case 0:

printf("Sunday");

break;

}

}

int main()

{

int ngay,thang,nam;

scanf("%d %d %d",&ngay,&thang,&nam);

in(thu(ngay,thang,nam));

return 0;

}

Kết quả của chương trình:

1.  Monday

2.  Friday

3.  Wednesday

4.  CE

Đáp án:D (Cần khai báo thêm thư viện math.h cho hàm abs)

**Bài 116:**

\#include&lt;stdio.h&gt;

\#include&lt;math.h&gt;

int checkPrime(int n){

if(n&lt;2) return 0;

for(int i=2;i&lt;=sqrt(n);i++){

if(n%i==0) return 0;

}

return 1;

}

int main(){

int n,i,count=0;

scanf("%d",&n);

for(i=2;i&lt;n;i++){

if(checkPrime(i)==1){

count++;

}

}

printf("%d",count);

}

Input là 17, hỏi in ra gì:

A.5

B.6

C.7

D.CE

Đáp án:B (Tìm số số nghuyên tố &lt; số nhập vào, khỏi nói nhiều)

**Bài 117:**

Chọn kết quả đúng cho chương trình sau:

\#include &lt;stdio.h&gt;

int main()

{

clrscr();

struct sv

{

float d;

char ht\[10\];

};

struct sv m, \*p;

p=&m;

(\*p).d=p-&gt;d=10;

strcpy(m.ht,”NguyenVanTuan”);

printf(“%0.1f”,m.d);

printf(“%s”,m.ht);

}

A.“10.000000NguyenDoanDai”.

B.“10.0NguyenDoanDai”.

C.Kết quả khác.

D.Chương trình bị lỗi.

Đáp án:C ((“NguyenVanTuan”)// ht\[10\]. – Kết quả trên máy.)

**Bài 118:**

Trong các khai báo sau, khai báo nào không đúng:

A.struct Date{int ngay, thang, nam;};

B.struct { int ngay, thang, nam;} D1,D2;

C.typedef struct { int ngay, thang, nam;} Date;

D.struct Date

{

> long int ngay:7;
>
> long int thang:6;
>
> long int nam:5;

};

Đáp án:D

**Bài 119:**

Dự đoán kết quả chương trình:

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

int main()

{

int a = 2013;

if(a++=4 &gt; 2017)

printf("C/C++ %d", a);

else

printf("Java %d", a);

}

A. C/C++ 2016

B. C/C++ 2017

C. Java 2016

D. Java 2017

Đáp án:D

Bài **120.**

Cho 2 đoạn code:

\#include &lt;stdio.h&gt;

int main()

{

long double val= 5.555;

printf("%.2llg",val);

}

và

\#include &lt;iomanip&gt;

\#include &lt;iostream&gt;

int main()

{

long double val = 5.555; cout &lt;&lt; fixed &lt;&lt; setprecision(2)
&lt;&lt; val;

}

Hãy tìm output của 2 chương trình:

1.  Không khác nhau

2.  Đoạn code đầu tiên in ra 5.6, đoạn code thứ hai in ra 5.56

3.  Đoạn code đầu tiên in ra 5.56, đoạn code thứ hai in ra 5.55

4.  Đoạn code đầu tiên in ra 5.6, đoạn code thứ hai in ra 5.55

5.  Đoạn code thứ nhất bị CE

6.  Đoạn code thứ hai bị CE

Đáp án : F (tại đoạn code thứ 2, cout, fixed và setprecision phải có
tiền tố std:: hoặc using namespace std trước khi viết hàm main())

Bài **121.**

Xét đoạn code sau:

\#include &lt;iostream&gt;

\#include &lt;math.h&gt;

int main()

{

unsigned long int a, rt; std::cin &gt;&gt; a; rt = sqrt(a);

std::cout &lt;&lt; rt;

}

Hỏi chương trình sẽ cho ra output như thế nào, biết 456 là input được
nhập:

1.  21.354156

2.  21.35

3.  21

4.  21.00

Đáp án: D (rt là kiểu long int (không dấu), nên giá trị trả lại của hàm
sqrt sẽ bị cắt phần thập phân)

Bài **122.**:

Hàm (hoặc đối tượng stream) nào sau đây không được dùng để lấy chuỗi ký
tự nhập vào từ console:

1.  std::cin

2.  getline()

3.  scanf()

4.  getchar()

Đáp án: D (getchar()được sử dụng để lấy MỘT ký tự stdin, không dùng để
lấy chuỗi)

Bài **123.**

Muốn dùng hàm std::reverse() cần khai báo tập tin header nào:

1.  &lt;algorithm&gt;

2.  &lt;string&gt;

3.  &lt;vector&gt;

4.  &lt;iomanip&gt;

Đáp án: A (tham khảo
[*http://www.cplusplus.com/reference/algorithm/reverse/*](http://www.cplusplus.com/reference/algorithm/reverse/)*)*

Bài **124.**

\#include &lt;iostream&gt;

int main()

{

double input; std::cin &gt;&gt; input; int half = input / 2;

while (input / 2 = half)

{

if (input % 2 == 0)

{

std::cout &lt;&lt; "EVEN";

}

else

{

std::cout &lt;&lt; "ODD";

};

};

};

Chương trình mắc bao nhiêu lỗi:

1.  1

2.  2

3.  Không mắc lỗi

4.  3

Đáp án: 2 (tại phần khai báo vòng lặp while, đặt điều kiện là phép gán →
luôn trả về giá trị true, dẫn tới lặp vô hạn; tại cấu trúc rẽ nhánh if
bên trong while, sử dụng toán tử modulo (chia lấy dư) cho 2 giá trị
không cùng kiểu nguyên (input là double) )

Bài **125.**

Cho đoạn code sau:

\#include &lt;iostream&gt;

\#include &lt;string&gt;

void main()

{

   unsigned long long int n; cin &gt;&gt; n;                           

   long long int arr\[n - 1\];                                  

   for (unsigned long long int i = 0 ; i &lt;  n - 1 ; i++)          

   {                                                   

       string tmp;                                     

       getline(cin,tmp,' ');                           

       arr\[i\] = std::stoi(tmp);                        

   };                                

   string tmp2 ; getline(cin,tmp2) ; arr\[n - 1\] = std::stoi(tmp2);

   unsigned long long int a = n - 1;

   while (true)

   {

       cout &lt;&lt; arr\[a\] &lt;&lt; ' '; a--;

   };

}

Biết đề bài yêu cầu như sau: Nhập vào số phần tử của mảng trên dòng đầu
tiên, dòng thứ 2 nhập các phần tử nguyên (cách nhau 1 dấu cách), in ra
mảng đó theo chiều ngược lại.

| Input     | Output    |
|-----------|-----------|
| 5         
            
 1 2 3 4 5  | 5 4 3 2 1 |

Hỏi đoạn code trên mắc bao nhiêu lỗi sai:

1.  1 lỗi

2.  3 lỗi

3.  2 lỗi

4.  Có thể đưa vào compiler, không có lỗi nào

Đáp án: B

( - lỗi đầu tiên: khai báo và sử dụng string, nhập/xuất bằng cin/cout mà
không sử dụng using namespace std;

- lỗi thứ hai: hàm  main() luôn luôn trả về giá trị kiểu int (vì vậy
khai báo void main() là sai

 - lỗi thứ ba: tại phần vòng lặp while không có điều kiện kết thúc (tạo
nên vòng lặp vô hạn, do đó chỉ mục của mảng sẽ âm - gây lỗi crash) )

Bài **126.**

Kiểu dữ liệu unsigned long long int chiếm bao nhiêu bit trong bộ nhớ:

1.  8 bits

2.  16 bits

3.  32 bits

4.  64 bits

Đáp án: D (theo chuẩn ***ISO/IEC 9899:1999***, tiền tố long long sẽ sử
dụng ́t nhất 64 bits trong bộ nhớ cho biến được khai báo)

Bài **127.**

Cho đoạn code sau:

\#include &lt;iostream&gt;

\#include &lt;iomanip&gt;

int main()

{

long double input; std::cin &gt;&gt; input;

for (unsigned int i = 0 ; i &lt;= 3 ; i++)

{

std::cout &lt;&lt; std::fixed &lt;&lt; std::setprecision(i) &lt;&lt;
input;

};

};

Biết rằng sau khi nhập vào input, chương trình in ra như sau:

| 668      
 667.8     
 667.78    
 667.778   |
|----------|

Tìm input được nhập:

1.  667.7775

2.  667.7771

3.  667.7797

4.  667.7773

Đáp án: A (std::setprecision làm tròn theo quy ước - chữ số thứ 3 sau
dấu chấm thập phân phải là 7 và chữ số thứ 4 phải ≥ 5)

Bài **128.**:

Trên một trang dạy nhập môn lập trình, có bài tập như sau:

| Viết chương trình nhập vào 3 biến rồi in ra chính 3 biến đó. Yêu cầu sử dụng mảng. |
|------------------------------------------------------------------------------------|

John đã nộp đoạn code sau:

\#include &lt;iostream&gt;

int main()

{

unsigned long long int arr\[3\];

std::cin &gt;&gt; arr\[1\] &gt;&gt; arr\[2\] &gt;&gt; arr\[3\];

unsigned long int i = 0;

while (i &lt;= 3)

{

std::cout &lt;&lt; arr\[i\] &lt;&lt; ' ';

i++;

};

};

Hỏi kết quả John nhận được là gì? Biết các giới hạn như sau:

| Time Limit : 1.0000s  
                        
 Memory Limit : 512 MB  |
|-----------------------|

1.  Compile Error

2.  Time Limit Exceeded

3.  Wrong Output

4.  Memory Limit Exceeded

Đáp án: C (do nhập vào các biến có index là 1, 2 và 3 mà bỏ qua trường
hợp index = 0, khi in ra mảng sẽ cho lại một giá trị bất định khi truy
nhập phần tử có index = 0)

Bài **129.**

Cho bài tập như sau:

| Đề bài              | Tính khoảng cách giữa 2 điểm trên mặt phẳng tọa độ với các tọa độ cho trước. Kết quả in ra mang 4 chữ số sau dấu chấm thập phân, làm tròn tại chữ số cuối cùng. 
                                                                                                                                                                                        
                       Định dạng: lần lượt là tọa độ x,y của 2 điểm, cách nhau 1 dấu cách                                                                                               |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Giá trị mẫu cần đạt | | INPUT   | OUTPUT |                                                                                                                                            
                       |---------|--------|                                                                                                                                             
                       | 5 4 6 7 | 3.1623 |                                                                                                                                             |

Dưới đây là 1 đoạn code được viết để giải bài tập trên:

\#include &lt;stdio.h&gt;

\#include &lt;iostream&gt;

int main()

{

long double x1,y1,x2,y2; cin &gt;&gt; x1 &gt;&gt; y1 &gt;&gt; x2
&gt;&gt; y2;

long double sq = pow(x2 - x1,2) + pow(y2 - y1,2);

cout &lt;&lt; sq &lt;&lt; endl;

long double result = sqrt(sq);

cout &lt;&lt; fixed &lt;&lt; setprecision(4) &lt;&lt; result;

}

Biết chương trình trên khi compile bị lỗi. Sửa đổi nào sau đây không có
tác dụng trong việc sửa lỗi:

1.  Thêm using namespace std;

2.  Xóa \#include &lt;stdio.h&gt;

3.  Thêm \#include &lt;math.h&gt;

4.  Thêm \#include &lt;iomanip&gt;

Đáp án: B (các lỗi cần sửa: A, C và D; stdio.h dù được gọi nhưng không
có hàm nào yêu cầu, do đó loại bỏ hay không không quan trọng và không có
tác dụng gì đối với việc sửa lỗi)

Bài **130.**

Cho bảng sau:

| Loại giá trị | float                                         | long double                                   |
|--------------|-----------------------------------------------|-----------------------------------------------|
| Cú pháp 1    | printf("%.4f",value);                         | printf("%.4llf",value);                       |
| Cú pháp 2    | printf("%.4g",value);                         | printf("%.4lg",value);                        |
| Cú pháp 3    | cout &lt;&lt; setprecision(4) &lt;&lt; value; | printf("%.5llg",value);                       |
| Cú pháp 4    | printf("%.5g",value);                         | cout &lt;&lt; setprecision(4) &lt;&lt; value; |

Cú pháp nào có thể sử dụng để in ra 1 giá trị float hoặc double với 4
chữ số sau dấu chấm thập phân (bài này không quy định về làm tròn và giả
sử toàn bộ header cần thiết được khai báo, sử dụng namespace std):

1.  Cú pháp 1

2.  Cú pháp 2

3.  Cú pháp 3

4.  Cú pháp 4

Đáp án: A (2 cú pháp đều đúng. Các đáp án còn lại:

- B: đối với float, máy sẽ in ra 3 chữ số (do sử dụng g thay vì f); đối
với long double, sai với lý do tương tự và sai cả định danh (long double
sử dụng llf)

- C: đối với float, sử dụng setprecision(4) mà không có fixed đứng trước
sẽ cho ra kết quả với 3 chữ số thập phân

- D: đối với long double, sai tương tự C)

Bài **131.**

Hàm min() có cú pháp như thế nào:

1.  min(arr,arrlength) với arr là mảng và arrlength là độ dài của mảng

2.  min(val\_1,val\_2,...,val\_n) với val\_1, val\_2,..val\_n là các giá
    trị số

3.  min(val\_1,val\_2) với val\_1 và val\_2 là các giá trị số

4.  min(str) với str là một đối tượng string

Đáp án: C (hàm min()trong &lt;algorithm&gt; chỉ so sánh 2 giá trị)

Bài **132.**

Toán tử nào có thể sử dụng trên mảng:

1.  “.”

2.  “&gt;&gt;”

3.  “++”

4.  “::”

5.  “~”

6.  Toàn bộ các toán tử trên

7.  Không có toán tử nào

Đáp án: G (mảng thì tính toán với biến đổi gì nếu không sử dụng chỉ số
để truy nhập)

Bài **133.**

Hàm thành viên nào không thuộc lớp std::string và được khai báo trong
&lt;string&gt;:

1.  pop\_back()

2.  append()

3.  size()

4.  isgreater()

Đáp án: D (hàm này dùng để so sánh 2 giá trị, nằm trong &lt;cmath&gt;
đối với C++ và &lt;math.h&gt; trong C)

Bài **134.**

(Xét kết quả chung nhất mà mọi hệ thống sẽ đưa ra)

Đoạn code sau khi đưa vào compiler và chạy sẽ cho ra kết quả gì:

\#include &lt;iostream&gt;

using namespace std;

int main()

{

int x; x++; cout &lt;&lt; x;

}

1.  1

2.  0

3.  Giá trị bất định

4.  Runtime Error

Đáp án: C (về lý thuyết, khi compiler chạy hoặc sẽ gán 1 giá trị bất kỳ,
hoặc để cho chương trình quyết định - khi được chạy sẽ cho ra 1 giá trị
ngẫu nhiên bất khả định)

Bài **135.**  
Giả sử 1 chương trình có phần khai báo header và sử dụng namespace như
sau:

\#include &lt;iostream&gt;

\#include &lt;ios&gt;      

\#include &lt;regex&gt;   

\#include &lt;array&gt;    

\#include &lt;string&gt;   

\#include &lt;stdio.h&gt;  

\#include &lt;algorithm&gt;

\#include &lt;iterator&gt;

\#include &lt;math.h&gt;   

\#include &lt;cmath&gt;    

\#include &lt;iomanip&gt;  

\#include &lt;cstring&gt;  

\#include &lt;string&gt;   

\#include &lt;cstdlib&gt;  

using namespace std;

Hỏi tên biến nào sau đây là hợp lệ (biết không có hàm nào được đặt tên
trùng với các lựa chọn dưới đây):

1.  size\_t

2.  string

3.  confirm

4.  asm

Đáp án: C (size\_t là kiểu biến được định nghĩa trong &lt;string&gt;,
string là kiểu dữ liệu chuỗi (cũng nằm trong &lt;string&gt;), asm là từ
khoá của C++) (nâng cao: asm sử dụng để nhúng mã assembly vào C++)

Bài **136.**

Cho đoạn code sau:

\#include &lt;iostream&gt;

\#include &lt;stdio.h&gt;

int main()

{

int a,b,c; scanf("%d %d %d",&a,&b,&c);

if (a &gt; b)

{

int tmp1 = a; a = b; b = tmp1;

};

if (b &gt; c)

{

int tmp2 = b; b = c; c = tmp2;

};

if (c &gt; a)

{

int tmp3 = c; c = a ; a = tmp;

};

cout &lt;&lt; a &lt;&lt; ' ' &lt;&lt; b &lt;&lt; ' ' &lt;&lt; c;

}

Nhập input là

| 5 4 6 |
|-------|

Hỏi chương trình sẽ cho lại output như thế nào:

| Trường hợp | Output            |
|------------|-------------------|
| 1          | 6 5 4             |
| 2          | 4 5 6             |
| 3          | 6 4 5             |
| 4          | \[Compile Error\] |

1.  Trường hợp 1

2.  Trường hợp 2

3.  Trường hợp 3

4.  Trường hợp 4

Đáp án: D (thiếu using namespace std;)

Bài **137.**

Từ nào sau đây không là tên của đối tượng đã được định nghĩa trước trong
C++:

1.  cin

2.  cout

3.  printf

4.  get

5.  max

6.  reverse

7.  confirm

Đáp án: G (trong C++ làm gì có từ khóa nào là confirm đâu)

Bài **138.**

Từ khóa nào cho phép tạo ra kiểu dữ liệu mới:

1.  struct

2.  declare

3.  create

4.  new

Đáp án: A (struct là từ khóa khai báo kiểu dữ liệu cấu trúc. new làm
việc với con trỏ chứ không liên quan tới khai báo mới, còn C và D không
tồn tại trong C++ dưới dạng từ khóa)

Bài **139.**

Xét đề bài:

| Cho 1 dãy số nguyên có độ dài xác định được nhập. Hãy tìm độ dài dãy con tăng lớn nhất. |
|-----------------------------------------------------------------------------------------|

Thuật toán nào sau đây là tối ưu để giải bài toán này:

1.  Quy hoạch động

2.  Tham lam

3.  Chia để trị

4.  Quay lui

Đáp án: A (cái này học Cấu trúc dữ liệu và giải thuật biết ngay)

Bài **140.**  
Khả năng lưu trữ và độ chính xác của kiểu long double:

1.  16 bit (từ -32767 đến 32767), chính xác tới 10<sup>-7</sup>

2.  32 bit (từ -2147483647 đến 2147483647), chính xác tới 10<sup>0</sup>

3.  64 bit (từ -1797693134862315,7 x 10<sup>308</sup> đến
    1797693134862315,7 x 10<sup>308</sup>), chính xác tới ≈ 2 x
    10<sup>308</sup>)

4.  8 bit (từ -128 tới 128), chính xác tới 10<sup>0</sup>

Đáp án: C (tham khảo
[*http://en.cppreference.com/w/cpp/language/types*](http://en.cppreference.com/w/cpp/language/types))

Bài **141.**

Cho đoạn code sau:

| \#include &lt;iostream&gt;              
                                          
 using namespace std;                     
                                          
 int x = 1;                               
                                          
 void fun()                               
                                          
 {                                        
                                          
    int x = 2;                            
                                          
    {                                     
                                          
        int x = 3;                        
                                          
        cout &lt;&lt; ::x &lt;&lt; endl;  
                                          
    }                                     
                                          
 }                                        
                                          
 int main()                               
                                          
 {                                        
                                          
    fun();                                
                                          
    return 0;                             
                                          
 }                                        |
|-----------------------------------------|

Hỏi output sẽ ra bao nhiêu:

1.  1

2.  2

3.  3

4.  Lỗi khi compile

Đáp án: A (toán tử :: trước biến x để chỉ ra rằng đây là sử dụng biến
toàn cục)

Bài **142.**

Hàm log() trong C++ có chức năng gì và giá trị trả lại mang kiểu thế
nào:

1.  Tính logarit của 1 số với cơ số xác định, trả lại giá trị int

2.  Tính logarit tự nhiên của 1 số, trả lại giá trị float

3.  Tính logarit của số nguyên với cơ số xác định, trả lại giá trị
    double

4.  Tính logarit tự nhiên của 1 số, trả lại giá trị double

Đáp án: D (hàm log() được định nghĩa sẵn chỉ tính logarit tự nhiên của
số đã cho chữ không tính với cơ số xác định)

Bài **143.**

Hàm thành viên nào sau đây là của lớp string:

1.  swap()

2.  pop()

3.  remove()

4.  concat()

Đáp án: A (các hàm còn lại đều không tồn tại; tham khảo
[*http://www.cplusplus.com/reference/string/string/*](http://www.cplusplus.com/reference/string/string/))

Bài **144.**

Cho đoạn code sau:

\#include&lt;iostream&gt;

using namespace std;

int main ()

{

int cin;

cin &gt;&gt; cin;

cout &lt;&lt; "cin" &lt;&lt; cin;

return 0;

}

Output của chương trình khi chạy:

1.  Lỗi compile

2.  &lt;không trả lại gì và không có lỗi&gt;

3.  cin  + giá trị bất kỳ

4.  Lỗi khi chạy (do dùng tên biến là cin)

Đáp án: C (cin lúc này mang giá trị bất định)

Bài **145.**

Hàm sqrt() nằm trong thư viện nào của C++:

1.  &lt;cmath&gt;

2.  &lt;cctype&gt;

3.  &lt;algorithm&gt;

4.  &lt;regex&gt;

Đáp án: A (trong C, sqrt() chứa trong &lt;math.h&gt; do đó trong C++ nó
được chuyển vào &lt;cmath&gt;)

Bài **146.**

Kiểu dữ liệu nào sau đây không được định nghĩa sẵn trong C++:

1.  bool

2.  vector

3.  array

4.  string

5.  char32

Đáp án: E (trong C++ chỉ tồn tại kiểu char32\_t, không tồn tại char32)

Bài **147.**

Tìm lựa chọn khác với các dòng còn lại:

1.  int func()

2.  void func()

3.  null func()

4.  bool func()

Đáp án: C (null trong C++ không phải là kiểu dữ liệu được định nghĩa
sẵn)

Bài **148.**

Cho đoạn code sau:

\#include &lt;cstdio&gt;

\#include &lt;iomanip&gt;

\#include &lt;cmath&gt;

\#include &lt;iostream&gt;

using namespace std;

void main()

{

string arr\[10\];

for (unsigned int i = 0 ; i &lt;= 10 ; i++)

{

getline(CIN,arr\[i\],' ');

};

short int pos = 0 ;

while (true)

{

   cout &lt;&lt; arr\[pos\]; pos++;

   if (pos &gt;= 11) break;

};

}

Cho input nhập vào như sau:

| a   
      
 b    
      
 c    
      
 d    
      
 e    
      
 f    
      
 g    
      
 h    
      
 i    
      
 j    |
|-----|

Cho giới hạn thời gian là 3s, bộ nhớ là 256 MB

Hỏi chương trình khi chạy sẽ cho kết quả gì:

1.  Lỗi khi compile, không thể chạy

2.  Vượt quá giới hạn thời gian

3.  abcdefghij

4.  Vượt quá giới hạn bộ nhớ

Đáp án: A (đoạn code này sai ở tên stream là cin chứ không phải CIN; hàm
main() phải trả lại giá trị nguyên int)

Bài **149.**

Cho đoạn code sau:

\#include &lt;cstdio&gt;

\#include &lt;iostream&gt;

const int i = 0;

int main()

{

   cout &gt;&gt; i++;

}

Hỏi đoạn code sau mắc bao nhiêu lỗi:

1.  1

2.  2

3.  3

4.  Không có lỗi

Đáp án: 3 (thiếu tiền tố std:: ; sử dụng sai toán tử (&gt;&gt; thay vì
&lt;&lt;) ; cố gắng thay đổi giá trị của hằng số)

Bài **150.**

Loại dữ liệu nào sau đây không thể sử dụng để làm giá trị trả về của một
hàm tự định nghĩa:

1.  Giá trị dấu chấm động kiểu double

2.  Giá trị dấu chấm động kiểu float

3.  Giá trị nguyên int

4.  Mảng

5.  void (tức không trả về giá trị nào)

Đáp án: D (tham khảo:
[*https://www.tutorialspoint.com/cplusplus/cpp\_return\_arrays\_from\_functions.htm*](https://www.tutorialspoint.com/cplusplus/cpp_return_arrays_from_functions.htm))

Bài **151.**

Cách nào sau đây là không hợp lệ để khai bào 1 biến nguyên int trong
C++17:

1.  int a = 3;

2.  int b(3);

3.  auto d = 3;

4.  int c{3};

5.  auto a(3);

6.  auto f{3};

7.  int(e) = 3;

8.  int g :: 3;

Đáp án: H (Các cách còn lại đều được chấp nhận, riêng F chỉ được sử dụng
từ C++17)

Bài **152.**

Dòng nhập và xuất chuẩn của C++ được gọi là:

1.  stdin và stdout

2.  stdin và stderr

3.  cin và cout

4.  stdio và iostream

Đáp án: A

Bài **153.**

Chọn dòng khác với các dòng còn lại:

1.  typedef

2.  const

3.  \#define

4.  \#include

5.  struct

6.  create

Đáp án: F (các dòng còn lại đều là chỉ thị tiền xử lý hoặc là từ khóa
của C++)

Bài **154.**

Số lượng toán hạng lớn nhất có thể có trong một phép tính đơn (chỉ dùng
1 toán tử) trong C++ là gì:

1.  1

2.  2

3.  3

4.  4

Đáp án: C (tồn tại toán tử 3 ngôi trong C++; tham khảo
[*http://www.cplusplus.com/doc/tutorial/operators/*](http://www.cplusplus.com/doc/tutorial/operators/))

Bài **155.**

Tập tin header nào sau đây không phải là tập tin chuẩn trong C++17:

1.  iomanip

2.  iostream.h

3.  cctype

4.  math.h

Đáp án: B (trong C++, header này là iostream)

Bài **156.**

Cho đoạn code sau:

\#include &lt;cstdio&gt;

\#include &lt;iomanip&gt;

\#include &lt;iostream&gt;

\#include &lt;ios&gt;

\#include &lt;regex&gt;

using namespace std;

int main()

{

   short i;

   std::cout &lt;&lt; "Enter an integer value";

   std::cin &gt;&gt; i++;

   std::cout &lt;&lt; --i;

}

Dòng nào cần sửa để đoạn code chạy:

1.  short i;

2.  std::cin &gt;&gt; i++;

3.  std::cout &lt;&lt; --i;

4.  \#include &lt;regex&gt;

Đáp án: B (sử dụng toán tử ++ trên cin là không được phép)

Bài **157.**

Hàm / đối tượng stream nào sau đây không thể sử dụng để lấy dữ liệu từ
dòng nhập chuẩn:

1.  getline()

2.  scanf()

3.  cin

4.  cout

5.  sscanf()

6.  gets()

Đáp án: E (sscanf() được dùng để lấy dữ liệu từ string theo cách scanf()
lấy dữ liệu. Tham khảo
[*http://www.cplusplus.com/reference/cstdio/sscanf/*](http://www.cplusplus.com/reference/cstdio/sscanf/))

Bài **158.**

Dòng code sau có mấy lỗi, biết nó không mắc lỗi liên quan tới việc gọi
tập tin header và khai báo namespace:

If (x = 100)

  Cout &lt;&lt; “x is 100”;

Đoạn code sau có mấy lỗi:

1.  1

2.  2

3.  4

4.  Không có lỗi

Đáp án: 2 (sai cách viết từ khóa (if khác If), sai cách viết stream
(thực tế là cout thay vì Cout)

Bài **159.**

Xét đoạn code sau:

\#include &lt;cmath&gt;

\#include &lt;iomanip&gt;

\#include &lt;iostream&gt;

using namespace std;

int main(long double i)

{

   cin &gt;&gt; i;

   cout &lt;&lt; fixed &lt;&lt; setprecision(9) &lt;&lt; i \* i;

}

Cho input là 1.414213562373, hỏi output là gì:

1.  1.999999999

2.  2.000000000

3.  1.999999998

4.  2

Đáp án: B (chú thích: GCC 4.9.2)

Bài **160.**

Dòng nào sau đây là chính xác:

1.  sscanf("%d %d %f",&value,&variable,&valuevar);

2.  getline(str);

3.  stringstream strstream;

4.  log(n,c);

Đáp án: C (cú pháp của sscanf() gồm 3 loại đối mục chứ không phải 2;
tương tự, cú pháp của getline() bao gồm 2 hoặc 3 đối mục, không phải 1;
log() trong C++ chỉ chấp nhận 1 đối mục; chỉ có C đúng)

Bài **161.**

Cho đoạn code sau:  
\#include &lt;cmath&gt;

\#include &lt;iomanip&gt;

\#include &lt;iostream&gt;

using namespace std;

int main(long double i)

{

   cout &lt;&lt; sizeof(bool) &lt;&lt; endl;

   cout &lt;&lt; sizeof(short) &lt;&lt; endl;

   cout &lt;&lt; sizeof(long int) &lt;&lt; endl;

   cout &lt;&lt; sizeof(double) &lt;&lt; endl;

   cout &lt;&lt; sizeof(long double) &lt;&lt; endl;

   cout &lt;&lt; sizeof(float);

   stringstream cin;

}

Output của chương trình là gì:

1.  

| 1   
      
 2    
      
 4    
      
 8    
      
 16   
      
 32   |
|-----|

1.  

| 1   
      
 2    
      
 8    
      
 4    
      
 16   
      
 4    |
|-----|

1.  

| 1   
      
 2    
      
 8    
      
 4    
      
 8    
      
 32   |
|-----|

1.  

| 1   
      
 2    
      
 8    
      
 8    
      
 16   
      
 4    |
|-----|

1.  

| 2   
      
 2    
      
 4    
      
 8    
      
 16   
      
 32   |
|-----|

Đáp án: D (chắc tự hiểu, hàm sizeof() để lấy độ lớn vùng bộ nhớ bị chiếm
dụng cho kiểu nhất định; tham khảo:
[*http://cpp.sh/9t3c*](http://cpp.sh/9t3c))

Bài **162.**

Hàm nào sau đây là chuẩn trong C++:

1.  isalnum()

2.  factor()

3.  toin()

4.  doubleto()

Đáp án: A (cái này tự hiểu khỏi giải thích)

Bài **163.**

Toán tử nào sau đây là có thể sử dụng với số dấu chấm động:

1.  ~

2.  %

3.  &lt;&lt;

4.  /

Đáp án: D (toán tử đầu tiên là toán tử đảo ngược bit, toán tử thứ 3 là
toán tử trích nhập không sử dụng cho kiểu double; cái thứ 2 chắc tự hiểu
tại sao)

Bài **164.**

Có bao nhiêu toán tử logic trong C++ (không tính các toán tử có cùng
chức năng nhưng khác cú pháp / ký hiệu):

1.  1

2.  2

3.  3

4.  4

Đáp án: C (khỏi giải thích, hoặc - và - phủ định)

Bài **165.**

Từ nào sau đây không phải từ khóa của C++:

1.  asm

2.  enum

3.  int

4.  void

5.  uint

Đáp án: E (không có giải thích)

Bài **166.**

Cho đoạn code sau:  
\#include &lt;iostream&gt;

using namespace std;

enum colour {

   green, red, blue, white, yellow, pink

};

int main()

{

   cout &lt;&lt; green&lt;&lt; red&lt;&lt; blue&lt;&lt; white&lt;&lt;
yellow&lt;&lt; pink;

   return 0;

}

Hỏi đoạn code trên khi compile sẽ cho output là gì:

1.  CE

2.  Lỗi thực thi

3.  012345

4.  123456

5.  Giá trị bất kỳ

Đáp án: C (các giá trị của một đối tượng liệt kê sẽ mang giá trị nguyên
tăng dần từ 0 nếu chưa được gán giá trị)

Bài **167.**

Truy xuất vào biến thành viên của một đối tượng có kiểu dữ liệu cấu trúc
cần sử dụng toán tử:

1.  “.”

2.  “::”

3.  “~&gt;”

4.  “\\”

Đáp án: A

Bài **168.**

Dòng nào sau đây là sai:

1.  std::string stream;

2.  std::cout &lt;&lt; stream++;  //stream là chuỗi

3.  scanf("%s",&stream);

4.  int x = &y; // y là giá trị nguyên

Đáp án: B (các câu còn lại có thể tự suy ra, câu cuối là khởi tạo biến
pointer (con trỏ) )

Bài **169.**

Toán tử nào sau đây không dùng để làm việc với con trỏ trong C++:

1.  new

2.  delete

3.  create

4.  this

Đáp án: C (trong C++ không có từ khóa nào là create)

**Bài 170**

Kết quả hiển thị ra màn hình của chương trình sau là gì :

\#include &lt;stdio.h&gt;

void main()

{

            int a,b ;

            a=100 ;

            b=56 ;

            printf(**“**%d**”**,(a&lt;B, ? a:B,;

}

A, 56

B, 100

C, CE

D, kết quả khác

Đáp án: A (vì kia là cách viết khác của câu lệnh if...else...)

**Bài 171**

Kết quả của chương trình sau:

\#include “stdio.h”

int main()

{

            int i;

            i=10;

            printf(“%o”,i);

}

A, 12

B, 10

C, 8

D, CE

Đáp án: A (vì chưa giải thích được :D,

**Bài 172**

Cho code

\#include &lt;stdio.h&gt;

int main()

{

            char c;

            int n;

            scanf(“%d%c”,&n,&C,;

            printf(“%3d%c”,n,C,;

}

Giả sử khi chạy chương trình ta gõ từ bản phím: “29h b”.

Kết quả in ra n và c tương ứng sẽ là:

A, 29b

B, 29h b

C, 29h

D,CE

Đáp án: C (vì %c ko lấy sau dấu cách)

**Bài 173**

Kết quả của chương trình sau là gì :

\#include &lt;stdio.h&gt;

float x\[\] = {63.2, -45.6, 70.1, 3.6, 14.5 };

int n=sizeof(x)/sizeof(float);

int main()

{           int i,j;

            floar c;

            for (i=0, j=n-1; i&lt;j; i++, j--);

            {

                        c=x\[i\];

                        x\[i\]=x\[j\];

                        x\[j\]=c;

            };

            for (i=0 ; i&lt;n ; i++)

            printf(“%8.2f ”,x\[i\]) ;

            return 0;

} 

A, 63.20, -45.60, 70.10, 3.60, 14.50.

B, 14.50, 3.60, 70.10, -45.60, 63.20.

C,  Kết quả khác.

D, 1 và 2.

Đáp án:A ( khởi tạo lồng)

**Bài 174**

Kí hiệu nào là con trỏ của phẩn tử thứ 3 của màng a có 4 kí tự:

A, \*(a+3);

B, \*(a+2);

C, a\[ \]+3;

D, \*(a+4);

**Bài 175**

Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

int main()

{

            struct diem;

                        {

                         float k;

                         float a;

                         float l;

                        }

            struct diem m;

            m.k = 8;

            m.a = 6.5;

            m.l = 6;

            printf(“%0.1f%0.1f%0.1f”, m.k, m.a, m.l);

}

A,   8.06.56.0

B,  86.56

C,  8.0000006.5000006.000000

D, CE

Đáp án D (vì khai báo phần stucture sai)

**Bài 176**

Chọn kết quả đúng cho chương trình sau:

\#include &lt;stdio.h&gt;

int main()

{

            struct sv

                        {

                         float d;

                         char ht\[10\];

                        };

            struct sv m, \*p;

            p=&m;

            (\*p).d=p-&gt;d=10;

            strcpy([m.ht](http://m.ht/),”Megumi”);

            printf(“%0.1f”,m.D,;

            printf(“%s”,[m.ht](http://m.ht/));

}

A, 10.000000Megumi

B, 10.0Megumi

C, 11Megumi

D, CE

Đáp án: B(suy luận như bình thường chắc chắn ra,hàm strcpy là hàm copy)

**Bài 177**

Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

int hoanvi(int \*px, int \*py)

{

            int z ;

            z=\*px;

            \*px=\*py ;

            \*py=z ;

}

void main()

{

            int a=15, b=21 ; hoanvi(a,B, ;

            printf (“%d %d”,a,B,;

}

A, 15 21

B, 21 15

C, CE

D, Kết quả khác.

Đáp án: B (hàm void trên có con trỏ sẽ hoán vị)

**Bài 178**

Nếu có các khai báo sau:

char msg\[10\];

char \*ptr;

char value;

Câu nào sau đây là đúng:

A, ptr=value

B, ptr=msg

C, Cả 2 đúng

D, Cả 2 sai

đáp án : B (vì biến con trỏ đầu tiên của char bằng với biến con trỏ của
phần tử đầu tiên của mảng)

**Câu 179:**

Cho các khai báo sau:

void \*tongquat;

int \*nguyen;

char \*kitu;

Phép gán nào là không hợp lệ:

A,  tongquat=nguyen

B, \*nguyen=\*tongquat

C,  kitu=(char)tongquat

D, tongquat=kitu

Đáp án: B (2 biến con trỏ có kiểu dữ liệu là int và void không gán được
cho nhau)

**Câu 180:** 

Cho biết kết quả của đoạn chương trình sau:

int p=4;

p=10+ ++p;

A, 14

B, 15

C, 16

D, CE

Đáp án : B(vì lệnh ++p được thực hiện trước lệnh 10+)

**Câu 181:**

Có các khai báo sau:

char tb, mang\[15\];

Trong các câu lệnh sau, câu nào đúng:

A, tb=”chào bạn”

B, gets(mang)

C, mang=”chaoban”

D, gets(tB,;

Đáp án: B (vì các câu lệnh còn lại sai)

**Câu 182:**

Phép cộng 1 con trỏ với một số nguyên sẽ là:

A, Một con trỏ có cùng kiểu.

B, Một số nguyên.

C, Cả hai kết quả đều đúng.

D, Cả hai kết quả đều sai.

Đáp án: A(cái này là lý thuyết)

**Câu 183**: Phép trừ 2 con trỏ có cùng kiểu sẽ là:

A, Một con trỏ có cùng kiểu.

B, Một số nguyên.

C, Kết quả khác.

D, Không thực hiện được.

Đáp án: B (lý thuyết)

**Câu 184**:

Khi khai báo mảng, ta khởi tạo luôn giá trị của mảng như sau:

int x\[3\]={4,2,6};

Nghĩa là:

A, x\[1\]=4, x\[2\]=2, x\[3\]=6

B, x\[0\]=4, x\[1\]=2, x\[2\]=6

C, Khai báo không đúng

D, Kết quả khác

Đáp án B (vì phần tử đầu tiên của mảng là phần tử có số thứ tự 0)

**Câu 185:** Khi biến con trỏ không chứa bất kì một địa chỉ nào thì giá
trị của nó sẽ là:

A, 0

B, NULL

C, Cả hai phương án trên đều đúng

D, Cả hai phương án trên đều sai

Đáp án : C (vì quy ước là như thế)

**Câu 186: **Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

int main()

{

            int x, \*p;

            x=3; x=6; p=&x;

            \*p=9; printf(“%d”,x);

            printf(“%d”,\*p); printf(“%d”,x);

}

A, 369

B, 696

C, 999

D, Kết quả khác.

Đáp án: C (vì biến p=&x sẽ biên soạn lại x, x=p)

**Câu 187:** 

Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

int change(int A,

{

            a=10;

            return a;

}

int main()

{

            int a=5;

            change(i);

            printf(“%d”,i);

}

A, 5

B, 10

C, 11

D, CE

Đáp án: A (vì biến a trong hàm change là biến cục bộ)

**Câu 188: **

Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

int change(int \*A,

{

            \*a=18;

            return \*a;

}

void main()

{

            int i=9;

            change(&i);

            printf(“%d”,i);

}

A, 9

B, 10

C, 18

D, CE

Đáp án: C ( vì trong hàm change truyền vào tham số một con trỏ là 18)

**Câu 189:**

Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

int main()

{

            printf(“%d”,3&lt;2||6);

}

A, false

B, 0

C, 1

D, CE

Đáp án: C (vì 3&lt;2 hoặc 6 thay cho 1 câu lệnh if và 6 luôn luôn đúng
nên sẽ trả về là true, ép kiểu true là %d thì sẽ in ra 1)

**Câu 190:**

Cái gì quyết định kích thước của vùng nhớ được cấp phát cho các biến:

A,      Tên biến.

**B,**     ***Kiểu dữ liệu của biến.***

C,     Giá trị của biến.

D,     Tất cả đều đúng.

**Câu 83:** Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

void main()

{

            int i,k;

            for(i=1; ; i++) k=5;

            printf(“%d”,i);

};

A,      0.

B,     5.

**C,**     ***Vòng lặp vô hạn.***

D,     Kết quả khác.

**Câu 191:** Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

void main()

{

            int i=1, k=0;

            for (; i&lt;5; i++) k++;

            printf(“%d”,k);

}

A,      0.

**B,**     ***4.***

C,     5.

D,     Vòng lặp vô hạn.

**Câu 192:** Lệnh nào trong các lệnh sau cho phép nhảy ra khỏi vòng lặp
đến vị trí bất kì mong muốn:

A,      break;

B,     continue;

**C,**     ***goto;***

D,     Không có phương án nào.

**Câu 193:**Trong các hàm sau, hàm nào không định dạng để in một kí tự
ra màn hình:

A,      puts();

B,     printf();

**C,**     ***putchar();***

D,     2 và 3.

**Câu 194:** Khi nhập vào đòng văn bản: “Chao Cac Ban”. Kết quả của
chương trình sau là gì:

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

int main()

{

            clrscr();

            char str\[80\];

            fflush(stdin);

            scanf(“%s”,str);

            cprintf(“Dong van ban vua nhap la: %s”,str);

            getch();

            return 0;

};

A,      “Chao Cac Ban”.

B,     “Chao Cac”.

**C,**     **“*Chao”.***

D,     Không hiện kết quả gì.

**Câu 195:** Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

void main()

{

            clrscr();

            int i;

            for (i=1; i&lt;=24; i++);

            printf(“\\n%d”,i);

            getch();

            return;

};

A,      In ra màn hình các số từ 1 đến 24.

B,     Lỗi khi xây dựng chương trình.

**C,**     ***Kết quả khác.***

D,     In ra màn hình các số từ 1 đến 24, mỗi số một dòng.

**Câu 196:** Lệnh fflush(stdin) dùng để làm gì:

A,      Đọc kí tự từ bàn phím.

**B,**     ***Xóa sạch bộ nhớ đệm.***

C,     Xóa bộ nhớ đệm.

D,     Kết quả khác.

**Câu 197:** Kết quả của đoạn chương trình sau là gì:

char c;

int n;

scanf(“%d%c”,&n,&C);

Nếu gõ vào : ”10 T”.

**A,**      ***n=10, c=’ ‘.***

B,     n=10, c=’T’.

C,     Lỗi khi xây dựng chương trình.

D,     Kết quả khác.

**Câu 198:** Kết quả in ra màn hình của chương trình sau:

\#include &lt;stdio.h&gt;

void main()

{

            int i=100;

            printf(“%c”,i);

};

**A,**      ***“d”.***

B,     “D”.

C,     “100”.

D,     Kết quả khác.

**Câu 199:** Hằng có thể được định nghĩa theo cách nào:

A,      \#define &lt;indentifier&gt; string

B,     const tên\_kiểu tên\_biến\_hằng = giá trị;

C,     Không có cách định nghĩa chung.

**D,**     ***1 và 2.***

**Câu 200: **Hàm gotoxy(int x, int y) là hàm:

A,      Đặt con trỏ tại dòng x, cột y.

**B,**     ***Đặt con trỏ tại cột x, dòng y.***

C,     Lưu dữ tọa độ của con trỏ màn hình cột x, dòng y.

D,     Lưu dữ tọa độ của con trỏ màn hình dòng x, cột y.

**Câu 201 :** Kết quả của chương trình sau là gì :

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

float x\[\] = {63.2, -45.6, 70.1, 3.6, 14.5 };

int n=sizeof(x)/sizeof(float);

void main()

{

            clrscr();

            int i,j;

            floar c;

            for (i=0, j=n-1; i&lt;j; i++, j--);

            {

                        c=x\[i\];

                        x\[i\]=x\[j\];

                        x\[j\]=c;

            };

            printf(“\\nDay ket qua la: \\n”) ;

            for (i=0 ; i&lt;n ; i++)

            printf(“%8.2f ”,x\[i\]) ;

            getch() ;

            return ;

} ;

**A,**      ***Dãy kết quả là: 63.20, -45.60, 70.10, 3.60, 14.50.***

B,     Dãy kết quả là : 14.50, 3.60, 70.10, -45.60, 63.20.

C,     Kết quả khác.

D,     1 và 2.

**Câu 202 :** Kết quả của chương trình sau là gì :

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

\#include &lt;ctype.h&gt;

\#define EOL ‘\\n’

void main()

{

            clrscr();

            char chu\[80\];

            int tong,dem;

            for (dem=0; dem&lt;tong; dem++);

            tong=dem;

            for (dem=0; dem&lt;tong; ++dem)

            putchar(toupper(chu\[dem\]));

            getch();

            return;

};

A,      Nhập vào một kí tự thường, sau đó chuyển sang chữ hoa rồi in ra
màn hình.

B,     Nhập một kí tự hoa, sau đó chuyển sang chữ thường rồi in ra màn
hình.

C,     1 và 2.

**D,**     ***Kết quả khác.***

**Câu 203: **Phép toán % có ý nghĩa gì:

A,      Đổi dấu một số thực hoặc một số nguyên.

B,     Chia hai số thực hoặc nguyên.

**C,**     ***Lấy phần dư của phép chia hai số nguyên.***

D,     1 và 2.

**Câu 205:** Hàm clrscr() là hàm gì:

A,      Là hàm xóa toàn bộ màn hình, sau khi xóa, con trỏ sẽ ở bên trái
màn hình.

B,     Dùng để xóa sạch bộ nhớ đệm bàn phím.

C,     Là hàm xóa kí tự nằm bên trái con trỏ.

D,     Là hàm xóa kí tự nằm bên phải con trỏ.

**Câu 206**: Kết quả của đoạn chương trình sau là gì:

char c;

int n;

scanf(“%c%d”,&n,&C);

Nếu gõ vào: “r 45”.

A,      n=45, c=’ ‘.

B,     n=45, c=’r’.

C,     Lỗi khi xây dựng chương trình.

**D,**     ***Kết quả khác*.**

**Câu 207: **Hàm scanf(“%\[^\\n\]”,str); tương với lệnh nào sau đây:

A,      getch();

B,     getche();

C,     macro getchar();

**D,**     ***gets(str);***

**Câu 208: **Cho đoạn chương trình sau:

\#include &lt;stdio.h&gt;

\#include &lt;conio.h&gt;

void main()

{

            char c;

            clrscr();

            do c=getchar();

while (c!=’\*’);

getch();

};

Yêu cầu của đoạn chương trình trên là:

**A,**      ***Nhập vào 1 kí tự cho đến khi gặp kí tự ‘\*’.***

B,     Nhập vào các kí tự cho tới khi gặp kí tự ‘\*’.

C,     Nhập các kí tự ‘\*’.

D,     Lỗi khi xây dựng chương trình.

**Câu 209:** Kết quả của chương trình sau là gì:

\#include &lt;stdio.h&gt;

void main()

{

            printf(“%d”,3&lt;7&&8&gt;6);

};

**A,**      ***1.***

B,     0.

C,     true.

D,     Kết quả khác.

**Câu 210:**Toán tử “++n” được hiểu:

A,      Giá trị n giảm đi sau khi giá trị của nó được sử dụng.

B,     Giá trị n giảm đi trước khi giá trị của nó được sử dụng.

C,     Giá trị của n được tăng sau khi giá trị của nó được sử dụng.

**D,**     ***Giá trị của n được tăng lên trước khi giá trị của nó được
sử dụng.***

**Câu 211: **Toán tử “n--“ được hiểu:

**A,**      ***Giá trị n giảm đi sau khi giá trị của nó được sử dụng.***

B,     Giá trị n giảm đi trước khi giá trị của nó được sử dụng.

C,     Giá trị của n được tăng sau khi giá trị của nó được sử dụng.

D,     Giá trị của n được tăng lên trước khi giá trị của nó được sử
dụng.

**Câu 212:**Phép toán 1 ngôi nào dùng để xác định giá trị ở địa chỉ con
trỏ trỏ tới:

A,      !;

B,     &;

C,     *\*;*

D,     Kết quả khác.

**Câu 213:** Phép trừ 1 con trỏ với một số nguyên sẽ là:

A,      Một số nguyên.

**B,**     ***Một con trỏ cùng kiểu.***

C,     Cả hai kết quả trên đều đúng.

D,     Cả hai kết quả trên đều sai.

**Câu 214:** Đâu là kết quả của đoạn mã sau:

struct Employee

{          char Code\[\], name\[\];

            long Salary;

};

Employee e1= { “E089”, “Hoang so”, 12000}, e2=e1;

printf(“%ld”,el.Salary+e2 -&gt; Salary);

A,      24000.

B,     12000.

**C,**     ***Đoạn mã bị lỗi.***

D,     Kết quả khác.

**Câu 215:**Đâu là kết quả của câu lệnh sau:

printf(“%2f”,123.5678908);

A,      123.56

B,     123.567890

C,     123.567

**D,**     ***Kết quả khác.           *            (123.567891).**

**Câu 216:**

char S\[20\]=”aaaaaea”;

char\* p=strstr(S,”e”);

Nếu địa chỉ của S là 1000, thì giá trị của p là bao nhiêu:

A,      1000.

**B,**     ***1005.***

C,     1003.

D,     Kết quả khác.

**Bài 217.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

double dis(double x, double y, double z, double t) {

return sqrt((x – z)\*(x – z) + (y – t)\*(y – x));

int main() {

double x, y, z, t;

scanf("%f %f %f %f", &x, &t, &z, &y);

printf("%.2f", dis(x, y, z, t));

return 0;

}

Với intput 5 0 0 12, chương trình sẽ in ra cái gì?

A, 7.00

B, 13.00

C, lỗi CE

D, 10.44

Đáp án: C, lỗi CE.

Do hàm sqrt nằm trong thư viện math.h – một thư viện chưa khai báo.

**Bài 218.** Cho đoạn code :

\#include &lt;stdio.h&gt;

int main() {

int k;

string n;

scanf("%s %f", &n, &k);

for(int i = 0; i &lt; k; i--) printf(“%s\\n”, n);

return 0;

}

Cần phải sửa mấy dòng, để chương trình có thể chạy và dừng trong thời
gian 2s?

A, 0

B, 1

C, 2

D, 3

Đáp án: D. 3

Cần phải sửa dòng:

- string n; vì ngôn ngữ C không có kiểu biến string

- scanf("%s %f", &n, &k); vì kiểu biến của k là số nguyên, không phải số
thực

- for(int i = 0; i &lt; k; i--) printf("%s\\n", n);

vì trong vòng for, i chạy từ 0 đến k, nhưng sau mỗi vòng lặp, i lại trừ
1. Do đó, chương trình sẽ rơi vào vòng lặp vô hạn.

**Bài 219.** Cho đoạn code

\#include &lt;stdio.h&gt;

void cout();

int main() {

for(int i = 0; i &lt; 100; i++) cout();

return 0;

}

void cout() {

printf("Codefun is not fun");

}

Do quá bực mình vì số lượng bài sai test, bạn Futymy muốn viết 1 chương
trình, in ra dòng “Codefun is not fun” 100 lần, mỗi lần trên 1 dòng. Vậy
nếu submit code này lên Codefun, Codefun sẽ báo về như thế nào?

A, CE

B, WA

C, AC

D, TLE

Đáp án : B, WA

Khi in ra “Codefun is not fun”, bạn Futymy đã quên xuống dòng. Do đó,
khi chạy, chương trình in ra “Codefun is not fun” 100 lần không xuống
dòng, và máy sẽ báo WA.

**Bài 220.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int prime(int i) {

if(n &lt; 2) return 0;

else

{

int d = sqrt(i) + 1, p = 1;

for(int j = 2, j &lt; d; j++)

{

if(i % j == 0)

{

p = 0;

break

}

}

return p;

}

}

int main() {  
int n, k;

scanf(“%d %d”, &n, &k);

for(int i = 0; i &lt; n \* k; i++)

{

printf("%d ", prime(i));

}

return 0;

}

Với input 2 3, chương trình sẽ in ra cái gì?

A, lỗi CE

B, 0 0 1 0 1 0 1

C, 0010101

D, 0101010

Đáp án: A. lỗi CE

Dòng lệnh break thiếu dấu “;”.

**Bài 221.** Cho đoạn code

\#include &lt;stdio.h&gt;

int main() {

int x = 2;

x = x++\*2;

printf("%d", x);

return 0;

}

Chương trình sẽ in ra cái gì?

A, CE

B, TLE

C, 6

D, 4

Đáp án: D, 4

"++" có nghĩa là tăng thêm 1. Do thứ tự ưu tiên giữa các phép toán, máy
sẽ ưu tiên thực hiện phép nhân trước. Khi chạy xong phép nhân, máy sẽ
thấy chương trình không còn gì, và in ra kết quả là x\*2 = 2\*2 = 4.

**Bài 222.** Cho đoạn code

\#include &lt;stdio.h&gt;

int main() {

for(int i = 1; i != 0; i--)

{

printf("%d", i);

i -= 1;

}

return 0;

}

Khi chạy, chương trình trên sẽ in ra cái gì?

A, TLE

B, 1

C, CE

D, Không phải 3 phương án trên

Đáp án: A, TLE

Ở vòng lặp đầu tiên, i = 1 thỏa mãn điều kiện i ≠ 0. Do đó, chương trình
sẽ chạy, in ra i. Sau đó i lại trừ 1, khi kết thúc vòng lặp thì i = 0.
Và trước khi bắt đầu vòng lặp thứ 2, máy sẽ trừ 1 ở i do yêu cầu ở vòng
for ("... = 0; i-- "). Như vậy, i = -1 và thỏa mãn điều kiện i ≠ 0. Máy
tiếp tục chạy, i càng giảm. Nói tóm lại, chương trình rơi vào vòng lặp
vô hạn.

**Bài 223.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int n;

scanf("%d", &n);

while(n)

{

printf("%d ", n);

n -= 1;

}

return 0;

}

Với input 5, chương trình sẽ in ra cái gì?

A, 5 4 3 2 1

B, 54321

C, lỗi CE

D, 5 4 3 2 1 0

Đáp án: A, 5 4 3 2 1

Hàm while này có 1 chỗ đặc biệt, là dùng biến làm điều kiện bool. Ở đây,
nói cho chính xác hơn thì while(x), nếu x ≠ 0 thì đoạn code trong vòng
while sẽ được thực thi.

**Bài 224.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

for(1;2;3) printf("1");

return 0;

}

Khi chạy chương trình trên, chương trình sẽ in ra cái gì?

A, lỗi CE

B, lỗi TLE

C, 1

D, Không phải 3 phương án trên

Đáp án: B, lỗi TLE

Do khai báo trong vòng for là 3 số nguyên khác 0, máy sẽ hiểu những điều
kiện trong vòng for luôn return true, và chương trình rơi vào vòng lặp
vô hạn.

**Bài 225.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

char a = 0;

for(int i = -1; i &lt; a; i++) printf("%c", a);

return 0;

}

Khi chạy chương trình trên, máy sẽ in ra cái gì?

A, Không gì cả

B, 1 số 0

C, 48 số 0

D, lỗi CE

Đáp án : A, Không gì cả

Ký tự a ở đây không được khai là kí tự 0, mà là ký tự có giá trị ASCII
là 0. Hay nói cách khác, a chính là ký tự NULL. Do đó, chương trình vẫn
sẽ chạy bình thường, nhưng không in ra gì cả.

**Bài 226.** Cho đoạn code sau đây:

\#include &lt;stdio.h&gt;

int main() {  
int a;

scanf("%d", &a);

for(int i = -1; i &lt; a; i++)

{

if(i = 0) printf("%d", a);

if(i &gt; 0) break;

}

return 0;

}

Với input 315, máy sẽ in ra cái gì?

A, 315 lần số 315

B, 1 lần số 315

C, 2 lần số 315

D, Không phải 3 phương án trên

Đáp án: D, Không phải 3 phương án trên

Do câu lệnh if(i = 0)là 1 câu lệnh gán i = 0, nên câu lệnh này luôn thực
hiện được, và dòng if luôn trả về true. Như vậy, trong mỗi vòng lặp, i
luôn được gán bằng 0. Hơn nữa, do a = 315 &gt; 0, nên điều kiện vòng for
luôn thỏa mãn, và trước câu lệnh if(i &gt; 0) break; thì i đã được gán
bằng 0 nên dòng if này luôn trả về false, câu lệnh break là vô nghĩa.

Nói tóm lại, chương trình này mắc lỗi TLE.

**Bài 227.** Cho đoạn code sau:

1.\#include &lt;stdio.h&gt;

2.

3.int main() {

4. int n;

5. signed char m;

6. scanf("%i", &n);

7. m = n;

8. for(int i = 0; i &gt; m; i--)

9. printf("%d", m);

10. return 0;

11.}

Với input 128, chương trình KHÔNG phải sửa (những) dòng nào để code có
thể in ra 128 lần số 128 viết liền?

A, 5, 6, 7, 8

B, 6, 7, 8, 9

C, 7, 8, 9, 5

D, 8, 9, 5, 6

Đáp án: A, 5, 6, 7, 8

Do %i và %d (dòng 6) đều có thể dùng với kiểu biến int nên n vẫn nhận
giá trị 128 như bình thường. Tuy nhiên, do signed char (dòng 5) lại nhận
giá trị âm nên m = -128 (dòng 7). Lúc này, vòng for (dòng 8) vẫn sẽ chạy
như bình thường, trong đó i chạy từ 0 đến -128. Nhưng nếu để thế này thì
dòng 9 sẽ in ra m = -128, hay nói cách khác, sẽ in ra-128-128-128…. Do
đó, phải sửa dòng 9 thành printf("%d", -m);

**Bài 228.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

float a = 0.1;

if(a == 0.1) printf("Codefun is not fun");

else printf("Codefun is fun");

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, Codefun is fun

B, Codefun is not fun

C, TLE

D, CE

Đáp án: A, Codefun is fun

Do trong C, tùy theo từng compiler, float được định nghĩa là có độ lớn
là 32 bit. Nhưng 0.1 thì lại có biểu diễn nhị phân vô hạn tuần hoàn, nên
trong **Thư viện tiêu chuẩn về dấu chấm động IEEE-754**, người ta định
nghĩa giá trị của 0.1 lại là 0.100000001490116119384765625. Do đó, có sự
chênh lệch giữa giá trị của a = 0.1 và 0.1, câu lệnh điều kiện của dòng
if sẽ trả về false, và máy in ra "Codefun is fun".

**Bài 229.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

float a = 0.1;

if(a == 0.1f) printf("Codefun is not fun");

else printf("Codefun is fun");

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, Codefun is fun

B, Codefun is not fun

C, TLE

D, CE

Đáp án: B, Codefun is not fun

Nếu giải thích như bài trên, ta sẽ thấy đáng nhẽ phải in ra "Codefun is
fun". Tuy nhiên, câu lệnh điều kiện dòng if lại là if(a == 0.1f), trong
đó, 0.1f có nghĩa là 0.1f ở dạng dấu chấm động, hay nói cách khác là ở
dạng IEEE-754. Do đó, câu lệnh này trả về true, và máy in ra "Codefun is
not fun".

**Bài 230.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

float a = 'a';

printf("%f", a);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, 97.000000

B, lỗi CE

C, a

D, a.0000000

Đáp án: A, 97.000000

Do giá trị ASCII của 'a' là 97, biến a nhận giá trị 97 theo kiểu dấu
chấm động, và lưu giá trị 97.000000

**Bài 231.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

printf("Codefun %s fun", "is %S", "not");

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, Codefun is not fun

B, Code is %s fun

C, Code not fun

D, lỗi CE

Đáp án, B, Codefun is %s fun

Trong câu lệnh printf, ngoặc kép đầu tiên được coi là phần template
(khuôn mẫu) được in ra, các phần sau chỉ có tác dụng thêm vào và bổ sung
phần trước, chứ không hề có ý nghĩa như ngoặc kép đầu tiên

Ở ngoặc kép đầu tiên, chỉ có 1 cụm "%s", nên máy sẽ hiểu là chỉ đọc 1
chuỗi sau đấy. Còn ở ngoặc kép thứ hai, cụm "%s" không được hiểu là thêm
vào chuỗi sau đấy.

Nói tóm lại, máy chưa bao giờ đọc chuỗi "not" và chỉ in ra " Codefun is
%s fun".

**Bài 232.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main(void) {

const int a = 5;

a = 10;

printf("%d", a);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, 10

B, 5

C, 105

D, lỗi CE

Đáp án: D, lỗi CE

"a" đã được định nghĩa là 5, nên a trở thành kiểu biến chỉ đọc
(read-only variable). Khi gặp dòng lệnh khai báo a = 10; , máy sẽ không
hiểu và báo lỗi CE.

**Bài 233.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a = 010;

printf("%d", a);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, 8

B, lỗi CE

C, 10

D, 010

Đáp án: A, 8

Ở đây, do có số 0 ở đầu, m lại hiểu là đây là mã bát phân (cơ số 8).
Trong cơ số 8, 010 chính là giá trị 8. Do đó, máy sẽ hiểu a = 8 và in ra
8.

**Bài 234.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main()

{

int j = 10;

[printf](http://www.opengroup.org/onlinepubs/009695399/functions/printf.html)("%d",
j++);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, 10

B, 11

C, lỗi CE

D, 0

Đáp án: A, 10

Compiler sẽ đọc từ trái sang phải, từ trên xuống dưới. Do đó, khi đọc
[printf](http://www.opengroup.org/onlinepubs/009695399/functions/printf.html)("%d",
j++); , máy sẽ hiểu là in ra j trước, r mới cộng 1 vào j. Máy in ra giá
trị ban đầu của j – 10.

**Bài 235.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

void print(int i)

{

if (i &gt; 10)

return i;

printf("%d ", i);

print((i++, i));

}

int main()

{

print(1);

}

Với input 10, chương trình trên sẽ in ra cái gì?

A, lỗi TLE

B, lỗi CE

C, lỗi MLE

D, 1 2 3 4 5 6 7 8 9 10

Đáp án: D, 1 2 3 4 5 6 7 8 9 10

Hàm print là một hàm đệ quy. Do cấu trúc của hàm print, nếu i lớn hơn 10
thì hàm sẽ tự trả về, không đệ quy và chương trình kết thúc.

Sau khi in số i, chương trình thực hiện lệnh print((i++, i));. Trong đó,
(i++, i) có nghĩa là i được cộng 1 rồi áp giá trị đó vào hàm. Như vậy,
sau mỗi lần gọi hàm, i lại tăng thêm 1. Chương trình tiếp tục đệ quy như
vậy từ 1 đến 10

**Bài 236.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int n;

scanf("%d", n);

for(int i = 0; i &lt; n, i--) printf("%d ", n);

return 0;

}

Với input 5, chương trình trên sẽ in ra cái gì?

A, 0 1 2 3 4 5

B, 0 1 2 3 4

C, lỗi TLE

D, lỗi CE

Đáp án: D, lỗi CE

Chương trình trên mắc 2 lỗi cơ bản ở vòng lặp for:

- i chạy từ 0 đến n, nhưng sau mỗi vòng lặp, i lại trừ 1 nên câu điều
kiện này luôn trả về true, và chương trình rơi vào vòng lặp vô hạn, gây
ra lỗi TLE.

- cú pháp trong câu lệnh điều kiện của vòng for bị sai chính tả. Cụ thể
for(int i = 0; i &lt; n, i--)phải thay dấu "," bằng dấu ";". Điều này
gây ra lỗi CE.

Tuy nhiên, do thứ tự xử lý của máy khi chạy code là compile trước rồi
mới chạy. Hay nói cách khác, nếu như có lỗi CE và lỗi TLE, lỗi CE sẽ
được báo trước.

**Bài 237.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

\#define a 7+134

int main() {

int y = a\*a\*a;

printf("%d", y);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, 2303221

B, 2017

C, lỗi CE

D, Không phải 3 phương án trên.

Đáp án: B, 2017

Câu \#define a 7+134 lại định nghĩa a chính là 7 + 134 mà không hề tính
toán cụ thể giá trị đó. Vậy nên, nó chỉ copy y nguyên, chỗ nào có a thì
thay vào bằng 7 + 134 rồi máy mới bắt đầu compile. Nên, khi thay vào,
máy sẽ hiểu như sau: y = a \* a \* a = 7 + 134\*7 + 134\*7 + 134 = 2017

Do đó, máy sẽ in ra 2017.

**Bài 238.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

printf("Hello World %d", printf("Hello World");

return 0;

}

Hỏi chương trình trên in ra cái gì?

A, lỗi CE

B, lỗi TLE

C, Hello World

D, Hello World 11

Đáp án: D, Hello World 11

Như bao hàm khác, hàm printf khi thực thi cũng trả về 1 số nguyên. Giá
trị của số nguyên này chính là số ký tự, tính cả dấu cách, của chuỗi mà
hàm printf đã in ra. Do đó, printf("Hello World") trả về 11, và máy in
ra Hello World 11.

**Bài 239.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int i = 1;

for(;i &lt;= 5;)

{

printf("%d ", i);

i++;

}

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, 1 2 3 4 5

B, lỗi TLE

C, 1 2 3 4

D, lỗi CE

Đáp án : A, 1 2 3 4 5

Do mỗi phần trong vòng for đều là tùy chọn, có thể không viết. Ở đây, có
i được khai báo là 1, điều kiện vòng for là i ≤ 5 và sau mỗi vòng lặp, i
được cộng 1. Như vậy, máy có thể chạy bình thường mà không báo lỗi.

**Bài 240.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int n;

scanf("%d", &n);

for(int i = 0; i &lt; n; i++);

printf("%d ", n);

return 0;

}

Với input 5, chương trình trên sẽ in ra cái gì?

A, 0 1 2 3 4

B, lỗi CE

C, 5

D, 5 5 5 5 5

Đáp án: C, 5

Không như những vòng lặp khác, ta để ý thấy vòng for lại kết thúc bằng
dấu chấm phẩy. Điều đó có nghĩa là vòng for này được coi như một vòng
for độc lập, không có phần thân. Do đó, câu lệnh printf("%d", n); chỉ
được thực thi 1 lần duy nhất.

**Bài 241.** Cho đoạn code sau:  
\#include &lt;stdio.h&gt;

int main() {

int a\[\] = {1, 2, 3, 4, 5, 6, 7, 8, 9};

for(int i = 0; i &lt; 9; i++)

printf("%d ", -i\[a\]);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, -1 -2 -3 -4 -5 -6 -7 -8 -9

B, 1 2 3 4 5 6 7 8 9

C, lỗi CE

D, lỗi TLE

Đáp án: A, -1 -2 -3 -4 -5 -6 -7 -8 -9

Trong C, máy sẽ hiểu code như sau:

i\[a\] = \*(i + a) = \*(a + i) = a\[i\]

Dễ thấy chương trình sẽ in ra kết quả như phương án A.

**Bài 242.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

\#include &lt;string.h&gt;

int main() {

char str1\[19\] = "Codefun is not fun.";

char str2\[19\] = "Codefun is fun.";

strcpy(str2, str1);

printf("%s %s", str1, str2);

return 0;

}

Chương trình trên in ra cái gì?

A, Codefun is not fun. Codefun is not fun.

B, Codefun is not fun. Codefun is fun.

C, Codefun is fun. Codefun is not fun.

D, Codefun is fun. Codefun is fun.

Đáp án: A, Codefun is not fun. Codefun is not fun.

Hàm strcpy chỉ đơn giản là copy str1 sang str 2.

**Bài 243.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

char a\[10\] = "Codefun is not";

char b\[\] = " fun.";

printf("%s%s", a, b);

return 0;

}

Chương trình trên in ra cái gì?

A, Codefun is fun.

B, Codefun is not fun.

C, lỗi CE

D, Không phải 3 phương án trên

Đáp án: A, Codefun is fun.

Mặc dù chuỗi a được khai báo là "Codefun is not", nhưng kích cỡ của a
lại là 10. Hay nói cách khác, a chỉ nhận 10 ký tự đầu tiên là "Codefun
is".

**Bài 244.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

static int a\[5\];

int n = 3;

a\[++n\] = ++n;

for(n = 0; n &lt; 5; n++) printf("%d ", a\[i\]);

return 0;

}

Chương trình trên in ra cái gì?

A, 0 2 0 0 0

b, 1 0 0 0 0

C, 0 1 0 0 0

D, 0 0 2 0 0

Đáp án: D, 0 0 2 0 0

Ta thấy, việc ++n được ưu tiên nhất. Máy sẽ quét xem câu lệnh đó có bao
nhiêu ký tự "++n" và thực hiện chúng trước. Về cơ bản, máy sẽ tính là n
= 2 trước, rồi mới gán vào hàng.

Hay nói cách khác, máy đã thực thi lệnh a\[2\] = 2;

**Bài 245.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a\[10\] = {1, 2, 3};

for(int i = 0; i &lt; sizeof(a)/sizeof(int); i++)

printf("%d ", \*(i + a));

return 0;

}

Chương trình trên in ra cái gì?

A, 1 2 3 4 5 6 7 8 9 10

B, 1 2 3 0 0 0 0 0 0 0

C, 1 3 5 4 5 6 7 8 9 10

D, lỗi CE

Đáp án: B, 1 2 3 0 0 0 0 0 0 0

Ở đây \*(i + a) có nghĩa truy cập vào phần tử thứ i của mảng a.

**Bài 246.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a\[3\] = {2, 3, 5};

printf("%d%d", \*(a + 2)\*\*a\*\*a, \*(a + 1)\*\*(a + 1)\*\*a - (\*(a +
2) - \*(a + 1))/ \*a);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, 2017

B, 2016

C, lỗi CE

D, lỗi MLE

Đáp án: A, 2017

Ta đã biết \*(a + i) có nghĩa là phần tử thứ i của a, hay nói cách khác
là a\[i\]. Khi ta thay vào biểu thức đầu tiên, ta nhận được như sau:

\*(a + 2)\*\*a\*\*a = a\[2\]\*a\[0\]\*a\[0\] = 5\*2\*2 = 20.

Tương tự, ta cũng có

\*(a + 1)\*\*(a + 1)\*\*a - (\*(a + 2) - \*(a + 1))/ \*a

= a\[1\] \* a\[1\] \* a\[0\] – (a\[2\] – a\[1\])/a\[0\] = 3\*3\*2 – (5 –
3)/2 = 17

Do đó, máy in ra 2017

**Bài 247.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

for(unsigned int i = 0; i &lt; 256; i++)

printf("%u", i);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, lỗi TLE

B, lỗi CE

C, 0 1 2 3 4 5 6 … 255

D, 0 1 2 3 4 5 6 … 256

Đáp án: A, lỗi TLE

Biến a được khai báo là unsigned int, có khoảng giá trị từ 0 đến 255,
nên khi a vượt quá 255 thì giá trị của a sẽ quay lại từ đầu.

Cơ bản mà nói, chương trình sẽ chạy như sau. Đầu tiên, như mọi khi, nó
sẽ in 0 1 2 3 4… 255 như bình thường. Khi in xong 255, a sẽ được cộng 1,
thành 256. Tuy nhiên, do kiểu của a là unsigned int nên khi nhận giá trị
256, a tự động nhảy về 0. Câu lệnh điều kiện của vòng for trả về true và
cả vòng lặp lại bắt đầu lại từ đầu.

Do đó, chương trình này bị lỗi TLE

**Bài 248.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int p = 1;

if(p-- == 1) printf("Codefun is fun");

else printf("Codefun is not fun");

return 0;

}

Chương trình trên in ra cái gì?

A, Codefun is fun

B, Codefun is not fun

C, CE

D, Không in ra gì cả

Đáp án: A, Codefun is fun

Dù có câu lệnh p--==0, nhưng khi chạy câu lệnh điều kiện của if, máy vẫn
sẽ coi như p = 1, chỉ khi sau khi thực thi xong thì máy mới trừ 1 ở p.
Do đó, câu lệnh điều kiện trả về TRUE, và máy in ra "Codefun is fun".

**Bài 249.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a = 2017;

if(a == 2017)

{

printf("Hello");

break;

printf(" World!");

}

else printf("Hi");

return 0;

}

Chương trình trên in ra cái gì?

A, Hello World!

B, Hello

C, Hi

D, lỗi CE

Đáp án: D, lỗi CE

Do dòng lệnh break chỉ được phép sử dụng với những câu lệnh switch và
những vòng lặp for hoặc while, nên khi dùng để dừng đoạn code trong if,
máy sẽ báo lỗi: error: break statement not within loop or switch.

**Bài 250.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

if((2017 && -2017) || (2018 && -2018))

{

printf("Codefun is fun");

}

else

{

printf("Codefun isn't fun");

}

return 0;

}

Chương trình trên in ra cái gì?

A, Codefun isn't fun

B, Codefun is fun

C, lỗi CE

D, Không in ra gì cả

Đáp án: B. Codefun is fun

Do mọi số nguyên không phải số 0 đều được coi là true, câu lệnh điều
kiện của if sẽ được thực thi như sau:

if((2017 && -2017) || (2018 && -2018))

= if((1) || (1))

= if(1)

Vậy nên, chương trình sẽ in ra "Codefun is fun".

**Bài 251.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int i = 1;

if(i)

printf("Futymy");

printf("Haise");

else

printf("Megumi");

printf("BHĐ");

return 0;

}

Chương trình trên bị lỗi gì?

A, CE

B, TLE

C, MLE

D, Không bị lỗi

Đáp án: A, CE

Do dòng if được viết không kèm dấu ngoặc kép, máy sẽ hiểu là khối lệnh
nằm trong dòng if chỉ là 1 dòng printf("Futymy");. Khi đó, câu lệnh

printf("Haise"); được coi như 1 câu lệnh độc lập, không nằm trong dòng
if. Như vậy, máy sẽ báo lỗi về câu lệnh else phía sau, do không có bất
kỳ dòng if nào phía trước.

Cụ thể, máy sẽ báo lỗi CE : error: 'else' without previous 'if'.

**Bài 252.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a = 5;

if(a == 10);

printf("Hello");

printf("World");

return 0;

}

Chương trình trên in ra cái gì?

A, World

B, Lỗi CE

C, Không in ra cái gì

D, HelloWorld

Đáp án: D, HelloWorld

Để ý thấy sau câu lệnh if có dấu chấm phẩy, nên câu lệnh
printf("Hello"); được coi là câu lệnh độc lập, không liên quan với câu
lệnh if trước đó. Do đó, máy sẽ chạy bình thường và in ra HelloWorld.

**Bài 253.** Cho đoạn code sau:

1.\#include &lt;stdio.h&gt;

2.

3.int main() {

4. int a = 1;

5. for(;a&lt;=5;++a)

6. {

7. printf("%d", a--);

8. }

9. while(!a)

10. {

11. printf("%d", a--);

12. if(a == 100) break;

13. }

14. return 0;

15.}

Chương trình trên bị lỗi TLE ở dòng nào?

A, Dòng 5

B, Dòng 7

C, Dòng 9

D, Dòng 11

Đáp án: B, Dòng 7

Sau mỗi vòng lặp, a lại trừ 1. Nhưng trước khi bắt đầu vòng lặp mới, a
lại cộng 1. Như vậy, với mỗi vòng lặp, a đều không thay đổi. Ban đầu, a
= 1 nên điều kiện a &lt; 5 thỏa mãn, và do a luôn không thay đổi trong
mỗi vòng lặp nên câu lệnh này luôn trả về true. Do đó, chương trình bị
TLE.

**Bài 254.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a = 0;

while(!a)

{

if(a == 10) break;

printf("%d", a++);

}

return 0;

}

Chương trình trên in ra cái gì?

A, 0 1 2 3 4 5 6 7 8 9

B, 0

C, lỗi CE

D, lỗi TLE

Đáp án: B, 0

Do câu lệnh của vòng while tương đối đặc biệt - !a. Bình thường, nếu để
a không thì với mọi số nguyên a khác 0 nó sẽ trả về TRUE. Tuy nhiên, dấu
"!" cũng là toán tử logic NOT, có nghĩa là TRUE thành FALSE và ngược
lại. Hay nói cách khác, vòng while trên chỉ chạy khi a = 0. Sau khi in
ra 0 thì a được cộng 1, trở thành 1 và vòng while dừng.

**Bài 255.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {  
for(int i = 1; i != 100; i += 2)

{

printf("%d ", i++);

}

return 0;

}

Chương trình trên mắc lỗi nào?

A, lỗi CE

B, lỗi TLE

C, không mắc lỗi

D, không phải 3 phương án trên

Đáp án: C, không mắc lỗi

Dù điều kiện của vòng for hơi kỳ lạ - i != 100, và chỉ cần nhìn qua, ta
cũng có cảm giác chương trình sẽ bị lỗi TLE. Bởi vì i = 1 là số lẻ, 100
là số chẵn, và sau mỗi vòng lặp, i được cộng thêm 2 do đó tính chẵn lẻ
của i là không thay đổi nên có thể thấy i luôn khác 100.

Tuy nhiên, sau mỗi lần printf, i được cộng thêm 1 nữa. Như vậy, sau mỗi
vòng lặp thì i được cộng 3. Rõ ràng ta có 100 = 1 + 3\*33 nên chương
trình này có thể chạy bình thường mà không có lỗi.

**Bài 256.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int i, max;

scanf("%d", &i);

int a\[i\];

for(int j = 0; j &lt; i; j++) scanf("%d", &a\[i\]);

max = a\[0\];

for(int j = 1; j &lt; i; j++)  
{

if(max &lt; a\[j\]) max = a\[j\];

}

printf("%d", max);

return 0;

}

Bạn Souma, sau khi chơi 4 ván LOL, chợt giật mình nhớ ra còn bài tập lập
trình. Uống vội cốc cà phê, tay liên tục gõ, bạn Souma viết 1 chương
trình tìm max của 1 dãy các số nguyên. "Cái gì vậy? Lạ nhỉ...", Souma
lẩm bẩm, nhìn màn hình với chữ WA to tướng. Bạn hãy giúp Souma tìm lỗi
trong đoạn code trên.

Với input là 6 0 1 2 3 4 5 6, chương trình trên sẽ in ra cái gì?

A, Giá trị ngẫu nhiên

B, 5

C, lỗi CE

D, lỗi MLE

Đáp án: A, Giá trị ngẫu nhiên.

Ở dòng for(int j = 0; j &lt; i; j++) scanf("%d", &a\[i\]); đãng nhẽ phải
là a\[j\] chứ không phải là a\[i\]. Chính lỗi này đã khiến chương trình
đưa ra 1 con số ngẫu nhiên do lỗi tràn số.

P/S: Làm bài cho xong rồi hãy chơi game, đừng để bản thân phải thức
khuya, uống cà phê rồi mắc những lỗi ngớ ngẩn thế này

**Bài 257.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main(void) {

int n = 5;

n \*= n++;

printf("%d", n);

return 0;

}

Chương trình trên in ra cái gì?

A, 30

B, 26

C, 25

D, 36

Đáp án: A, 30

Máy sẽ cộng n với 1 (n++) rồi mới nhân với n, hay n = 5\*6 = 30.

**Bài 258.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

double a, b;

scanf("%f %f", &a, &b);

printf("%f", a%b);

return 0;

}

Bạn Phát muốn tìm xem với 2 số thực a và b (a &gt; b) và số nguyên k,
giá trị nhỏ nhất không âm của a – b\*k là bao nhiêu. Bạn Phát có cần
thêm thư viện gì hỗ trợ không?

A, Thư viện math.h

B, Thư viện string.h

C, Thư viện stdlib.h

D, Không cần thêm thư viện gì cả

Đáp án: A, Thư viện math.h  
Ở đây, toán tử % chỉ để tìm số dư của 2 số nguyên chứ không thể dùng cho
2 số thực. Nếu muốn, bạn Phát cần phải sử dụng hàm fmod(a, b) – một hàm
trong thư viện math.h.

**Bài 259.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a = 2017;

a = a &gt;&gt; 2 &gt;&gt; 1;

a = a &lt;&lt; 2 &lt;&lt; 1;

printf("%d", a);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, lỗi CE

B, 2016

C, 2017

D, 2018

Đáp án: B, 2016

Trong các C compiler 32bit nói chung, kiểu biến int được lưu trong 32
bit (4 byte). Hay nói cách khác, số 2017 được lưu trong bộ nhớ như sau:

00000000 00000000 00000111 11100001

Phép toán "&gt;&gt;" và "&lt;&lt;" được gọi là phép dịch phải và dịch
trái; về cơ bản, "&lt;&lt; 4" có nghĩa là xóa đi 4 bit đầu tiên và thêm
4 bit 0 vào bên phải, tương tự với "&gt;&gt; 4".

Còn về thứ tự thì "&gt;&gt;" và "&lt;&lt;" cũng có thứ tự ưu tiên như
các phép toán "+, -, \*, /" – thực hiện từ trái sang phải.

Như vậy, chương trình sẽ dùng phép toán lên 2017 như sau

00000000 00000000 00000111 11100001

00000000000 00000000 00000111 11100

00000000000 00000000 00000111 11100

00000000 00000000 00000111 11100000

Số cuối cùng, 00000000 00000000 00000111 11100000, cũng chính bằng 2016.

**Bài 260.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int a = -2017;

a = a &gt;&gt; 2 &gt;&gt; 1;

a = a &lt;&lt; 2 &lt;&lt; 1;

printf("%d", a);

return 0;

}

Chương trình trên sẽ in ra cái gì?

A, lỗi CE

B, 2016

C, 2017

D, 2018

Đáp án: A, lỗi CE

Các phép toán "&lt;&lt;" và "&gt;&gt;" chỉ dành cho các số nguyên dương.
Do đó, khi áp các phép toán này lên -2017 – 1 số âm, chương trình sẽ báo
lỗi CE.

**Bài 261.** Cho đoạn code sau:

\#include &lt;stdio.h&gt;

int main() {

int i;

for(int i = 97; i &lt; 123; i++) printf("%c", i);

return 0;

}

Chương trình trên in ra cái gì?

A,979899100101102103104105106107108109110111112113114115116117118119120

B, abcdefghijklmnopqrstuv

C, lỗi CE

D, lỗi TLE

Đáp án: C, lỗi CE

Để ý thấy biến i được khai 2 lần, int i; và for(int i = 97; i &lt; 123;
i++). Do đó, máy sẽ không hiểu chuyện gì đang diễn ra và báo lỗi:
