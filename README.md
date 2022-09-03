# leetcode刷题笔记

> 对刷过的题做一下分类记录，方便面试前进行复习。其中参考了很多leetcode题解区算法大佬的答案， 综合考量了算法复杂度和容易理解两方面。

## 数据结构
### 1.数组

+ 双指针

|Title|Solution|
|-|:-:|
|[26. 删除有序数组中的重复项](https://leetcode.cn/problems/remove-duplicates-from-sorted-array/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/26.%E5%88%A0%E9%99%A4%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E9%A1%B9.md)|
|[83. 删除排序链表中的重复元素](https://leetcode.cn/problems/remove-duplicates-from-sorted-list/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/83.%E5%88%A0%E9%99%A4%E6%8E%92%E5%BA%8F%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E5%85%83%E7%B4%A0.md)|
|[27. 移除元素](https://leetcode.cn/problems/remove-element/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/27.%E7%A7%BB%E9%99%A4%E5%85%83%E7%B4%A0.md)|
|[283. 移动零](https://leetcode.cn/problems/move-zeroes/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/283.%E7%A7%BB%E5%8A%A8%E9%9B%B6.md)|
|[167. 两数之和 II - 输入有序数组](https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/167.%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C%20II%20-%20%E8%BE%93%E5%85%A5%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84.md)|
|[344. 反转字符串](https://leetcode.cn/problems/reverse-string/)|[C++]()|
|[5. 最长回文子串](https://leetcode.cn/problems/longest-palindromic-substring/)|[C++]()|
|[870. 优势洗牌](https://leetcode.cn/problems/advantage-shuffle/)|[C++]()|
+ 滑动窗口

|Title|Solution|
|-|:-:|
|[76. 最小覆盖子串](https://leetcode.cn/problems/minimum-window-substring/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/76.%E6%9C%80%E5%B0%8F%E8%A6%86%E7%9B%96%E5%AD%90%E4%B8%B2.md)|
|[567. 字符串的排列](https://leetcode.cn/problems/permutation-in-string/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/567.%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E6%8E%92%E5%88%97.md)|
|[438. 找到字符串中所有字母异位词](https://leetcode.cn/problems/find-all-anagrams-in-a-string/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/438.%E6%89%BE%E5%88%B0%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E6%89%80%E6%9C%89%E5%AD%97%E6%AF%8D%E5%BC%82%E4%BD%8D%E8%AF%8D.md)|
|[3. 无重复字符的最长子串](https://leetcode.cn/problems/longest-substring-without-repeating-characters/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/3.%E6%97%A0%E9%87%8D%E5%A4%8D%E5%AD%97%E7%AC%A6%E7%9A%84%E6%9C%80%E9%95%BF%E5%AD%90%E4%B8%B2.md)|

+ 二分查找

> [二分查找模板总结](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE%E6%A8%A1%E6%9D%BF%E6%80%BB%E7%BB%93.md)

|Title|Solution|
|-|:-:|
|[704. 二分查找](https://leetcode.cn/problems/binary-search/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/704.%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE.md)|
|[34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/34.%E5%9C%A8%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E6%9F%A5%E6%89%BE%E5%85%83%E7%B4%A0%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%92%8C%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E4%BD%8D%E7%BD%AE.md)|
|[875. 爱吃香蕉的珂珂](https://leetcode.cn/problems/koko-eating-bananas/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/875.%20%E7%88%B1%E5%90%83%E9%A6%99%E8%95%89%E7%9A%84%E7%8F%82%E7%8F%82.md)|
|[1011. 在 D 天内送达包裹的能力](https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/1011.%20%E5%9C%A8%20D%20%E5%A4%A9%E5%86%85%E9%80%81%E8%BE%BE%E5%8C%85%E8%A3%B9%E7%9A%84%E8%83%BD%E5%8A%9B.md)|
|[410. 分割数组的最大值](https://leetcode.cn/problems/split-array-largest-sum/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/410.%20%E5%88%86%E5%89%B2%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%A4%A7%E5%80%BC.md)|

+ 前缀和

|Title|Solution|
|-|:-:|
|[303. 区域和检索 - 数组不可变](https://leetcode.cn/problems/range-sum-query-immutable/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/303.%20%E5%8C%BA%E5%9F%9F%E5%92%8C%E6%A3%80%E7%B4%A2%20-%20%E6%95%B0%E7%BB%84%E4%B8%8D%E5%8F%AF%E5%8F%98.md)|
|[304. 二维区域和检索 - 矩阵不可变](https://leetcode.cn/problems/range-sum-query-2d-immutable/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/304.%20%E4%BA%8C%E7%BB%B4%E5%8C%BA%E5%9F%9F%E5%92%8C%E6%A3%80%E7%B4%A2%20-%20%E7%9F%A9%E9%98%B5%E4%B8%8D%E5%8F%AF%E5%8F%98.md)|
|[528. 按权重随机选择](https://leetcode.cn/problems/random-pick-with-weight/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/528.%20%E6%8C%89%E6%9D%83%E9%87%8D%E9%9A%8F%E6%9C%BA%E9%80%89%E6%8B%A9.md)|

+ 
+ 差分

|Title|Solution|
|-|:-:|
|[1109. 航班预订统计](https://leetcode.cn/problems/corporate-flight-bookings/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/1109.%20%E8%88%AA%E7%8F%AD%E9%A2%84%E8%AE%A2%E7%BB%9F%E8%AE%A1.md)|
|[1094. 拼车](https://leetcode.cn/problems/car-pooling/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/1094.%20%E6%8B%BC%E8%BD%A6.md)|

+ 遍历数组

|Title|Solution|
|-|:-:|
|[48. 旋转图像](https://leetcode.cn/problems/rotate-image/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/48.%20%E6%97%8B%E8%BD%AC%E5%9B%BE%E5%83%8F.md)|
|[54. 螺旋矩阵](https://leetcode.cn/problems/spiral-matrix/)|[C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/54.%20%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5.md)|

+ 常数时间删除/查找数组中的任意元素

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [380. O(1) 时间插入、删除和获取随机元素](https://leetcode.cn/problems/insert-delete-getrandom-o1/) | [C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/380.%20O(1)%20%E6%97%B6%E9%97%B4%E6%8F%92%E5%85%A5%E3%80%81%E5%88%A0%E9%99%A4%E5%92%8C%E8%8E%B7%E5%8F%96%E9%9A%8F%E6%9C%BA%E5%85%83%E7%B4%A0.md)  |
| [710. 黑名单中的随机数](https://leetcode.cn/problems/random-pick-with-blacklist/) | [C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/710.%20%E9%BB%91%E5%90%8D%E5%8D%95%E4%B8%AD%E7%9A%84%E9%9A%8F%E6%9C%BA%E6%95%B0.md)  |

+ 单调栈

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [402. 移掉 K 位数字](https://leetcode.cn/problems/remove-k-digits/) | [C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/402.%20%E7%A7%BB%E6%8E%89%20K%20%E4%BD%8D%E6%95%B0%E5%AD%97.md)  |
| [1081. 不同字符的最小子序列](https://leetcode.cn/problems/smallest-subsequence-of-distinct-characters/) | [C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/1081.%20%E4%B8%8D%E5%90%8C%E5%AD%97%E7%AC%A6%E7%9A%84%E6%9C%80%E5%B0%8F%E5%AD%90%E5%BA%8F%E5%88%97.md)  |
| [321. 拼接最大数](https://leetcode.cn/problems/create-maximum-number/) | [C++](https://github.com/damenshi/leetcode-Notes/blob/main/%E6%95%B0%E7%BB%84/321.%20%E6%8B%BC%E6%8E%A5%E6%9C%80%E5%A4%A7%E6%95%B0.md)  |

### 2.链表

+ 双指针

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [141. 环形链表](https://leetcode.cn/problems/linked-list-cycle/) | [C++]()  |
| [142. 环形链表 II](https://leetcode.cn/problems/linked-list-cycle-ii/) | [C++]()  |
| [160. 相交链表](https://leetcode.cn/problems/intersection-of-two-linked-lists/) | [C++]()  |
| [19. 删除链表的倒数第 N 个结点](https://leetcode.cn/problems/remove-nth-node-from-end-of-list/) | [C++]()  |
| [21. 合并两个有序链表](https://leetcode.cn/problems/merge-two-sorted-lists/) | [C++]()  |
| [23. 合并K个升序链表](https://leetcode.cn/problems/merge-k-sorted-lists/) | [C++]()  |
| [86. 分隔链表](https://leetcode.cn/problems/partition-list/) | [C++]()  |
| [234. 回文链表](https://leetcode.cn/problems/palindrome-linked-list/) | [C++]()  |

+  反转链表

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [206. 反转链表](https://leetcode.cn/problems/reverse-linked-list/) | [C++]()  |
| [92. 反转链表 II](https://leetcode.cn/problems/reverse-linked-list-ii/) | [C++]()  |
| [25. K 个一组翻转链表](https://leetcode.cn/problems/reverse-nodes-in-k-group/) | [C++]()  |

### 3.哈希表

| Title | Solution |
| ----- | :------: |
|       | [C++]()  |
|       | [C++]()  |
|       | [C++]()  |

### 

### 4.字符串

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [30. 串联所有单词的子串](https://leetcode.cn/problems/substring-with-concatenation-of-all-words/) | [C++]()  |
|                                                              | [C++]()  |
|                                                              | [C++]()  |

### 5.栈和队列

| Title | Solution |
| ----- | :------: |
|       | [C++]()  |
|       | [C++]()  |
|       | [C++]()  |

### 6.二叉树

+ 二叉树遍历

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [144. 二叉树的前序遍历](https://leetcode.cn/problems/binary-tree-preorder-traversal/) | [C++]()  |
| [94. 二叉树的中序遍历](https://leetcode.cn/problems/binary-tree-inorder-traversal/) | [C++]()  |
| [145. 二叉树的后序遍历](https://leetcode.cn/problems/binary-tree-postorder-traversal/) | [C++]()  |
| [102. 二叉树的层序遍历](https://leetcode.cn/problems/binary-tree-level-order-traversal/) | [C++]()  |

+ 二叉树属性

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [104. 二叉树的最大深度](https://leetcode.cn/problems/maximum-depth-of-binary-tree/) | [C++]()  |
| [111. 二叉树的最小深度](https://leetcode.cn/problems/minimum-depth-of-binary-tree/) | [C++]()  |
| [543. 二叉树的直径](https://leetcode.cn/problems/diameter-of-binary-tree/) | [C++]()  |
| [101. 对称二叉树](https://leetcode.cn/problems/symmetric-tree/) | [C++]()  |
| [222. 完全二叉树的节点个数](https://leetcode.cn/problems/count-complete-tree-nodes/) | [C++]()  |
| [110. 平衡二叉树](https://leetcode.cn/problems/balanced-binary-tree/) | [C++]()  |
|                                                              |          |

+ 二叉树修改与构造
  

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [114. 二叉树展开为链表](https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/) | [C++]()  |
| [116. 填充每个节点的下一个右侧节点指针](https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/) | [C++]()  |
| [226. 翻转二叉树](https://leetcode.cn/problems/invert-binary-tree/) | [C++]()  |
| [105. 从前序与中序遍历序列构造二叉树](https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | [C++]()  |
| [106. 从中序与后序遍历序列构造二叉树](https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | [C++]()  |
| [654. 最大二叉树](https://leetcode.cn/problems/maximum-binary-tree/) | [C++]()  |
| [889. 根据前序和后序遍历构造二叉树](https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/) | [C++]()  |

### 7.图



## 算法

### 1.排序

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [912. 排序数组](https://leetcode.cn/problems/sort-an-array/)：快速排序 | [C++]()  |
|                                                              | [C++]()  |
|                                                              | [C++]()  |
|                                                              |          |

### 2.回溯


+ 组合、排列、子集
| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [77. 组合](https://leetcode.cn/problems/combinations/)       | [C++]()  |
| [39. 组合总和](https://leetcode.cn/problems/combination-sum/) | [C++]()  |
|                                                              | [C++]()  |
|                                                              |          |

+ 字符串中的回溯问题

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
|                                                              | [C++]()  |
| [17. 电话号码的字母组合](https://leetcode.cn/problems/letter-combinations-of-a-phone-number/) | [C++]()  |
|                                                              | [C++]()  |

+ 

### 3.贪心

### 4.动态规划

## CodeTop

+ https://codetop.cc/home

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [206. 反转链表](https://leetcode.cn/problems/reverse-linked-list/) |          |
| [146. LRU 缓存](https://leetcode.cn/problems/lru-cache/)     | [C++]()  |
| [3. 无重复字符的最长子串](https://leetcode.cn/problems/longest-substring-without-repeating-characters/) | [C++]()  |
| [25. K 个一组翻转链表](https://leetcode.cn/problems/reverse-nodes-in-k-group/) | [C++]()  |
| [215. 数组中的第K个最大元素](https://leetcode.cn/problems/kth-largest-element-in-an-array/) | [C++]()  |
| [15. 三数之和](https://leetcode.cn/problems/3sum/)           | [C++]()  |
| [21. 合并两个有序链表](https://leetcode.cn/problems/merge-two-sorted-lists/) |          |
| [33. 搜索旋转排序数组](https://leetcode.cn/problems/search-in-rotated-sorted-array/) |          |
| [ 23. 合并K个排序链表](https://leetcode.cn/problems/merge-k-sorted-lists) |          |
| [88. 合并两个有序数组](https://leetcode.cn/problems/merge-sorted-array/) | [C++]()  |
| [165. 比较版本号](https://leetcode.cn/problems/compare-version-numbers/) | [C++]()  |
| [415. 字符串相加](https://leetcode.cn/problems/add-strings/) | [C++]()  |
| [20. 有效的括号](https://leetcode.cn/problems/valid-parentheses/) | [C++]()  |
| [46. 全排列](https://leetcode.cn/problems/permutations/)     | [C++]()  |



