     * 程序名:图书管理系统
     * 作者: WenBao
     * 前言:师从B站楠哥视频"Java Web从入门到实战【完整版】",历经一个月多学完JavaWeb基础构建.
     *     并在楠哥"项目实战"视频引领下完成的第一个JavaWeb项目,十分感谢楠哥视频的帮助,希望自己
     *     以后能找到满意的工作.
     * 工期:2020年12月23日~2021年1月27日
     
     * 主要实现业务逻辑:
     *          1)读者:
     *                  1>图书馆图书资源展示
     *                  2>借阅书籍申请
     *                  3>查询已借图书审核情况
     *                  4>换书申请
     *          2)管理员:
     *                  1>图书馆图书资源展示
     *                  2>读者借阅情况审核
     *                  3>读者还书情况审核
     * 本程序采用MVC设计模式,主要分为实体类(entity),控制类(controller),实现类(repository),接口类(service).
     * 结构为   Controller -> Service -> Repository
     * 实体类(entity):
     *          1)Admin     管理员类
     *          2)Reader    读者类
     *          3)BookCase  图书情况类
     *          4)Borrow    借书类
     *          5)Book      图书类
     * 控制类(controller):
     *          1)LoginServlet   登录业务逻辑
     *          2)LogoutServlet  注销业务逻辑
     *          3)BookServlet    图书业务逻辑
     *          4)AdminServlet   管理员业务逻辑
     * 接口类(service)
     *          1)BookService   图书接口
     *          2)LoginService  登录接口
     * 实现类(repository):
     *          1)AdminRepository   管理员底层实现类
     *          2)ReaderRepository  读者底层实现类
     *          3)BookRepository    图书底层实现类
     *          4)BorrowRepository  借书底层实现类
