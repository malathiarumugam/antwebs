说明：
build.xml文件中是将 web项目打包成war包上传（使用scp）至linux，并且停启tomcat进行项目部署（其中操作tomcat有两种方式：使用tomcat 	managerment和sshexec方式）

build-ant带lib jar.xml:是将普通java项目打包成jar包上传到服务器运行的方式（其中包括处理jar包的依赖lib的问题）


commit and push到remote