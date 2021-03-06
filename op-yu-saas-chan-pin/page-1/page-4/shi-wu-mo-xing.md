# 事物模型

## 事件的产生

在GrowingIO中将<mark style="color:green;">**用户的各种行为称之为事件**</mark>，事件的产生遵循以下过程：

1. GrowingIO的SDK在客户端通过监听等手段捕获用户行为
2. SDK将用户行为转化为”事件“消息，并发送到GrowingIO服务器

## 事件的构成

一个完整的事件应该由以下几个部分组成:

▷ 用户信息(WHO)：描述事件发生的对象，如用户的ID

▷ 时间信息(WHEN)：描述事件发生的时间

▷ 行为信息(WHAT)：描述用户发生了什么行为，产生了什么事件

▷ 行为信息对象(HOW)：描述用户的行为发生在哪些对象上，比如点击了”按钮“，浏览了”商品“

## 采集事件类型

按照事件采集方式的不同，我们将事件分为两大类：‌

### 无埋点事件

‌无埋点事件是指用户无需额外开发任何代码，通过集成 GrowingIO SDK ，自动采集生成的事件‌

