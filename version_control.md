# 版本管理
为了方便相关人员对于需求推进、问题描述、以及影响范围等基于一个共同约定进行描述，拟定如下版本约定。

## 预期版本号

> x.0.0.000

```mermaid
graph TD;
x.0.0.000 --"x._._.___"--> A["大版本"]
x.0.0.000 --"_.0._.___"--> B["milestone号"]
x.0.0.000 --"_._.0.___"--> C["sprint号"]
x.0.0.000 --"_._._.0000"--> D["编译号/发布号"]
```

## 参考方案

[《SprintSCM发布方案》](https://share.weiyun.com/5fA31tv)

## 现有情况
### 环境
1. DEV
2. TEST
3. BAT
4. PRE
5. PROD

### 产品 & 版本
1. 乐乎公寓APP
    * android：3.0.4
    * ios：3.0.4
2. 公寓管家APP
    * android：3.0.3
    * iOS：3.0.3
3. 公寓管家web端：3.0.35
4. 公寓管家客户端：3.0.13
5. 找房小程序：2.1.9
6. 电商小程序：2.0.9
7. 活动小程序：2.1.7
8. 官网（没有版本）

## 现有调整

1. 乐乎公寓APP
    * android：3.0.4 -> <font color="Hotpink">3.1.0</font>
    * ios：3.0.4 -> <font color="Hotpink">3.1.0</font>
2. 公寓管家APP
    * android：3.0.3 -> <font color="Hotpink">3.1.0</font>
    * iOS：3.0.3 -> <font color="Hotpink">3.1.0</font>
3. 公寓管家web端：3.0.35 -> <font color="Hotpink">3.1.0</font>
4. 公寓管家客户端：3.0.13 -> <font color="Hotpink">3.1.0</font>
5. 找房小程序：2.1.9 -> **2.2.0**（<font color="Hotpink">3.1.0</font>）
6. 电商小程序：2.0.9 -> **2.1.0**（<font color="Hotpink">3.1.0</font>）
7. 活动小程序：2.1.7 -> **2.2.0**（<font color="Hotpink">3.1.0</font>）
8. 官网（没有版本） -> **2.0.0**（<font color="Hotpink">3.1.0</font>）