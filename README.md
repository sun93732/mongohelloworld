# mongohelloworld

第一次尝试把Hibernate和MongoDB结合起来，网上的很多教程都有问题。不能很全面的概括，导致出现了很多异常。
后来发现引入的依赖必须版本之间保持兼容，否则很容易出现很多无法ClassNotFoundException

目前这个依旧比较依赖Jboss的类， 后续希望可以替换成比较通用的Transaction。
