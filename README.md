# B-spring-ioc-container-homework
Spring IoC Container Basics 课程课后作业。

@Component 已经可以支持声明一个 bean 了，为何还要再弄个 @Bean 出来？

A:@Component作用于类，由Spring自动装配Bean对象；
  @Bean作用于方法，显示指定通过此方法获得Bean对象，因此更灵活，必须和@Configuration注解一起使用
