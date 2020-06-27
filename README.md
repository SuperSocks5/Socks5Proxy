# Socks5Proxy
# Android 手机上支持Socks5代理也比较多，ProxyDroid 也是比较有名，但是感觉用起来还是不符合习惯，对小白用户来说设置太多，功能不强大，自己搞了一个。用起来还不错。


## 目前代理的缺点
 - 不能同时开多个代理
 - 所有的APP 都只能用一个代理，不支持区分APP 使用不同代理
 - 页面设置太多，对于小白太不友好了，简单来说就是不会用



## 优化之后
 - 最多可以同时开启两个代理，后面可以继续支持更多。
 - 可以选择App 使用不同的代理，比如QQ 使用A 代理，微信使用B 代理。其他没有选择的就正常上网，实际测试一个模拟器可以支持到40个代理，也就是理想情况下每个App 都可以使用自己的代理
 - 设置超级简单


## 代理设置
     直接打开APP ，点击 代理服务器设置 
![在这里插入图片描述](https://github.com/SuperSocks5/Socks5Proxy/raw/master/image/%E9%A6%96%E9%A1%B5.png)

## 添加代理服务器

    只支持socks代理，直接点击左下角 添加Socks5服务器。目前可以同时支持2个代理。


	这里需要注意下一，可以一次性添加N 多个代理，但是开启的时候最大只能同时开启2个。

![在这里插入图片描述](https://github.com/SuperSocks5/Socks5Proxy/raw/master/image/%E4%BB%A3%E7%90%86%E8%AE%BE%E7%BD%AE%E9%A1%B5%E9%9D%A2.png)
## 设置代理服务器
	这个页面可以设置代理服务器的地址，支持域名或者直接填IP地址。 以及端口号。有些代理服务器需要验证的，这个时候需要填上用户名和密码。没有密码的代理服务器，不需要填用户名和密码。

![在这里插入图片描述](https://github.com/SuperSocks5/Socks5Proxy/raw/master/image/%E8%AE%BE%E7%BD%AE%E4%BB%A3%E7%90%86.png)
## 选择需要代理的APP
	代理服务器可以是全局的， 也就是系统所有的APP 都会通过代理， 也可以指定一些APP 使用代理，非常灵活。

	注意：这里可以同时开启两个代理，一个代理指定部分APP，另一个全局代理。这样的话指定的APP 使用一个代理，其他没有指定的就会使用全局代理了。
![在这里插入图片描述](https://github.com/SuperSocks5/Socks5Proxy/raw/master/image/%E9%80%89%E6%8B%A9App.png)
## 启动代理
	代理添加了之后，一定要记得启用，否则是不起作用的。目前最大支持同时启用2个，貌似是免费版的限制，不清楚后面是否会放开更多代理的支持。
![在这里插入图片描述](https://github.com/SuperSocks5/Socks5Proxy/raw/master/image/%E5%BC%80%E5%90%AF%E5%85%B3%E9%97%AD%E4%BB%A3%E7%90%86.png)

## 启动代理(总开关)
	回到主界面，点击右上角那个按钮就可以直接启动了。简单测试了下效果还不错，满足各种需求，就是目前同时只能支持2个。
![在这里插入图片描述](https://github.com/SuperSocks5/Socks5Proxy/raw/master/image/%E5%90%AF%E5%8A%A8%E4%BB%A3%E7%90%86(%E6%80%BB%E5%BC%80%E5%85%B3).png)

## 注意事项

 - 测试的时候用的雷电模拟器，其他模拟器没有试过，不知道行不行。
 - 真机没有测试，安装APP 的时候，提示我没有root。 后面找个root 的手机来试试看。

