Eureka服务注册中心的创建过程
    1、添加依赖
        spring-cloud-starter-eureka-server
    2、在@SpringbootApplication注解的启动类，打上注解@EnableEurekaServer
    3、配置application.yml
    4、打开浏览器：访问http://localhost:8761/eureka