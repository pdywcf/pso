海角社区真实偷伦AV视频老熟女ThePorn社区

Collection<String> collection1 = new ArrayList<>();
collection1.add("apple");
collection1.add("banana");

Collection<String> collection2 = new ArrayList<>();
collection2.add("cherry");

boolean addedAll = collection1.addAll(collection2);
System.out.println(addedAll);  // 输出 true
System.out.println(collection1);  // 输出 [apple, banana, cherry]

typescript
运行

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10

    删除元素：
        boolean remove(Object o)：从集合中移除指定的元素，如果移除成功则返回true，否则返回false。比如：

Collection<String> collection = new ArrayList<>();
collection.add("apple");
boolean removed = collection.remove("apple");
System.out.println(removed);  // 输出 true

typescript
运行

    1
    2
    3
    4

    boolean removeAll(Collection<?> c)：从当前集合中移除指定集合中包含的所有元素，如果当前集合因为这个操作而发生了改变，则返回true。例如：
————————————————
