# Website_Tutorial 



**使用XAMPP建立網頁伺服器，再將程式碼放入指定位置，完成成績分析網站的建立。** 
> *XAMPP是一個把Apache網頁伺服器與PHP、Perl及MariaDB集合在一起的安裝包，允許用戶可以在自己的電腦上輕易的建立網頁伺服器。*



## **步骤**
**本实验为windows环境下**
### 安裝XAMPP

![](https://github.com/fcu-d0573754/website_tutorial/raw/master/Picture/xampp.png)

具體安裝參考[鏈接網址](https://ithelp.ithome.com.tw/articles/10197921)

安裝完成後，點擊下圖紅色里的`Start`，此時將開啟Apache和MySQL

<img src="https://github.com/fcu-d0573754/website_tutorial/raw/master/Picture/xampp_2.png" width = "450" height = "350" >

用[http://localhost/](http://localhost/)網址來連線XAMPP網絡服務，成功將看到如下圖

![](https://github.com/fcu-d0573754/website_tutorial/raw/master/Picture/xampp_3.png)

### 下載網頁程式碼

下載此專案上的`HTML5-BayesNet-Tools-master`文件夾

打開XAMPP所在的資料夾下的`htdocs`資料夾

將之前下載的`HTML5-BayesNet-Tools-master`文件夾里資料複製到`htdocs`資料夾，如圖所示：

<img src="https://github.com/fcu-d0573754/website_tutorial/raw/master/Picture/xampp_4.png" width = "450" height = "350" >

此時雙擊此目錄下的`index.html`，即可跳轉至首頁

由於此次成績分析只需要跳轉至貝式頁面,請點選首頁的`BayesNet Viewer`鏈接

若成功會出現如圖所示的頁面

<img src="https://github.com/fcu-d0573754/website_tutorial/raw/master/Picture/web_1.png" width = "450" height = "350" >

> *通過此頁面可以在線產生貝式網絡分析出的結果，點選頁面中的`選擇檔案`上傳需要分析的XML檔案*
 
**到此本地端網站架設成功！！**

### 外網訪問

由於剛剛架設的網站只是能本地端訪問，外部人員無法存取此頁面

故需要如下幾個步驟：

- 打開https-xampp.conf文件
- 查找Require local
- 將這行注釋 變成＃Require local

即可完成外網訪問

其中此網址就是本機的IP地址

本地端[IP地址查詢參考網址](https://kknews.cc/zh-tw/game/nmx6jv3.html)

知道IP后就可以直接在瀏覽器上輸入IP鏈接到本網站




