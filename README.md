

# ant build.xml 的示例 #

1. Hello:  一个最简单的build.xml 

	build 没有依赖关系分别执行下面的命令
	ant compile
	ant jar
	ant run

2. hello-with-prop :增加了一些依赖关系及属性变量配置 


3. hello-with-lib:如何使用第三方的库文件


4. hello-copy-res:编译时候拷贝一些资源到classes目录



5. hello-ant-cmd:ant 携带参数的实例变量及属性在参数中携带
执行下面的命令
<code>
ant "-DPACKAGE_NAME=chrome"
</code>


##参考链接## 
http://ant.apache.org/manual/tutorial-HelloWorldWithAnt.html "apache ant hello"
