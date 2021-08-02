# Git_Tutorial_For_Beginer
## Mục lục
[I. Thao tác cơ bản](#ThaoTacCoBan)

[II. Thao tác trên branch](#ThaoTacTrenBranch)

[III. Thao tác tag](#ThaoTacTag)

[IV. Thiết lập kết nối SSH](#ThietLapKetNoiSSH)

[V. Thao tác commit log](#ThaoTacCommitLog)

[VI. Thao tác remote](#ThaoTacRemote)

[VII. Thiết lập Git](#ThietLapGit)

[VIII. Stash](#Stash)

[IX. So sánh Git-Subversion](#SoSanhGit-Subversion)

[X. Xử lý sự cố](#XuLySuCo)

---------------------------------------
<a name="ThaoTacCoBan"></a>

# I. Thao tác cơ bản

[1. Tạo repository](#I1)

[2. Muốn đăng ký file và thư mục trong Index](#I2)

[3. Muốn commit file được thêm trong Index](#I3)

[4. Muốn hiển thị danh sách của file đã được chỉnh sửa](#I4)

[5. Muốn xem phần sai khác của file được chỉnh sửa](#I5)

[6. Muốn xem commit log](#I6)

[7. Muốn xác nhận chi tiết của commit](#I7)

[8. Muốn di chuyển, thay đổi tên thư mục và file](#I8)

[9. Muốn xóa file](#I9)

[10. Muốn xóa file không phải là đối tượng quản lý](#I10)

[11. Muốn phục hồi lại file ban đầu sau khi đã chỉnh sửa trong Index](#I11)

[12. Muốn bỏ file đã đăng ký trong Index](#I12)

[13. Muốn đăng ký trong tất cả Index chỉ những file đã có commit trước đó](#I13)

---
<a name="ThaoTacTrenBranch"></a>

# II. Thao tác trên branch

---

<a name="ThaoTacTag"></a>

# III. Thao tác tag

---

<a name="ThietLapKetNoiSSH"></a>

# IV. Thiết lập kết nối SSH

---

<a name="ThaoTacCommitLog"></a>

# V. Thao tác commit log

---

<a name="ThaoTacCoBan"></a>

# VI. ThaoTacRemote

---

<a name="ThietLapGit"></a>

# VII. Thiết lập Git

---

<a name="Stash"></a>

# VIII. Stash

---

<a name="SoSanhGit-Subversion"></a>

# IX. So sánh Git-Subversion

---

<a name="XuLySuCo"></a>

# X. Xử lý sự cố

---

<a name="ThaoTacCoBan"></a>

# I. Thao tác cơ bản
<a name="I1"></a>
## 1. Tạo repository.

```
$ git init
```

- Trong thư mục muốn tạo repository thực hiện bằng lệnh init.

<a name="I2"></a>
## 2. Muốn đăng ký file và thư mục trong Index

```
$ git add <filepattern>
```
- filepattern thì ngoài cách chỉ định tên file trực tiếp thì cũng có thể chỉ định bằng cách đính kèm thẻ đại diện kiểu như "*.txt". 

- Khi mà chỉ định "." thì bao hàm luôn cả thư mục phụ (sub directory) bên trong có thể đăng ký trong index cho tất cả file.

- Khi thêm lựa chọn -p thì có thể đăng ký thay đổi chỉ 1 bộ phận của file muốn chỉnh sửa. 

- Và nếu thêm lựa chọn -i thì có thể lựa chọn mang tính tương tác file đăng ký trong Index.

<a name="I3"></a>
## 3. Muốn commit file được thêm trong Index

```
$ git commit
```
- Khi thêm lựa chọn -a thì chuỗi những hành động kiểm tra file bị thay đổi (trừ trường hợp thêm mới file), rồi thêm trong index sau đó commit thì có thể thực hiện chỉ bằng 1 lệnh.

- Khi thêm lựa chọn -m thì có thể chỉ định nội dung giải thích của commit rồi thực hiện commit. 

- Trường hợp không có thêm vào lựa chọn -m thì editor để chỉnh sửa nội dung của giải thích commit sẽ được khởi động.

<a name="I4"></a>
## 4. Muốn hiển thị danh sách của file đã được chỉnh sửa

```
$ git status
```
- Khi thêm lựa chọn -s thì có thể thực hiện việc không hiển thị nội dung giải thích.

- Thêm nữa là khi thêm lựa chọn -b thì không hiển thị nội dung giải thích nhưng có thể thực hiện việc hiển thị tên nhánh.

<a name="I5"></a>
## 5. Muốn xem phần sai khác của file được chỉnh sửa

```
$ git diff
```
- Tình trạng không có chỉ định lựa chọn thì sẽ hiển thị phần sai khác của index với cây công việc (working tree).

- Khi thêm lựa chọn -cached thì sẽ hiển thị phần sai khác của HEAD với index.

- Và khi chỉ định commit và HEAD thì sẽ hiển thị phần sai khác của HEAD được chỉ định với cây công việc (working tree).

<a name="I6"></a>
## 6. Muốn xem commit log

```
$ git log
```
- Lệnh log sẽ mặc định hiển thị danh sách commit của branch.

- Trường hợp muốn xem commit log của file đặc định nào đó thì hãy chỉ định tên file.

<a name="I7"></a> 
## 7. Muốn xác nhận chi tiết của commit

```
$ git show <commit>
```
- Tham số của lệnh show thì có thể chỉ định HEAD và commit đã tham chiếu bằng lệnh log.

<a name="I8"></a> 
## 8. Muốn di chuyển, thay đổi tên thư mục và file

```
$ git mv <oldfilename> <newfilename>
```
<a name="I9"></a> 
## 9. Muốn xóa file

```
$ git rm <file>
```
<a name="I10"></a>
## 10. Muốn xóa file không phải là đối tượng quản lý

```
$ git clean
```
- Khi thêm lựa chọn -n thì có thể xác nhận file đã bị xóa. Thêm lựa chọn -f thì sẽ xóa file thực tế.

- Mặc định thì file được chỉ định là .gitignore sẽ không phải là đối tượng xóa, nhưng thêm lựa chọn -x thì cho dù là file được chỉ định là .gitignore thì cũng sẽ là đối tượng xóa.

<a name="I11"></a> 
## 11. Muốn phục hồi lại file ban đầu sau khi đã chỉnh sửa trong Index

```
$ git checkout -- <file>
```
<a name="I12"></a> 
## 12. Muốn bỏ file đã đăng ký trong Index

```
$ git reset HEAD -- <file>
```
<a name="I13"></a> 
## 13. Muốn đăng ký trong tất cả Index chỉ những file đã có commit trước đó

```
$ git add -u
```

---

# II. Thao tác trên branch

## 1. Muốn hiển thị danh sách của branch

```
$ git branch
```
- Khi thêm lựa chọn -r sẽ liệt kê những branch điều khiển từ xa. 
- Khi thêm lựa chọn -a thì có thể hiển thị danh sách cả remote và local branch.

## 2. Muốn tạo branch
```
$ git branch <branchname>
```
- Khi thực hiện lệnh branch mà không chỉ định tham số, thì có thể hiển thị danh sách các branch. Ở đầu có dấu * là branch hiện tại.
```
$ git branch
  issue1
* master
```

## 3. Muốn thay đổi tên branch
```
$ git branch -m <oldbranch> <newbranch>
```

## 4. Muốn xóa branch
```
$ git branch -d <branchname>
```
- Trường hợp có commit chưa được merge vào HEAD thì không thể xóa branch. Để xóa branch có commit chưa được merge cách cưỡng chế thì thêm lựa chọn -D vào rồi thực thi.


## 5. Chuyển đổi branch
```
$ git checkout <branch>
```
- Lệnh này sẽ cho phép thực hiện check out và chuyển sang branch mong muốn.

- Khi thêm lựa chọn -b có thể thực hiện việc tạo branch mới và chuyển đổi sang branch đó chỉ bằng 1 lệnh.

(Để thêm commit vào branch đã tạo mới, thì cần checkout branch đó.

Checkout branch sẽ thực hiện bằng lệnh checkout.)


## 6. Muốn Merge branch
```
$ git merge <branch>
```
- Khi thêm lựa chọn --no-ff thì cho dù là có merge kiểu fast-forward thì commit cũng được tạo ra. 

- Đây là lựa chọn hữu ích khi muốn để lại thông tin branch đã tồn tại.

(Tích hợp thay đổi đã thực hiện trên branch mới vào branch master)

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/Merge_branches_1.png">


- Để đưa issue1 vào branch master, thì trước hết sẽ di chuyển đến branch master.
```
$ git checkout master
```
- Sau đó:
```
$ git merge <branch>
```
- Commit chỉ branch master đã di chuyển đến vị trí giống với branch chỉ định. Merger này là merge fast-forward (chuyển tiếp nhanh).

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/Merge_branches_2.png">

