public.maven.repository.release
===

Jagadeesh's Public Release Repository

[Maven](http://en.wikipedia.org/wiki/Maven) repository:

    <repository>
         <id>jagadeesh.public.maven.repository.release</id>
         <name>Jagadeesh's Public Release Repository</name>
         <url>https://raw.github.com/ashwinjagadeesh/public.maven.repository/master/releases/</url>
         <snapshots>
             <enabled>false</enabled>
         </snapshots>
    </repository>


Maven dependencies:

    <properties>
        <com.cybozu.labs.version>0.1.0</com.cybozu.labs.version>
        <edu.jwetherell.version>0.2.0</edu.jwetherell.version>
    </properties>

    <dependency>
         <groupId>com.cybozu.labs</groupId>
         <artifactId>langdetect</artifactId>
         <version>${com.cybozu.labs.version}</version>
    </dependency>

    <dependency>
        <groupId>edu.jwetherell</groupId>
        <artifactId>jw-algorithms</artifactId>
        <version>${edu.jwetherell.version}</version>
    </dependency>
