<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e973dcd3-595b-474e-8021-9cec50273f2f" />># btap1-web-
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
1 Tại Solution Explorer → chuột phải vào Solution StepSuite → Add → New Project…

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9c6f34b5-443d-401f-b5b7-a61e159ca115" />

Project name: LuckyNumberWeb
Frame work: Chọn .NET Framework 2.0 
chọn template Empty → Create.
2 Thêm tham chiếu:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b8f019b1-4562-4b99-ba85-7e73020ae85c" />

 LuckyNumberWeb→ References → Add Reference… → Projects → tích  → OK.
 3 Thêm file index.html
 LuckyNumberWeb → chuột phải → Add → New Item… → HTML Page → Name: index.html → Add.
 
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/fc452156-2dca-4d40-9a51-67d855780b63" />

4 Thêm file api.aspx:
tạo thêm
<img width="1834" height="1079" alt="image" src="https://github.com/user-attachments/assets/b37fba3b-e2bf-4a4f-9a04-db4b48937b2c" />

Kết quả sau khi run 

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2a4d4c3a-2dae-4917-b912-ecfd1e45b834" />

# Cấu hình IIS cho Project Web
A.Bật tính năng Windows cần thiết
Mở Control Panel → Programs and Features.

<img width="1269" height="570" alt="image" src="https://github.com/user-attachments/assets/377f24a6-b1f0-4296-85ff-f7f8aa27d27b" />
2 Chọn Turn Windows features on or off Tích:
.NET Framework 3.5 (includes .NET 2.0 and 3.0) → OK để cài.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f066869c-ca33-4bd4-affb-7d4014018804" />

Internet Information Services → mở World Wide Web Services → Application Development Features → tích:

ASP.NET 3.5

.NET Extensibility 3.5

ISAPI Extensions

ISAPI Filters → OK
B.Tạo domain cục bộ (hosts)
1 Mở Notepad dưới quyền admin: Start → gõ Notepad → chuột phải → Run as administrator.
tìm tới đia chỉ và thêm host 
<img width="1518" height="183" alt="image" src="https://github.com/user-attachments/assets/1bea6d70-d543-4d59-9a57-9ab76b167c12" />

hiển thị 

<img width="1202" height="677" alt="image" src="https://github.com/user-attachments/assets/d196bf4e-6384-47b8-bfc5-29766f13e288" />
sau đó nhấn ctrl S 

C.Thêm Website & Binding domain

Mở IIS Manager: nhấn Win, gõ inetmgr → Enter.

<img width="862" height="390" alt="image" src="https://github.com/user-attachments/assets/b84d6640-0e42-4bc3-97ba-43deca38073f" />

Trong IIS Manager → cột trái Sites → chuột phải → Add Website…

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b5b44907-a5b0-4686-bc0a-67aac061830a" />

Site name: 

Physical path: nhấn … → trỏ đúng thư mục project "C:\Users\ACER\Documents\Zalo Received Files\LuckyNumberDLL\LuckyNumberWeb"
Type: http
IP address: All Unassigned
Port: 80
Host name:  LuckyNumber.local
Nhấn OK.

D.Tạo Application Pool dùng .NET 2.0
Mở IIS Manager → cột trái chọn Application Pools.
Chuột phải → Add Application Pool
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9755f1b2-e872-4132-8c10-a5280eca4da4" />
 ktra và làm lại
 

 
 







