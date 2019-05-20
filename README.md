# students
一个学生信息管理平台
一个maven项目，相比之前新增了选课功能
运行DemoApplication.java即可启动项目
修改application.yml中的数据库连接信息
students

├─ log
│    ├─ manage.2019-03-18.log
│    ├─ manage.2019-03-19.log
│    ├─ manage.2019-03-20.log
│    ├─ manage.2019-03-21.log
│    ├─ manage.2019-03-22.log
│    ├─ manage.2019-03-25.log
│    ├─ manage.2019-03-26.log
│    ├─ manage.2019-03-27.log
│    ├─ manage.2019-03-28.log
│    ├─ manage.2019-04-01.log
│    ├─ manage.2019-04-02.log
│    ├─ manage.2019-04-03.log
│    ├─ manage.2019-04-04.log
│    ├─ manage.2019-04-08.log
│    ├─ manage.2019-04-09.log
│    ├─ manage.2019-04-10.log
│    ├─ manage.2019-04-11.log
│    ├─ manage.2019-04-12.log
│    ├─ manage.2019-04-15.log
│    ├─ manage.2019-04-17.log
│    ├─ manage.2019-04-18.log
│    ├─ manage.2019-04-19.log
│    ├─ manage.2019-04-22.log
│    ├─ manage.2019-04-23.log
│    ├─ manage.2019-04-24.log
│    └─ manage.log
├─ mvnw
├─ mvnw.cmd
├─ out
│    └─ artifacts
│           └─ students_jar
│                  ├─ HikariCP-3.2.0.jar
│                  ├─ classmate-1.4.0.jar
│                  ├─ filters-2.0.235-1.jar
│                  ├─ hibernate-validator-6.0.14.Final.jar
│                  ├─ jackson-annotations-2.9.0.jar
│                  ├─ jackson-core-2.9.8.jar
│                  ├─ jackson-databind-2.9.8.jar
│                  ├─ jackson-datatype-jdk8-2.9.8.jar
│                  ├─ jackson-datatype-jsr310-2.9.8.jar
│                  ├─ jackson-module-parameter-names-2.9.8.jar
│                  ├─ javax.annotation-api-1.3.2.jar
│                  ├─ javax.servlet-api-4.0.1.jar
│                  ├─ jboss-logging-3.3.2.Final.jar
│                  ├─ jul-to-slf4j-1.7.25.jar
│                  ├─ kaptcha-2.3.2.jar
│                  ├─ log4j-api-2.11.2.jar
│                  ├─ log4j-to-slf4j-2.11.2.jar
│                  ├─ logback-classic-1.2.3.jar
│                  ├─ logback-core-1.2.3.jar
│                  ├─ mybatis-3.5.0.jar
│                  ├─ mybatis-spring-2.0.0.jar
│                  ├─ mybatis-spring-boot-autoconfigure-2.0.0.jar
│                  ├─ mybatis-spring-boot-starter-2.0.0.jar
│                  ├─ mybatisplus-spring-boot-starter-1.0.5.jar
│                  ├─ mysql-connector-java-8.0.15.jar
│                  ├─ slf4j-api-1.7.25.jar
│                  ├─ snakeyaml-1.23.jar
│                  ├─ spring-aop-5.1.5.RELEASE.jar
│                  ├─ spring-beans-5.1.5.RELEASE.jar
│                  ├─ spring-boot-2.1.3.RELEASE.jar
│                  ├─ spring-boot-autoconfigure-2.1.3.RELEASE.jar
│                  ├─ spring-boot-configuration-processor-2.1.3.RELEASE.jar
│                  ├─ spring-boot-starter-2.1.3.RELEASE.jar
│                  ├─ spring-boot-starter-jdbc-2.1.3.RELEASE.jar
│                  ├─ spring-boot-starter-json-2.1.3.RELEASE.jar
│                  ├─ spring-boot-starter-logging-2.1.3.RELEASE.jar
│                  ├─ spring-boot-starter-tomcat-2.1.3.RELEASE.jar
│                  ├─ spring-boot-starter-web-2.1.3.RELEASE.jar
│                  ├─ spring-context-5.1.5.RELEASE.jar
│                  ├─ spring-core-5.1.5.RELEASE.jar
│                  ├─ spring-expression-5.1.5.RELEASE.jar
│                  ├─ spring-jcl-5.1.5.RELEASE.jar
│                  ├─ spring-jdbc-5.1.5.RELEASE.jar
│                  ├─ spring-tx-5.1.5.RELEASE.jar
│                  ├─ spring-web-5.1.5.RELEASE.jar
│                  ├─ spring-webmvc-5.1.5.RELEASE.jar
│                  ├─ students.jar
│                  ├─ tomcat-embed-core-9.0.16.jar
│                  ├─ tomcat-embed-el-9.0.16.jar
│                  ├─ tomcat-embed-websocket-9.0.16.jar
│                  └─ validation-api-2.0.1.Final.jar
├─ pom.xml
├─ src
│    ├─ main
│    │    ├─ java
│    │    │    └─ com
│    │    │           └─ example
│    │    │                  └─ demo
│    │    │                         ├─ DemoApplication.java
│    │    │                         ├─ controller
│    │    │                         │    ├─ CourseController.java
│    │    │                         │    ├─ StudentController.java
│    │    │                         │    ├─ TeacherController.java
│    │    │                         │    └─ UserController.java
│    │    │                         ├─ entity
│    │    │                         │    ├─ ChooseCourse.java
│    │    │                         │    ├─ Course.java
│    │    │                         │    ├─ Student.java
│    │    │                         │    ├─ Teacher.java
│    │    │                         │    ├─ TeacherSeeCourseList.java
│    │    │                         │    ├─ User.java
│    │    │                         │    └─ adminSeeStudentChooseCourseMsg.java
│    │    │                         ├─ mapper
│    │    │                         │    ├─ CourseMapper.java
│    │    │                         │    ├─ StudentMapper.java
│    │    │                         │    ├─ TeacherMapper.java
│    │    │                         │    └─ UserMapper.java
│    │    │                         ├─ service
│    │    │                         │    ├─ CourseService.java
│    │    │                         │    ├─ CourseServiceImpl.java
│    │    │                         │    ├─ StudentService.java
│    │    │                         │    ├─ StudentServiceImpl.java
│    │    │                         │    ├─ TeacherService.java
│    │    │                         │    ├─ TeacherServiceImpl.java
│    │    │                         │    ├─ UserService.java
│    │    │                         │    └─ UserServiceImpl.java
│    │    │                         └─ utils
│    │    │                                ├─ Response.java
│    │    │                                └─ Verify.java
│    │    └─ resources
│    │           ├─ a.xml
│    │           ├─ application.yml
│    │           ├─ logback-spring.xml
│    │           ├─ mapper
│    │           │    ├─ CourseMapper.xml
│    │           │    ├─ StudentMapper.xml
│    │           │    ├─ TeacherMapper.xml
│    │           │    └─ UserMapper.xml
│    │           └─ static
│    │                  ├─ admin
│    │                  │    ├─ adminCenter.html
│    │                  │    ├─ adminSeeStudentChooseCourseMsg.html
│    │                  │    ├─ adminUserCenter.html
│    │                  │    ├─ courseMsgCenter.html
│    │                  │    ├─ showAllStudentsMsg.html
│    │                  │    └─ showAllTeachersMsg.html
│    │                  ├─ css
│    │                  │    └─ head.css
│    │                  ├─ img
│    │                  │    └─ timg.jpg
│    │                  ├─ js
│    │                  │    └─ jquery2.0.js
│    │                  ├─ student
│    │                  │    ├─ chooseClass.html
│    │                  │    ├─ forgetPassword.html
│    │                  │    ├─ login.html
│    │                  │    ├─ register.html
│    │                  │    ├─ studentMsgAdd.html
│    │                  │    ├─ studentPersonalMsgCenter.html
│    │                  │    ├─ userIndex.html
│    │                  │    └─ userPersonalCenter.html
│    │                  └─ teacher
│    │                         ├─ showCourseMsg.html
│    │                         ├─ showStudentList.html
│    │                         ├─ teacherAddCourse.html
│    │                         ├─ teacherCenter.html
│    │                         ├─ teacherMsgCenter.html
│    │                         ├─ teacherPersonalCenter.html
│    │                         └─ teacherPersonalMsgCenter.html
│    └─ test
│           └─ java
│                  └─ com
│                         └─ example
│                                └─ demo
│                                       └─ DemoApplicationTests.java
├─ students.iml
└─ target
       ├─ classes
       │    ├─ a.xml
       │    ├─ application.yml
       │    ├─ com
       │    │    └─ example
       │    │           └─ demo
       │    │                  ├─ DemoApplication.class
       │    │                  ├─ controller
       │    │                  │    ├─ CourseController.class
       │    │                  │    ├─ StudentController.class
       │    │                  │    ├─ TeacherController.class
       │    │                  │    └─ UserController.class
       │    │                  ├─ entity
       │    │                  │    ├─ ChooseCourse.class
       │    │                  │    ├─ Course.class
       │    │                  │    ├─ Student.class
       │    │                  │    ├─ Teacher.class
       │    │                  │    ├─ TeacherSeeCourseList.class
       │    │                  │    ├─ User.class
       │    │                  │    └─ adminSeeStudentChooseCourseMsg.class
       │    │                  ├─ mapper
       │    │                  │    ├─ CourseMapper.class
       │    │                  │    ├─ StudentMapper.class
       │    │                  │    ├─ TeacherMapper.class
       │    │                  │    └─ UserMapper.class
       │    │                  ├─ service
       │    │                  │    ├─ CourseService.class
       │    │                  │    ├─ CourseServiceImpl.class
       │    │                  │    ├─ StudentService.class
       │    │                  │    ├─ StudentServiceImpl.class
       │    │                  │    ├─ TeacherService.class
       │    │                  │    ├─ TeacherServiceImpl.class
       │    │                  │    ├─ UserService.class
       │    │                  │    └─ UserServiceImpl.class
       │    │                  └─ utils
       │    │                         ├─ Response.class
       │    │                         └─ Verify.class
       │    ├─ logback-spring.xml
       │    ├─ mapper
       │    │    ├─ CourseMapper.xml
       │    │    ├─ StudentMapper.xml
       │    │    ├─ TeacherMapper.xml
       │    │    └─ UserMapper.xml
       │    └─ static
       │           ├─ admin
       │           │    ├─ adminCenter.html
       │           │    ├─ adminSeeStudentChooseCourseMsg.html
       │           │    ├─ adminUserCenter.html
       │           │    ├─ courseMsgCenter.html
       │           │    ├─ showAllStudentsMsg.html
       │           │    └─ showAllTeachersMsg.html
       │           ├─ css
       │           │    └─ head.css
       │           ├─ img
       │           │    └─ timg.jpg
       │           ├─ js
       │           │    └─ jquery2.0.js
       │           ├─ student
       │           │    ├─ chooseClass.html
       │           │    ├─ forgetPassword.html
       │           │    ├─ login.html
       │           │    ├─ register.html
       │           │    ├─ studentMsgAdd.html
       │           │    ├─ studentPersonalMsgCenter.html
       │           │    ├─ userIndex.html
       │           │    └─ userPersonalCenter.html
       │           └─ teacher
       │                  ├─ showCourseMsg.html
       │                  ├─ showStudentList.html
       │                  ├─ teacherAddCourse.html
       │                  ├─ teacherCenter.html
       │                  ├─ teacherMsgCenter.html
       │                  ├─ teacherPersonalCenter.html
       │                  └─ teacherPersonalMsgCenter.html
       ├─ demo-0.0.1-SNAPSHOT.jar
       ├─ demo-0.0.1-SNAPSHOT.jar.original
       ├─ maven-archiver
       │    └─ pom.properties
       ├─ maven-status
       │    └─ maven-compiler-plugin
       │           ├─ compile
       │           │    └─ default-compile
       │           │           ├─ createdFiles.lst
       │           │           └─ inputFiles.lst
       │           └─ testCompile
       │                  └─ default-testCompile
       │                         ├─ createdFiles.lst
       │                         └─ inputFiles.lst
       ├─ surefire-reports
       │    ├─ TEST-com.example.demo.DemoApplicationTests.xml
       │    └─ com.example.demo.DemoApplicationTests.txt
       └─ test-classes
              └─ com
                     └─ example
                            └─ demo
                                   └─ DemoApplicationTests.class
