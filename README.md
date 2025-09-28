# PROJECT_WEB
TẠO SOLUTION GỒM CÁC PROJECT SAU:
1. DLL đa năng, keyword: c# window library -> Class Library (.NET Framework) bắt buộc sử dụng .NET Framework 2.0: giải bài toán bất kỳ, độc lạ càng tốt, phải có dấu ấn cá nhân trong kết quả, biên dịch ra DLL. DLL độc lập vì nó ko nhập, ko xuất, nó nhận input truyền vào thuộc tính của nó, và trả về dữ liệu thông qua thuộc tính khác, hoặc thông qua giá trị trả về của hàm. Nó độc lập thì sẽ sử dụng được trên app dạng console (giao diện dòng lệnh - đen sì), cũng sử dụng được trên app desktop (dạng cửa sổ), và cũng sử dụng được trên web form (web chạy qua iis).
2. Console app, bắt buộc sử dụng .NET Framework 2.0, sử dụng được DLL trên: nhập được input, gọi DLL, hiển thị kết quả, phải có dấu án cá nhân. keyword: c# window Console => Console App (.NET Framework), biên dịch ra EXE
3. Windows Form Application, bắt buộc sử dụng .NET Framework 2.0**, sử dụng được DLL đa năng trên, kéo các control vào để có thể lấy đc input, gọi DLL truyền input để lấy đc kq, hiển thị kq ra window form, phải có dấu án cá nhân; keyword: c# window Desktop => Windows Form Application (.NET Framework), biên dịch ra EXE
4. Web đơn giản, bắt buộc sử dụng .NET Framework 2.0, sử dụng web server là IIS, dùng file hosts để tự tạo domain, gắn domain này vào iis, file index.html có sử dụng html css js để xây dựng giao diện nhập được các input cho bài toán, dùng mã js để tiền xử lý dữ liệu, js để gửi lên backend. backend là api.aspx, trong code của api.aspx.cs thì lấy được các input mà js gửi lên, rồi sử dụng được DLL đa năng trên. kết quả gửi lại json cho client, js phía client sẽ nhận được json này hậu xử lý để thay đổi giao diện theo dữ liệu nhận dược, phải có dấu án cá nhân. keyword: c# window web => ASP.NET Web Application (.NET Framework) + tham khảo link chatgpt thầy gửi. project web này biên dịch ra DLL, phải kết hợp với IIS mới chạy được.

## BÀI LÀM
### *DLL ĐA NĂNG:* ###
- ClassDuong
- Code C# and Build Succeeded

<img width="1857" height="979" alt="image" src="https://github.com/user-attachments/assets/808eeb0b-3811-4e52-8ca4-03530d9ffe94" />

  <img width="1893" height="1010" alt="image" src="https://github.com/user-attachments/assets/995349d6-4232-4a5e-bdab-6f04410904e5" />

### *CONSOLE APP:* ###
- ConsoleDuong
  Build Succeeded and Table Console
<img width="1907" height="1001" alt="image" src="https://github.com/user-attachments/assets/99708fa6-1bc2-42a9-adb9-5e41a3465b27" />

  <img width="1892" height="550" alt="image" src="https://github.com/user-attachments/assets/5618dc4c-8d40-4e92-a491-1b8a1fa56147" />

### *WINDOWNFORMAPP:* ###

- WindownformDuong
   Build Succeeded and Table Form
  <img width="1854" height="974" alt="image" src="https://github.com/user-attachments/assets/183375d9-95f6-4a35-a48c-82f8a624225e" />
- Form1 and Code 
 <img width="429" height="298" alt="image" src="https://github.com/user-attachments/assets/f5d66627-c719-4aab-a0e5-3e48c517dfb6" />

<img width="1828" height="936" alt="image" src="https://github.com/user-attachments/assets/1a004334-6d7b-4079-aca2-f9072f6abf22" />
- Code C# Program.cs
  <img width="1902" height="668" alt="image" src="https://github.com/user-attachments/assets/8bac8f4d-6c19-4da8-8d77-dbf4308d63cc" />

  ### *WEB --> ASP.NET Web Application (.NET Framework):* ###
- Giao diện Form Web + Kết quả tính toán
  <img width="1844" height="823" alt="image" src="https://github.com/user-attachments/assets/6f70cabb-80c0-44f5-a76f-a69d20b7e084" />
- Localhost : http://duongit12.local/
   <img width="1909" height="903" alt="image" src="https://github.com/user-attachments/assets/0b4e23f4-94b6-476d-a7c2-da479bae4dca" />

