## nohup java -jar jodconverter-web-1.5.8.RELEASE.war >fileOnlineLog.txt &  

�ֱ�������
startFileOnlineServer.bat
startEurekaServer.bat
startAdminServer.bat
startZuulServer.bat

#��ý����Դ����Ԥ������
java -jar jodconverter-web-1.5.8.RELEASE.war

#����ע������
java -jar mycloud-eureka-1.0.0.war

#������̨����
java -jar mycloud-admin.war

#��������
java -jar mycloud-zuul-1.0.0.war