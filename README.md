# -
自用规则

发现个问题，clash调用规则集，yaml文件内容只有匹配方式和域名是不行的，要有payload开头才可以，困惑了我两天，加入payload之前一直调用失败。但是loon是可以正常调用的。
最初是下图这样的写法：
![error](https://github.com/user-attachments/assets/d9a77d86-7312-4060-9b66-42dd3737ae94)
但是规则集更新失败（下面两个），对比上面两个成功的（来自于[blackmatrix7](https://raw.githubusercontent.com/blackmatrix7)）
![问题表现](https://github.com/user-attachments/assets/e1fa319a-6129-4deb-aa7b-887794c4f429)
后面仿照[blackmatrix7](https://raw.githubusercontent.com/blackmatrix7)的规则格式加入了payload：
![right](https://github.com/user-attachments/assets/691016e5-416c-441d-88aa-324c9a5ccee9)
就可以正常使用了。
![afteredit](https://github.com/user-attachments/assets/9b662a79-0f52-46c8-9ed6-d43ffe6968b2)
问几个ai，也都不知道关键是哪里出了问题，果然成功还是要靠借鉴😭
