# redisframework
a demo that shows how to implement a 'second kill' using redis distributed lock.

代码中
setnx和expire两个操作不具有原子性，建议改用set来做一个复合操作或者采用lua脚本控制
