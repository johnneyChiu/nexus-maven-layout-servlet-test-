# nexus-maven-layout-servlet-test-
# <H4>第一个maven分层项目</H4>

# <div>
# 一、安装nexus 创建远程库myProxy和私库relaseHost、snapshotHost
# 二、安装maven 设置setting.xml的本地库位置
# 三、创建dependency.profile依赖库maven项目,并deploy到私库releaseHost或者snapshotHost
# 四、创建分层的maven项目并将maven setting.xml插件添加<code>&lt;pluginGroup&gt;org.mortbay.jetty&lt;/pluginGroup&gt;</code>
# 五、启动 jetty:run -e
# 六、打开页面http://localhost:8099/layoutFramework-web/hello/12
# </div>
