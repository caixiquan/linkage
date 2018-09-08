# linkage
gradle添加模式：
首先在项目中添加
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
然后
	dependencies {
	        implementation 'com.github.caixiquan:linkage:v1.0'
	}
如果是maven模式：
首先
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
 然后
 	<dependency>
	    <groupId>com.github.caixiquan</groupId>
	    <artifactId>linkage</artifactId>
	    <version>v1.0</version>
	</dependency>
