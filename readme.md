# Learing Git Colleborator

## Các lệnh và khái niệm

```Tạo nhánh (branch)```
+ Cách 1: 
* git branch <branch_name>: ví dụ: git branch development
* git checkout <branch_name>: ví dụ: git checkout development

+ Cách 2:
* git checkout -b <branch_name>: ví dụ: gỉ checkout -b development

```Đồng nhánh mới từ local lên remote```
* git push -u origin <branch_name> ví dụ: git push -u origin development

```git fetch```
* đồng bộ mã nguồn tủ origin (remote) với local

```git pull```
* lấy mã từ từ origin về local

```Lưu ý khi sử lý conflict```
* những gì nằm trong block
<<<<<<< HEAD
.... của mình
=======

* những gì nằm trong block
=======
.... của partner
>>>>>>> b44aa3232af44747001f53ed6d1ad6fff625b98d