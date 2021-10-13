# xxl-job-oracle
xxl-job for oracle


# 注意事项 author：fkty
* 使用时导入tables_xxl_job-oracle.sql文件
* oracle字符集和驱动版本问题 pom引入依赖
  
      <dependency>
          <groupId>com.oracle.database.jdbc</groupId>
          <artifactId>ojdbc8</artifactId>
          <version>21.3.0.0</version>
      </dependency>

  	<dependency>
  		<groupId>cn.easyproject</groupId>
  		<artifactId>orai18n</artifactId>
  		<version>12.1.0.2.0</version>
  	</dependency>
  
* 修改配置文件 application.properties oracle驱动
