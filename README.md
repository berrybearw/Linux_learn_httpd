# Linux_learn_httpd
httpd 安全性設定

# httpd 安全性設定

參考 :
* [https://www.ltsplus.com/linux/disable-selinux](https://www.ltsplus.com/linux/disable-selinux)
* [https://help.aliyun.com/document_detail/157022.html](https://help.aliyun.com/document_detail/157022.html)
* [https://limsing.medium.com/solved-permission-denied-error-show-in-apache-logs-when-used-as-a-reverse-proxy-b9497c55100b](https://limsing.medium.com/solved-permission-denied-error-show-in-apache-logs-when-used-as-a-reverse-proxy-b9497c55100b)

![image](https://user-images.githubusercontent.com/96226780/202847603-3048fdfe-a7dd-43be-9395-4d58ab89b400.png)

apache http 設定
---

* [https://ithelp.ithome.com.tw/articles/10225101](https://ithelp.ithome.com.tw/articles/10225101)

SELinux 簡介
---

參考 :
* [https://wiki.centos.org/zh-tw/TipsAndTricks/SelinuxBooleans](https://wiki.centos.org/zh-tw/TipsAndTricks/SelinuxBooleans)
* [https://www.cnblogs.com/pengyunjing/p/10663135.html](https://www.cnblogs.com/pengyunjing/p/10663135.html)

設定範例 
---

`Permission denied: AH00957`

SELinux 調整

`/usr/sbin/setsebool -P httpd_can_network_connect 1`
