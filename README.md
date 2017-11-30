# jeestone
## tomcat7-maven-plugin 这个插件有14个目标：
* __tomcat7:deploy__   
将WAR部署到Tomcat。
* __tomcat7:deploy-only__   
将WAR部署到Tomcat而不分叉包生命周期。
* __tomcat7:exec-war__     
创建一个包含所有必需的Apache Tomcat的自执行jar文件类。这允许只使用java -jar mywebapp.jar来运行你的webapp而无需安装Tomcat实例。更多细节在这里。
* __tomcat7:exec-war-only__     
和exec-war目标一样，不会影响包的生命周期。
* __tomcat7:help__    
在tomcat7-maven-plugin上显示帮助信息。调用mvn tomcat7：help -Ddetail = true -Dgoal = <goal-name>来显示参数细节。
* __tomcat7:redeploy__     
在Tomcat中重新部署一个WAR。 （具有更新参数的部署目标的别名设置为true）。
* __tomcat7:redeploy-only__     
在Tomcat中重新部署WAR，而不会影响包的生命周期。 （别名为其更新参数设置为true的部署目标。）
* __tomcat7:run__    
使用嵌入式Tomcat将当前项目作为动态Web应用程序运行服务器。
* __tomcat7:run-war__      
使用嵌入式将当前项目作为打包的Web应用程序运行Tomcat服务器。
* __tomcat7:run-war-only__     
同运行战争目标一样，不要求分发包周期。
* __tomcat7:shutdown__     
关闭所有可能启动的嵌入式Tomcat服务器。这会是通过关闭挂钩自动完成，或者你可以调用这个关闭Mojo他们明确表示。 默认情况下，关闭目标不会绑定到任何阶段。对于集成测试你可能想把它绑定到post-integration-test。
* __tomcat7:standalone-war__      
这个Mojo将创建一个带有嵌入式Tomcat的可执行文件能够在别处部署。

* __tomcat7:standalone-war-only__    
这Mojo将创建一个可执行的战争文件与嵌入式的Tomcat也是能够在别处部署。

* __tomcat7:undeploy__    
从Tomcat中取消部署WAR。
