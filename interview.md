<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [面试题](#%E9%9D%A2%E8%AF%95%E9%A2%98)
  - [算法](#%E7%AE%97%E6%B3%95)
    - [把一个数组旋转k步](#%E6%8A%8A%E4%B8%80%E4%B8%AA%E6%95%B0%E7%BB%84%E6%97%8B%E8%BD%ACk%E6%AD%A5)
    - [判断一个字符串是否是括号匹配](#%E5%88%A4%E6%96%AD%E4%B8%80%E4%B8%AA%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%98%AF%E5%90%A6%E6%98%AF%E6%8B%AC%E5%8F%B7%E5%8C%B9%E9%85%8D)
    - [用两个栈实现一个队列](#%E7%94%A8%E4%B8%A4%E4%B8%AA%E6%A0%88%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E9%98%9F%E5%88%97)
    - [使用js反转单向链表](#%E4%BD%BF%E7%94%A8js%E5%8F%8D%E8%BD%AC%E5%8D%95%E5%90%91%E9%93%BE%E8%A1%A8)
      - [用链表实现队列](#%E7%94%A8%E9%93%BE%E8%A1%A8%E5%AE%9E%E7%8E%B0%E9%98%9F%E5%88%97)
    - [用 js 实现二分查找](#%E7%94%A8-js-%E5%AE%9E%E7%8E%B0%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE)
    - [找出一个数组中和为n的两个数](#%E6%89%BE%E5%87%BA%E4%B8%80%E4%B8%AA%E6%95%B0%E7%BB%84%E4%B8%AD%E5%92%8C%E4%B8%BAn%E7%9A%84%E4%B8%A4%E4%B8%AA%E6%95%B0)
      - [观察者模式和发布订阅模式的区别](#%E8%A7%82%E5%AF%9F%E8%80%85%E6%A8%A1%E5%BC%8F%E5%92%8C%E5%8F%91%E5%B8%83%E8%AE%A2%E9%98%85%E6%A8%A1%E5%BC%8F%E7%9A%84%E5%8C%BA%E5%88%AB)
    - [实际工作中，做过什么vue优化](#%E5%AE%9E%E9%99%85%E5%B7%A5%E4%BD%9C%E4%B8%AD%E5%81%9A%E8%BF%87%E4%BB%80%E4%B9%88vue%E4%BC%98%E5%8C%96)
      - [使用 vue 遇到过哪些坑](#%E4%BD%BF%E7%94%A8-vue-%E9%81%87%E5%88%B0%E8%BF%87%E5%93%AA%E4%BA%9B%E5%9D%91)
    - [如果统一监听 Vue 组件报错](#%E5%A6%82%E6%9E%9C%E7%BB%9F%E4%B8%80%E7%9B%91%E5%90%AC-vue-%E7%BB%84%E4%BB%B6%E6%8A%A5%E9%94%99)
    - [工作中遇到哪些项目难点，如何解决](#%E5%B7%A5%E4%BD%9C%E4%B8%AD%E9%81%87%E5%88%B0%E5%93%AA%E4%BA%9B%E9%A1%B9%E7%9B%AE%E9%9A%BE%E7%82%B9%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3)
  - [HTTP/HTML/浏览器](#httphtml%E6%B5%8F%E8%A7%88%E5%99%A8)
    - [http 和 https](#http-%E5%92%8C-https)
    - [tcp 三次握手](#tcp-%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B)
    - [WebSocket 的实现和应用](#websocket-%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%92%8C%E5%BA%94%E7%94%A8)
    - [HTTP 请求的方式，HEAD 方式](#http-%E8%AF%B7%E6%B1%82%E7%9A%84%E6%96%B9%E5%BC%8Fhead-%E6%96%B9%E5%BC%8F)
    - [一个图片 url 访问后直接下载的实现](#%E4%B8%80%E4%B8%AA%E5%9B%BE%E7%89%87-url-%E8%AE%BF%E9%97%AE%E5%90%8E%E7%9B%B4%E6%8E%A5%E4%B8%8B%E8%BD%BD%E7%9A%84%E5%AE%9E%E7%8E%B0)
  - [HTTP2.0](#http20)
    - [HTML5 drag API](#html5-drag-api)
    - [状态码](#%E7%8A%B6%E6%80%81%E7%A0%81)
    - [click 在 ios 上有 300ms 延迟，原因及如何解决](#click-%E5%9C%A8-ios-%E4%B8%8A%E6%9C%89-300ms-%E5%BB%B6%E8%BF%9F%E5%8E%9F%E5%9B%A0%E5%8F%8A%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3)
    - [addEventListener 参数](#addeventlistener-%E5%8F%82%E6%95%B0)
    - [在地址栏里输入一个 URL,到这个页面呈现出来，中间会发生什么](#%E5%9C%A8%E5%9C%B0%E5%9D%80%E6%A0%8F%E9%87%8C%E8%BE%93%E5%85%A5%E4%B8%80%E4%B8%AA-url%E5%88%B0%E8%BF%99%E4%B8%AA%E9%A1%B5%E9%9D%A2%E5%91%88%E7%8E%B0%E5%87%BA%E6%9D%A5%E4%B8%AD%E9%97%B4%E4%BC%9A%E5%8F%91%E7%94%9F%E4%BB%80%E4%B9%88)
    - [浏览器渲染原理与过程](#%E6%B5%8F%E8%A7%88%E5%99%A8%E6%B8%B2%E6%9F%93%E5%8E%9F%E7%90%86%E4%B8%8E%E8%BF%87%E7%A8%8B)
      - [浏览器渲染网页的具体流程](#%E6%B5%8F%E8%A7%88%E5%99%A8%E6%B8%B2%E6%9F%93%E7%BD%91%E9%A1%B5%E7%9A%84%E5%85%B7%E4%BD%93%E6%B5%81%E7%A8%8B)
      - [回流和重绘（reflow和repaint）](#%E5%9B%9E%E6%B5%81%E5%92%8C%E9%87%8D%E7%BB%98reflow%E5%92%8Crepaint)
    - [常见的 HTTP 的头部](#%E5%B8%B8%E8%A7%81%E7%9A%84-http-%E7%9A%84%E5%A4%B4%E9%83%A8)
    - [浏览器缓存机制](#%E6%B5%8F%E8%A7%88%E5%99%A8%E7%BC%93%E5%AD%98%E6%9C%BA%E5%88%B6)
  - [CSS/LESS/SASS](#csslesssass)
    - [viewport 和移动端布局](#viewport-%E5%92%8C%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%B8%83%E5%B1%80)
  - [Vue](#vue)
    - [Vue渲染/更新过程](#vue%E6%B8%B2%E6%9F%93%E6%9B%B4%E6%96%B0%E8%BF%87%E7%A8%8B)
    - [父子组件生命周期](#%E7%88%B6%E5%AD%90%E7%BB%84%E4%BB%B6%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F)
    - [keep-alive](#keep-alive)
    - [响应式原理](#%E5%93%8D%E5%BA%94%E5%BC%8F%E5%8E%9F%E7%90%86)
    - [hash和history](#hash%E5%92%8Chistory)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<!--
 * @Author: lijiaying 1640106564@qq.com
 * @Date: 2022-06-16 08:54:05
 * @LastEditors: lijiaying 1640106564@qq.com
 * @LastEditTime: 2022-06-16 09:03:12
 * @FilePath: \面试题\面试题.md
 * @Description: 面试题
-->
# 面试题

## 算法

### 把一个数组旋转k步

> 时间复杂度 `O(1)`，后面部分裁切，放到前面

```ts
function rotate(arr:number[], k: number): number {
    const length = arr.length
    if(!k || length === 0) return arr
    const step = Math.abs(k % length) // abs 取绝对值
    const part1 = arr.slice(-step)
    const part2 = arr.slice(0, length - step)
    const all = part1.concat(part2)
    return all
}
```


### 判断一个字符串是否是括号匹配

> 可以用栈实现
> 栈：逻辑结构
> 时间复杂度`O(n)`

```ts
/**
 * 判断是否括号匹配
 */
function isMatch(left: string, right: string): boolean {
    if(left === '{' && right === '}') return true
    if(left === '(' && right === ')') return true
    if(left === '[' && right === ']') return true
    return false
}

/**
 * 判断是否括号匹配
 */
function matchBracket(str: string): boolean {
    const length = str.length
    if(length === 0) return true

    const stack = []
    const leftSymbols = '{[('
    const rightSymbols = ')]}'

    // 遍历字符串每一项判断入栈和出栈
    for(let i = 0; i < length; i++) {
        const s = str[i]
        // 左括号压栈 右括号匹配出栈
        if(leftSymbols.includes(s)) {
            stack.push(s)
        } else if(rightSymbols.includes(s)) {
            const top = stack[stack.length - 1] // 栈顶
            if (isMatch(top, s)) {
                stack.pop()
            } else {
                return false
            }
        }
    }

    return stack.length === 0
}
```

### 用两个栈实现一个队列

> 队列：逻辑结构

```ts
/**
 * 用两个栈实现一个队列
 */
class MyQueue {
    // 定义两个栈 private 私有 在内部可以调用 外部无法调用
    private stack1: number[] = []
    private stack2: number[] = []

    /**
     * 入队
     */
    add(n: number) {
        this.stack1.push(n)
    }

    /**
     * 出队
     */
    delete(): number | null {
        let res
        const stack1 = this.stack1
        const stack2 = this.stack2

        // 1. 将 stack1 中所有元素移动到 stack2 中
        while (stack1.length) {
            const n = stack1.pop()
            if(n !== null) {
                stack2.push(n)
            }
        }

        // 2. stack2 pop
        res = stack2.pop()

        // 将 stack2 中所有元素放回 stack1 栈
        while (stack2.length) {
            const n = stack2.pop()
            if(n !== null) {
                stack1.push(n)
            }
        }

        return res || null
    }

    // 通过属性方式调用
    get length(): number {
        return this.stack1.length
    }
}
```


### 使用js反转单向链表

> 链表：物理结构
> 数组需要一段连续的内存空间，而链表是零散的
> 链表节点的数据结构：`{value,next?,prev?}`

- 数组Array，映射Map => 有序结构
- 对象Object，集合set => 无序结构
- 链表 VS 数组
    - 都是有序结构
    - 链表：查询慢`O(n)`，新增和删除快`O(1)`
    - 数组：查询快`O(1)`,新增和删除慢`O(n)`

1. 根据数组创建列表
```ts
/**
 * 定义接口类型
 */
interface ILickListNode {
    value: number,
    next?: ILickListNode
}

/**
 * 根据数组创建单向链表
 * @param arr number arr
 */
function createLinkList(arr: number[]): ILickListNode {
    const length = arr.length
    if(length === 0) throw new Error('arr is empty')

    // 链表从前往后访问 数组转化成列表需要从后往前转化，先生成最后一个
    let curNode: ILickListNode = {
        value: arr[length - 1]
    }

    if(length === 1) return curNode

    // 从倒数第二个开始 设置指针和value
    for (let i = length - 2; i >= 0; i--) {
        curNode = {
            value: arr[i],
            next: curNode
        }
    }

    return curNode
}
```
![链表指针运行](/image/%E9%93%BE%E8%A1%A8%E6%8C%87%E9%92%88%E8%BF%90%E8%A1%8C.png)
![单向链表运行结果](/image/%E5%8D%95%E5%90%91%E9%93%BE%E8%A1%A8%E8%BF%90%E8%A1%8C%E7%BB%93%E6%9E%9C.png)

2. 思路：
- 反转 => 节点 `next` 指向前一个节点
- 很容易造成 `nextNode` 消失
- 需要三个指针 `prevNode` `curNode` `nextNode`


```ts
/**
 * 定义接口类型
 */
interface ILickListNode {
    value: number,
    next?: ILickListNode
}

/**
 * 反转单向链表，并返回反转之后的 head node
 */
function reverseLinkList(listnode: ILickListNode): ILickListNode {
    // 定义三个指针
    let prevNode: ILickListNode | undefined = undefined
    let curNode: ILickListNode | undefined = undefined
    let nextNode: ILickListNode | undefined = listnode

    // 以 nextNode 为主 遍历链表
    while(nextNode) {
        // 第一个元素 删掉 next  防止循环引用
        if(curNode && !prevNode) {
            // 反转后第一个元素指向 null 所以删除
            delete curNode.next
        }

        // 反转指针
        // 如果是链表中间的 node
        if(curNode && prevNode) {
            curNode.next = prevNode
        }

        // 整体向后移动指针
        prevNode = curNode
        curNode = nextNode
        nextNode = nextNode?.next
    }

    // 最后一个 node：当 nextNode 空时，此时 curNode 尚未设置 next
    // ! 确定是有值的 ts语法
    curNode!.next = prevNode

    return curNode!
}

/**
 * 根据数组创建单向链表
 * @param arr number arr
 */
function createLinkList(arr: number[]): ILickListNode {
    const length = arr.length
    if(length === 0) throw new Error('arr is empty')

    // 链表从前往后访问 数组转化成列表需要从后往前转化，先生成最后一个
    let curNode: ILickListNode = {
        value: arr[length - 1]
    }

    if(length === 1) return curNode

    // 从倒数第二个开始 设置指针和value
    for (let i = length - 2; i >= 0; i--) {
        curNode = {
            value: arr[i],
            next: curNode
        }
    }

    return curNode
}
```

#### 用链表实现队列

链表和数组实现队列性能分析
1. 空间复杂度 => `O(n)`
2. `add` 时间复杂度 => 链表`O(1)`，数组`O(1)`
3. `delete` 时间复杂度 => 链表`O(1)`，数组`O(n)`
- 数据结构的选择，要比算法优化更重要

```ts
interface IListNode {
    value: number,
    next?: IListNode // 相当于 next: IListNode | undefined
}

class MyQueue {
    // 头
    private head: IListNode | null = null
    // 尾
    private tail: IListNode | null = null
    // 长度
    private len = 0
    /**
     * 入队，在 tail 位置
     * @param n number
     */
    add(n: number) {
        const newNode: IListNode = {
            value: n,
            next: null
        }

        // 处理 head
        if(this.head === null) {
            this.head = newNode
        }

        // 处理 tail
        const tailNode = this.tail
        if(tailNode) {
            tailNode.next = newNode
        }
        this.tail = newNode

        // 记录长度
        this.len++
    }
    delete(): number | null {
        const headNode = this.head
        if (headNode === null) return null
        if (this.len <= 0) return null

        // 取值
        const value = headNode.value

        // 处理 head
        this.head = headNode.next

        // 记录长度
        this.len--
        return value
    }
    get length(): number {
        // length 要单独存储 不能遍历链表获取 否则时间复杂度过高
        return this.len
    }
}
```

### 用 js 实现二分查找

> 循环比递归性能更好
> 凡有序必二分
> 凡二分，时间复杂度必包含`O(logn)`

- 递归会增加函数调用次数，细节上会慢一些，但是代码更简洁

```ts
/**
 * 二分查找（循环）
 * @param arr arr
 * @param target target
 */
function binarySearch1(arr: number[], target: number): number {
    const length = arr.length
    if(length === 0) return -1
    
    let startIndex = 0 // 当前查找区域的开始位置
    let endIndex = length - 1 // 当前查找区域的结束位置

    while (startIndex <= endIndex) {
        // 中间值索引
        const midIndex = Math.floor((startIndex + endIndex) / 2)
        // 中间值
        const midValue = arr[midIndex]
        if(target < midIndex) {
            // 目标值较小，继续在左侧查找
            endIndex = midIndex - 1
        } else if(target > midIndex) {
            // 目标值较大，继续在右侧查找
            startIndex = midIndex + 1
        } else {
            // 相等，返回
            return midIndex
        }
    }
    return -1
}

/**
 * 二分查找（递归）
 * @param arr arr
 * @param target target
 * @param startIndex 当前查找区域的开始位置 不传默认是 0
 * @param endIndex 当前查找区域的结束位置 不传默认是 arr.length - 1
 */
function binarySearch2(arr: number[], target: number, startIndex?: number = 0, endIndex?: number = arr.length - 1): number {
    const length = arr.length
    
    // 如果 start 和 end 相遇 则结束
    if(startIndex > endIndex) return -1

    // 中间值索引
    const midIndex = Math.floor((startIndex + endIndex) / 2)
    // 中间值
    const midValue = arr[midIndex]
    if(target < midIndex) {
        // 目标值较小，继续在左侧查找
        endIndex = midIndex - 1
        return binarySearch2(arr, target, startIndex, endIndex)
    } else if(target > midIndex) {
        // 目标值较大，继续在右侧查找
        startIndex = midIndex + 1
        return binarySearch2(arr, target, startIndex, endIndex)
    } else {
        // 相等，返回
        return midIndex
    }
}
```

### 找出一个数组中和为n的两个数

> 双指针 => 把时间复杂度降为`O(n)`
> 优化嵌套循环，可以考虑“双指针”
> 凡有序，必二分
```ts
/**
 * 查找和为n的两个数（双指针）
 * @param arr
 * @param n
 */
function findTwoNumbers(arr: number[], n: number): number[] {
    const res: number[] = []

    const length = arr.length
    if(length === 0) return res

    let i = 0 // 头
    let j = length - 1 // 尾

    while(i < j) {
        const n1 = arr[i]
        const n2 = arr[j]
        const sum = n1 + n2

        if(n < sum) {
            // 需要查找的和n比当前的和sum小，j 需要向前移动
            j--
        } else if (n > sum) {
            // 需要查找的和n比当前的和sum大，i 需要向后移动
            i++
        } else {
            // 相等
            res.push(n1)
            res.push(n2)
            break
        }
    }

    return res
}
```

### 二叉树

> 前序遍历：**root** -> left -> right
> 中序遍历：left -> **root** -> right
> 后序遍历：left -> right -> **root**

```ts

```

## 实际工作经验

### H5页面如何进行首屏优化

1. 路由懒加载（SPA）

- 路由拆分，优先保证首页加载

2. 服务端渲染 SSR （成本高）

- 传统的前后端分离（SPA）渲染页面过程复杂
- SSR渲染页面过程简单，所有性能好
- 如果是纯H5页面，SSR是性能优化的终极方案（直接渲染HTML）

3. App 预取

- 如果H5在 App WebView 中展示，可使用App预取
- 用户访问列表页时，App预加载文章首屏内容
- 用户进入H5页，直接从App中获取内容，瞬间展示首屏

4. 分页

- 针对列表页
- 默认只展示第一页内容

5. 图片懒加载

- 针对详情页
- 默认只展示文本内容，然后触发图片懒加载
- 注意：提前设置图片尺寸，尽量只重绘不重拍

6. Hybrid

- 提前将 HTML JS CSS 下载到 App 内部
- 在App webview 中使用 `file://` 协议（打开本地文件）加载页面文件
- 再用 Ajax 获取内容并展示（也结合App预取）

**注意：**
- 性能优化要配合分析、统计、评分等，做了事情要有结果
- 性能优化也要配合体验，如骨架屏，loading动画等

### 后端一次性返回10w条数据，要怎么办

1. 设计不合理
- 主动和面试官沟通

2. 浏览器能否处理10w条数据
- JS没问题
- 渲染到 DOM 会非常卡顿

3. 自定义中间层
- 自定义 nodejs 中间层，获取并拆分这10w条数据
- 前端对接 nodejs 中间层，而不是服务端
- 成本比较高

4. 虚拟列表

- 只渲染可视区内 DOM
- 其他隐藏区域不显示，只用`<div>`撑起高度
- 随着浏览器滚动，创建和销毁 DOM

5. 虚拟列表 - 第三方 lib

- 实现起来复杂，借用第三方 lib
- Vue-virtual-scroll-list
- React-virtualiszed

**注意：**
- 要主动沟通，表达观点
- 后端的问题，首先要用后端的思维去解决 - 中间层
- 虚拟列表只是无奈的选择，实现复杂而且效果不一定好（低配手机）

### 前端的常用设计模式和使用场景

1. 设计原则
- 最重要的思想：开放封闭原则
    - 对扩展开放
    - 对修改封闭

2. 工厂模式
- 用一个工厂函数创建实例，隐藏 `new`
    - 如jQuery `$` 函数
    - 如 React `createElement` 函数

```js
class Foo {}

// 工厂模式
function factory(a,b,c) {
    // if else
    return new Foo()
}

const f = factory(1,2,3)

// $('div')
// => new JQuery()
```

3. 单例模式

- 全局唯一的实例（无法生成第二个）
    - 如 Vuex Redux 的 `store`
    - 如全局唯一的 `dialog model`

```ts
class SingleTon {
    private static instance: SingleTon | null = null
    private constructor() {}
    public static getInstance(): SingleTon {
        // 没有的话创建新的实例，有的话直接返回
        if (this.instance === null) {
            this.instance = new SingleTon()
        }
        return this.instance
    }
    fn1()
    fn2()
}

// const s = new SingleTon() => 报错 => 私有的构造函数并且只有在class内部才可以访问
const s = SingleTon.getInstance() // getInstance 静态方法
s.fn1()
s.fn2()

const s1 = SingleTon.getInstance()
s === s1 // true
```

**注意：**
- JS 是单线程的 创建单例很简单
- Java 是支持多线程的，创建单例要考虑锁死线程
    - 否则多个线程同时创建，单例就重复了（多线程共享进程内存）

4. 代理模式

- 使用者不能直接访问对象，而是访问一个代理层
- 在代理层可以监听 get set 做很多事情
    - 如 ES6 Proxy 实现 Vue3 响应式

5. 观察者模式
```js
// 一个主题，一个观察者，主题变化之后触发观察者执行
btn.addEventListener('click', () => { ... })
```

6. 发布订阅模式
```js
// 绑定
event.on('event-key', () => {
    // 事件1
})
event.on('event-key', () => {
    // 事件2
})

// 触发执行
event.emit('event-key')
```

**注意：**
- 绑定的事件要记得解除，防止内存泄露

```js
function fn1() { /* 事件1 */}
function fn2() { /* 事件2 */}

// mounted 时绑定
event.on('event-key', fn1)
event.on('event-key',fn2)

// beforeUnmount 时解绑
event.off('event-key', fn1)
event.off('event-key', fn2)
```

7. 装饰器模式

- 原功能不变，增加一些新功能（AOP面向切面编程）
- ES 和 TS 的 `Decorator` 语法

#### 观察者模式和发布订阅模式的区别
![观察者模式和发布订阅模式的区别](/image/%E8%A7%82%E5%AF%9F%E8%80%85%E5%92%8C%E5%8F%91%E5%B8%83%E8%AE%A2%E9%98%85%E6%A8%A1%E5%BC%8F%E7%9A%84%E5%8C%BA%E5%88%AB.png)

1. 观察者模式
- Subject 和 Observer 直接绑定 没有中间媒介
    - 如 addEventListener 绑定的事件

2. 发布订阅模式
- Publisher 和 Observer 互不认识 需要中间媒介 Event channel
    - 如 EventBus 自定义事件

### 实际工作中，做过什么vue优化

1. `v-if` 和 `v-show`
- `v-if` 彻底销毁组件
- `v-show` 使用 css 隐藏组件
- 大部分情况下使用 `v-if` 更好，不要过度优化

2. `v-for`使用`key`

3. 使用 `computed` 缓存
```js
export default {
    data() {
        return {
            msgList: [ ... ] // 消息列表
        }
    },
    computed: {
        // 未读消息的数量
        // 只要 list 不修改 computed就不会修改 做一个缓存
        unreadCount() {
            return this.msgList.filter(m => m.read === false).length
        }
    }
}
```

4. `keep-alive` 缓存组件
- 频繁切换的组件，如 `tabs`
- 不要乱用，缓存太多会占内存，而且不好 `debug`

5. 异步组件
- 针对体积较大的组件，如编辑器，复杂表格，复杂表单等
- 拆包，需要时异步加载，不需要时不加载
- 减少主包体积，首页会加载更快

6. 路由懒加载

7. 服务端渲染 SSR
- 可使用 Nuxt.js
- 按需优化，使用 SSR 的成本比较高

#### 使用 vue 遇到过哪些坑

1. 内存泄漏
- 全局变量，全局事件，全局定时器
- 自定义事件

2. vue2 响应式缺陷（vue3 不再有）
- `data` 新增属性用 `Vue.set`
- `data` 删除属性用 `Vue.delete`
- 无法直接修改数据 `arr[index] = value`

3. 路由切换时 `scroll` 到顶部
- SPA 通病，不仅仅是 Vue
- 如 列表页 滚动到第二屏，点击进入详情页
- 再返回到列表页（此时组件重新渲染）就 `scroll` 到顶部

**解决方案：**
- 在列表页缓存数据和 `scrollTop` 的值
- 当再次返回列表页，渲染组件时，执行 `scrollTo(xx)`
- 终极方案： MPA + App WebView

### 如果统一监听 Vue 组件报错

1. `window.onerror`
- 全局监听所有JS错误
- 是JS级别的，识别不了Vue组件信息
- 捕捉一些 Vue 监听不到的错误信息

`App.vue`
```js
// 不能监听到 try-catch
export default {
    mounted() {
        window.onerror = function(msg, sourse, line, column, error) {
            console.info('window.onerror-------', msg, sourse, line, column, error)
        }
        window.addEventListener('error', event => {
            console.info('window error------', event)
        })
    }
}
```

2. `errorCaptured` 生命周期
- 监听所有**下级**组件的错误
- 返回 `false` 会阻止向上传播
`app.vue`
```js
export default {
    errorCaptured: (err, vm, info) => {
        console.info('errorCaptured-------', error, vm, info)
        // 防止重复捕获
        return false
    }
}
```

3. `errorHandler` 配置
- vue 全局错误监听，所有组件错误都会汇总到这里
- 但 `errorCaptured` 返回 `false` 不会传播到这里
- 在 `main.js` 配置

```js
app.config.errorHandler = (error, vm, info) => {
    // 已经是全局监听，没有必要再触发 window.onerror() => 互斥，会阻止 window.onerror
    console.info('errorHandler-------', error, vm, info)
}
```

4. 异步错误(setTimeout)
- `errorCaptured` 和 `errorHandler` 无法监听
- 会在 `window.onerror` 监听

**注意：**
- 实际工作中，三者需要结合使用
- `errorCaptured` 监听一些重要，有风险组件的错误
- `window.onerror` 和 `errorHandler` 候补全局监听
- `Promise` 未处理的 `catch` 需要 `onunhandledrejection`

### 工作中遇到哪些项目难点，如何解决

- 遇到问题需要积累
- 描述问题：背景 + 现象 + 造成的影响
- 问题如何被解决：分析 + 解决
- 自己的成长：学到了什么 + 以后如何避免

## HTTP/HTML/浏览器

### http 和 https

- https 的 SSL 加密是在传输层实现的。
1. http 和 https 的基本概念
- http: 超文本传输协议，是互联网上应用最为广泛的一种网络协议，是一个客户端和服务器端请求和应答的标准（TCP），用于从 WWW 服务器传输超文本到本地浏览器的传输协议，它可以使浏览器更加高效，使网络传输减少。
- https: 是以安全为目标的 HTTP 通道，简单讲是 HTTP 的安全版，即 HTTP 下加入 SSL层，HTTPS 的安全基础是 SSL，因此加密的详细内容就需要 SSL。https 协议的主要作用是：建立一个信息安全通道，来确保数组的传输，确保网站的真实性。
2. http 和 https 的区别
> http 传输的数据都是未加密的，也就是明文的，网景公司设置了 SSL 协议来对 http 协议传输的数据进行加密处理，简单来说 https 协议是由 http 和 ssl 协议构建的可进行加密传输和身份认证的网络协议，比 http 协议的安全性更高。
- 主要的区别如下：
    1. Https 协议需要 ca 证书，费用较高。
    2. http 是超文本传输协议，信息是明文传输，https 则是具有安全性的 ssl 加密传输协议。使用不同的链接方式，端口也不同，一般而言，http 协议的端口为 80，https 的端口为443
    3. http 的连接很简单，是无状态的；HTTPS 协议是由 SSL+HTTP 协议构建的可进行加密传输、身份认证的网络协议，比 http 协议安全。
3. https 协议的工作原理
- 客户端在使用 HTTPS 方式与 Web 服务器通信时有以下几个步骤
    1. 客户使用 https url 访问服务器，则要求 web 服务器建立 ssl 链接。
    2. web 服务器接收到客户端的请求之后，会将网站的证书（证书中包含了公钥），返回或者说传输给客户端。
    3. 客户端和 web 服务器端开始协商 SSL 链接的安全等级，也就是加密等级。
    4. 客户端浏览器通过双方协商一致的安全等级，建立会话密钥，然后通过网站的公钥来加密会话密钥，并传送给网站。
    5. web 服务器通过自己的私钥解密出会话密钥。
    6. web 服务器通过会话密钥加密与客户端之间的通信。
4. https 协议的优点
    1. 使用 HTTPS 协议可认证用户和服务器，确保数据发送到正确的客户机和服务器；
    2. HTTPS 协议是由 SSL+HTTP 协议构建的可进行加密传输、身份认证的网络协议，要比http 协议安全，可防止数据在传输过程中不被窃取、改变，确保数据的完整性。
    3. HTTPS 是现行架构下最安全的解决方案，虽然不是绝对安全，但它大幅增加了中间人攻击的成本。
    4. 谷歌曾在 2014 年 8 月份调整搜索引擎算法，并称“比起同等 HTTP 网站，采用 HTTPS加密的网站在搜索结果中的排名将会更高”。
5. https 协议的缺点
    1. https 握手阶段比较费时，会使页面加载时间延长 50%，增加 10%~20%的耗电。
    2. https 缓存不如 http 高效，会增加数据开销。
    3. SSL 证书也需要钱，功能越强大的证书费用越高。
    4. SSL 证书需要绑定 IP，不能再同一个 ip 上绑定多个域名，ipv4 资源支持不了这种消耗。

### tcp 三次握手

> 客户端和服务端都需要直到各自可收发，因此需要三次握手

1. 客户端发起请求连接服务端确认，也发起连接客户端确认
2. 每次握手的作用：
    - 第一次握手：服务端只可以确认自己可以接受客户端发送的报文段
    - 第二次握手：客户端可以确认服务端收到了自己发送的报文段，并且可以确认 自己可以接受服务端发送的报文段
    - 第三次握手：服务端可以确认客户端

- TCP 和 UDP 的区别

1. TCP 是面向连接的，UDP 是无连接的即发送数据前不需要先建立链接。
2. TCP 提供可靠的服务。也就是说，通过 TCP 连接传送的数据，无差错，不丢失，不重复，且按序到达;UDP 尽最大努力交付，即不保证可靠交付。 并且因为 TCP 可靠，面向连接，不会丢失数据因此适合大数据量的交换。
3. TCP 是面向字节流，UDP 面向报文，并且网络出现拥塞不会使得发送速率降低（因此会出现丢包，对实时的应用比如 IP 电话和视频会议等）。
4. TCP 只能是 1 对 1 的，UDP 支持 1 对 1,1 对多。
5. TCP 的首部较大为 20 字节，而 UDP 只有 8 字节。
6. TCP 是面向连接的可靠性传输，而 UDP 是不可靠的。

### WebSocket 的实现和应用

> WebSocket 是 HTML5 中的协议，支持持久连续，http 协议不支持持久性连接。Http1.0和 HTTP1.1 都不支持持久性的链接，HTTP1.1 中的 `keep-alive`，将多个 http 请求合并为1 

- WebSocket 是什么样的协议，具体有什么优点

1. HTTP 的生命周期通过 `Request` 来界定，也就是 `Request` 一个 `Response`，那么在 Http1.0协议中，这次 Http 请求就结束了。在Http1.1 中进行了改进，是的有一个 `connection：Keep-alive`，也就是说，在一个 Http 连接中，可以发送多个 `Request`，接收多个 `Response`。
2. 但是在 Http 中一个 Request 只能对应有一个 Response，而且这个 Response是被动的，不能主动发起。
3. WebSocket 是基于 Http 协议的，或者说借用了 Http 协议来完成一部分握手，在握手阶段与 Http 是相同的。
    - websocket 握手协议的实现，基本是 2 个属性，upgrade，connection。基本请求如下：
    ```
    GET /chat HTTP/1.1
    Host: server.example.com
    Upgrade: websocket
    Connection: Upgrade
    Sec-WebSocket-Key: x3JJHMbDL1EzLkh9GBhXDw==
    Sec-WebSocket-Protocol: chat, superchat
    Sec-WebSocket-Version: 13
    Origin: http://example.com
    ```
    - 多了下面 2 个属性：
        - `Upgrade:webSocket`
        - `Connection:Upgrade`
    - 告诉服务器发送的是 websocket
        - `Sec-WebSocket-Key: x3JJHMbDL1EzLkh9GBhXDw==`
        - `Sec-WebSocket-Protocol: chat, superchat`
        - `Sec-WebSocket-Version: 13`

### HTTP 请求的方式，HEAD 方式

- `head`：类似于 `get` 请求，只不过返回的响应中没有具体的内容，用户获取报头
- `options`：允许客户端查看服务器的性能，比如说服务器支持的请求方式等等

### 一个图片 url 访问后直接下载的实现

> 请求的返回头里面，用于浏览器解析的重要参数就是 OSS 的 API 文档里面的返回 http 头，决定用户下载行为的参数。
下载的情况下：
1. `x-oss-object-type: Normal`
2. `x-oss-request-id: 598D5ED34F29D01FE2925F41`
3. `x-oss-storage-class: Standard`

## HTTP2.0

1. 提升访问速度（请求资源所需时间更少，访问速度更快）
2. 允许多路复用：多路复用允许同时通过单一的 HTTP/2 连接发送多重`请求-响应`信息。
3. 改善了：在 http1.1 中，浏览器客户端在同一时间，针对同一域名下的请求有一定数量限制（连接数量），超过限制会被阻塞。
4. 二进制分帧：HTTP2.0 会将所有的传输信息分割为更小的信息或者帧，并对他们进行二进制编码、首部压缩、服务器端推送
5. 内容安全，因为 http2.0 是基于 https 的，天然具有安全特性，通过 http2.0 的特性可
以避免单纯使用 https

### HTML5 drag API

1. `dragstart`：事件主体是**被拖放**元素，在**开始拖放**被拖放元素时触发。
2. `darg`：事件主体是**被拖放**元素，在**正在拖放**被拖放元素时触发。
3. `dragenter`：事件主体是**目标**元素，在**被拖放元素进入某元素**时触发。
4. `dragover`：事件主体是**目标**元素，在**被拖放在某元素内移动**时触发。
5. `dragleave`：事件主体是**目标**元素，在被拖放元素**移出目标元素**时触发。
6. `drop`：事件主体是**目标**元素，在**目标元素完全接收被拖放元素**时触发。
7. `dragend`：事件主体是**被拖放**元素，在整个拖放操作**结束**时触发

### 状态码

**成功类（请求已经被成功处理了）**
1. 200 请求已成功，返回想要的东西。出现此状态码是表示正常状态。
2. 201 请求成功，服务器正在创建请求的资源
3. 202 服务器收到请求了，但是未处理
4. 203 服务器成功处理，但是返回的信息是另一个来源
5. 204 服务器成功处理，但是没有返回内容
6. 205 服务器成功处理，但是没有返回内容
7. 206 成功处理了部分get请求

**重定向类（要完成请求，需要进一步操作）**
1. 300 针对请求，服务器可执行多种操作
2. 301 请求的网页已永久移动到新位置。 服务器返回此响应（对 GET 或 HEAD 请求的响应）时，会自动将请求者转到新位置
3. 302 服务器目前从不同位置的网页响应请求，但请求者应继续使用原有位置来进行以后的请求
4. 304 自从上次请求后，请求的网页未修改过。 服务器返回此响应时，不会返回网页内容
5. 305 请求者只能使用代理访问请求的网页。 如果服务器返回此响应，还表示请求者应使用代理

**请求错误（请求可能出错，导致服务器处理不了）**
1. 400 语义错误，请求无法被服务器理解。或者请求参数有误
2. 401 请求需要请求者验证
3. 403 服务器拒绝该请求
4. 404 找不到请求网页
5. 405 请求的方法是服务器中禁用的
6. 406 请求的资源的内容特性无法满足请求头中的条件，因而无法生成响应实体
7. 408 请求超时
8. 410 被请求的资源在服务器上已经不再可用，而且没有任何已知的转发地址
9. 413 服务器拒绝处理当前请求，因为该请求提交的实体数据大小超过了服务器愿意或者能够处理的范围

**服务器错误**
1. 500 服务器代码报错
2. 501 服务器不具备完成请求的功能。 例如，服务器无法识别请求方法时可能会返回此代码
3. 502 服务器作为网关或代理，从上游服务器收到无效响应
4. 503 服务器目前无法使用（由于超载或停机维护）。 通常，这只是暂时状态
5. 504 服务器作为网关或代理，但是没有及时从上游服务器收到请求
6. 505 服务器不支持请求中所用的 HTTP 协议版本

**简单来说就是2开头是好事 4开头是自己的问题 5开头后端的问题**


### click 在 ios 上有 300ms 延迟，原因及如何解决

1. 粗暴型，禁用缩放
```html
<meta name="viewport" content="width=device-width, user-scalable=no">
```
2. 利用 `FastClick`，其原理是：检测到 `touchend` 事件后，立刻出发模拟 `click` 事件，并且把浏览器 300 毫秒之后真正触发的事件给阻断掉

### addEventListener 参数

```js
addEventListener(event, function, useCapture)
```
其中，`event` 指定事件名；`function` 指定要事件触发时执行的函数；`useCapture` 指定事件是否在捕获或冒泡阶段执行


### 在地址栏里输入一个 URL,到这个页面呈现出来，中间会发生什么

1. 找到这个 `url` 域名的服务器 `ip`
    - 为了寻找这个 `ip`，浏览器首先会寻找缓存，查看缓存中是否有记录，缓存的查找记录为：
        - 浏览器缓存 -> 系统缓存 -> 路由器缓存
    - 缓存中没有则查找系统的 `hosts` 文件中是否有记录，如果没有则查询 DNS 服务器
2. 得到服务器的 `ip` 地址后，浏览器根据这个 `ip` 以及相应的端口号，构造一个 `http` 请求
    - 这个请求报文会包括这次请求的信息，主要是`请求方法`，`请求说明`和`请求附带的数据`
    - 并将这个 `http` 请求封装在一个 `tcp` 包中，这个 `tcp` 包会依次经过`传输层`，`网络层`，`数据链路层`，`物理层`到达服务器
3. 服务器解析这个请求来作出响应，返回相应的 `html` 给浏览器
    - 因为 `html` 是一个树形结构，浏览器根据这个 `html` 来构建 `DOM` 树
    - 在 dom 树的构建过程中如果遇到 JS 脚本和外部 JS 连接，则会停止构建 `DOM` 树来执行和下载相应的代码，这会造成阻塞
        - 这就是为什么推荐 JS 代码应该放在 `html` 代码的后面
    - 之后根据外部样式，内部样式，内联样式构建一个 CSS 对象模型树 `CSSOM` 树，构建完成后和 `DOM` 树合并为渲染树，这里主要做的是排除非视觉节点，比如 `script`，`meta` 标签和排除 `display` 为 `none` 的节点
    - 之后进行布局，布局主要是确定各个元素的位置和尺寸之后是渲染页面，因为 `html` 文件中会含有图片，视频，音频等资源，在解析 `DOM` 的过程中，遇到这些都会进行并行下载
        - 浏览器对每个域的并行下载数量有一定的限制，一般是 4-6 个
    - 当然在这些所有的请求中我们还需要关注的就是缓存，缓存一般通过`Cache-Control`、`Last-Modify`、`Expires` 等首部字段控制。 
        - `Cache-Control` 和 `Expires` 的区别在于 `Cache-Control` 使用相对时间，`Expires` 使用的是基于服务器端的绝对时间，因为存在时差问题，一般采用 `Cache-Control`
        - 在请求这些有设置了缓存的数据时，会先查看是否过期，如果没有过期则直接使用本地缓存，过期则请求并在服务器校验文件是否修改
        - 如果上一次响应设置了 `ETag` 值会在这次请求的时候作为 `If-None-Match` 的值交给服务器校验
            - 如果一致，继续校验 `Last-Modified`
            - 没有设置 `ETag` 则直接验证`Last-Modified`，再决定是否返回 `304`

**问：**浏览器在生成页面的时候，构造两棵树，DOM 树和 CSSOM 规则树，当浏览器接收到服务器相应来的 HTML 文档后，会遍历文档节点，生成 DOM 树，CSSOM 规则树由浏览器解析 CSS 文件生成。

**问2：**输入 URL 到页面加载显示完成发生了什么

1. DNS 解析
2. TCP 连接
3. 发送 HTTP 请求
4. 服务器处理请求并返回 HTTP 报文
5. 浏览器解析渲染页面
6. 连接结束

### 浏览器渲染原理与过程

- 要了解浏览器渲染页面的过程，首先得知道一个名词——**关键渲染路径**。关键渲染路径是指浏览器从最初接收请求来的HTML、CSS、javascript等资源，然后解析、构建树、渲染布局、绘制，最后呈现给用户能看到的界面这整个过程。
- 用户看到页面实际上可以分为两个阶段：**页面内容加载完成**和**页面资源加载完成**，分别对应于`DOMContentLoaded`和`Load`。

`DOMContentLoaded`事件触发时，仅当DOM加载完成，不包括样式表，图片等
`load`事件触发时，页面上所有的DOM，样式表，脚本，图片都已加载完成
浏览器渲染的过程主要包括以下五步：
1. 浏览器将获取的HTML文档解析成DOM树。
2. 处理CSS标记，构成层叠样式表模型CSSOM(CSS Object Model)。
3. 将DOM和CSSOM合并为渲染树(`rendering tree`)，代表一系列将被渲染的对象。
4. 渲染树的每个元素包含的内容都是计算过的，它被称之为布局`layout`。浏览器使用一种流式处理的方法，只需要一次绘制操作就可以布局所有的元素。
5. 将渲染树的各个节点绘制到屏幕上，这一步被称为绘制`painting`。
- 需要注意的是，以上五个步骤并不一定一次性顺序完成，比如DOM或CSSOM被修改时，亦或是哪个过程会重复执行，这样才能计算出哪些像素需要在屏幕上进行重新渲染。而在实际情况中，JavaScript和CSS的某些操作往往会多次修改DOM或者CSSOM。
![浏览器渲染过程](/image/%E6%B5%8F%E8%A7%88%E5%99%A8%E6%B8%B2%E6%9F%93%E8%BF%87%E7%A8%8B.png)

#### 浏览器渲染网页的具体流程

> https://www.jianshu.com/p/e6252dc9be32
1. 构建DOM树
> 当浏览器接收到服务器响应来的HTML文档后，会遍历文档节点，生成DOM树。
- 需要注意以下几点：
    1. DOM树在构建的过程中可能会被CSS和JS的加载而执行阻塞
    2. `display:none`的元素也会在DOM树中
    3. 注释也会在DOM树中
    4. `script`标签会在DOM树中
    5. 无论是DOM还是CSSOM，都是要经过`Bytes→characters→tokens→nodes→object model`这个过程。
    6. 当前节点的所有子节点都构建好后才会去构建当前节点的下一个兄弟节点。
![构建DOM树](/image/%E6%9E%84%E5%BB%BADOM%E6%A0%91.png)


2. 构建CSSOM规则树
> 浏览器解析CSS文件并生成CSSOM，每个CSS文件都被分析成一个StyleSheet对象，每个对象都包含CSS规则。CSS规则对象包含对应于CSS语法的选择器和声明对象以及其他对象。
- 在这个过程需要注意的是：
    1. CSS解析可以与DOM解析同时进行。
    2. CSS解析与script的执行互斥 。
    3. 在Webkit内核中进行了script执行优化，只有在JS访问CSS时才会发生互斥。

3. 构建渲染树（Render Tree）

> 通过DOM树和CSS规则树，浏览器就可以通过它两构建渲染树了。浏览器会先从DOM树的根节点开始遍历每个可见节点，然后对每个可见节点找到适配的CSS样式规则并应用。
- 有以下几点需要注意：
    1. Render Tree和DOM Tree不完全对应
    2. `display: none`的元素不在Render Tree中
    3. `visibility: hidden`的元素在Render Tree中

![构建渲染树](/image/%E6%B8%B2%E6%9F%93%E6%A0%91.png)

渲染树生成后，还是没有办法渲染到屏幕上，渲染到屏幕需要得到各个节点的位置信息，这就需要布局（Layout）的处理了。

4. 渲染树布局(layout of the render tree)
> 布局阶段会从渲染树的根节点开始遍历，由于渲染树的每个节点都是一个`Render Object`对象，包含宽高，位置，背景色等样式信息。所以浏览器就可以通过这些样式信息来确定每个节点对象在页面上的确切大小和位置，布局阶段的输出就是我们常说的盒子模型，它会精确地捕获每个元素在屏幕内的确切位置与大小。
- 需要注意的是：
    - `float`元素，`absoulte`元素，`fixed`元素会发生位置偏移。
    - 我们常说的脱离文档流，其实就是脱离Render Tree。

5. 渲染树绘制（Painting the render tree）
> 在绘制阶段，浏览器会遍历渲染树，调用渲染器的`paint()`方法在屏幕上显示其内容。渲染树的绘制工作是由浏览器的UI后端组件完成的。

6. 浏览器主要组件结构
![浏览器主要组件](/image/%E6%B5%8F%E8%A7%88%E5%99%A8%E4%B8%BB%E8%A6%81%E7%BB%84%E4%BB%B6.png)

渲染引擎主要有两个：`webkit`和`Gecko`
Firefox使用`Geoko`，Mozilla自主研发的渲染引擎。
Safari和Chrome都使用`webkit`。
- Webkit是一款开源渲染引擎，它本来是为linux平台研发的，后来由Apple移植到Mac及Windows上。
虽然主流浏览器渲染过程叫法有区别，但是主要流程还是相同的。

7. 渲染阻塞
> JS可以操作DOM来修改DOM结构，可以操作CSSOM来修改节点样式，这就导致了浏览器在遇到`<script>`标签时，DOM构建将暂停，直至脚本完成执行，然后继续构建DOM。如果脚本是外部的，会等待脚本下载完毕，再继续解析文档。现在可以在script标签上增加属性`defer`或者`async`。脚本解析会将脚本中改变DOM和CSS的地方分别解析出来，追加到DOM树和CSSOM规则树上。
> 每次去执行JavaScript脚本都会严重地阻塞DOM树的构建，如果JavaScript脚本还操作了CSSOM，而正好这个CSSOM还没有下载和构建，浏览器甚至会延迟脚本执行和构建DOM，直至完成其CSSOM的下载和构建。所以，script标签的位置很重要。
- JS阻塞了构建DOM树，也阻塞了其后的构建CSSOM规则树，整个解析进程必须等待JS的执行完成才能够继续，这就是所谓的JS阻塞页面。
- 由于CSSOM负责存储渲染信息，浏览器就必须保证在合成渲染树之前，CSSOM是完备的，这种完备是指所有的CSS（内联、内部和外部）都已经下载完，并解析完，只有CSSOM和DOM的解析完全结束，浏览器才会进入下一步的渲染，这就是CSS阻塞渲染。
    - CSS阻塞渲染意味着，在CSSOM完备前，页面将一直处理白屏状态，这就是为什么样式放在`head`中，仅仅是为了**更快**的解析CSS，保证更快的**首次渲染**。
    - 需要注意的是，即便你没有给页面任何的样式声明，CSSOM依然会生成，默认生成的CSSOM自带浏览器默认样式。
    - 当解析HTML的时候，会把新来的元素插入DOM树里面，同时去查找CSS，然后把对应的样式规则应用到元素上，查找样式表是按照**从右到左**的顺序去匹配的。
        - 例如：`div p {font-size: 16px}`，会先寻找所有p标签并判断它的父标签是否为`div`之后才会决定要不要采用这个样式进行渲染。
        - 所以，我们平时写CSS时，尽量用`id`和`class`，千万不要过渡层叠。

#### 回流和重绘（reflow和repaint）
我们都知道HTML默认是流式布局的，但CSS和JS会打破这种布局，改变DOM的外观样式以及大小和位置。因此我们就需要知道两个概念：`replaint`和`reflow`。

**`reflow`（回流）**
> 当浏览器发现布局发生了变化，这个时候就需要倒回去重新渲染，这个回退的过程叫`reflow`。
`reflow`会从`html`这个`root frame`开始**递归往下**，依次计算所有的结点几何尺寸和位置，以确认是渲染树的一部分发生变化还是整个渲染树。`reflow`几乎是无法避免的，因为只要用户进行交互操作，就势必会发生页面的一部分的重新渲染，且通常我们也无法预估浏览器到底会`reflow`哪一部分的代码，因为他们会相互影响。

**`repaint`（重绘）**
`repaint`则是当我们改变某个元素的背景色、文字颜色、边框颜色等等不影响它周围或内部布局的属性时，屏幕的一部分要重画，但是元素的几何尺寸和位置没有发生改变。
- 需要注意的是，`display:none`会触发`reflow`，而`visibility: hidden`属性则并不算是不可见属性，它的语义是隐藏元素，但元素仍然占据着布局空间，它会被渲染成一个空框。所以`visibility:hidden`只会触发`repaint`，因为没有发生位置变化。
- 另外有些情况下，比如修改了元素的样式，浏览器并不会立刻`reflow`或`repaint`一次，而是会把这样的操作积攒一批，然后做一次`reflow`，这又叫异步`reflow`或增量异步`reflow`。但是在有些情况下，比如`resize`窗口，改变了页面默认的字体等。对于这些操作，浏览器会马上进行`reflow`。

**引起`reflow`**
> 现代浏览器会对回流做优化，它会等到足够数量的变化发生，再做一次批处理回流。
1. 页面第一次渲染（初始化）
2. DOM树变化（如：增删节点）
3. Render树变化（如：`padding`改变）
4. 浏览器窗口`resize`
5. 获取元素的某些属性
6. 浏览器为了获得正确的值也会提前触发回流，这样就使得浏览器的优化失效了，这些属性包括`offsetLeft`、`offsetTop`、`offsetWidth`、`offsetHeight`、 `scrollTop/Left/Width/Height`、`clientTop/Left/Width/Height`、调用了`getComputedStyle()`。

**引起`repaint`**
> `reflow`回流必定引起`repaint`重绘，重绘可以单独触发。
- 背景色、颜色、字体改变（注意：字体大小发生变化时，会触发回流）

**减少`reflow`、`repaint`触发次数**
1. 用`transform`做形变和位移可以减少reflow
2. 避免逐个修改节点样式，尽量一次性修改
3. 使用`DocumentFragment`将需要多次修改的DOM元素缓存，最后一次性`append`到真实DOM中渲染
4. 可以将需要多次修改的DOM元素设置`display:none`，操作完再显示。（因为隐藏元素不在`render`树内，因此修改隐藏元素不会触发回流重绘）
5. 避免多次读取某些属性
6. 通过绝对位移将复杂的节点元素脱离文档流，形成新的Render Layer，降低回流成本
几条关于优化渲染效率的建议
结合上文有以下几点可以优化渲染效率。

1. 合法地去书写HTML和CSS ，且不要忘了文档编码类型。
2. 样式文件应当在head标签中，而脚本文件在body结束前，这样可以防止阻塞的方式。
3. 简化并优化CSS选择器，尽量将嵌套层减少到最小。
4. DOM 的多个读操作（或多个写操作），应该放在一起。不要两个读操作之间，加入一个写操作。
5. 如果某个样式是通过重排得到的，那么最好缓存结果。避免下一次用到的时候，浏览器又要重排。
6. 不要一条条地改变样式，而要通过改变`class`，或者`csstext`属性，一次性地改变样式。
7. 尽量用`transform`来做形变和位移
8. 尽量使用离线DOM，而不是真实的网页DOM，来改变元素样式。比如，操作Document Fragment对象，完成后再把这个对象加入DOM。再比如，使用`cloneNode()`方法，在克隆的节点上进行操作，然后再用克隆的节点替换原始节点。
9. **先将元素设为`display: none`（需要1次重排和重绘），然后对这个节点进行100次操作，最后再恢复显示（需要1次重排和重绘）。这样一来，你就用两次重新渲染，取代了可能高达100次的重新渲染。**
10. `position`属性为`absolute`或`fixed`的元素，重排的开销会比较小，因为不用考虑它对其他元素的影响。
11. 只在必要的时候，才将元素的`display`属性为可见，因为不可见的元素不影响重排和重绘。另外，`visibility : hidden`的元素只对重绘有影响，不影响重排。
12. 使用`window.requestAnimationFrame()`、`window.requestIdleCallback()`这两个方法调节重新渲染。


### 常见的 HTTP 的头部

可以将 http 首部分为`通用首部`，`请求首部`，`响应首部`，`实体首部`
- **通用首部**表示一些通用信息，比如 `date` 表示报文创建时间，
- **请求首部**就是请求报文中独有的，如 `cookie`，和缓存相关的如 `if-Modified-Since`
- **响应首部**就是响应报文中独有的，如 `set-cookie`，和重定向相关的 `location`，
- **实体首部**用来描述实体部分，如 `allow` 用来描述可执行的请求方法，`content-type` 描述主题类型，`content-Encoding` 描述主体的编码方式。

### 浏览器缓存机制

> 对于一个数据请求来说，可以分为发起网络请求、后端处理、浏览器响应三个步骤。浏览器缓存可以帮助我们在第一和第三步骤中优化性能。比如说直接使用缓存而不发起请求，或者发起了请求但后端存储的数据和前端一致，那么就没有必要再将数据回传回来，这样就减少了响应数据。
> https://csdnnews.blog.csdn.net/article/details/89324384?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1-89324384-blog-122680032.pc_relevant_multi_platform_whitelistv1&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1-89324384-blog-122680032.pc_relevant_multi_platform_whitelistv1&utm_relevant_index=2

![浏览器缓存机制](/image/%E6%B5%8F%E8%A7%88%E5%99%A8%E7%BC%93%E5%AD%98%E6%9C%BA%E5%88%B6.jpg)

1. 为什么需要缓存

- 在前端开发中，我们主要追求的是性能和用户体验。对于一个网站查看性能最简单的方式就是打开网站的速度。而一个好的缓存策略可以大大提升网站的性能。使得已经下载后的资源被重复利用。减少客户端和服务器之间的请求次数，减少带宽，减少网络负荷。

2. 什么是缓存

- 对于web缓存，主要是针对一些web资源（html, js,图片，数据等），就是介于web服务器和浏览器之间的文件数据副本。
- 当我们第一次打开某一个网页时，浏览器向服务器发起请求，请求所需要的资源。
- 如果我们使用了web缓存，当我们下一次再次访问该网站页面的时候，我们可以根据一些缓存策略，来决定是否直接使用缓存中的一些资源，还是再次向服务端发起请求，从而避免再次向服务器发起请求，减少客户端和服务器之间通信的时延。

3. 缓存的作用

- 减少网络带宽的消耗
- 降低服务器压力
- 减少网络延时，加快页面打开速度。

4. 浏览器的缓存机制

> 对于浏览器端的缓存来说，规则是在http协议头和html的`mate`标签中定义的，他们分别从过期机制和校验值来判断是否直接使用该缓存，还是需要从服务器去获取更新的版本。
- 新鲜度(过期机制)：也就是缓存副本的有效期。一个缓存副本必须满足以下条件之一，浏览器才会认为它是有效的，足够新的，才会直接使用缓存。
    - http协议头中存在过期时间等信息，并且仍在有效期内。
    - 浏览器已经使用过这个缓存副本，并且在一个会话中已经检查过新鲜度。
- 校验值(验证机制)：服务器相应中，在响应头中存在`Etag`标签，用来验证资源是否更改的标识，如果缓存的标识和服务器的标识相同则无需重新请求资源，如果不相同，则重新发送资源请求。

5. 浏览器缓存控制

- html中的`mate`标签设置缓存
```html
<!-- 设置过期时间 -->
<meta http-equiv="expires" content="Wed, 20 Jun 2007 22:33:00 GMT">
<!-- 设置缓存 -->
<meta http-equiv="Pragma" content="no-cache">
```
- 与缓存有关的字段
    - `cache-control` 是一个通用消息头字段被用于 HTTP 请求和响应中，通过指定指令来实现缓存机制，这个缓存指令是单向的，常见的取值有 `private`、`no-cache`、`max-age`、`must-revalidate` 等，默认为 `private`
    - `Cache-control:max-age`(单位为s),当某一个资源的响应头设置`max-age=3600`，
    则表示在`1h`时间内，服务器的资源发生变化，浏览器都不会向服务器发送该资源的请
    求，直接使用缓存。并且`max-age`会覆盖`Expires`。
    ```
    Cache-Control: max-age=3600
    ```
    - `Cache-control:s-maxage`,`s-maxage`表示CDN缓存，也就是`代理缓存`，如果设置`s-maxage=60`,表示60秒内无论cdn服务器的该资源发生怎么样的改变，都不会重新请求，并且`s-maxage`会覆盖`max-age`和`Expires`

    - `Cache-control:public`，指定是否是共享缓存，如果设置`Cache-control`的值设置为`public`,则表示多个浏览器之间可以共同使用该资源缓存。
    如果没有指定`Cache-control`是为`private`还是`public`，则默认是`public`
    ![共享缓存](/image/%E5%85%B1%E4%BA%AB%E7%BC%93%E5%AD%98.png)

    - `Cache-control:private`，表示该缓存是私有的，不存在用户共享。
    ![私有缓存](/image/%E7%A7%81%E6%9C%89%E7%BC%93%E5%AD%98.png)

    - `Cache-control:no-cache`：`Cache-control`的值设置为`no-cache`并不代表不缓存，浏览器是缓存的，但是当每一次访问该资源的时候，都要向服务器请求查看资源是否改变，如果改变，则直接重新下载，如果没有改变，则使用缓存。可以在设置完`no-cache`之后，再设置`private`，以及设置过期时间为过去的时间。

    - `Cache-control:no-store`：表示严格不缓存，每一次资源必须从服务器上重新获取。

    - `Expires`：缓存过期时间，`Expires=max-age + 最后一次请求的时间`。`Cache-control`和`Expires`相比，`Cache-control`的优先级更高。`Expires`需要和`Last-modifyed`来一起使用。

    ```
    Expires: Mon, 25 Dec 2017 07:16:44 GMT
    Last-Modified: Sat, 08 Apr 2017 17:20:05 GMT
    ```
    - `Last-Modified`和`if-modified-since:last-modified`是响应头上的属性，`if-modifyed-since`是请求头的数据。该属性值需要`cache-control`配合使用。当再次向服务器发送请求该资源时，会携带`if-modified-since`的请求头字段，到服务器比对和`last-modified`是否相同。如果相同则直接返回`304`,直接使用缓存，如果不相同，则再次请求新的数据，返回`200`

    - `ETag`和`if-None-Match`：这两个属性其实和`last-modified`和`if-modified-since` 类似。不过`Etag`是服务器更加内容产生的`hash`字符串，并且`Etag`是响应头内容。`if-None-match`是请求头的内容。当再次向服务器发送请求某一个资源时，请求头会携带`if-None-match`属性，到达服务器后，和`Etag`进行比对。如果相同，则返回304，如果不相同则返回该资源，并且状态码为`200`

6. 缓存报文头种类和优先级

- `Cache-control`和`Expires`比较
    - `Cache-control`的优先级比`Expires`的优先级高。
- `Last-Modified`和`ETag`比较
    - `Etag`的优先级要高于`Last-modified`，当在请求头中会先进行`ETag`比较，然后再进行`Last-modified`比较，如果两者都相等，则直接返回`304`,直接使用缓存资源。
    - 两者比较一下，你可能会觉得两者的功能差不多，但是为什么要在`http1.1`中新增`Etag`呢
    1. `Last-modified`精确到秒，如果在一秒钟内修改多次文件，则无法准确拿到最新的文件。
    2. 如果缓存文件，打开后但是不修改内容，导致`Last-modified`发生变化，下一次就没有办法使用缓存文件了。
    3. 可能存在服务器没有获取准确的修改时间，或者代理服务器时间不一致的情况。
- `Last-Modified/Etag`和`Cache-control/Expires`比较
    - `Cache-control/Expries`的优先级要比`Last-Modified/Etag`的优先级高
    - 当第二次发送请求时，会首先查看`Cache-control/Expries`是否过期，如果没有过期，则任然使用该资源，如果过期了，则再次向服务器发送请求来请求最新的资源。
    - 到达服务器时通过比对`Last-modified/Etag`是否和原来的值相等，来判断资源是否改变，如果没有改变，则返回`304`。如果改变了，则返回最新的资源，并且状态码为`200`

7. 无法被浏览器缓存的请求

- `http`信息头部`cache-control:no-cache` , `pragma: nocache`或者使用`cache-control:max-age=0`
- 根据`cookie`，认证信息决定输入内容的信息是否可以被缓存的。
- 经过`https`加密的请求。
- `post`请求无法被缓存。
- 在`http`响应头中不存在`last-modified/Etag`和`cache-control/expires`等。

8. 使用缓存流程

![使用缓存流程](/image/%E4%BD%BF%E7%94%A8%E7%BC%93%E5%AD%98%E6%B5%81%E7%A8%8B.png)

- 上面的过程可以分为三个阶段：
    1. 本地缓存阶段：如果本地存在缓存，并且通过检查本地资资源的缓存并没有过期，则直接使用本地缓存。
    2. 协商缓存阶段：如果在本地存在该资源，但是本地资源已经过期，此时就需要封装http请求，向服务端发送请求，检查是否存在更改资源。如果资源没有更改，则直接返回`304`，直接在本地使用资源。
    3. 缓存失败阶段:如果资源发生了更改，则重新返回最新的资源，并且返回状态码为200。如果此时不存在该资源，则直接返回`404`

9. 用户行为与缓存的关系

- 用户在浏览器采用一些操作，例如，返回上一阶段，下一阶段，刷新页面，强制刷新等操作，这些对于一些缓存属性的影响是不一样的。
    1. 刷新（仅仅是`F5`刷新）:此时对于`cache-control/Expires`是不生效的，但是`last-modified/Etag`都生效的，所以此时会向服务器发起请求，用来判断目标文件是否发生变化。
    2. 强制刷新(`F5刷新+ctrl`):此时对于`cache-control/expires`和`last-modified/Etag`都不生效，此时必须从服务器拿到新数据。
    3. 回车或者转向：此时所有的缓存都生效。

10. 从缓存角度改善站点

- 同一个资源保证只有一个稳定的`url`地址。
- css,js,图片资源增加`http`缓存头，入口`html`文件不被缓存。
- 减少对`cookie`的依赖
- 减少对`http`协议加密的使用。

## CSS/LESS/SASS

### viewport 和移动端布局

1. px和视口
    1. 像素
    在静态网页中，我们经常用像素（px）作为单位，来描述一个元素的宽高以及定位信息。
    在pc端，通常认为css中,1px所表示的真实长度是固定的。

    如果在css中仅仅通过px作为长度和宽度的单位，造成的结果就是无法通过一套样式，实现各端的自适应。

    2. 视口
    - 广义的视口，是指浏览器显示内容的屏幕区域，狭义的视口包括了布局视口、视觉视口和理想视口
        1. 布局视口（layout viewport）
        布局视口定义了pc网页在移动端的默认布局行为，因为通常pc的分辨率较大，布局视口默认为980px。也就是说在不设置网页的viewport的情况下，pc端的网页默认会以布局视口为基准，在移动端进行展示。因此我们可以明显看出来，默认为布局视口时，根植于pc端的网页在移动端展示很模糊。
        2. 视觉视口（visual viewport）
        视觉视口表示浏览器内看到的网站的显示区域，用户可以通过缩放来查看网页的显示内容，从而改变视觉视口。视觉视口的定义，就像拿着一个放大镜分别从不同距离观察同一个物体，视觉视口仅仅类似于放大镜中显示的内容，因此视觉视口不会影响布局视口的宽度和高度。
        3. 理想视口（ideal viewport）
        理想视口或者应该全称为“理想的布局视口”，在移动设备中就是指设备的分辨率。换句话说，理想视口或者说分辨率就是给定设备物理像素的情况下，最佳的“布局视口”。

    - 上述视口中，最重要的是要明确理想视口的概念，在移动端中，理想视口或者说分辨率跟物理像素之间有什么关系呢？
    - 为了理清分辨率和物理像素之间的联系，我们介绍一个用DPR（Device pixel ratio）设备像素比来表示，则可以写成：
    ```
    1 DPR = 物理像素／分辨率
    ```
    - 在不缩放的情况下，一个css像素就对应一个dpr，也就是说，在不缩放
    ```
    1 CSS像素 = 物理像素／分辨率
    ```
    - 此外，在移动端的布局中，我们可以通过`viewport`元标签来控制布局，比如一般情况下，我们可以通过下述标签使得移动端在理想视口下布局：
    ```html
    <meta id="viewport" name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1; user-scalable=no;">
    ```

    上述meta标签的每一个属性的详细介绍如下：

    | 属性名     | 取值  | 描述                                   | 属性名     |
    | ------------- | ------- | ---------------------------------------- | ------------- |
    | width         | 正整数 | 定义布局视口的宽度，单位为像素 | width         |
    | height        | 正整数 | 定义布局视口的高度，单位为像素，很少使用 | height        |
    | initial-scale | [0,10]  | 初始缩放比例，1表示不缩放    | initial-scale |
    | minimum-scale | [0,10]  | 最小缩放比例                       | minimum-scale |
    | maximum-scale | [0,10]  | 最大缩放比例                       | maximum-scale |
    | user-scalable | yes／no | 是否允许手动缩放页面，默认值为yes | user-scalable |
    其中我们来看`width`属性，在移动端布局时，在`meta`标签中我们会将`width`设置称为`device-width`，`device-width`一般是表示分辨率的宽，通过`width=device-width`的设置我们就将布局视口设置成了理想的视口。

    3. px与自适应
    - 上述我们了解到了当通过`viewport`元标签，设置布局视口为理想视口时，1个css像素可以表示成：
    ```
    1 CSS像素 = 物理像素／分辨率
    ```
    - 我们知道，在pc端的布局视口通常情况下为`980px`，移动端以iphone6为例，分辨率为`375 * 667`，也就是说布局视口在理想的情况下为`375px`。比如现在我们有一个`750px * 1134px`的视觉稿，那么在pc端，一个css像素可以如下计算：
    ```
    PC端： 1 CSS像素 = 物理像素／分辨率 = 750 ／ 980 =0.76 px
    ```
    - 而在iphone6下：
    ```
    iphone6：1 CSS像素 = 物理像素 ／分辨率 = 750 ／ 375 = 2 px
    ```
    - 也就是说在PC端，一个CSS像素可以用0.76个物理像素来表示，而iphone6中 一个CSS像素表示了2个物理像素。此外不同的移动设备分辨率不同，也就是1个CSS像素可以表示的物理像素是不同的，因此如果在css中仅仅通过px作为长度和宽度的单位，造成的结果就是无法通过一套样式，实现各端的自适应。

2. 媒体查询

- 不同端的设备下，在css文件中，1px所表示的物理像素的大小是不同的，因此通过一套样式，是无法实现各端的自适应。由此我们联想：

如果一套样式不行，那么能否给每一种设备各一套不同的样式来实现自适应的效果？

答案是肯定的。

使用`@media`媒体查询可以针对不同的媒体类型定义不同的样式，特别是响应式页面，可以针对不同屏幕的大小，编写多套样式，从而达到自适应的效果。举例来说：

```css
@media screen and (max-width: 960px){
    body{
      background-color:#FF6699
    }
}

@media screen and (max-width: 768px){
    body{
      background-color:#00FF66;
    }
}

@media screen and (max-width: 550px){
    body{
      background-color:#6633FF;
    }
}

@media screen and (max-width: 320px){
    body{
      background-color:#FFFF00;
    }
}
```

- 上述的代码通过媒体查询定义了几套样式，通过`max-width`设置样式生效时的最大分辨率，上述的代码分别对分辨率在`0～320px`，`320px～550px`，`550px～768px`以及`768px～960px`的屏幕设置了不同的背景颜色。
- 通过媒体查询，可以通过给不同分辨率的设备编写不同的样式来实现响应式的布局，比如我们为不同分辨率的屏幕，设置不同的背景图片。比如给小屏幕手机设置`@2x`图，为大屏幕手机设置`@3x`图，通过媒体查询就能很方便的实现。
- 但是媒体查询的缺点也很明显，如果在浏览器大小改变时，需要改变的样式太多，那么多套样式代码会很繁琐。

3. 百分比
- 除了用px结合媒体查询实现响应式布局外，我们也可以通过百分比单位 " % " 来实现响应式的效果。
- 比如当浏览器的宽度或者高度发生变化时，通过百分比单位，通过百分比单位可以使得浏览器中的组件的宽和高随着浏览器的变化而变化，从而实现响应式的效果。
- 为了了解百分比布局，首先要了解的问题是：
    - css中的子元素中的百分比（%）到底是谁的百分比？
        - 直观的理解，我们可能会认为子元素的百分比完全相对于直接父元素，height百分比相对于height，width百分比相对于width。当然这种理解是正确的，但是根据css的盒式模型，除了height、width属性外，还具有padding、border、margin等等属性。那么这些属性设置成百分比，是根据父元素的那些属性呢？此外还有border-radius和translate等属性中的百分比，又是相对于什么呢？下面来具体分析。

-  百分比的具体分析
    1. 子元素`height`和`width`的百分比
    - 子元素的`height`或`width`中使用百分比，是相对于子元素的直接父元素，`width`相对于父元素的`width`，`height`相对于父元素的`height`。比如：
    ```html
    <div class="parent">
        <div class="child"></div>
    </div>
    ```
    如果设置：
    ```css
    .father{
    width:200px;
    height:100px;
    }
    .child{
    width:50%;
    height:50%;
    }
    ```
    展示的效果为：
    ![image](https://user-images.githubusercontent.com/17233651/41773411-91e22044-764e-11e8-8ad4-9066db87166f.png)

    2. `top`和`bottom` 、`left`和`right`
    - 子元素的top和bottom如果设置百分比，则相对于直接非static定位(默认定位)的父元素的高度
    - 子元素的left和right如果设置百分比，则相对于直接非static定位(默认定位的)父元素的宽度
    展示的效果为：
    ![image](https://user-images.githubusercontent.com/17233651/41774950-67423bfc-7654-11e8-9947-aa1621fe39f9.png)

    3. `padding`
    - 子元素的`padding`如果设置百分比，不论是垂直方向或者是水平方向，都相对于直接父亲元素的`width`，而与父元素的`height`无关。
    ```css
    .parent{
        width:200px;
        height:100px;
        background:green;
    }
    .child{
        width:0px;
        height:0px;
        background:blue;
        color:white;
        padding-top:50%;
        padding-left:50%;
    }
    ```
    展示的效果为：
    ![image](https://user-images.githubusercontent.com/17233651/41775365-36a0b0da-7656-11e8-8495-bd58f7ab0bf2.png)
    - 子元素的初始宽高为0，通过`padding`可以将父元素撑大，上图的蓝色部分是一个正方形，且边长为`100px`,说明`padding`不论宽高，如果设置成百分比都相对于父元素的`width`。

    4. `margin`
    - 跟`padding`一样，子元素的`margin`如果设置成百分比，不论是垂直方向还是水平方向，都相对于直接父元素的`width`

    5. `border-radius`
    - `border-radius`不一样，如果设置`border-radius`为百分比，则是相对于自身的宽度，举例来说：
    ```html
    <div class="trangle"></div>
    ```
    ```css
    .trangle{
        width:100px;
        height:100px;
        border-radius:50%;
        background:blue;
        margin-top:10px;
    }
    ```
    展示效果为：
    ![image](https://user-images.githubusercontent.com/17233651/41775919-6a41ae42-7658-11e8-8e54-43ad05c12d43.png)

    - 除了`border-radius`外，还有比如`translate`、`background-size`等都是相对于自身的

- 百分比单位布局应用
    - 要实现一个固定长宽比的长方形，比如要实现一个长宽比为`4:3`的长方形,我们可以根据`padding`属性来实现，因为`padding`不管是垂直方向还是水平方向，百分比单位都相对于父元素的宽度，因此我们可以设置`padding-top`为百分比来实现，长宽自适应的长方形：
    ```html
    <div class="trangle"></div>
    ```
    设置样式让其自适应：
    ```css
    .trangle{
        height:0;
        width:100%;
        padding-top:75%;
    }
    ```
    - 通过设置`padding-top：75%`,相对比宽度的`75%`，因此这样就设置了一个长宽高恒定比例的长方形

- 百分比单位缺点

    1. 计算困难，如果我们要定义一个元素的宽度和高度，按照设计稿，必须换算成百分比单位。
    2. 各个属性中如果使用百分比，相对父元素的属性并不是唯一的。比如`width`和`height`相对于父元素的`width`和`height`，而`margin`、`padding`不管垂直还是水平方向都相对比父元素的宽度、`border-radius`则是相对于元素自身等等，造成我们使用百分比单位容易使布局问题变得复杂。


4. 自适应场景下的`rem`解决方案
    1.  `rem`单位
    > `rem`是一个灵活的、可扩展的单位，由浏览器转化像素并显示。与`em`单位不同，`rem`单位无论嵌套层级如何，都只相对于浏览器的根元素（HTML元素）的`font-size`。默认情况下，html元素的`font-size`为16px，所以：
        ```
        1 rem = 16px
        ```
    - 为了计算方便，通常可以将html的`font-size`设置成：
        ```
        html{ font-size: 62.5% }
        ```
    - 这种情况下：
        ```
        1 rem = 10px
        ```
    2. 通过`rem`来实现响应式布局
    - rem单位都是相对于根元素`html`的`font-size`来决定大小的,根元素的`font-size`相当于提供了一个基准，当页面的`size`发生变化时，只需要改变`font-size`的值，那么以`rem`为固定单位的元素的大小也会发生响应的变化。
因此，如果通过`rem`来实现响应式的布局，只需要根据视图容器的大小，动态的改变`font-size`即可。
```js
function refreshRem() {
    var docEl = doc.documentElement;
    var width = docEl.getBoundingClientRect().width;
    var rem = width / 10;
    docEl.style.fontSize = rem + 'px';
    flexible.rem = win.rem = rem;
}
win.addEventListener('resize', refreshRem);
```
- 上述代码中将视图容器分为10份，`font-size`用十分之一的宽度来表示，最后在`header`标签中执行这段代码，就可以动态定义`font-size`的大小，从而`1rem`在不同的视觉容器中表示不同的大小，用`rem`固定单位可以实现不同容器内布局的自适应。
    3. `rem2px`和`px2rem`
    - 如果在响应式布局中使用`rem`单位，那么存在一个单位换算的问题，`rem2px`表示从`rem`换算成`px`，这个就不说了，只要`rem`乘以相应的`font-size`中的大小，就能换算成`px`。更多的应用是`px2rem`，表示的是从`px`转化为`rem`。
    - 比如给定的视觉稿为`750px`（物理像素），如果我们要将所有的布局单位都用`rem`来表示，一种比较笨的办法就是对所有的`height`和`width`等元素，乘以相应的比例，现将视觉稿换算成`rem`单位，然后一个个的用`rem`来表示。另一种比较方便的解决方法就是，在css中我们还是用`px`来表示元素的大小，最后编写完css代码之后，将css文件中的所有`px`单位，转化成`rem`单位。
    - `px2rem`的原理也很简单，重点在于预处理以`px`为单位的css文件，处理后将所有的`px`变成``rem``单位。可以通过两种方式来实现：
        1. webpack loader的形式：
        ```
        npm install px2rem-loader
        ```
        - 在webpack的配置文件中：
        ```js
        module.exports = {
        // ...
        module: {
            rules: [{
            test: /\.css$/,
            use: [{
                loader: 'style-loader'
            }, {
                loader: 'css-loader'
            }, {
                loader: 'px2rem-loader',
                // options here
                options: {
                remUni: 75,
                remPrecision: 8
                }
            }]
            }]
        }
        }
        ```
        2. webpack中使用`postcss` `plugin`
        ```
        npm install postcss-loader
        ```
        - 在webpack的`plugin`中:
        ```js
        var px2rem = require('postcss-px2rem');

        module.exports = {
        module: {
            loaders: [
            {
                test: /\.css$/,
                loader: "style-loader!css-loader!postcss-loader"
            }
            ]
        },
        postcss: function() {
            return [px2rem({remUnit: 75})];
        }
        }
        ```
        4. `rem` 布局的缺点
        - 在响应式布局中，必须通过js来动态控制根元素`font-size`的大小。
            - css样式和js代码有一定的耦合性。且必须将改变`font-size`的代码放在css样式之前

5. 通过`vw/vh`来实现自适应

css3中引入了一个新的单位`vw/vh`，与视图窗口有关，`vw`表示相对于视图窗口的宽度，`vh`表示相对于视图窗口高度，除了`vw`和`vh`外，还有`vmin`和`vmax`两个相关的单位。各个单位具体的含义如下：

| 单位 | 含义                            |
| ---- | --------------------------------- |
| vw   | 相对于视窗的宽度，视窗宽度是100vw |
| vh   | 相对于视窗的高度，视窗高度是100vh |
| vmin | vw和vh中的较小值            |
| vmax | vw和vh中的较大值            |
这里我们发现视窗宽高都是`100vw／100vh`，那么`vw`或者`vh`，下简称`vw`，很类似百分比单位。`vw`和`%`的区别为：

| 单位 | 含义                                                                          |
| ----- | ------------------------------------------------------------------------------- |
| %     | 大部分相对于祖先元素，也有相对于自身的情况比如（`border-radius`、`translate`等) |
| vw/vh | 相对于视窗的尺寸                                                        |
从对比中我们可以发现，vw单位与百分比类似，单确有区别，前面我们介绍了百分比单位的换算困难，这里的vw更像"理想的百分比单位"。任意层级元素，在使用vw单位的情况下，1vw都等于视图宽度的百分之一。

2. vw单位换算
同样的，如果要将`px`换算成`vw`单位，很简单，只要确定视图的窗口大小（布局视口），如果我们将布局视口设置成分辨率大小，比如对于`iphone6/7 375*667`的分辨率，那么px可以通过如下方式换算成`vw`：
```
1px = （1/375）*100 vw
```

此外，也可以通过`postcss`的相应插件，预处理css做一个自动的转换，`postcss-px-to-viewport`可以自动将`px`转化成`vw`。
`postcss-px-to-viewport`的默认参数为：
```js
var defaults = {
  viewportWidth: 320,
  viewportHeight: 568, 
  unitPrecision: 5,
  viewportUnit: 'vw',
  selectorBlackList: [],
  minPixelValue: 1,
  mediaQuery: false
};
```

通过指定视窗的宽度和高度，以及换算精度，就能将`px`转化成`vw`。

## Vue

### Vue渲染/更新过程

1. 渲染过程
    1. 解析模板为`render`函数（或在开发环境已完成，vue-loader）
    2. 触发响应式，监听`data`属性`getter` `setter`
    3. 执行`render`函数，生成`vnode`，`patch（elem，vnode）`

2. 更新过程
    1. 修改`data`，触发`setter`（此前在`getter`中已被监听）
    2. 重新执行`render`函数，生成`newVnode`
    3. `patch(vnode，newVnode)` 比较新老节点的不同，然后更新
3. vue组件是异步渲染
    - Vue 在更新 DOM 时是异步执行的。只要侦听到数据变化，Vue 将开启一个队列，并缓冲在同一事件循环中发生的所有数据变更。如果同一个 `watcher` 被多次触发，只会被推入到队列中一次。这种在缓冲时去除重复数据对于避免不必要的计算和 DOM 操作是非常重要的。

### 父子组件生命周期

> 父组件先创建，然后子组件创建；子组件先挂载，然后父组件挂载。
![父子组件生命周期](/image/%E7%88%B6%E5%AD%90%E7%BB%84%E4%BB%B6%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.png)
- 子组件挂载完成后，父组件还未挂载。所以组件数据回显的时候，在父组件`mounted`中获取`api`的数据，子组件的`mounted`是拿不到的。
- `created`这个钩子是按照从外内顺序执行，所以回显场景的解决方案是：在`created`中发起请求获取数据，依次在子组件的`created`中会接收到这个数据。

> 更新过程`父 beforeUpdate` -> `子 beforeUpdate` -> `子 updated` -> `父 updated`

### keep-alive

> `keep-alive`是Vue提供的一个抽象组件，用来对组件进行缓存，从而节省性能，由于是一个抽象组件，所以在v页面渲染完毕后不会被渲染成一个DOM元素

- Props
1. `include` - 字符串或正则表达式。只有名称匹配的组件会被缓存。
2. `exclude` - 字符串或正则表达式。任何名称匹配的组件都不会被缓存。
3. `max` - 数字。最多可以缓存多少组件实例。

- 生命周期函数
1. `activated`
    - 在 `keep-alive` 组件激活时调用
        - 该钩子函数在服务器端渲染期间不被调用
2. `deactivated`
    - 在 `keep-alive` 组件停用时调用
        - 该钩子在服务器端渲染期间不被调用
3. 被包含在 `keep-alive` 中创建的组件，会多出两个生命周期的钩子: `activated` 与 `deactivated`

- 使用 `keep-alive` 会将数据保留在内存中，如果要在每次进入页面的时候获取最新的数据，需要在 `activated` 阶段获取数据，承担原来 `created` 钩子函数中获取数据的任务。

**注意：**只有组件被 `keep-alive` 包裹时，这两个生命周期函数才会被调用，如果作为正常组件使用，是不会被调用的，以及在 2.1.0 版本之后，使用 `exclude` 排除之后，就算被包裹在 `keep-alive` 中，这两个钩子函数依然不会被调用！另外，在服务端渲染时，此钩子函数也不会被调用。

**结合Router，缓存部分页面**

```js
import Vue from 'vue'
import Router from 'vue-router'
const Home = resolve => require(['@/components/home/home'], resolve)
const Goods = resolve => require(['@/components/home/goods'], resolve)
const Ratings = resolve => require(['@/components/home/ratings'], resolve)
const Seller = resolve => require(['@/components/home/seller'], resolve)

Vue.use(Router)

export default new Router({
  mode: 'history',
  routes: [
    {
      path: '/',
      name: 'home',
      component: Home,
      redirect: 'goods',
      children: [
        {
          path: 'goods',
          name: 'goods',
          component: Goods,
          meta: {
        	keepAlive: false // 不需要缓存
      	  }
        },
        {
          path: 'ratings',
          name: 'ratings',
          component: Ratings,
          meta: {
        	keepAlive: true  // 需要缓存
      	  }
        },
        {
          path: 'seller',
          name: 'seller',
          component: Seller,
          meta: {
        	keepAlive: true  // 需要缓存
      	  }
        }
      ]
    }
  ]
})
```

```vue
<template>
  <div id="app">
  	<keep-alive>
      <router-view v-if="$route.meta.keepAlive"></router-view>
    </keep-alive>
    <router-view v-if="!$route.meta.keepAlive"></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
```

**根据条件缓存页面**

```vue
<template>
  <div id="app">
  	<!-- 1. 将缓存 name 为 test 的组件 -->
  	<keep-alive include='test'>
      <router-view/>
    </keep-alive>
	
	<!-- 2. 将缓存 name 为 a 或者 b 的组件，结合动态组件使用 -->
	<keep-alive include='a,b'>
  	  <router-view/>
	</keep-alive>
	
	<!-- 3. 使用正则表达式，需使用 v-bind -->
	<keep-alive :include='/a|b/'>
  	  <router-view/>
	</keep-alive>	
	
	<!-- 4. 动态判断 -->
	<keep-alive :include='includedComponents'>
  	  <router-view/>
	</keep-alive>
	
	<!-- 5. 将不缓存 name 为 test 的组件 -->
	<keep-alive exclude='test'>
  	  <router-view/>
	</keep-alive>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
```

### 响应式原理

> “响应式”，是指当数据改变后，Vue 会通知到使用该数据的代码。例如，视图渲染中使用了数据，数据改变后，视图也会自动更新。

- Vue 的响应式原理是核心是通过 ES5 的保护对象的 `Object.defindeProperty` 中的访问器属性中的 `get` 和 `set` 方法，`data` 中声明的属性都被添加了访问器属性，当读取 `data` 中的数据时自动调用 `get` 方法，当修改 `data` 中的数据时，自动调用 `set` 方法，检测到数据的变化，会通知观察者 `Watcher`，观察者 `Watcher`自动触发重新`render` 当前组件（子组件不会重新渲染）,生成新的虚拟 DOM 树，Vue 框架会遍历并对比新虚拟 DOM 树和旧虚拟 DOM 树中每个节点的差别，并记录下来，最后，加载操作，将所有记录的不同点，局部修改到真实 DOM 树上。
    ![vue响应式原理](/image/vue%E5%93%8D%E5%BA%94%E5%BC%8F%E5%8E%9F%E7%90%86.png)
    ![发布订阅和观察者模式](/image/%E8%A7%82%E5%AF%9F%E8%80%85%E5%92%8C%E5%8F%91%E5%B8%83%E8%AE%A2%E9%98%85%E6%A8%A1%E5%BC%8F%E7%9A%84%E5%8C%BA%E5%88%AB.png)
    - 观察者模式： 观察者（Observer）直接订阅（Subscribe）主题（Subject），而当主题被激活的时候，会触发（Fire Event）观察者里的事件。

    - 发布订阅模式： 订阅者（Subscriber）把自己想订阅的事件注册（Subscribe）到调度中心（Topic），当发布者（Publisher）发布该事件（Publish topic）到调度中心，也就是该事件触发时，由调度中心统一调度（Fire Event）订阅者注册到调度中心的处理代码。

- 响应式缺陷
1. vue不能监听数组的变化

`Object.defindProperty`虽然能够实现双向绑定了，但是还是有缺点，只能对对象的属性进行数据劫持，所以会深度遍历整个对象，不管层级有多深，只要数组中嵌套有对象，就能监听到对象的数据变化无法监听到数组的变化，Proxy就没有这个问题，可以监听整个对象的数据变化，所以用vue3.0会用`Proxy`代替`definedProperty`。

2. Vue不能检测到对象属性的添加或删除

受现代JS的限制（以及废弃 `Object.observe`），Vue不能检测到对象属性的添加或删除，由于Vue会在初始化实例时对属性执行 `getter/setter`转化过程，所以属性必须在`data`对象上存在才能让Vue转换它，这样才能让它是响应的。

```js
var vm = new Vue({
  data:{
  　　a:1
  }
})
// `vm.a` 是响应的
vm.b = 2
// `vm.b` 是非响应的
```
- Vue不允许在已经创建的实例上动态添加新的根级响应式属性(root-level reactive property)，然而它可以使用 Vue.set(object, key, value) 方法将响应属性添加到嵌套的对象上。
```js
Vue.set(vm.someObject, 'b', 2)
```
- 也可以使用 vm.$set 实例方法，这也是全局 Vue.set 方法的别名。
```js
this.$set(this.someObject,'b',2)
```

- 有时想向已有对象上添加一些属性，例如使用`Object.assign()`或 `_.extend()`方法来添加属性。但是，添加到对象上的新属性不会触发更新。在这种情况下可以创建一个新的对象，让它包含原对象的属性和新的属性。

```js
// 代替 `Object.assign(this.someObject, { a: 1, b: 2 })`
this.someObject = Object.assign({}, this.someObject, { a: 1, b: 2 })
```

### hash和history

> https://zhuanlan.zhihu.com/p/130995492

`vue-router` 中`hash`模式和`history`模式
> 在vue的路由配置中有`mode`选项，最直观的区别就是在`url`中`hash` 带了一个很丑的 `#` ，而`history`是没有#的。`vue`默认使用hash。
```json
mode:"hash";  
mode:"history";
```

**hash**
> 监听 url 中 hash 的变化，然后渲染不同的内容，这种路由不向服务器发送请求，不需要服务端的支持
- 即地址栏 URL 中的 `#` 符号（此 `hash` 不是密码学里的散列运算）。
比如这个 URL：http://www.aaa.com/#/hello，hash 的值为 #/hello。
- 它的特点在于：`hash` 虽然出现在 URL 中，但不会被包括在 HTTP 请求中，对后端完全没有影响，因此改变 `hash` 不会重新加载页面。
- 当页面中的 `hash` 发生变化时，会触发`hashchange`事件，因此我们可以监听这个事件，来判断路由是否发生了变化。

```js
window.addEventListener(
    'hashchange',
    function (event) {
        const oldURL = event.oldURL; // 上一个URL
        const newURL = event.newURL; // 当前的URL
        console.log(newURL, oldURL);
    },
    false
);
```


**history**
> 监听 url 中的路径变化，需要客户端和服务端共同的支持
- 利用了 HTML5 History Interface 中新增的 `pushState()` 和 `replaceState()` 方法。（需要特定浏览器支持）


这两个方法应用于浏览器的历史记录栈，在当前已有的 `back`、`forward`、`go` 的基础之上，它们提供了对历史记录进行修改的功能。只是当它们执行修改时，虽然改变了当前的 URL，但浏览器不会立即向后端发送请求。

因此可以说，`hash` 模式和 `history` 模式都属于浏览器自身的特性，`Vue-Router` 只是利用了这两个特性（通过调用浏览器提供的接口）来实现前端路由。

`history`模式的问题
- 通过`history api`，我们丢掉了丑陋的#，但是它也有个问题：不怕前进，不怕后退，就怕刷新，f5，（如果后端没有准备的话）,因为刷新是实实在在地去请求服务器的。
- 在`hash`模式下，前端路由修改的是`#`中的信息，而浏览器请求时不会将`#`后面的数据发送到后台，所以没有问题。但是在`history`下，你可以自由的修改`path`，当刷新时，如果服务器中没有相应的响应或者资源，则会刷新出来404页面。