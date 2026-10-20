# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:Hoa Việt Hoàng**
- **Lớp:CNTT3**
- **Link repository:
- **Hệ điều hành (Windows/macOS): Windows**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
pwd
ls -Force
mv ".\lich-hoc.txt" "..\docs\"
mv .\logo-trung-tam.PNG,.\anh-lop-hoc.JPG .\media\
cp .\media\logo-trung-tam.PNG .\archive
rm .\temp_201.tmp
rm .\temp_202.tmp
cd .\logs\
ls
cd..
cd .\docs\
cp ..\media\anh-lop-hoc.JPG ..\archive\
cd..
```

### Kết quả B1 (pwd)
```text
Path
----
C:\Users\ADMIN\Downloads\starter-kit\trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
  Directory: C:\Users\ADMIN\Downloads\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026  10:02 PM                archive
d-----        10/20/2026   9:32 PM                data
d-----        10/20/2026   9:49 PM                docs
d-----        10/20/2026   9:34 PM                logs
d-----        10/20/2026   9:53 PM                media
-a----        10/20/2026   9:03 PM             83 .env
-a----        10/20/2026   9:03 PM            902 bai_lam_ngay1.md


    Directory: C:\Users\ADMIN\Downloads\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   9:03 PM          13559 anh-lop-hoc.JPG
-a----        10/20/2026   9:03 PM           5184 logo-trung-tam.PNG


    Directory: C:\Users\ADMIN\Downloads\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   9:03 PM           5070 hoc-vien-khoa.xlsx


    Directory: C:\Users\ADMIN\Downloads\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   9:03 PM             67 lich-hoc.txt


    Directory: C:\Users\ADMIN\Downloads\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   9:03 PM           1072 Access.log


    Directory: C:\Users\ADMIN\Downloads\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   9:03 PM          13559 anh-lop-hoc.JPG
-a----        10/20/2026   9:03 PM           5184 logo-trung-tam.PNG
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
