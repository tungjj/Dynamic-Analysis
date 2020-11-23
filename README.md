# Dynamic-Analysis
Tài liệu tham khảo:
1.https://github.com/ErikHorus1249/AndroPyTool-Doc/blob/master/AndroPyToolInstalling.md
2. https://github.com/alexMyG/AndroPyTool

## Một số lưu ý khi thực hiện theo link 2:
1. Cài riêng các thư viện bị lỗi
2. Cần tạo virtualenv bằng python2: 
3. Copy image cho DroidBox bằng link của bạn Erik.


## Những thao tác cần làm cho phân tích động:
1. Lọc lấy file name từ file tổng trên gg drive ==> name.txt
2. cd /local: xóa file ko có trong name.txt
3. Chia nhỏ folder thành những folder con khoảng 25 file/folder
4. Chạy động cho từng folder nhỏ.

```
source droidbox_env/bin/activate
cd AndroPyTool/
python androPyTool.py -s /home/tung/test/ -dr 
```
