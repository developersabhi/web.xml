<?xml version="1.0" encoding="UTF-8"?>
<web-app version="2.5" xmlns="http://JAVA.sun.com/xml/ns/javaee"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd">

  <display-name>Archetype Created Web Application</display-name>
  <servlet>
		<servlet-name>MyMvc</servlet-name>
		<servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
	</servlet>
		
	<servlet-mapping>
		<servlet-name>MyMvc</servlet-name>
		<url-pattern>/</url-pattern>
	</servlet-mapping>
</web-app>
