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
|[875. 爱吃香蕉的珂珂](https://leetcode.cn/problems/koko-eating-bananas/)|[C++]()|
|[1011. 在 D 天内送达包裹的能力](https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/)|[C++]()|
|[410. 分割数组的最大值](https://leetcode.cn/problems/split-array-largest-sum/)|[C++]()|

+ 前缀和
|Title|Solution|
|-|:-:|
|[303. 区域和检索 - 数组不可变](https://leetcode.cn/problems/range-sum-query-immutable/)|[C++]()|
|[304. 二维区域和检索 - 矩阵不可变](https://leetcode.cn/problems/range-sum-query-2d-immutable/)|[C++]()|
|[528. 按权重随机选择](https://leetcode.cn/problems/random-pick-with-weight/)|[C++]()|
+ 差分
|Title|Solution|
|-|:-:|
|[1109. 航班预订统计](https://leetcode.cn/problems/corporate-flight-bookings/)|[C++]()|
|[1094. 拼车](https://leetcode.cn/problems/car-pooling/)|[C++]()|

+ 遍历数组
|Title|Solution|
|-|:-:|
|[48. 旋转图像](https://leetcode.cn/problems/rotate-image/)|[C++]()|
|[54. 螺旋矩阵](https://leetcode.cn/problems/spiral-matrix/)|[C++]()|

+ 常数时间删除/查找数组中的任意元素

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [380. O(1) 时间插入、删除和获取随机元素](https://leetcode.cn/problems/insert-delete-getrandom-o1/) | [C++]()  |
| [710. 黑名单中的随机数](https://leetcode.cn/problems/random-pick-with-blacklist/) | [C++]()  |

+ 单调栈

| Title                                                        | Solution |
| ------------------------------------------------------------ | :------: |
| [402. 移掉 K 位数字](https://leetcode.cn/problems/remove-k-digits/) | [C++]()  |
| [1081. 不同字符的最小子序列](https://leetcode.cn/problems/smallest-subsequence-of-distinct-characters/) | [C++]()  |
| [321. 拼接最大数](https://leetcode.cn/problems/create-maximum-number/) | [C++]()  |

