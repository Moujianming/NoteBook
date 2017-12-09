* [github README.md的使用手册](https://github.com/guodongxiaren/README#￦ﾖﾇ￦ﾜﾬ￥ﾝﾗ)
* [hibernate注解开发](https://github.com/Moujianming/hibernate2)
* [hibernate xml配置文件开发](https://github.com/Moujianming/hibernate)
>两种开发的比较:
      
      XML配置方式： 
      优：容易编辑，配置比较集中，方便修改，在大业务量的系统里面，通过xml配置会方便后人理解整个系统的架构，修改之后直接重启应用即可 
      缺：比较繁琐，配置形态丑陋, 配置文件过多的时候难以管理 
      注解方式： 
      优：方便，简洁，配置信息和 Java 代码放在一起，有助于增强程序的内聚性。 
      缺：分散到各个class文件中，所以不宜维护, 修改之后你需要重新打包，发布，重启应用。 

      个人体会： 小项目，参与人数不多，不复杂的用注解，开发快速。 复杂项目，多人交互，配置量大，维护复杂度高的，用配置文件。
