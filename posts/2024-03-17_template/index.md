| [preview](./index) | [raw](./index.md) |
|:-------------------|------------------:|

---

- [基本格式](#基本格式)
    - [标题](#标题)
        - [0x01 标题1](#0x01-标题1)
        - [0x02 标题2](#0x02-标题2)
        - [0x03 标题3](#0x03-标题3)
        - [0x04 标题4](#0x04-标题4)
    - [列表](#列表)
        - [1. 有序列表](#1-有序列表)
        - [2. 无序列表](#2-无序列表)
    - [引用](#引用)
    - [任务列表](#任务列表)
- [高级格式](#高级格式)
    - [折叠](#折叠)
    - [脚注](#脚注)
    - [警报](#警报)
    - [代码块](#代码块)
    - [关系图](#关系图)
        - [1. 时序图](#1-时序图)

# 基本格式

## 标题

### 0x01 标题1

### 0x02 标题2

### 0x03 标题3

### 0x04 标题4

## 列表

### 1. 有序列表

1. 有序列表1
2. 有序列表2
3. 有序列表3

### 2. 无序列表

- 无序列表1
- 无序列表2
- 无序列表3

## 引用

> 引用内容

## 任务列表

- [x] 任务1
- [ ] 任务2
- [ ] 任务3

## 脚注

这是一个脚注[^1]

这是一个脚注[^2]

## 警报

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

# 高级格式

## 表格

| 1 | 2 | 3 |
|---|---|---|
| 4 | 5 | 6 |

对齐方式

| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| git status   |   git status   |    git status |
| git diff     |    git diff    |      git diff |

## 折叠

<details>
<summary>Tips for collapsed sections</summary>


You can add text within a collapsed section.

You can add an image or a code block, too.

```ruby

   puts "Hello World"
   
```

</details>

## 代码块

```
print("hello world")
```

```python
print("hello world")
```

## 关系图

### 1. 时序图

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

[^1]: 这是一个脚注1的内容

[^2]: 这是一个脚注2的内容