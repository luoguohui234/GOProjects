#OfflineServer
##说明
或者称为MockServer，顾名思义，离线使用的后台服务，即模拟真实的server，当后台服务不可达，或者在开发模式下使用。
特别在两个团队分前后台开发的时候，把后台服务直接模拟出来，两个团队之间只进行API接口编程，这样开发效率也会有较好的提升。

##offlineserver的框架介绍
###Third party lib
1. [httprouter](http://godoc.org/github.com/julienschmidt/httprouter)