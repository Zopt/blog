---
author: muyi
pubDatetime: 2024-08-15T15:22:00Z
modDatetime: 2024-08-15T09:12:47.400Z
title: Spring 笔记
slug: "Spring"
featured: true
draft: false
tags:
  - docs
  - 笔记
description:
   Spring的学习笔记
---

# Spring

## 百度AI

### [spring教程](http://www.baidu.com/link?url=SEmkHcGpyIiSeTKgiWkJZy6YVIxxXSi1nfRX5KU-fseyOodq9tUnwWvw31l1gq-pJI9dZlqdYi1WteBIzyLzfIZLBm-TSClC29eJiZGqFbwh18IY0u5Fbj9lGUYcMIMXvl0qw7SgPlmzfhDRVGmxUgU7sbzeRrEnz1I3jYGMFlgY_4HTih8w2yo0HTmIM3Rphqb_3iw2HSH6LQ4MlTFiZYpvsWC7TcVq8raiLgR9EgxtGvLmtSPOycrAIPhD5AuuRm9nI8jewd5W1FGVbcdpO5cKe92ccVwrbEswufn_atzdexji8jMkoNZ3rOciL56ocJOq-F40k0Dp9YSU1spELYmiRUXHw7jZUldwttXOcfrAHegOqJCtS0MSLpiRL0Nd899_pPRhDkUVTQEuwqRBZk3-gj8iidtK-LYL7RXbVvetY3sSjHkBlndz9dYUC5BecH6K5o26vViYaO1PryBXTa)

