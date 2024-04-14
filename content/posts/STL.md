+++
title = 'STL'
date = 2024-04-14T14:08:47+08:00
description = ''
author = 'thehanged'
categories = ['algorithm']
draft = true
+++

## Vector
需要引入头文件`<vector>`


## List
双向链表

## Deque
`priority_queue`优先队列，操作遵循队列的FIFO原则，但是里面的元素是优先级排列的，STL的优先队列默认是**大顶堆**实现的，可以通过`greater<int>`改变优先级为小顶堆。

![alt](/static/pq_base.png)

```cpp
// 引入头文件
#include <queue>

// 定义
priority_queue<int> a;
/**
 * 第一个参数是数据类型
 * 第二个参数是容器类型
 * 第三个参数是比较函数
 */
priority_queue<int, vector<int>, less<int>> a1; // 同a
priority_queue<int, vector<int>, greater<int>> c; // 小顶堆
```

## Map
