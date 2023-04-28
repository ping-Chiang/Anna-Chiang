---
title: JDBC连接
date: 2023-04-11 12:38:53
tags:
---

# 1、jdbc驱动的链接 

~~~java
public class jdbc {
    Connection conn;
    public Connection getConn() {
        // TODO 自动生成的方法存根
        try {
//    	 加载MYSQL驱动
            Class.forName("com.mysql.cj.jdbc.Driver");
            System.out.println("驱动加载成功");
//        连接数据库，获得连接对象
            String url = "jdbc:mysql://127.0.0.1:3306/student_system?user=root&password=20011223JP&useSSL=false&serverTimezone=Asia/Shanghai";
            conn = DriverManager.getConnection(url);
            System.out.println("数据库连接成功");
        } catch (ClassNotFoundException e) {

            e.printStackTrace();
            System.out.println("驱动加载失败");
            System.out.println("数据库连接失败");
        } catch(SQLException e) {
            e.printStackTrace();
        }
        return conn;
    }
    public static void main(String[] args)
    {

    }
}
~~~

