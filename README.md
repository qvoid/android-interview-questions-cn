### 关于

受 [android-interview-questions](https://github.com/MindorksOpenSource/android-interview-questions) 项目启发，这里想发挥众多 Android 中国开发者的力量，整理一份高质量、范围全的 Android 面试指南，旨在帮助更多的 Android 开发者提升技术，找到工作。

现在还是项目初期，项目背景见这里：[想跟大家一起做件小事](http://mp.weixin.qq.com/s/t038R0bDDZ6dg4bwDoj2cQ)，欢迎持续关注。

## Contents
 * [数据结构和算法](#数据结构和算法)
 * [Java 核心](#core-java)
 * [Android 核心](#core-android)
 * [架构](#architecture)
 * [设计问题](#design-problem)
 * [工具和技能](#tools-and-technologies)
 * [Android 测试驱动开发](#android-test-driven-development)
 * [其他](#others)


### 数据结构和算法

> 关于数据结构和算法的问题的难度取决于你面试的是哪一家。

* 数组
* 链表
    - 链表，有点像树，但又不同于数组，它是由一组代表序列的节点组成。每个节点包含数据和一个指针。这里的数据可以是任何东西，但是指针必须是指向链表中的下一个节点。链表包含头和尾，头是链表的第一个节点，尾是最后一个节点。链表不是环形的数据结构，所以尾没有指向头，其指针为空。链表的基本操作的时间复杂度如下:

        | 算法    | 平均值  | 最差情况   |
        |:-------:|:-------:|:----------:|
        | 空间    | O(n)    | O(n)       |
        | 搜索    | O(n)    | O(n)       |
        | 插入    | O(1)    | O(1)       |
        | 删除    | O(1)    | O(1)       |
        
* 双向链表
* 栈
    - A Stack is a basic data structure with a "Last-in-First-out" methodology. Which means that 
    the last item that was added to the stack, is the first item that comes out of the stack. A 
    Stack is like a stack of books. In order to get to the first book that was added in the stack 
    (the bottom book), all of the books that were added after need to be removed first. Adding to a 
    Stack is called a Push, removing from a stack is called a Pop, and getting the last item 
    inserted into the stack without removing it is called Top. [The most common way to implement a
     stack is by using a LinkedList, but there are also StackArray (implemented with an array) 
     which does not replace null entries, and there is also a Vector implementation that does 
     replace null entries.](https://en.wikibooks.org/wiki/Data_Structures/Stacks_and_Queues#Performance_Analysis)
     
        <table>
            <tr>
                <th>Algorithm</th>
                <th>Average</th>
                <th>Worst Case</th>
                <th>Image representation</th>
            </tr>
            <tr>
                <td>Space</td>
                <td>O(n)</td>
                <td>O(n)</td>
                <td rowspan="5">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Data_stack.svg/250px-Data_stack.svg.png"/>
                </td>
            </tr>
            <tr>
                <td>Search</td>
                <td>O(n)</td>
                <td>O(n)</td>
            </tr>
            <tr>
                <td>Insert (Push)</td>
                <td>O(1)</td>
                <td>O(1)</td>
            </tr>
            <tr>
                <td>Delete (Pop)</td>
                <td>O(1)</td>
                <td>O(1)</td>
            </tr>
            <tr>
              <td>Top</td>
              <td>O(1)</td>
              <td>O(1)</td>
            </tr>
        </table>
        
* 队列
* 优先队列
* 动态规划
* 字符串处理
* 二叉树
* 二叉搜索树
* 排序算法
* 哈希表
* 广度优先搜索
* 深度优先搜索
* 贪婪算法


### License
```
   Copyright (C) 2017 stormzhang

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
