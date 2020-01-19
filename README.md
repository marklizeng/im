# Lizeng

测试

1、composer require lizeng/im

2、打开config/app,php,在providers里添加 \Lizeng\Im\ImServiceProvider::class,

3、在项目根目录下composer.json文件中 autoload下psr-4里添加 "Lizeng\\Im\\": "vendor/lizeng/im/src"

4、执行composer dump-autoload

5、执行 php artisan vendor:publish --provider="\Lizeng\Im\ImServiceProvider"

完成!!!!

测试：

    http://localhost/hello