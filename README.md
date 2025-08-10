# intelligence-bom
公共管理BOM文件

统一管理以下依赖版本的 Maven BOM：
- Spring Boot 3.5.4
- Spring AI 1.0.0-M4
- Google Guava
- Apache Commons Lang & IO

## 使用方法

在项目的 `pom.xml` 中引入：
```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>io.github.gghqq</groupId>
            <artifactId>ai-model-management-bom</artifactId>
            <version>1.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>

