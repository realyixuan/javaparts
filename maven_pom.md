### add my jar in maven

~~~
<dependency>
    <groupId>com.example</groupId>
    <artifactId>my-library</artifactId>
    <version>1.0.0</version>
    <scope>system</scope>
    <systemPath>${project.basedir}/path/to/your/jar/my-library.jar</systemPath>
</dependency>
~~~