‌[Spring框架](https://www.baidu.com/s?rsv_idx=1&tn=88093251_104_hao_pg&wd=Spring框架&fenlei=256&usm=2&ie=utf-8&rsv_pq=9a06cb59007e99f2&oq=spring教程&rsv_t=1197nq6I5w0Rq1Vcj%2FfVofK1Z4FXWjIbhCH1fRWkZ3y4Tht0TcTvgljYG3qJJ%2By1mZd0f339Y1qksw&sa=re_dqa_generate)是一个开源的‌[Java](https://www.baidu.com/s?rsv_idx=1&tn=88093251_104_hao_pg&wd=Java&fenlei=256&usm=2&ie=utf-8&rsv_pq=9a06cb59007e99f2&oq=spring教程&rsv_t=305aRKUbI1eJ%2BZ3J7mnhbeN%2FjVNaltaaxYQBMt%2B8PUjOymVFxaHFqaPYdh8h7%2BLMHQhbqMdvFO833Q&sa=re_dqa_generate)平台，旨在简化企业级应用程序的开发。它提供了全面的程序和配置模型，支持现代Java企业级应用程序的开发，包括Web应用程序、服务端应用程序等。Spring框架的核心特性包括‌[依赖注入](https://www.baidu.com/s?rsv_idx=1&tn=88093251_104_hao_pg&wd=依赖注入&fenlei=256&usm=2&ie=utf-8&rsv_pq=9a06cb59007e99f2&oq=spring教程&rsv_t=f5daxuumE2w0Br30wRRnhINr5Qbnd%2BAHC6XBUZxBTHdTQ4fj5O6cXUpG8g4X7WCQLhfNdJk84wXbOA&sa=re_dqa_generate)（DI）和‌[面向切面编程](https://www.baidu.com/s?rsv_idx=1&tn=88093251_104_hao_pg&wd=面向切面编程&fenlei=256&usm=2&ie=utf-8&rsv_pq=9a06cb59007e99f2&oq=spring教程&rsv_t=afd5E1bv0Zye2ki8zjl%2BaaNeHVVZMzRaYVun1p4mAmD7EQjh4quiz0O3qkDox%2Bub7ynD7%2FnWxdQX1Q&sa=re_dqa_generate)（AOP），这些特性使得开发者能够更灵活地管理应用程序的组件和业务逻辑。

### Spring框架的主要功能模块

1. **核心容器**：提供基础功能，包括依赖注入和面向切面编程的支持。
2. **数据访问**：提供对JDBC、ORM框架（如Hibernate）和事务管理的支持。
3. **Web模块**：支持构建Web应用程序，包括‌[Spring MVC](https://www.baidu.com/s?rsv_idx=1&tn=88093251_104_hao_pg&wd=Spring MVC&fenlei=256&usm=2&ie=utf-8&rsv_pq=9a06cb59007e99f2&oq=spring教程&rsv_t=afd5E1bv0Zye2ki8zjl%2BaaNeHVVZMzRaYVun1p4mAmD7EQjh4quiz0O3qkDox%2Bub7ynD7%2FnWxdQX1Q&sa=re_dqa_generate)和RESTful Web服务。
4. **集成模块**：支持企业服务，如消息传递、调度等。
5. **测试模块**：提供对单元测试的支持。

### 依赖注入（DI）和面向切面编程（AOP）

- **依赖注入**：允许开发者通过配置文件或注解的方式将依赖关系注入到对象中，减少了代码之间的耦合度。（一种设计模式）
- **面向切面编程**：允许开发者在不修改现有代码的情况下增加新的功能，如日志记录、事务管理等，提高了代码的可维护性和可扩展性。

### 配置方式

- **XML配置**：通过XML文件定义Bean的配置信息，适用于复杂的配置场景。
- **注解配置**：通过注解直接在Java代码中定义Bean的配置信息，简化了配置过程。

### Spring与其他技术的集成

- **Spring MVC**：用于构建Web应用程序，提供了RESTful API的支持。
- **Spring Boot**：简化了新项目的搭建和开发过程，通过自动配置减少了手动配置的工作量。
- **Spring Security**：提供了安全认证和授权的功能，保护Web应用程序的安全。

通过上述介绍，可以看出Spring框架是一个功能强大且灵活的框架，它简化了企业级应用程序的开发过程，提高了开发效率和应用程序的可维护性。‌

> 教程：https://www.cainiaojc.com/spring/

产生的原因：为了解决Java项目开发的复杂问题而产生的。Spring的JavaBean是替代了EJB完成的任务。

Spring的主要应用与服务器开发。

其他特点：

- 简单性
- 可测试
- 松耦合

## 设计理念

当你了解一个框架时，重要的是不仅要知道它做什么，还要知道它遵循什么原则。下面是Spring框架的指导原则。

- 在每个层面上提供选择。Spring让你尽可能晚地推迟设计决策。例如，你可以通过配置来切换持久化供应商，而不需要改变你的代码。对于许多其他基础设施问题和与第三方API的集成也是如此。
- 适应不同的观点。Spring拥抱灵活性，对事情应该如何做不持意见。它支持具有不同视角的广泛的应用需求。
- 保持强大的后向兼容性。Spring的演进是经过精心管理的，在不同的版本之间几乎不存在破坏性的变化。Spring支持一系列精心选择的JDK版本和第三方库，以方便维护依赖Spring的应用程序和库。
- 关心API的设计。Spring团队花了很多心思和时间来制作直观的API，并且在很多版本和很多年中都能保持良好的效果。
- 为代码质量设定高标准。Spring框架非常强调有意义的、最新的和准确的javadoc。它是为数不多的可以宣称代码结构干净、包与包之间没有循环依赖关系的项目之一。

## Spring 框架（Spring Framwork）

> Spring Framwork 使得JavaEE的开发变得容易
>
> Spring Framwork的中文文档：https://springdoc.cn/spring/

Spring虽然是框架的框架，但确实轻量级的。

### Spring的模块

https://www.cainiaojc.com/spring/spring-modules.html

Spring框架包含许多模块，例如Core，bean，Context，Expression Language，AOP，Aspects，Instrumentation，JDBC，ORM，OXM，JMS，Transaction，Web，Servlet，Struts等。这些模块如下图所示，它们分为Test, Core Container, AOP，Aspects，工具，数据访问/集成，Web(MVC/Remoting)。

![Spring模块](https://www.cainiaojc.com/static/upload/210424/0811520.jpg)

- AOP：设计模式孜孜不倦追求的是调用者和被调用者之间的[解耦](https://baike.baidu.com/item/解耦/8592042?fromModule=lemma_inlink),提高代码的灵活性和[可扩展性](https://baike.baidu.com/item/可扩展性/8669999?fromModule=lemma_inlink)，AOP（Aspect Oriented Programming）可以说也是这种目标的一种实现。

    - AOP、[OOP](https://baike.baidu.com/item/OOP/1152915?fromModule=lemma_inlink)在字面上虽然非常类似，但却是面向不同领域的两种[设计思想](https://baike.baidu.com/item/设计思想/15627717?fromModule=lemma_inlink)。OOP（[面向对象编程](https://baike.baidu.com/item/面向对象编程/0?fromModule=lemma_inlink)）针对业务[处理过程](https://baike.baidu.com/item/处理过程/53549100?fromModule=lemma_inlink)的实体及其属性和行为进行抽象封装，以获得更加清晰高效的[逻辑单元](https://baike.baidu.com/item/逻辑单元/1596619?fromModule=lemma_inlink)划分。
    - 而AOP则是针对业务处理过程中的切面进行提取，它所面对的是处理过程中的某个步骤或阶段，以获得逻辑过程中各部分之间低[耦合性](https://baike.baidu.com/item/耦合性/4297612?fromModule=lemma_inlink)的隔离效果。这两种设计思想在目标上有着本质的差异。
    - OOD/OOP面向名词领域，AOP面向动词领域

- Aspects：AOP思想实现

- Core Container:核心容器

- Data Access：数据访问

- Data Integration：数据集成

- Transaction：事务

- Web:Web开发

- Test:单元测试与集成测试



#### JDBC

JDBC（Java Database Connectivity）是Java语言中用于连接和操作数据库的一种标准API。它提供了一种统一的接口，使得Java应用程序能够与多种关系型数据库进行交互，如MySQL、Oracle、SQL Server等。

以下是JDBC的一些主要特点和用途：

1. **数据库连接**：JDBC允许Java程序通过建立数据库连接来访问和操作数据库中的数据。

2. **SQL执行**：通过JDBC，可以执行SQL语句，包括查询、插入、更新和删除等操作。

3. **结果集处理**：对于查询操作，JDBC提供了ResultSet接口来处理查询结果，可以遍历结果集中的每一行数据。

4. **事务管理**：JDBC支持事务管理，可以控制事务的提交和回滚，以确保数据的完整性和一致性。

5. **数据库元数据访问**：JDBC还提供了DatabaseMetaData接口，用于获取数据库的结构信息，如表名、列名、数据类型等。

在使用JDBC时，通常需要遵循以下步骤：

1. 加载数据库驱动程序：根据所使用的数据库类型，加载相应的JDBC驱动程序。
2. 建立数据库连接：使用DriverManager类的getConnection方法建立与数据库的连接。
3. 创建Statement或PreparedStatement对象：根据需要创建Statement或PreparedStatement对象来执行SQL语句。
4. 执行SQL语句：调用Statement或PreparedStatement对象的executeQuery或executeUpdate方法执行SQL语句。
5. 处理结果集（如果适用）：对于查询操作，使用ResultSet对象处理查询结果。
6. 关闭资源：在完成数据库操作后，关闭ResultSet、Statement和Connection对象以释放资源。

> 总结:加载驱动、连接数据库、创建SQL对象、执行SQL、处理结果、关闭资源

需要注意的是，在使用JDBC时要注意异常处理和资源管理，以避免潜在的资源泄漏和错误。此外，还可以考虑使用ORM框架（如Hibernate）来简化数据库操作和提高开发效率。

JDBC的常用操作主要包括以下几个方面：

1. **建立数据库连接**：
    - 使用`DriverManager.getConnection()`方法，传入数据库的URL、用户名和密码，建立与数据库的连接。

2. **执行SQL语句**：
    - 创建`Statement`对象：通过`Connection.createStatement()`方法创建，用于执行静态SQL语句。
    - 创建`PreparedStatement`对象：通过`Connection.prepareStatement()`方法创建，用于执行预编译SQL语句，可以防止SQL注入攻击，并提高性能。
    - 执行查询：使用`Statement.executeQuery()`或`PreparedStatement.executeQuery()`方法执行SELECT语句，返回`ResultSet`对象。
    - 执行更新：使用`Statement.executeUpdate()`或`PreparedStatement.executeUpdate()`方法执行INSERT、UPDATE、DELETE等语句，返回受影响的行数。

3. **处理结果集**：
    - 遍历`ResultSet`对象：使用`ResultSet.next()`方法移动光标到下一行，通过`ResultSet`提供的get方法（如`getInt()`, `getString()`, `getDate()`等）获取当前行的数据。
    - 获取元数据信息：通过`ResultSetMetaData`对象获取结果集的列信息，如列名、列数等。

4. **事务管理**：
    - 设置自动提交模式：通过`Connection.setAutoCommit()`方法设置是否自动提交事务，默认为自动提交。
    - 提交事务：使用`Connection.commit()`方法提交事务。
    - 回滚事务：在发生异常时，使用`Connection.rollback()`方法回滚事务，以保证数据的一致性。

5. **关闭资源**：
    - 在完成数据库操作后，务必关闭`ResultSet`、`Statement`和`Connection`对象，以释放数据库连接和其他资源。可以使用`try-with-resources`语句来自动关闭这些资源。

以下是一个简单的JDBC操作示例：

```java
import java.sql.*;

public class JdbcExample {
    public static void main(String[] args) {
        Connection conn = null;
        Statement stmt = null;
        ResultSet rs = null;

        try {
            // 加载数据库驱动程序（根据实际情况修改）
            Class.forName("com.mysql.cj.jdbc.Driver");

            // 建立数据库连接
            conn = DriverManager.getConnection("jdbc:mysql://localhost:3306/mydatabase", "username", "password");

            // 创建Statement对象
            stmt = conn.createStatement();

            // 执行查询语句
            rs = stmt.executeQuery("SELECT * FROM mytable");

            // 处理结果集
            while (rs.next()) {
                int id = rs.getInt("id");
                String name = rs.getString("name");
                System.out.println("ID: " + id + ", Name: " + name);
            }
        } catch (ClassNotFoundException | SQLException e) {
            e.printStackTrace();
        } finally {
            // 关闭资源
            try {
                if (rs != null) rs.close();
                if (stmt != null) stmt.close();
                if (conn != null) conn.close();
            } catch (SQLException e) {
                e.printStackTrace();
            }
        }
    }
}
```

请注意，上述示例中的数据库驱动程序类名、数据库URL、用户名和密码应根据实际情况进行修改。此外，为了简化代码和提高安全性，建议在实际项目中使用`PreparedStatement`代替`Statement`，并适当处理异常。





#### ORM

ORM（Object-Relational Mapping，对象关系映射）是一种编程技术，用于将关系数据库中的数据映射到对象模型上。它允许开发者在编程时使用面向对象的方式来操作数据库，而无需直接编写SQL语句。ORM框架充当了数据库和应用程序之间的桥梁，简化了数据库操作，并提高了开发效率和可维护性。

以下是ORM的一些主要特点和优势：

1. **抽象层**：ORM提供了一个抽象层，将数据库操作封装起来，使开发者能够专注于业务逻辑而不是底层的SQL语句。

2. **跨数据库兼容性**：由于ORM框架通常支持多种数据库系统，因此可以轻松地在不同的数据库之间切换，而无需大量更改代码。

3. **减少样板代码**：ORM框架自动生成了许多重复的样板代码，如SQL语句的编写和结果集的处理，从而减少了开发者的工作量。

4. **提高安全性**：许多ORM框架支持预编译语句和参数化查询，这有助于防止SQL注入攻击。

5. **对象关系映射**：ORM允许将数据库表映射为Java类（或其他编程语言中的类），将表中的行映射为类的实例，从而实现了对象与关系的对应。

6. **延迟加载和级联操作**：ORM框架支持延迟加载（Lazy Loading）和级联操作（Cascade Operations），使得数据的加载和关联操作更加灵活和高效。

常见的ORM框架包括Hibernate（Java）、MyBatis（Java）、Entity Framework（.NET）等。这些框架提供了丰富的功能和配置选项，以满足不同项目的需求。

使用ORM框架时，通常需要定义数据模型类（通常与数据库表对应），并配置映射关系。然后，通过ORM框架提供的API进行数据库操作，如保存、更新、删除和查询等。这些操作在底层会转换为相应的SQL语句执行。

需要注意的是，虽然ORM框架提供了许多便利，但在某些复杂场景下，直接使用JDBC可能更加灵活和高效。因此，在选择是否使用ORM框架时，应根据项目的具体需求和团队的技术栈进行权衡。

ORM（Object-Relational Mapping）的使用可以显著简化数据库操作，提高开发效率。下面以Hibernate为例，简要介绍ORM的使用步骤：

##### Hibernate

###### 1. 添加依赖

首先，在项目的构建文件中添加Hibernate的依赖。如果是Maven项目，可以在`pom.xml`中添加如下依赖：

```xml
<dependencies>
    <!-- Hibernate核心依赖 -->
    <dependency>
        <groupId>org.hibernate</groupId>
        <artifactId>hibernate-core</artifactId>
        <version>5.6.0.Final</version>
    </dependency>
    <!-- 数据库驱动依赖，以MySQL为例 -->
    <dependency>
        <groupId>mysql</groupId>
        <artifactId>mysql-connector-java</artifactId>
        <version>8.0.27</version>
    </dependency>
</dependencies>
```

###### 2. 配置Hibernate

创建一个Hibernate配置文件（通常命名为`hibernate.cfg.xml`），并配置数据库连接信息、映射文件等。示例配置如下：

```xml
<!DOCTYPE hibernate-configuration PUBLIC
        "-//Hibernate/Hibernate Configuration DTD 3.0//EN"
        "http://www.hibernate.org/dtd/hibernate-configuration-3.0.dtd">
<hibernate-configuration>
    <session-factory>
        <!-- 数据库连接配置 -->
        <property name="connection.driver_class">com.mysql.cj.jdbc.Driver</property>
        <property name="connection.url">jdbc:mysql://localhost:3306/mydatabase</property>
        <property name="connection.username">username</property>
        <property name="connection.password">password</property>

        <!-- 其他配置 -->
        <property name="dialect">org.hibernate.dialect.MySQLDialect</property>
        <property name="show_sql">true</property>
        <property name="hbm2ddl.auto">update</property>

        <!-- 映射文件配置 -->
        <mapping resource="com/example/User.hbm.xml"/>
    </session-factory>
</hibernate-configuration>
```

###### 3. 定义数据模型类

创建Java类来表示数据库中的表。例如，定义一个`User`类：

```java
package com.example;

public class User {
    private int id;
    private String name;
    private String email;

    // 构造方法、getter和setter省略
}
```

###### 4. 创建映射文件

为每个数据模型类创建一个映射文件（通常命名为`*.hbm.xml`），定义类与表的映射关系。例如，创建`User.hbm.xml`：

```xml
<!DOCTYPE hibernate-mapping PUBLIC
        "-//Hibernate/Hibernate Mapping DTD 3.0//EN"
        "http://www.hibernate.org/dtd/hibernate-mapping-3.0.dtd">
<hibernate-mapping>
    <class name="com.example.User" table="users">
        <id name="id" column="id">
            <generator class="native"/>
        </id>
        <property name="name" column="name"/>
        <property name="email" column="email"/>
    </class>
</hibernate-mapping>
```

###### 5. 使用Hibernate进行数据库操作

编写代码使用Hibernate进行数据库操作，如保存、更新、删除和查询等。以下是一个简单的示例：

```java
package com.example;

import org.hibernate.Session;
import org.hibernate.SessionFactory;
import org.hibernate.cfg.Configuration;

public class HibernateExample {
    public static void main(String[] args) {
        // 创建SessionFactory对象
        SessionFactory sessionFactory = new Configuration().configure().buildSessionFactory();

        // 创建Session对象
        Session session = sessionFactory.openSession();

        // 开始事务
        session.beginTransaction();

        // 创建User对象并保存到数据库
        User user = new User();
        user.setName("John Doe");
        user.setEmail("john.doe@example.com");
        session.save(user);

        // 提交事务
        session.getTransaction().commit();

        // 关闭Session和SessionFactory
        session.close();
        sessionFactory.close();
    }
}
```

###### 注意事项

- 在使用ORM框架时，要注意配置文件的正确性和完整性。
- 映射文件中的字段映射关系要与数据模型类中的属性对应。
- 在进行数据库操作时，要遵循事务管理原则，确保数据的完整性和一致性。
- 根据项目的具体需求，可以进一步学习和掌握ORM框架的高级特性和优化技巧。

通过以上步骤，你可以开始使用ORM框架（如Hibernate）来简化数据库操作，并提高开发效率。



##### Mybatis

MyBatis是一个流行的Java ORM框架，它提供了灵活且高效的数据库操作方式。以下是以MyBatis为例，介绍其基本的使用步骤：

###### 1. 添加依赖

首先，在项目的构建文件中添加MyBatis的依赖。如果是Maven项目，可以在`pom.xml`中添加如下依赖：

```xml
<dependencies>
    <!-- MyBatis核心依赖 -->
    <dependency>
        <groupId>org.mybatis</groupId>
        <artifactId>mybatis</artifactId>
        <version>3.5.9</version>
    </dependency>
    <!-- 数据库驱动依赖，以MySQL为例 -->
    <dependency>
        <groupId>mysql</groupId>
        <artifactId>mysql-connector-java</artifactId>
        <version>8.0.27</version>
    </dependency>
</dependencies>
```

###### 2. 配置MyBatis

创建一个MyBatis配置文件（通常命名为`mybatis-config.xml`），并配置数据库连接信息、映射文件等。示例配置如下：

```xml
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE configuration
        PUBLIC "-//mybatis.org//DTD Config 3.0//EN"
        "http://mybatis.org/dtd/mybatis-3-config.dtd">
<configuration>
    <environments default="development">
        <environment id="development">
            <transactionManager type="JDBC"/>
            <dataSource type="POOLED">
                <property name="driver" value="com.mysql.cj.jdbc.Driver"/>
                <property name="url" value="jdbc:mysql://localhost:3306/mydatabase"/>
                <property name="username" value="username"/>
                <property name="password" value="password"/>
            </dataSource>
        </environment>
    </environments>
    <mappers>
        <mapper resource="com/example/UserMapper.xml"/>
    </mappers>
</configuration>
```

###### 3. 定义数据模型类

创建Java类来表示数据库中的表。例如，定义一个`User`类：

```java
package com.example;

public class User {
    private int id;
    private String name;
    private String email;

    // 构造方法、getter和setter省略
}
```

###### 4. 创建映射文件

为每个数据模型类创建一个映射文件（通常命名为`*Mapper.xml`），定义SQL语句与Java方法的对应关系。例如，创建`UserMapper.xml`：

```xml
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE mapper
        PUBLIC "-//mybatis.org//DTD Mapper 3.0//EN"
        "http://mybatis.org/dtd/mybatis-3-mapper.dtd">
<mapper namespace="com.example.UserMapper">
    <select id="selectUserById" resultType="com.example.User">
        SELECT id, name, email FROM users WHERE id = #{id}
    </select>
    <insert id="insertUser" parameterType="com.example.User">
        INSERT INTO users (name, email) VALUES (#{name}, #{email})
    </insert>
    <!-- 其他SQL语句 -->
</mapper>
```

###### 5. 创建Mapper接口

创建一个Java接口，定义与映射文件中SQL语句对应的方法。例如，创建`UserMapper.java`：

```java
package com.example;

import org.apache.ibatis.annotations.Select;
import org.apache.ibatis.annotations.Insert;

public interface UserMapper {
    @Select("SELECT id, name, email FROM users WHERE id = #{id}")
    User selectUserById(int id);

    @Insert("INSERT INTO users (name, email) VALUES (#{name}, #{email})")
    void insertUser(User user);

    // 其他方法
}
```

###### 6. 使用MyBatis进行数据库操作

编写代码使用MyBatis进行数据库操作。可以通过配置文件创建`SqlSessionFactory`对象，然后通过该对象获取`SqlSession`对象，最后通过`SqlSession`执行SQL语句。以下是一个简单的示例：

```java
package com.example;

import org.apache.ibatis.session.SqlSession;
import org.apache.ibatis.session.SqlSessionFactory;
import org.apache.ibatis.session.SqlSessionFactoryBuilder;

import java.io.InputStream;

public class MyBatisExample {
    public static void main(String[] args) {
        // 加载MyBatis配置文件
        InputStream inputStream = MyBatisExample.class.getResourceAsStream("/mybatis-config.xml");
        SqlSessionFactory sqlSessionFactory = new SqlSessionFactoryBuilder().build(inputStream);

        // 创建SqlSession对象
        SqlSession sqlSession = sqlSessionFactory.openSession();

        try {
            // 获取Mapper接口的代理对象
            UserMapper userMapper = sqlSession.getMapper(UserMapper.class);

            // 调用Mapper接口的方法执行SQL语句
            User user = userMapper.selectUserById(1);
            System.out.println(user);

            // 插入新用户
            User newUser = new User();
            newUser.setName("Jane Doe");
            newUser.setEmail("jane.doe@example.com");
            userMapper.insertUser(newUser);

            // 提交事务
            sqlSession.commit();
        } finally {
            // 关闭SqlSession
            sqlSession.close();
        }
    }
}
```

###### 注意事项

- 在使用MyBatis时，要注意配置文件的正确性和完整性。
- 映射文件中的SQL语句要与Mapper接口中的方法对应。
- 在进行数据库操作时，要遵循事务管理原则，确保数据的完整性和一致性。
- MyBatis提供了灵活的SQL映射方式，包括注解和XML配置，可以根据项目需求选择合适的方式。

通过以上步骤，你可以开始使用MyBatis来进行数据库操作，并体验其带来的便利性和灵活性。

#### OXM

OXM（Object/XML Mapping）是一种将对象模型与XML数据进行相互转换的技术。与ORM类似，OXM也提供了一种抽象层，使得开发者能够在对象和XML之间进行无缝的转换，而无需关心底层的解析和序列化细节。

OXM的主要应用场景包括：

1. **数据交换**：在不同的系统或组件之间，通过XML格式进行数据交换时，可以使用OXM来简化数据的序列化和反序列化过程。

2. **持久化存储**：将对象数据持久化存储为XML文件，或者从XML文件中读取数据并恢复为对象。

3. **Web服务**：在基于XML的Web服务（如SOAP Web服务）中，OXM可以帮助处理XML消息的编码和解码。

4. **配置文件**：将应用程序的配置信息存储为XML文件，并通过OXM将其加载为对象进行处理。

常见的OXM框架包括JAXB（Java Architecture for XML Binding）、Castor、XMLBeans等。这些框架提供了丰富的功能和灵活的配置选项，以满足不同项目的需求。

以下是使用JAXB进行OXM操作的简单示例：

##### 1. 定义数据模型类

首先，定义一个Java类来表示要序列化为XML的数据模型。例如，定义一个`Person`类：

```java
import javax.xml.bind.annotation.XmlElement;
import javax.xml.bind.annotation.XmlRootElement;

@XmlRootElement
public class Person {
    private String name;
    private int age;

    @XmlElement
    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    @XmlElement
    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }
}
```

##### 2. 序列化对象为XML

使用JAXB将`Person`对象序列化为XML字符串：

```java
import javax.xml.bind.JAXBContext;
import javax.xml.bind.JAXBException;
import javax.xml.bind.Marshaller;
import java.io.StringWriter;

public class OxmExample {
    public static void main(String[] args) {
        Person person = new Person();
        person.setName("John Doe");
        person.setAge(30);

        try {
            JAXBContext jaxbContext = JAXBContext.newInstance(Person.class);
            Marshaller marshaller = jaxbContext.createMarshaller();
            marshaller.setProperty(Marshaller.JAXB_FORMATTED_OUTPUT, Boolean.TRUE);

            StringWriter stringWriter = new StringWriter();
            marshaller.marshal(person, stringWriter);

            String xmlString = stringWriter.toString();
            System.out.println(xmlString);
        } catch (JAXBException e) {
            e.printStackTrace();
        }
    }
}
```

##### 3. 反序列化XML为对象

使用JAXB将XML字符串反序列化为`Person`对象：

```java
import javax.xml.bind.JAXBContext;
import javax.xml.bind.JAXBException;
import javax.xml.bind.Unmarshaller;
import java.io.StringReader;

public class OxmExample {
    public static void main(String[] args) {
        String xmlString = "<person><name>John Doe</name><age>30</age></person>";

        try {
            JAXBContext jaxbContext = JAXBContext.newInstance(Person.class);
            Unmarshaller unmarshaller = jaxbContext.createUnmarshaller();

            StringReader stringReader = new StringReader(xmlString);
            Person person = (Person) unmarshaller.unmarshal(stringReader);

            System.out.println("Name: " + person.getName());
            System.out.println("Age: " + person.getAge());
        } catch (JAXBException e) {
            e.printStackTrace();
        }
    }
}
```

通过以上示例，你可以看到OXM框架如何简化对象与XML之间的转换过程。在实际项目中，根据具体需求选择合适的OXM框架，并根据其提供的API进行相应的操作。

#### JMS

JMS（Java Message Service，Java消息服务）是Java平台中用于处理异步消息的标准API。它提供了一种在分布式系统中传递消息的可靠方式，支持点对点（Point-to-Point）和发布/订阅（Publish/Subscribe）两种消息传递模式。

以下是JMS的一些主要特点和用途：

1. **异步通信**：JMS允许应用程序通过发送和接收消息来实现异步通信，从而提高系统的可伸缩性和响应性。

2. **可靠性**：JMS提供了一定程度的消息传递保证，如消息持久化、事务支持等，以确保消息不会丢失或重复。

3. **解耦**：通过使用消息队列，JMS可以将生产者和消费者解耦，使得它们可以独立地运行和扩展。

4. **标准接口**：JMS定义了一组标准接口，使得不同的消息中间件提供商可以实现这些接口，从而实现跨平台的互操作性。

5. **多种消息传递模式**：JMS支持点对点和发布/订阅两种消息传递模式，以满足不同的业务需求。

在使用JMS时，通常需要遵循以下步骤：

1. **创建连接工厂**：使用JMS提供者提供的连接工厂类来创建连接工厂对象。连接工厂负责创建与JMS提供者的连接。

2. **创建连接**：使用连接工厂创建一个连接对象。连接表示与JMS提供者的通信链路。

3. **创建会话**：使用连接创建一个会话对象。会话是用于创建消息生产者、消息消费者和消息监听器的容器。

4. **创建消息生产者或消费者**：根据需求，使用会话创建消息生产者或消息消费者对象。消息生产者用于发送消息，而消息消费者用于接收消息。

5. **发送和接收消息**：通过消息生产者发送消息，并通过消息消费者接收消息。消息可以是文本、字节流、对象等类型。

6. **关闭资源**：在完成消息处理后，关闭会话、连接等资源以释放系统资源。

以下是一个简单的JMS示例，演示如何使用JMS发送和接收文本消息：

```java
import javax.jms.*;
import org.apache.activemq.ActiveMQConnectionFactory;

public class JmsExample {
    public static void main(String[] args) {
        ConnectionFactory connectionFactory = new ActiveMQConnectionFactory("tcp://localhost:61616");
        Connection connection = null;
        Session session = null;
        MessageProducer producer = null;
        MessageConsumer consumer = null;

        try {
            // 创建连接
            connection = connectionFactory.createConnection();
            connection.start();

            // 创建会话
            session = connection.createSession(false, Session.AUTO_ACKNOWLEDGE);

            // 创建目标队列
            Destination destination = session.createQueue("testQueue");

            // 创建消息生产者
            producer = session.createProducer(destination);

            // 发送消息
            TextMessage message = session.createTextMessage("Hello, JMS!");
            producer.send(message);

            // 创建消息消费者
            consumer = session.createConsumer(destination);

            // 接收消息
            Message receivedMessage = consumer.receive(1000);
            if (receivedMessage instanceof TextMessage) {
                TextMessage textMessage = (TextMessage) receivedMessage;
                System.out.println("Received message: " + textMessage.getText());
            }
        } catch (JMSException e) {
            e.printStackTrace();
        } finally {
            // 关闭资源
            try {
                if (consumer != null) consumer.close();
                if (producer != null) producer.close();
                if (session != null) session.close();
                if (connection != null) connection.close();
            } catch (JMSException e) {
                e.printStackTrace();
            }
        }
    }
}
```

请注意，上述示例使用了Apache ActiveMQ作为JMS提供者。在实际项目中，可以根据需求选择合适的JMS提供者，并根据其提供的API进行相应的操作。此外，还需要注意异常处理和资源管理，以确保系统的稳定性和可靠性。





JMS（Java Message Service）的提供者有很多，它们实现了JMS接口并提供具体的消息传递服务。以下是一些常见的JMS提供者：

1. **Apache ActiveMQ**：ActiveMQ是Apache软件基金会下的一个开源项目，它是一个功能强大的消息中间件，支持多种消息协议，包括JMS、AMQP、MQTT等。ActiveMQ具有高性能、高可用性和可扩展性等特点。

2. **RabbitMQ**：RabbitMQ是一个开源的消息代理和队列服务器，它实现了AMQP（Advanced Message Queuing Protocol）协议，同时也支持JMS。RabbitMQ具有灵活的路由配置、强大的消息持久化和高可用性等特点。

3. **IBM MQ**：IBM MQ（原名WebSphere MQ）是IBM公司开发的一款企业级的消息中间件产品。它支持多种消息协议，包括JMS、MQSeries等。IBM MQ具有高度的可扩展性、可靠性和安全性等特点，广泛应用于企业级应用中。

4. **Oracle WebLogic Server**：Oracle WebLogic Server是Oracle公司的一款应用服务器产品，它提供了JMS实现，支持企业级应用的消息传递需求。WebLogic Server具有高性能、可扩展性和安全性等特点。

5. **Red Hat JBoss Messaging (HornetQ)**：JBoss Messaging（现更名为HornetQ）是Red Hat公司的一款开源消息中间件产品，它实现了JMS接口，并提供了高性能、高可用性和可扩展性等特点。HornetQ支持多种消息协议和传输方式。

6. **SonicMQ**：SonicMQ是Sonic Software公司开发的一款高性能、轻量级的消息中间件产品。它支持JMS接口，并提供了可靠的消息传递、灵活的路由配置和易于集成的特点。

7. **Apache Kafka**：虽然Kafka最初是为了解决大数据处理中的日志收集和分发问题而设计的，但它也提供了类似于JMS的功能，支持发布/订阅模式和点对点模式的消息传递。Kafka具有高吞吐量、低延迟和可扩展性等特点。

这些JMS提供者各有特点，适用于不同的应用场景和需求。在选择JMS提供者时，需要考虑其性能、可靠性、安全性、易用性以及与现有系统的兼容性等因素。



#### Servlet

Servlet是用Java编写的服务器端程序，它是Java Servlet API的规范的一部分，用于扩展服务器的功能。Servlet对于处理HTTP请求和生成动态Web内容非常有用。它们通常用于创建Web应用程序，响应客户端请求，并与数据库或其他后端服务进行交互。

以下是Servlet的一些主要特点和用途：

1. **动态内容生成**：Servlet可以根据客户端请求动态生成HTML、XML或其他格式的内容。

2. **会话管理**：Servlet可以跟踪用户会话，存储和检索会话数据，以实现个性化用户体验。

3. **安全性**：Servlet提供了多种安全机制，如身份验证、授权和数据加密，以保护Web应用程序免受未经授权的访问和攻击。

4. **与数据库交互**：Servlet可以与关系型数据库或其他数据源进行交互，执行查询、插入、更新和删除等操作。

5. **可扩展性**：Servlet易于扩展和定制，可以根据项目需求添加新的功能和行为。

在使用Servlet时，通常需要遵循以下步骤：

1. **创建Servlet类**：编写一个继承自`javax.servlet.http.HttpServlet`的Java类，并重写`doGet()`、`doPost()`等方法以处理HTTP请求。

2. **配置Servlet**：在Web应用程序的`web.xml`文件中配置Servlet，指定Servlet的名称、URL映射和其他属性。

3. **部署Servlet**：将Servlet类打包成WAR文件，并将其部署到支持Servlet的Web服务器（如Apache Tomcat）上。

4. **处理请求和响应**：在Servlet中处理客户端请求，生成动态内容，并通过响应对象将结果发送回客户端。

以下是一个简单的Servlet示例，演示如何创建一个基本的Servlet来响应HTTP GET请求：

```java
import javax.servlet.ServletException;
import javax.servlet.annotation.WebServlet;
import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;
import java.io.IOException;
import java.io.PrintWriter;

@WebServlet("/hello")
public class HelloServlet extends HttpServlet {
    @Override
    protected void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
        // 设置响应内容类型
        response.setContentType("text/html;charset=UTF-8");

        // 获取PrintWriter对象以输出响应内容
        PrintWriter out = response.getWriter();

        // 生成动态内容并发送回客户端
        out.println("<html><body>");
        out.println("<h1>Hello, Servlet!</h1>");
        out.println("</body></html>");
    }
}
```

请注意，上述示例使用了`@WebServlet`注解来配置Servlet的URL映射。这是Java Servlet 3.0及更高版本中引入的注解方式，可以简化Servlet的配置过程。在较早的Servlet版本中，需要在`web.xml`文件中进行相应的配置。

此外，在使用Servlet时，还需要注意异常处理、资源管理和性能优化等方面的问题，以确保Servlet的稳定性和可靠性。



#### PortLet

Portlet 是一种用于构建 Web 应用程序的组件化架构元素，尤其在 Java 2 Platform Enterprise Edition (J2EE) 和后续版本中，如 Java EE（现在称为 Jakarta EE）中常见。Portlet 允许开发者创建可重用的模块，这些模块可以集成到门户网站中，提供个性化的用户体验。

以下是关于 Portlet 的一些关键点：

1. **标准化**：Portlet 遵循 JSR 168（Java Specification Request 168）和 JSR 286 标准，这些标准定义了 Portlet 的接口和行为。

2. **容器**：Portlet 运行在 Portlet 容器中，这是一个负责管理 Portlet 生命周期和与门户服务器交互的软件环境。

3. **MVC 架构**：Portlet 通常遵循模型-视图-控制器（Model-View-Controller, MVC）架构模式，其中模型管理数据，视图负责呈现内容，控制器处理用户交互。

4. **门户集成**：Portlet 可以与其他 Portlet 和门户服务器提供的服务（如导航、搜索、个性化等）集成，以提供丰富的用户体验。

5. **部署**：Portlet 通常是作为 WAR（Web Application Archive）文件部署到门户服务器上的。

6. **交互性**：Portlet 可以通过 AJAX（Asynchronous JavaScript and XML）等技术提供动态和交互式的用户界面。

7. **安全性**：由于 Portlet 可能会处理敏感数据，因此它们需要实现适当的安全措施，如身份验证、授权和加密。

8. **可扩展性**：Portlet 架构允许开发者轻松地添加新功能或修改现有功能，而不会影响整个门户网站的其他部分。

Portlet 技术在构建企业级门户网站时非常有用，因为它们提供了灵活性、可重用性和可维护性。然而，随着现代 Web 开发技术的发展，如单页应用程序（SPA）和微服务架构，Portlet 的使用也在逐渐演变和适应新的开发范式。



#### Struts

Struts 是一个用于创建企业级 Java Web 应用程序的开源框架。它基于 Model-View-Controller (MVC) 设计模式，旨在简化 Web 应用程序的开发过程。Struts 最初由 Craig McClanahan 创建，并在 2000 年首次发布。随着时间的推移，Struts 经历了多个版本的迭代，最新的主要版本是 Struts 2，它是基于 WebWork 框架的升级版。

以下是 Struts 的一些关键特性：

1. **MVC 架构**：Struts 提供了一个清晰的 MVC 分离，使得模型、视图和控制器之间的职责更加明确。

2. **标签库**：Struts 提供了一套丰富的标签库（Taglib），用于简化 JSP 页面的开发，使得页面设计师可以更容易地创建动态内容。

3. **拦截器**：Struts 2 引入了拦截器（Interceptor）的概念，它允许开发者在请求处理过程中插入自定义逻辑，例如身份验证、日志记录和文件上传处理。

4. **插件架构**：Struts 支持插件扩展，允许开发者通过插件来增加新的功能或修改现有行为。

5. **集成**：Struts 可以与其他 Java EE 技术和框架（如 Spring、Hibernate、EJB 等）集成，提供强大的功能。

6. **配置**：Struts 使用 XML 配置文件来定义动作（Action）、结果（Result）和拦截器栈（Interceptor Stack），这使得应用程序的行为可以很容易地被修改。

7. **表单验证**：Struts 提供了内置的表单验证机制，可以通过配置文件或注解来实现。

8. **国际化**：Struts 支持国际化，可以轻松地为应用程序提供多语言支持。

尽管 Struts 在过去非常流行，但由于一些安全性和维护性的问题，它的使用已经逐渐减少。特别是在 Apache Struts 2 中发现了一些严重的安全漏洞后，许多开发者转向了更现代的框架，如 Spring MVC、Jakarta EE 的 MVC 框架或其他基于微服务架构的解决方案。

如果你正在考虑使用 Struts 或将其迁移到其他框架，以下是一些建议：

- **安全性**：确保你使用的 Struts 版本是最新的，并且已经应用了所有必要的安全补丁。
- **维护性**：评估项目的长期维护性，考虑社区支持和框架的未来发展方向。
- **技术栈**：考虑将 Struts 迁移到更现代的框架，以利用最新的开发实践和技术优势。
- **团队技能**：评估团队的技能和经验，选择最适合项目需求的框架。

总的来说，Struts 是一个成熟的框架，对于一些遗留系统可能仍然是一个合适的选择，但对于新项目，开发者可能会倾向于选择更现代、更灵活的技术栈。

#### Instrumentation

在Java中，`Instrumentation` 是一个用于在Java虚拟机（JVM）运行时修改字节码的API。它允许开发者在类被加载到JVM之前或之后对其进行修改，从而实现诸如性能监控、代码覆盖率分析、AOP（面向切面编程）等功能。

##### 基本概念

* **Agent**：Instrumentation API通常通过Java代理（Agent）来使用。Java代理是一个在JVM启动时加载的特殊类，它包含一个 `premain` 方法，该方法在JVM启动之前被调用。
* **Instrumentation对象**：Java代理通过 `premain` 方法接收一个 `Instrumentation` 对象，该对象提供了修改字节码的方法。
* **字节码修改**：通过Instrumentation API，开发者可以在类加载时修改其字节码，例如添加新的方法、修改现有方法的实现等。

##### 使用步骤

1. **创建Java代理类**：实现一个包含 `premain` 方法的Java代理类，并在该方法中接收 `Instrumentation` 对象。

```java
public class MyAgent {
    public static void premain(String agentArgs, Instrumentation inst) {
        // 在这里使用Instrumentation对象进行字节码修改
    }
}
```

2. **配置代理**：在JVM启动参数中指定Java代理的路径。例如，通过 `-javaagent` 参数指定代理的jar文件路径。

```sh
java -javaagent:/path/to/my-agent.jar -jar my-application.jar
```

3. **实现字节码修改逻辑**：在Java代理类的 `premain` 方法中，使用 `Instrumentation` 对象提供的API进行字节码修改。例如，可以使用 `addTransformer` 方法添加一个类转换器，在类加载时修改其字节码。

```java
public static void premain(String agentArgs, Instrumentation inst) {
    inst.addTransformer(new ClassFileTransformer() {
        @Override
        public byte[] transform(ClassLoader loader, String className, Class<?> classBeingRedefined, ProtectionDomain protectionDomain, byte[] classfileBuffer) throws IllegalClassFormatException {
            // 在这里修改字节码
            return modifiedClassBytes;
        }
    });
}
```

##### 注意事项

* **性能影响**：字节码修改可能会引入额外的性能开销，因此在使用Instrumentation时应谨慎考虑性能问题。
* **兼容性问题**：不同的JVM实现可能对Instrumentation API的支持程度有所不同。在使用前，请确保您的JVM支持所需的Instrumentation功能。
* **安全性**：由于Instrumentation允许在运行时修改字节码，因此在使用时应特别注意安全性问题，避免恶意代码利用该功能进行攻击。

总之，Instrumentation API为Java开发者提供了一种强大的机制，用于在运行时修改字节码以实现各种高级功能。然而，在使用时需要仔细考虑性能、兼容性和安全性等方面的问题。

#### Expression Language

Spring的表达式语言（Expression Language，简称SpEL）是一种强大的表达式解析器，它允许在运行时求解表达式，并操作对象图。SpEL在Spring框架的多个组件中都有应用，如Spring MVC的视图解析、Spring Security的权限评估等。

以下是SpEL的一些基本特性和用法：

###### 1. 基本语法

SpEL表达式通常用 `#{...}` 包裹，例如：

```java
#{user.name}
```

###### 2. 访问对象属性

SpEL允许您访问对象的属性，包括嵌套属性。

```java
#{user.address.city}
```

###### 3. 调用方法

您还可以使用SpEL调用对象的方法。

```java
#{user.getAge()}
```

###### 4. 算术运算

SpEL支持基本的算术运算。

```java
#{user.age + 5}
```

###### 5. 比较运算

Sp类EL支持各种比较运算符。

```java
#{user.age > 18}
```

###### 6. 逻辑运算

SpEL还支持逻辑运算符，如 `and`、`or` 和 `not`。

```java
#{user.age > 18 and user.isStudent()}
```

###### 7. 正则表达式匹配

您可以使用 `matches` 运算符进行正则表达式匹配。

```java
#{user.email matches '[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\\.[a-zA-Z]{2,}' }
```

###### 8. 变量引用

SpEL允许您引用变量。

```java
#{user.name} // 假设user已经在上下文中定义
```

###### 9. 集合操作

SpEL提供了对集合（如List、Set和Map）的操作。

```java
#{users[0].name} // 访问List中的第一个元素
#{userMap['key'].name} // 访问Map中的元素
```

###### 10. 条件表达式

SpEL支持使用 `? :` 运算符进行条件表达式求值。

```java
#{user.age >= 18 ? 'Adult' : 'Minor'}
```

###### 在Spring中的应用

SpEL在Spring框架中有广泛的应用。例如，在Spring MVC中，您可以使用SpEL来定义视图名称、模型属性等。在Spring Security中，SpEL用于评估权限表达式。

以下是一个简单的Spring MVC示例，展示了如何在视图名称解析中使用SpEL：

```java
@Controller
public class MyController {
    @Value("#{user.name}")
    private String userName;

    @RequestMapping("/greet")
    public String greet(Model model) {
        model.addAttribute("userName", userName);
        return "greet-" + userName; // 使用SpEL动态设置视图名称
    }
}
```

在这个示例中，我们使用 `@Value` 注解将 `user.name` 的值注入到 `userName` 变量中，并在返回视图名称时使用了SpEL表达式。

#### Context

在Spring框架中，`Context` 通常指的是应用程序上下文，它是Spring IoC（控制反转）容器的核心接口之一。Spring提供了多种类型的上下文实现，以满足不同类型应用程序的需求。以下是一些常见的Spring上下文：

1. **AnnotationConfigApplicationContext**：
   这个类用于从Java配置类加载Spring应用程序上下文。它支持使用 `@Configuration` 注解的类来定义Bean。

   ```java
   AnnotationConfigApplicationContext context = new AnnotationConfigApplicationContext(AppConfig.class);
   ```

2. **ClassPathXmlApplicationContext**：
   这个类用于从类路径下的XML配置文件加载Spring应用程序上下文。

   ```java
   ClassPathXmlApplicationContext context = new ClassPathXmlApplicationContext("applicationContext.xml");
   ```

3. **FileSystemXmlApplicationContext**：
   这个类用于从文件系统中的XML配置文件加载Spring应用程序上下文。

   ```java
   FileSystemXmlApplicationContext context = new FileSystemXmlApplicationContext("file:./applicationContext.xml");
   ```

4. **WebApplicationContext**：
   这个接口是专门为Web应用程序设计的Spring上下文。它扩展了 `ApplicationContext` 接口，并添加了一些与Web相关的功能。Spring提供了两种实现：`XmlWebApplicationContext` 和 `AnnotationConfigWebApplicationContext`。

   ```java
   // 在Servlet容器中初始化WebApplicationContext
   ServletContext servletContext = request.getServletContext();
   WebApplicationContext context = WebApplicationContextUtils.getWebApplicationContext(servletContext);
   ```

Spring上下文的主要功能包括：

- **Bean管理**：上下文负责创建、配置和管理Bean实例。
- **依赖注入**：上下文支持通过构造函数、setter方法或字段注入依赖项。
- **生命周期管理**：上下文负责调用Bean的初始化和销毁方法。
- **事件发布**：上下文允许发布和监听应用程序事件。

通过使用Spring上下文，您可以轻松地管理应用程序的组件和依赖关系，从而实现松耦合和可测试的代码。

##### Context的使用

在Spring框架中，`Context`（通常指`ApplicationContext`）是核心组件之一，用于管理Bean的生命周期、依赖注入以及配置信息的加载。以下是`Context`的一些常见用法：

###### 1. 获取Bean实例

通过`ApplicationContext`，您可以获取由Spring容器管理的Bean实例。

```java
ApplicationContext context = new ClassPathXmlApplicationContext("applicationContext.xml");
MyBean myBean = (MyBean) context.getBean("myBean");
```

###### 2. 依赖注入

您可以使用`ApplicationContext`手动进行依赖注入，但在实际开发中，更常见的是通过注解（如`@Autowired`）自动注入依赖。

```java
@Autowired
private MyService myService;
```

###### 3. 发布和监听事件

Spring允许您通过`ApplicationContext`发布和监听应用程序事件。

```java
// 发布事件
context.publishEvent(new MyEvent(this));

// 监听事件
@Component
public class MyEventListener {
    @EventListener
    public void handleMyEvent(MyEvent event) {
        // 处理事件
    }
}
```

###### 4. 获取配置信息

您可以通过`ApplicationContext`获取配置信息，例如从`Environment`对象中读取属性。

```java
ConfigurableEnvironment environment = context.getEnvironment();
String propertyValue = environment.getProperty("my.property");
```

###### 5. 使用不同的上下文实现

根据您的需求，可以选择不同的`ApplicationContext`实现。例如，在Web应用程序中，您可能会使用`WebApplicationContext`。

```java
// 在Servlet容器中获取WebApplicationContext
ServletContext servletContext = request.getServletContext();
WebApplicationContext webApplicationContext = WebApplicationContextUtils.getWebApplicationContext(servletContext);
```

###### 6. 初始化和销毁Bean

`ApplicationContext`负责调用Bean的初始化和销毁方法。您可以在Bean类中使用`@PostConstruct`和`@PreDestroy`注解来标记这些方法。

```java
@Component
public class MyBean {
    @PostConstruct
    public void init() {
        // 初始化逻辑
    }

    @PreDestroy
    public void destroy() {
        // 销毁逻辑
    }
}
```

总之，`Context`在Spring框架中扮演着至关重要的角色，它提供了管理Bean、依赖注入、事件发布和配置信息等功能。通过合理地使用`Context`，您可以构建出松耦合、可扩展且易于维护的应用程序。

## 依赖注入(DI)和控制反转(IOC)

依赖注入的优势：

- 松耦合
- 代码易于测试

`org.springframework.beans` 和 `org.springframework.context` 包是Spring Framework的IoC容器的基础。

IOC  ：使用对象时，由主动new产生对象转换为由外部提供对象，对象的创建控制权由程序转移到外部，这种思想称为控制反转。就是解耦。

IOC容器  ：（Core Container）Spring提供了这个容器，用来充当IOC思想中的”外部“。

这两个就是同一个”外部“。

Bean ：IOC容器负责对象的创建，初始化等一系列工作，被创建或被管理的对象在IOC容器中统称为bean。

DI ：在容器中建立bean与bean之间的依赖关系的整个过程，就称为依赖注入。

原文链接：https://blog.csdn.net/weixin_74265534/article/details/132773355

## 名词概念

### POJO

（Plain Ordinary Java Object）简单的Java对象，实际就是普通JavaBeans，是为了避免和EJB混淆所创造的简称。

使用POJO名称是为了避免和[EJB](https://baike.baidu.com/item/EJB/0?fromModule=lemma_inlink)混淆起来, 而且简称比较直接. 其中有一些属性及其getter setter方法的类,没有业务逻辑，有时可以作为[VO](https://baike.baidu.com/item/VO/23210302?fromModule=lemma_inlink)(value -object)或[dto](https://baike.baidu.com/item/dto/16016821?fromModule=lemma_inlink)(Data Transform Object)来使用.当然,如果你有一个简单的运算属性也是可以的,但不允许有业务方法,也不能携带有connection之类的方法。

### Netty

非Servlet容器的服务器（如）

### AOT

> 处理可以用来提前（ahead-of-time）

###  [`BeanFactory`](https://docs.spring.io/spring-framework/docs/6.0.8-SNAPSHOT/javadoc-api/org/springframework/beans/factory/BeanFactory.html)

> 接口提供了一种高级配置机制，能够管理任何类型的对象。 [`ApplicationContext`](https://docs.spring.io/spring-framework/docs/6.0.8-SNAPSHOT/javadoc-api/org/springframework/context/ApplicationContext.html) 是 `BeanFactory` 的一个子接口。`ApplicationContext` 是 `BeanFactory` 的一个完整的超集

### MVC

> （Model-View-Controller）是一种设计模式，广泛用于构建用户界面，特别是 Web 应用程序。它通过将应用程序的数据模型、用户界面和控制逻辑分离，提高了代码的可维护性和可扩展性。MVC 的三个主要组件包括：

    1. **Model（模型）**：
       - 模型代表应用程序的数据和业务逻辑。
       - 它负责处理数据的存储、检索和处理。
       - 模型不知道视图和控制器的存在，它只是提供数据和处理业务规则。

    2. **View（视图）**：
       - 视图是用户看到和与之交互的界面。
       - 它负责显示模型中的数据。
       - 视图不处理数据，只是从模型获取数据并展示给用户。
       - 在 Web 应用程序中，视图通常是由 HTML、CSS 和 JavaScript 组成的页面。

    3. **Controller（控制器）**：
       - 控制器接收用户的输入，并调用模型和视图去执行相应的任务。
       - 它负责处理用户的请求，更新模型的状态，并选择合适的视图来显示结果。
       - 控制器充当模型和视图之间的协调者。

MVC 模式的优势包括：

- **分离关注点**：通过将应用程序的不同方面分离到不同的组件中，使得每个部分都可以独立开发和测试。
- **提高可维护性**：更改视图或模型时，不需要修改控制器，反之亦然，这减少了代码间的耦合。
- **促进团队协作**：不同的开发人员可以同时工作在不同的组件上，例如一个开发人员专注于用户界面，另一个专注于业务逻辑。
- **易于扩展**：添加新功能时，可以只修改或添加相关的组件，而不影响整个应用程序。

在 Web 开发中，MVC 模式通常与各种框架一起使用，这些框架提供了实现 MVC 架构所需的基础设施和约定。例如，Java 世界中有 Spring MVC、Struts 和 JSF，而在 Ruby on Rails、ASP.NET MVC 和 Laravel 等其他编程语言中也都有相应的 MVC 框架。

值得注意的是，虽然 MVC 是一种广泛认可的设计模式，但它并不是唯一的选择。根据项目的具体需求和上下文，可能会有其他的架构模式，如 MVP（Model-View-Presenter）、MVVM（Model-View-ViewModel）等，这些都是 MVC 的变种或衍生模式。



## 版本控制

Spring Framework 6.0开始，Spring需要Java 17+



## Spring的其他项目

Spring不断创新，不断发展。除了Spring框架，还有其他项目，如Spring Boot、Spring Security、Spring Data、Spring Cloud、Spring Batch等。重要的是要记住，每个项目都有自己的源代码库、issue tracker 和发布节奏。参见 [spring.io/projects](https://spring.io/projects)，了解Spring项目的完整列表。

