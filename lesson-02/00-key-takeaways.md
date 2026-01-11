Tổng hợp kiến thức được học trong bài 
***in đậm***
#: 1 dấu thăng tương đương với heading 1

1. Khởi tạo: git init
2. Cấu hình: + Cho từng repo 1:          git config [user.name](http://user.name) “<name>”

                                                                 git config [user.](http://user.name)email“<email>”

                        + Cho toàn bộ máy tính: git config - -global [user.name](http://user.name) “user” 

                                                            git config - -global [user.email](http://user.email) “email”

- bị treo con trỏ bấm Q
- Sửa là fix, thêm mới là feat, chore là sửa nhỏ lẻ (-m“fix: update file6”)
- git simple workflow:

+Không dùng global config: init > config > add > commit > push

+dùng global config: init > add > commit > push

- **JavaScript  (js)**

cú pháp in ra dòng chữ: console.log(”text”); 

câu lệnh để in ra: node <tenfile>

**Khai báo biến:** <Từ khóa > <Tên biến> = <Giá trị>

vd: var centerNam = “Thuy”;

let interview = true

+ let:  k cho khai báo lại, an toàn hơn, phạm vi theo block ⇒ dùng lét khi chắc chắn thay đổi giá trị

+var: cho phép khai báo lại, có phạm vi global ⇒ k dùng

→ biến thiên, có thể thay đổi được

**Khai báo hằng số**: <từ khóa> <tên hằng> = <gia tri> 

const

vs: const slogan = “Hoc nhanh học tốt”

→ không thể thay đổi, luôn luôn cố định, mặc định dùng const giúp code an toàn, dễ đọc hơn

- Mặc định dùng hằng số const - giúp code an toàn hơn, dễ đọc hơn
- chỉ dùng biến lét khi chắc chắn gán lại hằng số, không dùng var

**Kiểu dữ liệu**

Kiểu dữ liệu nguyên thủy

+ number: số nguyên, thực, vô hạn(Infinity),không phải là số (notANumber) 

+ string: ``(biến) ''(chuỗi)

+ Boolean: logic đúng sai true, false
+ Underfined

+ Null
+ Symbol

+ BigInt

Kiểu dữ liệu tham chiếu

+ Object

⇒ để biết biến thuộc kiểu dữ liệu gì dùng hàm typeof vd: console.log(typeof age)

**Toán tử so sánh**

== hai dấu bằng là (loose equality: không chặn chẽ lắm ) so sánh k quan tâm kiểu dữ liệu

vd: 5 == ‘’5’ → true, true = 1’ → true ⇒ nó tự biến string thành number,  boolean thành number

=== ba dấu bằng (strict equality: đúng cả kiểu dữ liệu và giá trị) so sánh check cả kiểu dữ liệu

vd: 5 ===”5” → fale

**Toán tử logic**

&& (AND): trả về đúng nếu cả 2 vế đúng

| | (OR) : trả về đúng nếu 1 trong 2 vế đúng 

**Toán tử 1 ngôi**

prefix: toán tử nằm ở phía trước - tăng trước, trả về sau

vd: ++x, - -x

let a = 10 

b = ++ 10 (tăng a lên 11 rồi trả về → b có giá trị = 11)

postfix: toán tử nằm về sau, trả về trước, tăng sau

vd: x ++, x - -

let a = 10

b = 10 ++ (trả về giá trị 10 cho b, rồi mới tăng → b có giá trị = 10, a  = 11)

**câu điều kiện**

vd: let a = 5

if (a>7){

console.log (’not ok’);

}

**Vòng lặp** 

for (i)

cú pháp: for(<Điều kiện khởi tạo>; <Điệu kiện dừng vòng  lặp>; <cập nhật>){

//code

}

Điều kiện khởi tạo: chạy 1 lần duy nhất khi vòng lặp bắt đầu

Điều kiện lặp: nếu đk đúng chạy tiếp, sai dừng lại

Cập nhật: chạy vào mỗi cuối vòng lặp, để thay đổi giá trị của biến đếm

vd: for (let i = 0; i < 1000; i ++){

console.log(’Xin chaos’)

}

for (of)

for (each)

for (in)

while

do..while