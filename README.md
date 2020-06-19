problem 1

@Component 与 @Bean 的不同 1.@Component 是用来自动发现和自动配置bean的，是在类与bean之间建立一个隐式的一对一的映射。 2.@Bean 是显式地声明一个bean。可以用来根据动态状态实现不同地场景。它可以告诉spring显示注册一个对象为bean 3.@bean 可以解耦类定义中bean声明，@Component不能 4.@Component是一个类级别的注释，@bean是一个方法级别的注释 5.@Component不需要和@Configuration 一起使用，而@bean需要 6.@Component不用用于spring 容器外的的类，而@bean可以 7.@Component 具有多样性，像@Repository @Service @ Controller,而@bean 不具有
