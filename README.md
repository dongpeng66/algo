# algo
## 鸡汤篇
* 用产品思维帮助更多的人学习算法 更多的为用户考虑而写的一个仓库
* 用老罗的话 彪悍的人生不需要解释 挑一点恶心的干干 先开始写算法，像打造产品一样写一个算法仓库， 帮助更多的人学习算法，同样也是自我学习的过程
* Java写的算法仓库  算法最重要的是心得

* 准备做一个长期的算法仓库 ，像阿甘一样做个傻子，不停奔跑，每天学习一个两个算法，复利思维

* 日拱一卒，功不唐捐

* 把人生比作公司或者游戏的话 ， 我准备长期做的事情，一个是跑步锻炼身体，一个阅读书籍（技术类，非技术类书籍），一个就是这个算法仓库了 
* 纸上得来终觉浅 ，绝知此事要躬行
* 三部曲： 模仿，学习， 超越
* 高筑墙 ， 广积粮 ， 缓称王
* 算法： 先把一个大问题拆解成一个个小问题 ，  再解决小问题 ， 小问题解决了拼接起来解决大问题

##  排序算法
*  冒泡排序 ：BubbleSort
*  插入排序 ： InsertSort   思路： 1. 每次碰到元素小的值  就往后面挪动一位  2.insertValue的值插入适当的位置
*  选择排序： SelectSort    首先找出数组中最小的哪个元素 ，其次，将它和数组的第一个元素交换位置 以此类推 
*  快速排序： QuickSort   1. 递归  2 。 二分  3. 双指针的思路
*  计数排序：CountSort
*  归并排序： mergeSort  主要思想是递归   2. 主要是两个小的有序的数组合并成一个大的数组
*   希尔排序: ShellSort  思路 : 先分组 再使用插入排序 ，再缩小间隔d
*   堆排序 ：HeapSort    题解： 1. 堆存储结构是个数组  2. 先构建一个大顶堆 3 ， 遍历取大顶堆  取最大值

##  二叉树
*  二分查找：  HalfSearch        有序序列采用二分查找
* 二叉树前序遍历题解  ：Solution   1. 根结点 ---> 左子树 ---> 右子树  2. 单层条件是先根节点，左节点 右节点 后使用递归 ，递归的基线条件是：root节点==null 终止
*  二叉树中序遍历：MiddleSolution     ： 题解：  左子树——根节点——右子树   迭代解法  ：1. while   2 .入栈 3. 出栈
* 平衡二叉搜索树 ： AVLTree            关键字1. LL 右旋  2.RR 左旋  3.LR 先左旋 再右旋  4 RL 先右旋  再左旋
* 二叉堆:BinaryHeap                数学要好 1.  父节点的下标是P 他的左孩子下标就是 2P+1 2P+2          2. 最大堆上浮，跟自己的父节点对比 ， 比父节点大上浮， 不断对比
*  优先队列： PriorityQueue   题解：插入进行上浮操作  删除进行：最后一个替换到堆顶 ， 然后进行下沉操作  

##  算法题解
* 三数之和:ThreeNum 主要思路： 1.先排序 2.遍历每一个元素 3. 使用双指针
*  股票问题:StockProfit  如何获得最大收益  思路： 记录最小值 ，差值较大的覆盖之前的
*  缓存淘汰算法:  LruCache      维护一个双向链表 ，一个hashMap


##  算法图书  
* 如果侵权 ， 联系删除
* 数据结构与算法分析：C语言描述_原书第2版_高清版
* 算法图解.PDF
* 数据结构 C++ .3rd_edn. 邓俊辉
* 算法4
* 算法新解
* 我的第一本算法书


### 有错误勘误，可以联系我
* 邮箱： 2695621767@qq.com







