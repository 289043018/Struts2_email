# Struts2_email
使用struts2代理发送邮件
正如上面的源代码中看到的，Emailer.java 有对应于下面给出的email.jsp页面中的表单属性的属性。这些属性是：

from - 发件人的电子邮件地址。由于我们使用的是谷歌的 SMTP，因此我们需要一个有效的 gtalk id。
password - 上述帐户的密码
to - 给谁发送电子邮件？
Subject - 电子邮件的主题
body - 实际的电子邮件消息
