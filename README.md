># btap1-web-
Một lớp thư viện tính toán "số may mắn cá nhân" dựa trên tên và ngày sinh.
Người dùng nhập Tên và Ngày sinh.
Hệ thống sẽ tính Số may mắn (Lucky Number) dựa theo ngày sinh.
Kết quả được hiển thị trên trang web.
# Bài Làm 
#1.Tạo Solution & 4 project
#A. Tạo Solution
1 Mỏ Visual Studio 2022.
2 Chọn Create a new project
3 Tìm "Blank Solution" trên thanh tìm kiếm->chọn Blank Solution -> Nhấn Next 
<img width="1917" height="1079" alt="image" src="https://github.com/user-attachments/assets/3a7d8980-2a88-4207-8b76-e3ff0dc69a73" />
4 Tại Solution name: Đặt tên Solution "StepSuite"
5 Tại location: chọn nơi lưu trữ -> Create.
# B. Project 1 — Class Library (DLL)
1 Tại Solution Explorer → chuột phải vào Solution StepSuite → Add → New Project…

<img width="544" height="383" alt="image" src="https://github.com/user-attachments/assets/532de975-7be7-4037-ac4f-30202da6d750" />

2 Tìm Class Library (.NET Framework)-> Chọn -> Next.

<img width="467" height="526" alt="image" src="https://github.com/user-attachments/assets/67ec2aec-ce2a-4980-b337-ca5c594ccced" />

3 Project name: StepLib
Frame work: Chọn .NET Framework 2.0 -> Create

<img width="573" height="403" alt="image" src="https://github.com/user-attachments/assets/5784c70a-aef8-470b-b796-2df2253f8198" />

4 Viết code vào Luckynember.cs 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2f8b9030-b014-432e-a2ff-bdc8ea4d5ed7" />

# C. Project 2 — Console appConsole
1 Tại Solution Explorer → chuột phải vào Solution StepSuite → Add → New Project….
2 Tìm Console App (.NET Framework) ->Chọn → Next.

<img width="514" height="582" alt="image" src="https://github.com/user-attachments/assets/a83062c1-c711-4494-8b3b-f4e30f35c2ea" />

3 Project name:LuckyNumberConsole 
  Frame work: Chọn .NET Framework 2.0
  
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c821f475-a333-46ff-ba9f-dd443eee7363" />

  Thêm tham chiếu tới DLL:
  
  <img width="1917" height="1079" alt="image" src="https://github.com/user-attachments/assets/2d3cfa63-c593-4400-b15e-f9869b6c4168" />
  
 4 Ctrl+Shift+B (Build) → Run
 #D.Project 3 - Windows Form Application 
 1 Tại Solution Explorer → chuột phải vào Solution StepSuite → Add → New Project….
 
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9dc1b4b4-e0cb-4577-ada2-b1a36316cd94" />
 
2 Tìm Windows Forms App (.NET Framework)->Chọn ->Next.

<img width="795" height="532" alt="image" src="https://github.com/user-attachments/assets/64bbead7-b2f6-4b1b-a7e6-219d592dd635" />

3 Project name :LuckyNumberWinForms
Frame work: Chọn .NET Framework 2.0 -> Create 
4 Thêm tham chiếu DLL

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/075992fa-621f-40f4-92fa-ca7ff4c88cfe" />

5 Thiết kế from 
View → Toolbox (hoặc Ctrl+Alt+X).

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c28bf70e-8171-4dbf-b089-bfa5de62a76b" />

 Tạo giao diện 
 
 <img width="1266" height="690" alt="image" src="https://github.com/user-attachments/assets/825e861a-89cb-4659-8935-a12b41d9325c" />
 
# E Project 4 — WebForms










