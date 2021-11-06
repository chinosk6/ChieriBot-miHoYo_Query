# Chieri Bot miHoYo模块

- 数据获取部分由[YuanShen_User_Info](https://github.com/Womsxd/YuanShen_User_Info)修改而来
- 此模块已实装至[Chieri Bot](https://space.bilibili.com/697847106)



# 调用方法

#### 准备阶段

- 将米游社`cookie` (cookie获取方法请参考:[YuanShen_User_Info](https://github.com/Womsxd/YuanShen_User_Info)) 添加至`Genshin_query/YuanShen_User_Info/mys_cookies.db`内, 可以添加多个, 以便触发30次的限制后切换cookie

#### 调用

- 参考`run.py`

```python
import Genshin_query

# 原神个人信息
Genshin_query.functions.generate_genshin_baseinfo("米游社id")

# 原神深境螺旋
Genshin_query.functions.generate_genshin_sjlxinfo("米游社id")

# 崩坏三个人信息
Genshin_query.functions.generate_honkai_userinfo("米游社id")

# 以上函数返回值均为图片生成后的绝对位置
```



 # 效果预览

- 原神个人信息

![](https://github.com/chinosk114514/ChieriBot-miHoYo_Query/blob/master/example_ys_info.jpg?raw=true)

- 原神深渊信息

![](https://github.com/chinosk114514/ChieriBot-miHoYo_Query/blob/master/example_ys_abyss.jpg?raw=true)

- 崩坏三信息

![](https://github.com/chinosk114514/ChieriBot-miHoYo_Query/blob/master/example_bh3.jpg?raw=true)