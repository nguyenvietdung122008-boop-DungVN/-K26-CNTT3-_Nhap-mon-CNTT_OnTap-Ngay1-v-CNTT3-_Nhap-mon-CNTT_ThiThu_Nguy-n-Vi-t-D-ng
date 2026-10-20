# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Nguyễn Việt Dũng
- **Lớp:** HNKS26CNTT3
- **Link repository:** [GitHub](https://github.com/nguyenvietdung122008-boop-DungVN/-K26-CNTT3-_Nhap-mon-CNTT_OnTap-Ngay1-v-CNTT3-_Nhap-mon-CNTT_ThiThu_Nguy-n-Vi-t-D-ng)
- **Hệ điều hành (Windows/macOS):** Windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

- Phần A5:
Input
```powershell
mkdir docs, media, data, logs, archive
```
Output:
```powershell
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   9:11 PM                docs
d-----        10/20/2026   9:11 PM                media
d-----        10/20/2026   9:11 PM                data
d-----        10/20/2026   9:11 PM                logs
d-----        10/20/2026   9:11 PM                archive
```
Input
```powershell
mv .\Hoc_Vien_Khoa_3.xlsx data
mv .\Access.log logs
```

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)
B1
```powershell
pwd
```

B2
```powershell
ls -Force
```

B3
```powershell
mv .\Lich_Hoc.txt .\docs\
mv .\Anh_Lop_Hoc.JPG .\media\
mv .\Logo_Trung_Tam.PNG .\media\
```

B4
```powershell
cp .\media\Logo_Trung_Tam.PNG .\archive\
```

B5
```powershell
rm -r .\temp_201.tmp
rm -r .\temp_202.tmp
```

B6
```powershell
cd .\logs\
ls
cd ..
```

B7
```powershell
cd docs
cp ..\media\Anh_Lop_Hoc.JPG ..\archive\
cd ..
```

B8
```powershell
ls -Force
```

### Kết quả
B1
```text
Path
----
D:\starter-kit\trung-tam-tieng-anh
```

B2
```text
    Directory: D:\starter-kit\trung-tam-tieng-anh
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   9:11 PM                archive
d-----        10/20/2026   9:11 PM                data
d-----        10/20/2026   9:11 PM                docs
d-----        10/20/2026   9:12 PM                logs
d-----        10/20/2026   9:11 PM                media
-a----        10/19/2026  10:04 AM             83 .env
-a----        10/19/2026  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----        10/19/2026  10:04 AM             67 Lich_Hoc.txt
-a----        10/19/2026  10:04 AM           5184 Logo_Trung_Tam.PNG
-a----        10/19/2026  10:04 AM             22 temp_201.tmp
-a----        10/19/2026  10:04 AM             22 temp_202.tmp
```

B3
```text
(Không có output)
```

B4
```text
(Không có output)
```

B5
```text
(Không có output)
```

B6
```text
    Directory: D:\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 Access.log
```

B7
```text
(Không có output)
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
    Directory: D:\starter-kit\trung-tam-tieng-anh\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   9:20 PM                archive
d-----        10/20/2026   9:11 PM                data
d-----        10/20/2026   9:18 PM                docs
d-----        10/20/2026   9:12 PM                logs
d-----        10/20/2026   9:20 PM                media
-a----        10/19/2026  10:04 AM             83 .env
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** 100/100
- **Lỗi mình đã mắc và cách sửa:** Không có lỗi