QuestionAnsweringSystem��һ��Javaʵ�ֵ��˻��ʴ�ϵͳ���ܹ��Զ��������Ⲣ������ѡ�𰸡�


ʹ��˵����

1����ʼ��MySQL���ݿ⣺   
	��MySQL��������ִ��QuestionAnsweringSystem\src\main\resources\mysql\questionanswer.sql�ļ��еĽű�
	MySQL������127.0.0.1���˿ڣ�3306�����ݿ⣺questionanswer���û�����root�����룺root
	
2������war�ļ�������tomcat��
	cd QuestionAnsweringSystem
	mvn install
	cp target\QuestionAnsweringSystem-1.0.war apache-tomcat-7.0.37/webapps/QuestionAnsweringSystem-1.0.war
	����tomcat
	
3������������ʣ�
	http://localhost:8080/QuestionAnsweringSystem-1.0/