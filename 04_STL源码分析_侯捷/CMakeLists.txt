cmake_minimum_required(VERSION 3.21)
project(STL_)

set(CMAKE_CXX_STANDARD 11)

add_executable(STL_ main.cpp 01_基础问题/01分析基础.cpp 01_基础问题/assist.h 02_allocator/test.cpp 02_allocator/jjalloc.h 03_迭代器/3_1_find.cpp 03_迭代器/3_2_1_auto_ptr.cpp 03_迭代器/3_2_2_mylist.h 03_迭代器/3_2_3_myList_test.cpp 03_迭代器/3_2_4_myListIter.h 03_迭代器/3_2_5_MyList_Iter_Test.cpp 03_迭代器/3_4_1_traits.cpp 03_迭代器/3_4_2_traits.cpp 03_迭代器/3_4_3_traitrs.cpp 04_顺序容器/4_2_1_vecotr迭代器问题.cpp 04_顺序容器/4_3_2_list结构.h 04_顺序容器/4_4_1_deque基本结构.h 04_顺序容器/4_5_1_stack基本结构.cpp 04_顺序容器/4_6_1_queue基本结构.cpp 04_顺序容器/4_2_2_vector基本结构.cpp 04_顺序容器/4_2_3_vector自增长问题.cpp 04_顺序容器/test.cpp 04_顺序容器/4_4_2_deque的随机插入问题.cpp 04_顺序容器/4_4_3_deque如何模拟连续空间.cpp 05_关联容器/5_1_1_红黑树问题.cpp 05_关联容器/5_3_1_set.cpp 05_关联容器/5_4_1_map.cpp)
