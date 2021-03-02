# Iterators

Iterators are the link between algorithm and containers. We can comprehend it like a "pointer" to an array. But it was designed together with the container itself.



## declaration & initialization

default iterator:

container_name::iterator  x;

reverse iterator:

container_name::reverse_iterator x;



## operations

 ++x : move to the next element

*x : visit the element

正向迭代器仅支持++

双向：支持--

随机访问：支持p+=i,即随意移动指针的操作。

|      容器      |  迭代器功能  |
| :------------: | :----------: |
|     vector     |   随机访问   |
|     deque      |   随机访问   |
|      list      |     双向     |
| set / multiset |     双向     |
| map / multimap |     双向     |
|     stack      | 不支持迭代器 |
|     queue      | 不支持迭代器 |
| priority_queue | 不支持迭代器 |