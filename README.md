# 简介

这是我2018年参加的校园招聘中，整理出来的C++面试题。总共大概300多道题。从各个面经中抽离出来的，目前还没有整合，所以里面有些经常被问到的高频题会重复。**重复率越高的题，说明越容易问，越重要**。应该算比较全的了，基本上在我自己面试过程中，被问到关于C++的部分，都在这里面。

# C++校招面试题300道（每一题对应的答案，以后有时间添加）


1. 智能指针的作用
2. 纯虚函数作用和实现方式
3. STL数据结构的内部实现
4. 红黑树插入和红黑树的用途
5. C、C++的区别以及C++的优势
6. STL中的各种数据结构的底层实现
7. C++11的新特性有哪些，智能指针
8. STL的掌握程度
9. 指针和引用的区别，引用需要释放内存吗
10. 智能指针的底层实现
11. 虚函数的底层实现
12. define的特点，预处理进行替换及define的优缺点
13. static作用
14. 红黑树有哪些具体应用
15. 指针和引用的区别
16. new和malloc的区别
17. 形参加const的优点
18. 内存四区
19. vector的扩容原理
20. C++单例模式
21. map查找重复值的函数
22. map的实现原理和红黑树的特点
23. main函数传参数的意义
24. 三种继承方式
25. 析构函数和虚函数
26. extern “C”的作用
27. 多态
28. 构造函数是否能为虚函数，构造顺序和析构顺序
29. 指针常量和常量指针
30. string的构造次数
31. C++多态实现机制
32. 模板和类封装各自在什么不同的情况使用，各有什么优缺点
33. C++内存管理
34. 多态实现机制
35. 类中哪些函数不能为虚函数？static成员函数如果想实现虚函数的功能，怎么实现？
36. C++11的auto和lambda
37. hashmap的底层实现
38. vector的底层实现，有什么特点
39. C++的内存布局
40. 内存对齐是什么及其实现原理
41. 函数调用怎么实现的，传参数怎么实现的？
42. 有什么好的内存管理模式
43. 智能指针，有什么缺点
44. static、const
45. C++多态
46. C++特性
47. 虚函数
48. static作用，是否能为虚函数
49. 析构函数能否为虚函数
50. 如何检测内存泄漏
51. 讲讲智能指针
52. C++容器有哪些
53. list和vector有什么区别
54. 讲讲大端小端，如何检测
55. public和private关键字
56. 设计一个内存分配类
57. 智能指针，shared_ptr内部实现
58. 面向对象的特征，讲讲多态，什么是多态？
59. sizeof和strlen的区别
60. 析构函数能不能用virtual
61. 引用和指针的区别
62. 引用必须初始化，现在要设计一个类中如何初始化引用。
63. C++如何处理异常，异常向上抛出，抛到最上层是什么情况？
64. vector实现原理
65. 如何实现vector在扩容的时候不进行新的空间申请，即不想有扩容操作，该如何设计？
66. STL中的空间配置器
67. 面向对象的特性
68. 多态：重载，虚函数，override，overload
69. 继承中的private、public；class与struct的区别
70. 内联函数与虚函数
71. 指针和引用
72. static和const
73. 智能指针
74. 宏和const、inline
75. 构造函数、析构函数、虚函数、拷贝构造、赋值操作符
76. new和malloc
77. 进程地址空间内存分配
78. strcopy、memcopy、memmove
79. 内存对齐
80. 类型转换
81. sizeof与strlen的区别
82. 深拷贝、浅拷贝
83. 静态链接、动态链接的区别
84. STL空间配置
85. STL空间配置，具体实现过程，如果内存链表中没有空间会怎么处理，如果内存池中没有空间会怎么处理，如果heap中没有空间会怎么处理，为什么自由链表中的倍数是8byte，而不是其他。
86. vector的实现，如何实现不发生拷贝到新空间就只在当前空间扩容
87. set、map的底层实现，红黑树的概念，红黑树的插入
88. 多态实现机制
89. static成员函数作用
90. 虚拟内存
91. 动态链接库的认识
92. 继承和多态，多态的实现原理
93. 指针和引用的区别
94. 纯虚函数有什么特点
95. vector::push_back()的实现
96. 多态的类，内存布局是怎么样
97. extern "c"的作用
98. unordered_set的底层数据结构
99. 隐式类型转换与显式类型转换
100. 如何避免编译器进行隐式类型转换
101. 大小端字节序相关
102. 虚拟内存作用，如何根据虚拟地址得到物理地址
103. 抽象类和普通类有什么区别
104. 前置操作与后置操作的区别，比如++i和i++。
105. STL中常用的容器的实现
106. std::string类的实现
107. 手写atoi
108. 指针与引用的区别
109. C++如何实现多态
110. STL里面的map如何实现
111. 谈谈红黑树
112. C++中，你觉得哪些关键字比较有意思
113. 宏定义#define与const常量有什么区别
114. static关键字有什么作用
115. STL下sort()的内部实现，stable_sort()内部实现，lower_bound()内部实现
116. 简单说说，大小端字节序。
117. malloc()申请的内存，在系统的内存分布中，处于哪一段
118. 纯虚函数与一般函数的区别，纯虚函数能否具体实现。
119. C++多态的实现
120. 虚函数表存放什么内容，子类继承基类后，重写与不重写虚函数的情况下，虚函数表的内容分别是什么
121. 函数压栈的过程
122. 类的成员函数的压栈过程，this指针
123. static关键字的作用，定义的变量存储在进程空间的哪个区域
124. 只能在栈上构造的类，只能在堆上构造的类
125. 对面向对象设计的认识
126. STL中各容器的实现
127. hash如何避免冲突
128. 指针和引用的区别
129. C++对象的内存布局
130. 类的静态成员存储在哪，静态成员函数能访问非静态数据成员吗
131. C++多态如何实现的
132. 智能指针，使用智能指针会不会内存泄露
133. C++类的内存分布
134. 虚函数实现多态
135. 静态库与动态库，静态链接与动态链接
136. C++多态的实现
137. 堆和栈的区别
138. new和delete是如何实现的，new和malloc的异同处
139. C和C++的区别
140. struct和class的区别
141. define和const的区别（编译阶段，安全性，内存占用等）
142. 在C++中const和static的用法
143. const和static在类中使用的注意事项
144. C++中的const类成员函数
145. C++的STL介绍
146. STL源码中的hash表的实现
147. STL中unordered_map和map的区别
148. STL中vector的实现
149. vector使用的注意点及其原因，频繁对vector调用push_back()对性能的影响和原因
150. C++的重载和重写的区别
151. C++内存管理
152. 介绍面向对象的三大特性
153. 多态的实现
154. C++虚函数相关（虚函数表，虚函数指针），虚函数的实现原理
155. 实现编译器处理虚函数表应该如何处理。
156. 析构函数一般写成虚函数的原因
157. 构造函数为什么一般不定义为虚函数
158. 构造函数或许析构函数中调用虚函数会怎么样
159. 纯虚函数
160. 静态绑定和动态绑定的介绍
161. 引用是否能实现动态绑定，为什么引用可以实现
162. 深拷贝和浅拷贝的区别，举例子说明深拷贝的安全性
163. 对象复用的了解，零拷贝的了解
164. 介绍C++所有的构造函数
165. 什么情况下会调用拷贝构造函数
166. 结构体内存对齐方式和为什么要进行内存对齐
167. 内存泄露的定义，如何检测与避免
168. 手写智能指针类
169. 调用程序的方法
170. 遇到coredump要怎么调试
171. 内存检查工具的了解
172. 模板的用法与适用场景
173. 成员初始化列表的概念，为什么用成员初始化列表会快一些
174. 用过C++11吗，知道C++11新特性吗
175. C++的调用管理（C++函数调用的压栈过程）
176. C++的四种强制转换
177. C++的内存管理有哪些
178. 指针和引用的区别
179. define和const有什么区别
180. define和const分别在什么时候编译，哪个更安全
181. 在类中，基类的析构函数为什么要设置成虚函数
182. 虚函数的实现
183. 面向对象的三个特性是什么
184. 详细介绍一下多态
185. set、map和vector的插入复杂度
186. 讲讲static的用法
187. 全局变量和局部的静态变量除了可见区域不同，还有什么不用
188. 什么时候要有拷贝构造函数
189. C++里面的红黑树
190. C++类里面函数加const的原因和实现？能不能在函数前面加上static，为什么
191. C++中加入构造函数里面有虚函数，会怎么样
192. 虚函数的实现，及其具体的过程，例如虚函数指针在不同对象的指向
193. vector迭代器失效的情况
194. 面向对象的理解
195. 多态的理解
196. C++的const和static作用
197. C++的内存泄漏
198. 面向对象的三个特性
199. C++的虚函数
200. map里面的并发
201. 怎么将一个map清空（map的clear和erase的区别）
202. 怎么用C++连接到数据库
203. 多态的实现
204. static的作用
205. vector一直插入会导致的问题
206. 指针和引用的区别
207. C++的static怎么使用
208. new和malloc的区别
209. 面向对象三大特性
210. C++的虚函数实现
211. C++的多态，详细说说动态绑定和静态绑定
212. STL的了解：vector的扩容问题，map和unordered_map的底层实现
213. list和vector的使用场景
214. C++的多态实现
215. 了解C++的模板吗？怎么使用的？
216. C++模板为什么声明和定义要放在一个文件里，而不能放在不同文件
217. 如何消除隐式转换？
218. 重载、重写和隐藏的区别
219. volatile表示什么？有什么作用？
220. 四种强制转换的各自作用和使用环境
221. free和delete的区别
222. free一个数组时如何知道要释放多大的内存
223. _stdcall和 _cdecl的区别
224. 出现异常时，try和catch做了什么
225. C++如何处理多个异常的
226. 常对象的成员变量一定不可以修改吗？为什么？
227. 虚函数的调用过程
228. 单继承、多继承、菱形继承、虚继承时，对象内存中的差异区别？如果存在虚函数呢？
229. 实现一个vector？是1.5还是2倍扩容，各有什么优缺点？
230. map底层用了什么？
