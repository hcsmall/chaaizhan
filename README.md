# chaaizhan
原链接：https://github.com/langsasec/chaaizhan

langsasec大佬写的很好，但是代码在执行过程中会出现点问题，就是在频繁查询的时候会出现，网站查询无数据的情况，这个时候会出现报错。

大佬的逻辑是查询完成后统一写入xls文件中，那么在运行过程中报错就会导致文件无法保存，我做了点点小小的改动，报错打印出来跳过。

亲测150W域名不结束程序
