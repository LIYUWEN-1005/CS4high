process managment CPU排程
行程    管理
----------------------------
```
memory  managment
記憶體   管理
(CPU)-------cahe快取
            L1 xxk
            L2 xxM
            L3 xxM

RAM  4GB  12GB

Hard

Swap 虛擬記憶體
```
----------------------------
協調工作
----------------------------
task managment  
工作管理員
----------------------------
怎麼知道連線(必考)
```
netstat -ano
-a	顯示所有活動中的網路連接和電腦正在監聽的TCP/UDP埠。
-n	顯示活動中的TCP連接，但主機位址和埠號以數字形式表示，不會嘗試確定實際主機名。
-o	顯示活動中的TCP連接，並包含每個連接的行程ID（PID）。根據PID，可在Windows工作管理員的「行程」索引標籤中找到該應用程式。此參數可以與-a、-             n和-p組合使用。如果安裝了Windows修補程式，則此參數在Windows XP、Windows Server 2003和Windows 2000上可用。
```
----------------------------
