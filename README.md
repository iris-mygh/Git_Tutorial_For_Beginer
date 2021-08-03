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

[1. Giới thiệu branch](#II1)

[2. Muốn hiển thị danh sách của branch](#II2)

[3. Muốn tạo branch](#II3)

[4. Muốn thay đổi tên branch](#II4)

[5. Muốn xóa branch](#II5)

[6. Chuyển đổi branch](#II6)

[7. Muốn Merge branch](#II7)

---

<a name="ThaoTacTag"></a>

# III. Thao tác tag

[1. Giới thiệu tag](#III1)

[2. Muốn hiển thị danh sách của tag](#III2)

[3. Muốn tạo tag](#III3)

[4. Muốn tạo tag có gắn kèm chú thích](#III4)

[5. Muốn xóa tag](#III5)

[6. Hướng dẫn sử dụng tag](#III6)
---

<a name="ThietLapKetNoiSSH"></a>

# IV. Thiết lập kết nối SSH

[1. Muốn thiết lập kết nối SSH (Windows)](#IV1)

[2. Muốn thiết lập kết nối SSH (Mac)](#IV1)

[3. Muốn thiết lập kết nối SSH (Console)](#IV1)

[4. Muốn thiết lập khóa SSH trong Backlog](#IV1)

---

<a name="ThaoTacCommitLog"></a>

# V. Thao tác commit log

[1. Muốn chỉnh sửa nội dung commit ngay trước đó](#V1)

[2. Chỉ muốn sửa phần giải thích của commit ngay trước đó](#V2)

[3. Muốn chỉnh sửa nội dung commit trong quá khứ](#V3)

[4. Chỉ muốn sửa phần giải thích của commit trong quá khứ](#V4)

[5. Muốn bỏ rebase đang thực hiện](#V5)

[6. Muốn xem lịch sử thay đổi của HEAD](#V6)

[7. Muốn xem lịch sử thay đổi của branch đầu](#V7)

[8. Muốn xem như không có commit ngay trước đó](#V8)

[9. Muốn xem như không có rebase](#V9)

[10. Muốn xem như không có reset ngay trước đó](#V10)

[11. Muốn di chuyển commit bị sai sang branch khác](#V11)

[12. Muốn tìm kiếm commit bao hàm bình luận đặc định](#V112)

---

<a name="ThaoTacRemote"></a>

# VI. Thao tác Remote

[1. Muốn nhân ra nhiều remote repository có sẵn](#VI1)

[2. Muốn thêm remote repository](#VI2)

[3. Muốn hiển thị danh sách remote repository](#VI3)

[4. Từ branch của remote repository muốn tạo branch của local repository](#VI4)

[5. Muốn tạo branch trong remote repository / muốn phản ánh nội dung thay đổi trong branch](#VI5)

[6. Muốn xác nhận nội dung thay đổi trong branch của remote repository](#VI6)

[7. Muốn lấy nội dung thay đổi trong branch của remote repository](#VI7)

[8. Muốn xóa branch của remote repository](#VI8)

[9. Muốn tạo tag trong remote repository](#VI9)

[10. Muốn xóa tag của remote repository](#VI10)

[11. Muốn thay đổi địa chỉ của remote repository đã đăng ký xong](#VI11)

[12. Muốn thay đổi tên của remote repository đã đăng ký xong](#VI12)

---

<a name="ThietLapGit"></a>

# VII. Thiết lập Git

[1. Muốn thiết lập tên người dùng / địa chỉ email](#VII1)

[2. Muốn tô màu kết quả xuất ra](#VII2)

[3. Muốn thiết lập bí danh trong lệnh](#VII3)

[4. Muốn bỏ ra ngoài đối tượng quản lý những file không cần thiết](#VII4)

[5. Muốn các thư mục rỗng nằm trong đối tượng quản lý](#VII5)

[6. Muốn hiển thị danh sách thiết lập](#VII6)

[7. Muốn thông qua proxy server kết nối http](#VII7)

[8. Muốn thông qua proxy server có cần thiết chứng thực người sử dụng để kết nối http](#VII8)

---

<a name="Stash"></a>

# VIII. Stash

[1. Muốn tạm thời lưu lại công việc hiện tại](#VIII1)

[2. Muốn hiển thị danh sách công việc lưu tạm](#VIII2)

[3. Muốn quay lại tiếp tục công việc lưu tạm](#VIII3)

[4. Muốn xóa công việc lưu tạm](#VIII4)

[5. Muốn xóa tất cả công việc lưu tạm](#VIII5)

---

<a name="SoSanhGit-Subversion"></a>

# IX. So sánh Git-Subversion

- Đây là biểu đồ so sánh lệnh của *Git* với *Subversion*: [here](#IX1)

---

<a name="XuLySuCo"></a>

# X. Xử lý sự cố

1. SSH

[Lỗi "Permission denied (publickey)" khi dự định kết nối vào remote repository bằng SSH](#X1)

2. HTTPS

[Không thể clone remote repository bằng HTTPS URL
Mỗi lần push/pull từ remote repositoy thì đều bị hỏi mật khẩu](#X2)

3. SSH/HTTPS

[Cho dù đã push nhưng vẫn không phản ánh trên remote repository](#X3.1)

[Mỗi lần push/pull từ remote repositoy thì đều bị hỏi mật khẩu](#X3.2)

---
Source: Internet

Some document links:

- [backlog.com](https://backlog.com/git-tutorial/vn/reference/)
- [GitHub Docs](https://docs.github.com/en/github)
- [Git và Github cho sysadmin](https://github.com/hocchudong/git-github-for-sysadmin)

Thanks a lot

---

**Feedback**

Bài viết trên tôi tổng hợp lại những kiến thức thu được khi tìm hiểu và sử dụng git và github cùng những nguồn tài liệu quý giá từ Internet. Giúp tôi dễ review hơn. Hi vọng cũng hữu ích cho các bạn beginers

Rất vui nhận được feedback để bài viết thêm hoàn thiện hơn.

Email: lnkngoc8@gmail.com

Xin chân thành cảm ơn!

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

<a name="II1"></a>

# II. Thao tác trên branch

## 1. Giới thiệu branch

[1.1 Branch](#II1.1)

[1.2 Vận dụng branch](#II1.2)

[1.3 Chuyển đổi branches](#II1.3)

[1.4 Tích hợp branches](#II1.4)

[1.5 Ví dụ vận dụng bằng nhánh chủ đề (topic branch) và nhánh tích hợp (integration branch)](#II1.5)

---

<a name="II1.1"></a>

#### 1.1 Branch

- Trong việc phát triển phần mềm, thì ứng với một phần mềm có nhiều thành viên đồng thời tiến hành thêm chức năng hay là tiến hành chỉnh sửa lỗi cùng một lúc. 

- Tình trạng tồn tại của nhiều phiên bản đã phát hành thì cũng phải lưu giữ.

- Chính vì vậy để hỗ trợ quản lý phiên bản hay thêm nhiều chức năng được tiến hành song song, một chức năng được trang bị thêm được gọi là branch ở Git.

- Branch là gì?

- Branch là cái dùng để phân nhánh và ghi lại luồng của lịch sử. 

- Branch đã phân nhánh sẽ không ảnh hưởng đến branch khác nên có thể tiến hành nhiều thay đổi đồng thời trong cùng 1 repository.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/branches_1.png">

- Hơn nữa, branch đã phân nhánh có thể chỉnh sửa tổng hợp lại thành 1 branch bằng việc hợp lại (merge) với branch khác.

Sơ đồ bên dưới là mô hình của thao tác song song đã sử dụng branch.

Các thành viên của nhóm sẽ tạo branch dùng riêng cho công việc của mình từ branch chính để không ảnh hưởng đến công việc của các thành viên khác. 

- Sau đó, những thành viên đã hoàn thành công việc của mình sẽ thực hiện đưa thay đổi của mình vào branch chính. Theo cách như vậy, sẽ không bị ảnh hưởng từ công việc của các thành viên khác, và bản thân mình có thể thực hiện công việc của mình.

Hơn nữa, bằng việc để lại lịch sử theo đơn vị công việc, trong trường hợp có phát sinh vấn đề thì việc điều tra nguyên nhân ở những vị trí thay đổi cũng như việc tiến hành đối sách khắc phục sẽ trở nên dễ dàng hơn.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/branches_2.png">

- Branch master

Khi tiến hành commit lần đầu trong repository thì Git sẽ tạo ra một branch có tên là master. 

- Vì thế những lần commit sau sẽ được thêm vào branch master cho đến khi chuyển đổi branch.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/branches_3.png">

---

<a name="II1.2"></a>

#### 1.2 Vận dụng branch 

- Trên Git thì có thể tự do tạo branch. Thế nhưng để sử dụng branch hiệu quả thì trước hết cần thiết phải thiết lập qui tắc vận dụng.

- Ở đây sẽ giới thiệu phương pháp vận dụng đã sử dụng với 2 loại branch là branch chủ đề (Topic branch) và branch tích hợp (Intergration branch).

**Branch tích hợp (Integration branch)**
- Branch tích hợp là branch có thể tạo ra bản phát hành bất cứ khi nào. Hơn nữa, nó cũng được sử dụng như là nguồn phân branch của branch chủ đề. Vì thế, việc duy trì trạng thái ổn định là điều cần thiết.

- Trường hợp tiến hành thay đổi gì đó sẽ thường tạo ra branch chủ đề rồi thực hiện thay đổi. Và việc kiểm tra và build tự động sử dụng công cụ CI như Jenkins chẳng hạn thì sẽ sử dụng branch này để tiến hành.

- Thông thường sẽ sử dụng branch master như là một branch tích hợp.

**Branch chủ đề (Topic branch)**
- Branch chủ đề là branch tạo ra nhằm tiến hành công việc liên quan đến chủ đề như là chỉnh sửa lỗi hay là thêm chức năng. Khi tiến hành cùng lúc những công việc có liên quan đến nhiều chủ đề thì số lượng branch chủ đề tương ứng sẽ được tạo ra.

- Branch chủ đề sẽ tạo ra bằng cách phân branch từ branch tích hợp đã ổn định, khi đã hoàn thành xong công việc sẽ sử dụng đưa vào branch tích hợp.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/vandungbranches.png">

---

<a name="II1.3"></a>

#### 1.3 Chuyển đổi branches

- Để chuyển đổi branch làm việc thì sẽ thực hiện thao tác gọi là checkout. Khi thực hiện checkout, trước tiên nội dung của lần commit cuối cùng trong branch chuyển đến sẽ được mở ra trong work tree. Và commit đã tiến hành sau khi check out thì sẽ được thêm vào branch sau khi di chuyển đến.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/chuyendoibranch_1.png">

**HEAD**

- HEAD là tên hiển thị phần đầu của branch đang sử dụng hiện tại. Mặc định là đang hiển thị phần đầu của master. Bằng việc di chuyển HEAD thì branch đang sử dụng sẽ được thay đổi.


- Khi chỉ định commit, cũng có thể sử dụng dấu ~(tilde) và ^(caret), chỉ định bằng vị trí tương đối từ commit nào đó . Lúc này, HEAD rất hay được sử dụng.

- Bằng việc gắn thêm dấu ~(Tilde) vào phía sau thì có thể chỉ định cha của thế hệ trước nào đó.

^(Caret) thì ở trường hợp mà có nhiều cha do merge branch, có thể chỉ định cha của số thứ mấy nào đó.

Designate the corresponding position from certain commit using tilde and caret

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/chuyendoibranch_1.png">

**Stash**

- Khi những file được thêm mới hay nội dung thay đổi vẫn chưa commit vẫn còn lưu lại Index và Work tree, mà thực hiện checkout đến branch khác thì nội dung thay đổi đó sẽ di chuyển từ branch ban đầu đến branch chuyển đến.

- Tuy nhiên ở branch di chuyển đến, trường hợp có file giống như vậy đã được tiến hành thay đổi cái gì đó thì checkout sẽ thất bại. Khi xảy ra trường hợp này thì sẽ commit lại nội dung thay đổi 1 lần nữa hoặc là sử dụng stash để lưu tạm thời nội dung thay đổi, sau đó phải thực hiện commit.

- Stash là khu vực ghi lại tạm thời nội dung thay đổi của file. Bằng việc sử dụng stash, trong work tree và index, những thay đổi chưa được commit có thể lưu lại tạm thời.

- Những thay đổi lưu tạm này về sau có thể lấy ra và hiển thị trên branch ban đầu hay là phản ánh lên branch khác.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/chuyendoibranch_3.png">

---

<a name="II1.4"></a>

#### 1.4 Tích hợp branches

**Tích hợp branches**
- Branch chủ đề đã hoàn thành công việc, cuối cùng sẽ được tích hợp vào branch tích hợp. Việc tích hợp branch thì có hai phương pháp, phương pháp sử dụng merge và phương pháp sử dụng rebase. 

- Dựa vào việc sử dụng phương pháp nào mà lịch sử của branch sau khi tích hợp sẽ có sự khác biệt lớn.

**Merge**
- Khi sử dụng merge, có thể tổng hợp nhiều luồng lịch sử.

- Ví dụ, có branch bugfix phân nhánh ra từ branch master như sơ đồ bên dưới.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_3.png">

- Khi merge branch bugfix này vào branch master, nếu trạng thái branch master không có gì thay đổi thì có thể thực hiện merge hết sức đơn giản. 

- Vì lịch sử của branch bugfix sẽ bao gồm tất cả lịch sử của branch master, nên branch master chỉ có việc di chuyển đơn giản là có thể lấy được nội dung của branch bugfix. Và, người ta gọi merge như thế này là merge fast-forward (chuyển tiếp nhanh).

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_4.png">

- Nhưng, cũng có trường hợp lịch sử của branch master vẫn đang tiến triển sau khi phân branch bugfix. Trường hợp này thì cần thiết phải tổng hợp nội dung thay đổi của branch master và nội dung thay đổi của branch bugfix thành một.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_5.png">

- Vì thế, merge commit đã lấy thay đổi của cả hai branch sẽ được tạo ra. Đầu branch master sẽ di chuyển đến commit đó.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_6.png">


```
Khi thực hiện merge, bằng việc chỉ định lựa chọn merge non fast-forward, cho dù là trường hợp có thể merge fast-forward thì vẫn có thể tạo ra merge commit mới rồi kết hợp lại.

```
<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_7.png">

```
Khi tiến hành non fast-forward, vì branch vẫn còn nguyên như vậy, nên việc chỉ định công việc đã tiến hành tại branch đó sẽ trở nên đơn giản.

```
**Rebase**

- Giống với ví dụ merge, sẽ có branch bugfix phân nhánh từ branch master như sơ đồ bên dưới.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_8.png">

- Trường hợp sử dụng rebase ở đây rồi tiến hành tích hợp branch thì lịch sử sẽ giống như sơ đồ tiếp theo. Bây giờ, sẽ trình bày đơn giản trình tự rebase như thế nào.

- Trước hết, khi rebase branch bugfix vào branch master, lịch sử branch bugfix sẽ được thay đổi đính kèm sau branch master. Cho nên, lịch sử sẽ thành 1 đường như trong sơ đồ.

- Khi này sẽ có trường hợp phát sinh xung đột tại commit di chuyển X và Y. Lúc đó tại từng commit cần thiết phải chỉnh sửa lại những chỗ phát sinh xung đột.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_9.png">

- Nếu chỉ rebase không thôi thì vị trí đầu master vẫn cứ như vậy. Vì thế, merge branch bugfix từ branch master rồi di chuyển master đến phần đầu của bugfix.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_10.png">

```
NOTE

- Cả merge và rebase đều là tích hợp lịch sử lại với nhau nhưng đặc trưng thì khác nhau.

Merge
- Lịch sử nội dung thay đổi vẫn còn lại nhưng sẽ trở nên phức tạp hơn.


Rebase
- Lịch sử sẽ trở nên đơn giản nhưng nội dung thay đổi từ commit ban đầu sẽ bị thay đổi. Cho nên cũng có trường hợp rơi vào tình trạng commit gốc không hoạt động.

Merge và Rebase thì tùy theo phương châm áp dụng của nhóm mà chia ra sử dụng.

Ví dụ, nếu áp dụng để hợp nhất hóa lịch sử, thì sẽ phân ra sử dụng như sau:

Trường hợp đưa code mới nhất của branch tích hợp vào branch chủ đề thì sử dụng rebase.
Trường hợp đưa branch chủ đề vào branch tích hợp, thì trước hết hãy rebase rồi merge.
```

---

<a name="II1.5"></a>

#### 1.5 Ví dụ vận dụng bằng nhánh chủ đề (topic branch) và nhánh tích hợp (integration branch)

- Ví dụ vận dụng trên branch chủ đề (topic branch) và branch tích hợp (integration branch)

- Về phương pháp vận dụng có sử dụng branch chủ đề và branch tích hợp, sẽ sử dụng ví dụ đơn giản để giải thích.

- Ví dụ, trong khi đang tiến hành công việc thêm chức năng ở branch chủ đề thì có lỗi cần phải sửa.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/topic_integration_branch_1.png">

- Cho dù trong trường hợp như thế này, branch tích hợp vẫn đang ở trạng thái trước khi bắt đầu thêm chức năng, nên bằng việc tạo branch chủ đề dùng sửa lỗi mới từ chỗ này thì việc thêm tính năng có thể độc lập bắt đầu công việc.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/topic_integration_branch_2.png">


- Nội dung sửa lỗi đã hoàn thành, có thể công khai bằng cách đưa vào nhánh tích hợp ban đầu.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/topic_integration_branch_3.png">


- Quay lại nhánh ban đầu có thể tiếp tục công việc thêm chức năng.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/topic_integration_branch_4.png">

- Tuy nhiên, đối với việc tiếp tục công việc thì nội dung của commit X sửa lỗi lúc nãy nhận thấy là cần thiết. Tại đây, đối với việc lấy nội dung của commit X thì có phương pháp merge trực tiếp và phương pháp rebase vào branch tích hợp đã lấy vào commit X.

- Tại đây, đã quyết định rebase vào branch tích hợp.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/topic_integration_branch_5.png">

- Bằng cái này, có thể tiếp tục thêm chức năng ở trạng thái đã đưa vào nội dung của commit X.

```
Với việc sử dụng tốt branch như thế này thì có thể tiến hành song song các công việc.
```

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/topic_integration_branch_6.png">

- Cột 「A successful Git branching model」

```
Chúng tôi khuyên bạn nên tìm những bài viết về "A successful Git branching model" ở http://nvie.com/posts/a-successful-git-branching-model/. Nó bao gồm một trong những phương pháp phổ biến nhất để quản lý Git trong sử dụng nhánh công việc.

Trong mô hình ứng dụng này, phân chia theo sử dụng thành 4 loại branch lớn và vẫn đang phát triển.

- Branch chính (Main branch)
- Branch tính năng(feature branch) (branch chủ đề(topic branch))
- Branch phát hành (release branch)
- Branch sửa lỗi (hotfix branch)
```
**Branch chính (main branch)**
```
- Sử dụng 2 branch master và branch develop như là branch chính.

+ Master
Trên branch master sẽ chỉ quản lý trạng thái có thể release. Và để commit sẽ sử dụng tag rồi ghi mã số release.

+ Develop
Branch develop là branch sử dụng để phát triển thông thường hướng đến trước khi release. Nó sẽ đảm nhiệm vai trò của branch tích hợp đã giải thích trước đó.

```

**Branch tính năng (feature branch)**
```
Trên branch feature, sẽ đảm nhiệm vai trò của branch chủ đề đã được giải thích trước.

Branch này sẽ phân nhánh từ branch develop khi phát triển chức năng mới hay sửa lỗi. Công việc tại branch feature vì cơ bản là không cần chia sẻ nên không quản lý bằng remote. Nếu phát triển hoàn tất, sẽ công khai bằng việc merge vào branch develop.
```

**Branch phát hành (release branch)**

```
- Tại branch release, sẽ tiến hành chuẩn bị release. Và theo quy ước, ở đầu tên branch sẽ thêm release-. Bằng việc tạo branch release, vừa có thể thực hiện chỉnh sửa lần cuối trên branch này cũng như có thể tiến tục phát triển hướng đến release kế tiếp trên branch develop.

- Vì phát triển thông thường sẽ được tiến hành trên branch develop, nên sau khi trạng thái có thể release gần đến sẽ tạo branch release. Sau đó, sẽ tiến hành phát triển như sửa lỗi lần cuối để release chẳng hạn.

- Cuối cùng, khi branch release đã trở thành trạng thái có thể phát hành thì sẽ thực hiện merge vào branch master, rồi thêm tag số release đối với commit đã merge.

- Thêm nữa, vì sẽ đưa vào chỉnh sửa đã tiến hành trên branch release, nên cũng sẽ merge đối với branch develop.

```

**Branch sửa lỗi nhanh (hotfix branch)**

```
- Trường hợp cần chỉnh sửa gấp đối với sản phẩm đã release, thì đây là branch được tạo ra bằng việc phân nhánh từ branch master.

- Như quy ước, đầu của tên branch thì sẽ thêm hotfix-.

- Ví dụ, trong khi việc phát triển trên branch develop vẫn còn ở trạng thái đang tiến hành, mà cần phải nhanh chóng chỉnh sửa. Trong trường hợp này, vì việc tạo ra phiên bản có thể release từ branch develop sẽ mất thời gian, nên sẽ tạo branch trực tiếp từ branch master, rồi tiến hành chỉnh sửa và merge.

- Branch hotfix đã tạo lúc chỉnh sửa cũng sẽ merge rồi đưa vào branch develop.

```

---

## 2. Muốn hiển thị danh sách của branch

```
$ git branch
```
- Khi thêm lựa chọn -r sẽ liệt kê những branch điều khiển từ xa. 
- Khi thêm lựa chọn -a thì có thể hiển thị danh sách cả remote và local branch.

## 3. Muốn tạo branch
```
$ git branch <branchname>
```
- Khi thực hiện lệnh branch mà không chỉ định tham số, thì có thể hiển thị danh sách các branch. Ở đầu có dấu * là branch hiện tại.
```
$ git branch
  issue1
* master
```

## 4. Muốn thay đổi tên branch
```
$ git branch -m <oldbranch> <newbranch>
```

## 5. Muốn xóa branch
```
$ git branch -d <branchname>
```
- Trường hợp có commit chưa được merge vào HEAD thì không thể xóa branch. Để xóa branch có commit chưa được merge cách cưỡng chế thì thêm lựa chọn -D vào rồi thực thi.


## 6. Chuyển đổi branch
```
$ git checkout <branch>
```
- Lệnh này sẽ cho phép thực hiện check out và chuyển sang branch mong muốn.

- Khi thêm lựa chọn -b có thể thực hiện việc tạo branch mới và chuyển đổi sang branch đó chỉ bằng 1 lệnh.

(Để thêm commit vào branch đã tạo mới, thì cần checkout branch đó.

Checkout branch sẽ thực hiện bằng lệnh checkout.)


## 7. Muốn Merge branch
```
$ git merge <branch>
```
- Khi thêm lựa chọn --no-ff thì cho dù là có merge kiểu fast-forward thì commit cũng được tạo ra. 

- Đây là lựa chọn hữu ích khi muốn để lại thông tin branch đã tồn tại.

(Tích hợp thay đổi đã thực hiện trên branch mới vào branch master)

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_1.png">


- Để đưa issue1 vào branch master, thì trước hết sẽ di chuyển đến branch master.
```
$ git checkout master
```
- Sau đó:
```
$ git merge <branch>
```
- Commit chỉ branch master đã di chuyển đến vị trí giống với branch chỉ định. Merger này là merge fast-forward (chuyển tiếp nhanh).

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/Merge_branches_2.png">

```
$ git checkout <branch>
```
```
$ git add <file>
```
```
$ git commit -m "Thêm giải thích pull"
```

**Giải quyết xung đột bằng merge**

Merge branch1 thành công, sau đó merge branch2.

Tự động merge đã thất bại do phát sinh xung đột vì đã thay đổi cùng một dòng với nội dung khác. 

Ở những chổ có xung đột thì Git đang chèn vào phần khác biệt. Hãy sửa lại và commit lại

```
$ git add <file>
$ git commit -m "Thực hiện merge branch2"
```

**Merge bằng rebase**

Khi merge branch2, nếu rebase nhánh branch2 trước thì cũng có thể hợp nhất lịch sử.

Tạm thời, hãy xóa merge trước đó.
```
$ git reset --hard HEAD~
```
History before rabase

Sau khi checkout với branch2, hãy thực hiện rebase đối với master.
```
$ git checkout branch2
```
Switched to branch 'branch2'
```
$ git rebase master
```

- Giống với lúc merge, xung đột tại file sẽ phát sinh nên hãy chỉnh sửa.

- Trường hợp rebase, sau khi đã chỉnh sửa chổ xung đột thì không commit, mà hãy chỉ định lựa chọn *--continue* trong lệnh rebase rồi thực hiện. 

- Giả sử nếu là trường hợp xóa bỏ chính rebase thì hãy chỉ định lựa chọn --abort.

```
$ git add <file>
$ git rebase --continue
```

Như thế, branch master đã có thể merge fast-forward với branch2.

Sau khi checkout branch master hãy thử thực hiện merge.

```
$ git checkout master
```
```
$ git merge branch2
```
---

# III. Thao tác tag

<a name="III1"></a>

## 1. Giới thiệu tag
- Tag là chức năng đặt tên một cách dễ hiểu để có thể dễ dàng tham chiếu commit.

- Trên Git có thể sử dụng 2 loại tag là lightweigh tag và annotated tag. Thêm nữa, tag đã đính kèm một lần là cố định, vị trí không di chuyển được như branch.

  - Lightweigh tag

    - Temporary tag là cái không thể thay đổi

    - Có thể đặt tên

  - Annotated tag
    - Có thể đính kèm tên và email của người thực hiện và ngày
    - Có thể đặt tên
    - Có thể đính kèm bình luận
    - Có thể đính kèm chữ ký

- Annotated tag sẽ trở nên quan trọng khi có kế hoạch đánh dấu commit quan trọng. Thông thường dùng để đánh dấu commit dùng để release và cũng có thể thêm những chú thích bên cạnh.

- Mặt khác lightweigh tag thì chủ yếu được dùng trên không gian local làm việc tạm thời.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/tag_1.png">

```
Bằng việc reset mô tả ở [Thay đổi commit] hay chỉ định tên tag rồi checkout thì có thể dễ dàng quay lại trạng thái định trước trong quá khứ.
```
---

<a name="III2"></a>

## 2. Muốn hiển thị danh sách của tag
```
$ git tag
```
- Khi thêm lựa chọn -n thì có thể hiển thị chú thích được thêm vào trong tag.
---

<a name="III3"></a>

## 3. Muốn tạo tag
```
$ git tag <tagname>
```
---

<a name="III4"></a>

## 4. Muốn tạo tag có gắn kèm chú thích
```
$ git tag -a <tagname>
```
---

<a name="III5"></a>

## 5. Muốn xóa tag
```
$ git tag -d <tagname>
```

---

<a name="III6"></a>

## 6. Hướng dẫn sử dụng tag
Hãy thử sử dụng tag!

### 6.1 Chuẩn bị trước
Trước tiên hãy tạo thư mục mới, rồi tạo repository trống ở đó. Ở đây đã tạo thư mục có tên là tutorial

```
$ mkdir tutorial
$ cd tutorial
$ git init

```

Ở thư mục tutorial, tạo file có tên là file_example.txt với nội dung như bên dưới rồi commit.

Lệnh Git mà ngay cả khỉ cũng hiểu.


```

$ git add file_example.txt
$ git commit -m "first commit"

```
- Lịch sử tại thời điểm này thì như bên dưới.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/tag_2.png">

### 6.2 Thêm lightweight tag

- Để thêm tag, thì sử dụng lệnh tag. Trong <tagname> sẽ chỉ định tên tag.

```
$ git tag <tagname>
```
Để thêm tag có tên là apple trong commit mà HEAD hiện đang chỉ đến, thì hãy chạy lệnh bên dưới.

```
$ git tag apple
```
Nếu chạy lệnh tag mà không có tham số, thì có thể hiển thị danh sách tag.

```
$ git tag

apple
```

- Và, khi thực hiện lệnh log có gắn lựa chọn *--decorate*, thì có thể hiển thị lịch sử bao gồm thông tin tag.

```
$ git log --decorate
```
<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/tag_3.png">


### 6.3 Thêm annotated tag

- Để thêm annotated tag, hãy chỉ định lựa chọn -a trong lệnh tag rồi thực hiện. Khi thực hiện thì trình soạn thảo sẽ khởi động nên hãy nhập bình luận sẽ thiết lập trong tag.

- Cũng có thể chỉ định lựa chọn -am nếu muốn vừa tạo tag vừa thêm bình luận.

```
$ git tag -a <tagname>
```
- Để gắn annotated tag có tên là banana trong commit mà HEAD hiện đang chỉ đến, thì hãy thực hiện lệnh bên dưới.

```
$ git tag -am "Vi du" 

banana
```
- Khi chỉ định lựa chọn -n rồi thực hiện lệnh tag, thì có thể hiển thị danh sách tag và bình luận.

```
$ git tag -n

apple           first commit
banana          Vi du
```
<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/tag_4.png">

### 6.4 Xóa tag

- Để xóa tag, hãy chỉ định lựa chọn -d trong lệnh tag rồi thực hiện.

```
$ git tag -d <tagname>
```
<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/tag_5.png">

---
<a name="IV1"></a>

# IV. Thiết lập kết nối SSH

## 1. Muốn thiết lập kết nối SSH (Windows)

- Từ menu Start > All Programs > Mở TortoiseGit và khởi động Putty Key Generator.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_win_1.png">

- Nhấn vào nút , cho đến khi tiến trình hoàn tất thì hãy di chuyển chuột di động trong khung tô đỏ. Ở đây sẽ tạo ra key ngẫu nhiên.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_win_2.png">

- Khi hoàn tất việc tạo thành key thì màn hình sẽ thay đổi như bên dưới. Nhấn vào nút , lưu lại file .ppk.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_win_3.png">

- Và đoạn ký tự được hiển thị trong [Public key] là nội dung của khóa công khai (public key). Khóa công khai này có thể hiển thị lại bằng việc nhấn vào nút để đọc lại file ppk.

- Trường hợp thiết lập kết nối SSH khi push thì nhấn chuột phải vào menu TortoiseGit, sau đó chọn .

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_win_4.png">

- Ở *[Remote]* nhập "origin", ở [URL] nhập đường dẫn của SSH, ở [Putty key] thì chỉ định file ppk đã lưu khi nãy rồi nhấn vào nút . Origin sẽ được thêm vào danh sách Remote nên hãy nhấn vào nút .

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_win_5.png">



<a name="IV2"></a>

## 2. Muốn thiết lập kết nối SSH (Mac)

- Ở trong thư mục application/utility khởi động terminal, tiếp theo thực hiện lệnh như sau

```
$ ssh-keygen
```

- Như thế thì nội dung xuất ra như bên dưới sẽ được hiển thị, hãy nhập chuỗi ký tự thiết lập vào passphrase và enter key vào những chỗ cần thiết.

- Trường hợp không thiết lập cho passphrase thì ở vị trí nhập của passphrase không nhập gì cả chỉ nhập vào enter key.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_mac_1.png">


- Nội dung khóa công khai SSH (public SSH key) sinh ra thì có thể xác nhận được bằng lệnh bên dưới.

```
$ cat ~/.ssh/id_rsa.pub
```

- Ví dụ kết quả xuất ra

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_mac_2.png">

- Sau nữa thì hãy thiết lập khóa công khai này vào remote repository.

<a name="IV3"></a>

## 3. Muốn thiết lập kết nối SSH (Console)

- Hãy thực hiện câu lệnh bên dưới.

```
$ ssh-keygen
```

- Khi đó kết quả xuất ra như bên dưới sẽ được hiển thị, hãy nhập chuỗi ký tự thiết lập vào passphrase và enter key vào những chổ cần thiết.

- Trường hợp không thiết lập cho passphrase thì ở vị trí nhập của passphrase không nhập gì cả chỉ nhập vào enter key.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_console_1.png">

- Nội dung khóa công khai SSH (public SSH key) sinh ra thì có thể xác nhận được bằng lệnh bên dưới.

```
$ cat ~/.ssh/id_rsa.pub
```

- Ví dụ kết quả xuất ra

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_console_2.png">

- Sau nữa thì hãy thiết lập khóa công khai này vào remote repository.



<a name="IV4"></a>

## 4. Muốn thiết lập khóa SSH trong Backlog

- Sao chép SSH public key vào khay nhớ tạm của bạn.

Nếu tệp khóa công khai SSH của bạn có tên khác với mã ví dụ, hãy sửa đổi tên tệp để phù hợp với thiết lập hiện tại của bạn. Khi sao chép khóa của bạn, không thêm bất kỳ dòng mới hoặc khoảng trắng nào.

```
$ clip < ~/.ssh/id_ed25519.pub
# Copies the contents of the id_ed25519.pub file to your clipboard

```

*Mẹo: Nếu clipkhông hoạt động, bạn có thể tìm *.ssh* thư mục ẩn , mở tệp trong trình soạn thảo văn bản yêu thích của bạn và sao chép nó vào khay nhớ tạm.*

- Hãy đăng nhập bằng User sử dụng Git repository trong Backlog, nhấn vào [Setting].

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_backlog_1.png">

- Trong thanh bên cài đặt người dùng, nhấp vào SSH and GPG keys

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_backlog_2.png">

- Click New SSH key or Add SSH key

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_backlog_3.png">

- Trong trường "Title", hãy thêm nhãn mô tả cho khóa mới. Ví dụ: nếu bạn đang sử dụng máy Mac cá nhân, bạn có thể gọi khóa này là "MacBook Air cá nhân".

- Dán khóa của bạn vào trường "Key".

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_backlog_4.png">

- Click Add SSH key

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_backlog_5.png">

- Nếu được nhắc, hãy xác nhận mật khẩu GitHub của bạn.

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/ssh_backlog_6.png">

[*Đọc thêm*](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)


<a name="V1"></a>

# V. Thao tác commit log

## 1. Muốn chỉnh sửa nội dung commit ngay trước đó

```
$ git commit --amend
```

- Khi chỉ định lựa chọn *--amend* rồi commit thì có thể ghi đè lên commit trên cùng của branch hiện tại.


<a name="V2"></a>

## 2. Chỉ muốn sửa phần giải thích của commit ngay trước đó

```
$ git commit --amend
```

- Ở tình trạng file chưa được đăng ký trong index chỉ định lựa chọn *--amend* rồi tiến hành commit lại. Màn hình để nhập giải thích sẽ được hiển thị, hãy sửa lại phần giải thích.



<a name="V3"></a>

## 3. Muốn chỉnh sửa nội dung commit trong quá khứ

```
$ git rebase -i <commit>
```

Khi chỉ định commit cũ hơn commit đã chỉ định thì danh sách commit sẽ được hiển thị. Trong danh sách đó tìm commit muốn chỉnh sửa, và thay đổi dòng đó từ "pick" thành "edit", lưu lại rồi kết thúc.

Tiếp theo biên tập lại file muốn chỉnh sửa, sau khi lưu lại thì chỉ định lựa chọn *--amend* rồi thực hiện commit.

```
$ git commit --amend
```

Cuối cùng, chỉ định lựa chọn *--continue* rồi thực hiện rebase.

```
$ git rebase --continue
```



<a name="V4"></a>

## 4. Chỉ muốn sửa phần giải thích của commit trong quá khứ

```
$ git rebase -i <commit>
```

Khi chỉ định commit cũ hơn commit đã chỉ định thì danh sách commit sẽ được hiển thị. Trong danh sách đó tìm commit muốn chỉnh sửa, và thay đổi dòng đó từ "pick" thành "edit", lưu lại rồi kết thúc.

Tiếp theo, chỉ định lựa chọn *--amend* rồi thực hiện commit. Màn hình để nhập giải thích sẽ được hiển thị, thực hiện chỉnh sửa giải thích.

```
$ git commit --amend
```

Cuối cùng, chỉ định lựa chọn --continue rồi thực hiện rebase.

```
$ git rebase --continue
```



<a name="V5"></a>

## 5. Muốn bỏ rebase đang thực hiện

```
$ git rebase --abort
```

Chỉ định lựa chọn *--abort* rồi thực hiện lệnh rebase thì có thể ngừng rebase.



<a name="V6"></a>
## 6. Muốn xem lịch sử thay đổi của HEAD
```
$ git reflog
```
Bằng việc thực hiện lệnh reflog thì có thể xem danh sách của commit đã được chỉ định bởi HEAD trong quá khứ.
```
08084a5 HEAD@{0}: commit: thêm giải thích của pull
99daed2 HEAD@{1}: commit: thêm giải thích của commit
48eec1d HEAD@{2}: checkout: di chuyển từ master sang issue1
326fc9f HEAD@{3}: commit: thêm giải thích của add
48eec1d HEAD@{4}: commit (initial): commit đầu tiên
```

Ở danh sách này những commit đã xóa, hay rebase chẳng hạn thì có thể gom theo loại commit để hiển thị.


<a name="V7"></a>
## 7. Muốn xem lịch sử thay đổi của branch đầu

```
$ git reflog <ref>
```

Chỉ định tên của branch trong <ref>, rồi thực thi bằng lệnh reflog thì có thể xem danh sách của commit được chỉ định bởi branch đầu đó trong quá khứ với hình dạng như bên dưới.

```
445e0ae issue1@{0}: commit (merge): Merge branch master vào issue1
1c904bd issue1@{1}: commit (amend): Chỉnh sửa giải thích của pull
08084a5 issue1@{2}: commit: Thêm giải thích của pull
99daed2 issue1@{3}: commit: Thêm giải thích của commit
48eec1d issue1@{4}: branch: Tạo từ 48eec1ddf73a7fb508ef664efd6b3d873631742f
```

Ở danh sách này những commit đã xóa, hay rebase chẳng hạn thì có thể gom theo loại commit để hiển thị.



<a name="V8"></a>

## 8. Muốn xem như không có commit ngay trước đó

```
$ git reset --hard HEAD~

```

<a name="V9"></a>

## 9. Muốn xem như không có rebase

```
$ git reset --hard <commit>
```

-  Trước tiên sử dụng lệnh reflog, tìm kiếm commit trước khi rebase, xác định giá trị hash của commit đó hay giá trị của [HEAD@{số}]. 

- Lịch sử bên dưới là lịch sử sau khi commit update2, bằng lệnh rebase gom 2 commit lại, 71bdfbd hay HEAD@{4} là commit phù hợp.
```
a51f8d2 HEAD@{0}: rebase -i (finish): returning to refs/heads/dev
a51f8d2 HEAD@{1}: rebase -i (squash): update 1
3a273e1 HEAD@{2}: rebase -i (squash): updating HEAD
f55ef69 HEAD@{3}: checkout: moving from dev to f55ef69
71bdfbd HEAD@{4}: commit: update 2
f55ef69 HEAD@{5}: commit (amend): update 1

```
- Giá trị hash tìm thấy đó (71bdfbd and HEAD@{4}) chỉ định trong <commit> rồi thực hiện lệnh reset.

- Cái này thì tùy thuộc vào rebase mà vị trí đầu của branch di chuyển sẽ quay lại vị trí commit trước khi rebase, nghĩa là xem như không có rebase.


<a name="V10"></a>

## 10. Muốn xem như không có reset ngay trước đó

```
$ git reset --hard ORIG_HEAD
```

Commit trước khi reset thì bằng tên ORIG_HEAD có thể tham chiếu được, cho nên chỉ định cái này rồi reset.


<a name="V11"></a>

## 11. Muốn di chuyển commit bị sai sang branch khác

```
$ git cherry-pick "<commit>"
```

Sao chép commit chỉ định trong <commit> sang branch hiện tại.


<a name="V12"></a>

## 12. Muốn tìm kiếm commit bao hàm bình luận đặc định

```
$ git log --grep "<pattern>"
```

Chỉ hiển thị những commit bao hàm commit log có chứa những ký tự được thiết lập trong <pattern>.

[*Đọc thêm*](https://backlog.com/git-tutorial/vn/stepup/stepup6_1.html)


---

<a name="VI1"></a>

# VI. Thao tác Remote

## 1. Muốn nhân ra nhiều remote repository có sẵn

```
$ git clone <url>
```

- Trường hợp nhân bản bằng lệnh clone, thì việc theo dõi remote repository sẽ được tự động thiết lập.

- Tùy thuộc vào thiết lập này, khi thực hiện các lệnh push và fetch/pull về sau thì cho dù có tĩnh lược repository đi chăng nữa thì nội dung thay đổi cũng có thể phản ánh/ lấy đúng.

<a name="VI2"></a>

## 2. Muốn thêm remote repository

```
$ git remote add <name> <url>

```


<a name="VI3"></a>

## 3. Muốn hiển thị danh sách remote repository

```
$ git remote
```

Khi thêm lựa chọn -v thì có thể hiển thị chi tiết của remote repository.



<a name="VI4"></a>

## 4. Từ branch của remote repository muốn tạo branch của local repository

```
$ git checkout <branch>
```

- Với phiên bản gần đây của Git thì khi chỉ định branch đã tồn tại trong remote repository vào trong tham số của lệnh checkout thì có thể tạo branch trên local repository từ branch của remote repository.

- Trường hợp không thể tạo được do phiên bản cũ thì hãy tạo branch bằng lệnh branch như bên dưới.

```
$ git branch <branchname> origin/<branch>
```




<a name="VI5"></a>

## 5. Muốn tạo branch trong remote repository / muốn phản ánh nội dung thay đổi trong branch

```
$ git push <repository> <refspec>

```

- Khi thêm lựa chọn -u thì có thể theo dõi đối tượng branch trong remote repository. Tùy thuộc vào việc này, khi thực hiện các lệnh push và fetch/pull về sau thì cho dù có tĩnh lược repository đi chăng nữa thì nội dung thay đổi cũng có thể phản ánh/ lấy đúng.

- Trong <respository> bằng lệnh remote add thì ngoài việc thêm tên repository thì cũng có thể trực tiếp chỉ định URL. Khi tĩnh lược repository thì remote repository đang theo dõi sẽ trở thành đối tượng được chỉ định.

- Trong <refspec> thì có thể chỉ định tên của branch. Khi tĩnh lược refspec, thì mặc định là branch tồn tại trong cả hai nơi local repository và remote repository sẽ trở thành đối tượng.



<a name="VI6"></a>

## 6. Muốn xác nhận nội dung thay đổi trong branch của remote repository

```
$ git fetch <repository> <refspec>

```

- Trường hợp muốn xác nhận nội dung thay đổi ở remote repository nhưng không muốn phản ánh những nội dung đó trong local repository thì sử dụng lệnh fetch. Lệnh fetch thì branch của local repository sẽ không bị thay đổi.

- Có thể tĩnh lược repository và refspec. Các thao tác của trường hợp tĩnh lược repository thì giống với khi push. Khi tĩnh lược refspec thì mặc định là tất cả branch sẽ trở thành đối tượng.




<a name="VI7"></a>

## 7. Muốn lấy nội dung thay đổi trong branch của remote repository

```
$ git pull <repository> <refspec>
```

- Tùy thuộc vào lệnh pull mà nội dung thay đổi của remote repository sẽ được phản ánh trong branch của local repository. Có thể hiểu đơn giản là "pull = fetch + merge".

- Có thể tĩnh lược repository và refspec. Các thao tác của trường hợp tĩnh lược repository thì giống với khi push. Khi tĩnh lược refspec thì branch hiện tại sẽ trở thành đối tượng.



<a name="VI8"></a>

## 8. Muốn xóa branch của remote repository

```
$ git push --delete <repository> <branchname>
```

- Trong lệnh push chỉ định lựa chọn *--delete* với *<tên remote repository> <tên branch muốn xóa>* rồi thực hiện.

- Từ phiên bản git 1.7 trở về trước thì lựa chọn *--delete* không thể sử dụng được, nên hãy thực hiện chỉ định như bên dưới:

```
$ git push <repository> :<branchname>
```


<a name="VI9"></a>

## 9. Muốn tạo tag trong remote repository

```
$ git push <repository> <tagname>
```

- Khi thêm lựa chọn -tags vào thì có thể tạo tất cả tag đã tồn tại ở local repository vào remote repository.


<a name="VI10"></a>

## 10. Muốn xóa tag của remote repository

```
$ git push --delete <repository> <tagname>
```

- Trong lệnh push chỉ định lựa chọn *--delete* với *<tên remote repository> <tên của tag muốn xóa>* rồi thực hiện

- Từ phiên bản git 1.7 trở về trước thì lựa chọn *--delete* không thể sử dụng được, nên hãy thực hiện chỉ định như bên dưới:

```
$ git push <repository> :<tagname>
```



<a name="VI11"></a>

## 11. Muốn thay đổi địa chỉ của remote repository đã đăng ký xong

```
$ git remote set-url <name> <newurl>

```


- Bằng tên đã chỉ định, thay đổi địa chỉ của remote repository đang được đăng ký vào địa chỉ của *[newurl]*



<a name="VI12"></a>

## 12. Muốn thay đổi tên của remote repository đã đăng ký xong

```
$ git remote rename <old> <new>
```

- Thay đổi tên của remote repository đang được đăng ký chỉ định trong *[old]* bằng *[new]*.

---


<a name="VII1"></a>

# VII. Thiết lập Git

## 1. Muốn thiết lập tên người dùng / địa chỉ email

```
$ git config --global user.name <username>
$ git config --global user.email <mailaddress>
```

- Khi không thêm lựa chọn *--global* thì chỉ những repository có liên quan mới trở nên hữu hiệu với thiết lập.

<a name="VII2"></a>

## 2. Muốn tô màu kết quả xuất ra

```
$ git config --global color.ui auto
```

<a name="VII3"></a>

## 3. Muốn thiết lập bí danh trong lệnh

```
$ git config --global alias.<aliasname> <commandname>
```

<a name="VII4"></a>

## 4. Muốn bỏ ra ngoài đối tượng quản lý những file không cần thiết

```
$ echo <filename> >> .gitignore
```

- Tên file có *.gitignore* trong đó là ngoài đối tượng quản lý của Git. Và bản thân của *.gitignore* cũng cần thiết phải commit sẵn.


<a name="VII5"></a>

## 5. Muốn các thư mục rỗng nằm trong đối tượng quản lý

```
$ cd <dirname>
$ touch .gitkeep
```

- Ở Git thì thư mục rỗng sẽ không là đối tượng quản lý. Chính vì vậy, cần thiết phải đặt file tùy ý vào trong thư mục. 

Tên file thì bất cứ là gì cũng không sao, nhưng theo thói quen thì rất nhiều trường hợp sử dụng tên file là *.gitkeep*.



<a name="VII6"></a>

## 6. Muốn hiển thị danh sách thiết lập

```
$ git config --global --list

```

<a name="VII7"></a>

## 7. Muốn thông qua proxy server kết nối http

- Trong mục http của file .gitconfig thì thêm thiết lập như bên dưới.

```
[http]
proxy = <address of the proxy server>:<port of the proxy server>
```

Bằng lệnh config cũng có thể thiết lập như bên dưới:

```
$ git config --global http.proxy <address of the proxy server>:<port of the proxy server>
```

<a name="VII8"></a>

## 8. Muốn thông qua proxy server có cần thiết chứng thực người sử dụng để kết nối http

Trong mục http của file .gitconfig thì thêm thiết lập như bên dưới.

```
[http]
proxy = http://<username>:<password>@<address of the proxy server>:<port of the proxy server>
```

Bằng lệnh config cũng có thể thiết lập như bên dưới.

```
$ git config --global http.proxy http://<username>:<password>@<address of the proxy server>:<port of the proxy server>
```

---

<a name="VIII1"></a>

# VIII. Stash

## 1. Muốn tạm thời lưu lại công việc hiện tại

```
$ git stash save
```

Có thể tĩnh lược save. Và phía sau của save có thể thực hiện chỉ định nội dung giải thích hiển thị.

<a name="VIII2"></a>

## 2. Muốn hiển thị danh sách công việc lưu tạm

```
$ git stash list
```

<a name="VIII3"></a>

## 3. Muốn quay lại tiếp tục công việc lưu tạm

```
$ git stash pop
```

Khi không chỉ định tham số sẽ phục hồi lại công việc mới nhất trong số công việc lưu tạm.

Bằng việc chỉ định tham số theo kiểu stash@{1} thì có thể phục hồi lại công việc mong muốn.

<a name="VIII4"></a>

## 4. Muốn xóa công việc lưu tạm

```
$ git stash drop
```

Khi không chỉ định tham số sẽ xóa công việc mới nhất trong số công việc lưu tạm.

Bằng việc chỉ định tham số theo kiểu stash@{1} thì có thể xóa công việc mong muốn.

<a name="VIII5"></a>

## 5. Muốn xóa tất cả công việc lưu tạm

```
$ git stash clear
```

---

<a name="IX1"></a>

# IX. So sánh Git-Subversion

- Đây là biểu đồ so sánh lệnh của *Git* với *Subversion*

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/git_subversion_1.png">

*Note*

<img src="https://github.com/lnkngoc/Git_Tutorial_For_Beginer/blob/main/images/git_subversion_2.png">

---


<a name="X1"></a>

# X. Xử lý sự cố

### 1. SSH

*Lỗi "Permission denied (publickey)" khi dự định kết nối vào remote repository bằng SSH*

- Trước hết, phải đảm bảo những vấn đề sau:

  - URL có đúng không?
  
  - Ở máy local khóa bí mật (serect key) có được thiết lập đúng hay không?

  - Ở remote khóa công khai (public key) có được thiết lập đúng hay không?

- Đối với repository trên Backlog để xác nhận khóa bí mật (serect key) / khóa công khai (public key) có được thiết lập đúng hay không thì thực hiện lệnh như bên dưới:

```
$ ssh <space>@<space>.git.backlogtool.com
```
- Ở **space** thì thay thế bằng space sở hữu thích hợp (Ví dụ. nếu space đang sử dụng là 'demo.backlogtool.com', thì thay bằng 'demo@demo.git.backlogtool.com')

- Trường hợp được thiết lập đúng thì log như bên dưới sẽ được xuất ra. Trường hợp mà thông báo lỗi được hiển thị thì hãy xem lại và sửa lại thiết lập như bên trên.

```
Hi yourname! You've successfully authenticated, but Backlog does not provide shell access.
Connection to git.backlogtool.com closed.
```

<a name="X2"></a>

### 2. HTTPS

*Không thể clone remote repository bằng HTTPS URL
Mỗi lần push/pull từ remote repositoy thì đều bị hỏi mật khẩu*

- Ở phiên bản Git cũ thì cũng có trường hợp không thể thực hiện push và pull. Cho nên hãy sử dụng phiên bản 1.7.10 trở về sau. Những bạn đang sử dụng SourceTree và TortoiseGit thì xin hãy kiểm tra phiên bản mà mình đang sử dụng.


<a name="X3."></a>

## 3. SSH/HTTPS

### 3.1 *Cho dù đã push nhưng vẫn không phản ánh trên remote repository*

- Tạo mới repository, rồi clone, rồi tạo local repository, và ở trên local repository đó rồi thực hiện push thì cũng có trường hợp log như bên dưới được xuất ra.

```
$ git push
No refs in common and none specified; doing nothing.
Perhaps you should specify a branch such as 'master'.
Everything up-to-date
```

- Cái này là do trên remote branch thì master branch chưa được tạo ra. Trường hợp tham số khi push được tĩnh lược thì mặc định là branch tồn tại ở cả 2 remote repository với local repository sẽ trở thành đối tượng. 

- Chính vì vậy, trường hợp thực hiện push branch không tồn tại trong remote repository thì cần thiết phải chỉ định rõ repository và branch.

```
$ git push -u origin master
```

- Khi thực hiện push 1 lần thì master branch sẽ được tạo ra, do đó những lần push sau thì cũng có thể tĩnh lược việc chỉ định repository và branch.


<a name="X3.2"></a>

### 3.2 *Mỗi lần push/pull từ remote repositoy thì đều bị hỏi mật khẩu*

- Ở phiên bản Git 1.7.10 trở về sau thì tùy thuộc vào chứng thực API được trang bị sẵn trong Git và Helper chứng thực sử dụng cái đó thì có thể tránh được việc phải nhập lại mật khẩu.

- **Windows**
Sử dụng công cụ có tên là [git-credential-winstoreu](https://github.com/Microsoft/Git-Credential-Manager-for-Windows) thì từ lần thứ 2 trở đi việc nhập mật mã sẽ không cần thiết nữa.

- **Mac**
Ở phần nhập môn và phần phát triển trong GuiClient của Mac đã có đề cập, chức năng liên kết SourceTree với Mac Keychain đã được chuẩn bị như là chức năng chuẩn. Sử dụng chức năng này thì mỗi lần pull và push thì không cần phải thực hiện việc nhập mật khẩu.

- **Console**
Ở Mac, thì có thể sử dụng Git's credentials API để liên kết username/password với thao tác Git. Nếu như sử dụng Homebrew thì Git credential API sẽ tự động được cài đặt. Ngoài những trường hợp đó ra thì cần thiết phải cài đặt bằng tay.

Có thể kiểm tra credential API đã được cài đặt bằng lệnh bên dưới.

```
$ git credential-osxkeychain
Usage: git credential-osxkeychain <get|store|erase>
```

Nếu như credential API chưa được cài đặt thì nội dung xuất ra như bên dưới sẽ được hiển thị.

```
$ git credential-osxkeychain
git: 'credential-osxkeychain' is not a git command. See 'git --help'.
```

Trong trường hợp đó thì có thể tải nó về và di chuyển files đến /usr/local/bin

```
curl -s -O http://github-media-downloads.s3.amazonaws.com/osx/git-credential-osxkeychain
chmod u+x git-credential-osxkeychain
mv git-credential-osxkeychain /usr/local/bin
```

Sau khi đã hoàn thành cài đặt thì chạy lệnh bên dưới để kích hoạt credential API.

```
git config --global credential.helper osxkeychain
```

