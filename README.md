# Nhóm 16 – Học phần: HỆ THỐNG NHÚNG

## I. Video lý thuyết SysTick (STM32)

### Phần 1 – Tổng quan SysTick
Video trình bày tổng quan lý thuyết về SysTick, gồm:
- Khái niệm SysTick và vai trò trong STM32  
- Nguyên lý hoạt động  
- Ý nghĩa các thanh ghi  
- Công thức tính toán tốc độ SysTick  
- Ứng dụng thực tế  

> [[7S - N16] Video tổng quan lý thuyết về Systick và cách thay đổi tốc độ trên STM32 (Phần 1)](https://drive.google.com/file/d/1188mG7XfajLIXDvEJkd8X1rKLGl1LyNT/view?usp=sharing) 



### Phần 2 – Các biến & hàm liên quan SysTick
Video trình bày:
- Các biến – cấu trúc HAL liên quan SysTick  
- Hàm callback & interrupt  
- Thay đổi chu kỳ SysTick  

>[[7S - N16] Video tổng quan lý thuyết về Systick và cách thay đổi tốc độ trên STM32 (Phần 2)](https://drive.google.com/file/d/1SdrHPHBvm2Ps1yC2JFU00UnOooGznjOC/view?usp=sharing)


## II. Thư viện HAL SysTick 

### Phần 1 - Nhấp nháy LED với Systick (HAL) trên STM32

Trình bày ý nghĩa của các hàm có hẵn trong thư viện HAL
Soure code: [Link](https://github.com/giunzz/SYSTICK_STM32/tree/main/Systick_HAL)

> [[7S - N16] Video nhấp nháy LED với SysTick (HAL) – Phần 1](https://drive.google.com/file/d/17cQ2f_ty3O_-Vn1Wuj1U5wM46kwlum9t/view?usp=sharing)

Phần mềm sử dụng : KeilC, CubeMx, proteus



### Phần 2 - Modify Systick (HAL) trên STM32

- Điều chỉnh SysTick để thay đổi tần số nhấp nháy  
- Công thức tính SysTick Clock  
- Dùng `HAL_SYSTICK_Config()`  
- Ứng dụng bài tập thay đổi tốc độ LED  

Soure code: [Link](https://github.com/giunzz/SYSTICK_STM32/tree/main/Systick_HAL)

> [[7S - N16] VIdeo nhấp nháy LED với SysTick (HAL) trên STM32 – Phần 2 (Điều chỉnh tần số)](https://drive.google.com/file/d/1gvZQGouSlzX1wQB8T25jtVudOyVjRGSu/view?usp=sharing)

Phần mềm sử dụng : KeilC, CubeMx, proteus

## III. Thanh ghi SysTick 

- Truy cập và cấu hình thanh ghi SysTick (CTRL, LOAD, VAL)  
- Thay đổi tốc độ SysTick trực tiếp qua thanh ghi  
- Mô phỏng trên phần mềm proteus
- Video demo thực tế  


Soure code: [Link](https://github.com/giunzz/SYSTICK_STM32/tree/main/Systick_register)

> [[7S - N16] Video nhấp nháy LED với SysTick trên STM32 -  Phần 3 (sử dụng thanh ghi)](https://drive.google.com/file/d/1-Qr87zFan58AQnEX1nsw6BVvi1VKZUXl/view?usp=sharing)


Phần mềm sử dụng : STM32CubeIDE, CubeMx, proteus


## III. Ứng dụng SysTick – Điều khiển Servo

- Điều chế xung PWM bằng SysTick  
- Điều khiển servo ở các góc khác nhau  
- Ứng dụng thực tế: module cho cá ăn  
- Demo phần cứng + phân tích code  

Soure code: [Link](https://github.com/giunzz/SYSTICK_STM32/tree/main/feeding_systick)

Phần mềm sử dụng : STM32CubeIDE, CubeMx, proteus

## IV. Báo cáo
- **Slide trình bày:**  [Slide SysTick – Nhóm 16](https://github.com/giunzz/SYSTICK_STM32/blob/main/report/mid_term_systick.pdf)

- **Báo cáo .docx:**  [Report SysTick – Nhóm 16](https://github.com/giunzz/SYSTICK_STM32/blob/main/report/Embeded_Project_GK.pdf)

- **Nhóm 16 – Thành viên**

1. Hoàng Ngọc Dung - 23139006 
2. Đoàn Minh Duy Bình - 23139005 
3. Trần Hữu Dương - 23139009 
4. Nguyễn Trần Minh Đức - 23139012 
5. Cao Như Ý - 23139052 
