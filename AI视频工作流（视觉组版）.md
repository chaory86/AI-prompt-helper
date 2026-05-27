# AI视频工作流（视觉组版）

# 示范案例

# 1\.利用白色帐篷模板生成品牌贴图

## ①\.在网盘提取出白色帐篷图片，可以上传多张参考视角 。网盘链接（Y:\\平面设计组资料包\\D 图片整理包\\折叠帐篷5套组白色）。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=ZmQ5OTQyZDhmMGJiNjdlMWJhMDI2ZGQyZGQyY2Y5NzdfOTY4NjYyYjcwNjUxNDFkYTQ0N2U4NWQxYjIyOWEyNTNfSUQ6NzYyMDI1NDQ4MjQyMDgyOTEyN18xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)

## ②\.上传到tapnow平台（https://app\.tapnow\.ai/home），模型选择**Banana Pro，关键词逻辑：****主体\+ 视觉与品牌设计\+修改约束**

### 1\.锁定载体（基础物理参数）

类型：10×10ft 标准折叠帐篷

高度：3\.35m

### 2\.**定义视觉与品牌（核心设计要求）**

主色：红色

品牌元素：印有品牌标识 “Eat the Ball” 和标语 “eat smart, feel good”

### 3\.限定修改范围（关键约束条件）

核心约束：**仅替换帐篷顶部的白色面料**

作用：强调 “只改顶部那块白色布”，帐篷的支架、侧面布料、结构等其他部分保持原样，精准控制修改范围，不做额外变更。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=ZWI0ZDQwZDRhZDlkOGU2YzBlZmNhMGUwNTNmNzRkYjVfYjUyMGZhZjkyYjhiOTJlMWQ5ODJjNTc5OWRmMDkxYzNfSUQ6NzYyMDI1NTg3NjI5NzAzNDY5M18xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)



# 2\.平面品牌贴图转矢量并重新贴回三维模型

## ①\.根据生成的产品品牌贴图上传到tapnow平台，模型选择**Banana Pro，**提取帐篷贴图的平面信息

AI关键词：提取图中折叠帐篷表面的完整图案设计，生成用于印刷生产的平面展开图。忽略 3D 结构、透视、光照、阴影和黑色背景，仅保留帐篷布料上的视觉元素。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=YWE2MGE0NTJmYzFhNThjMTY0YWNlYTk2YWU1MzUwOWRfZjkzYTlhMDA3ZWQ5ODQwYmM1NDExY2ZmY2M4MTk1YzFfSUQ6NzYyMDMyODY2NzA4ODYzNzEzMl8xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)

## ②\.生成的平面图，再利用lovart平台（Lovart\.com ）变成矢量图片。

将上一步生成的平面展开图上传，通过矢量转换功能，将位图图案转换为**可编辑的矢量图形**（如 SVG/AI 格式），保证印刷精度与后期可修改性。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=MGI2ZmExOWZhMGRjM2I4N2VlNTU2MmUzNzViOTU1Y2FfY2Y2OTUyZDkxMTk3ZjE1MTFjMTE2YTE5Njk5NGI3YmRfSUQ6NzYyMDMyOTA3Njg1MTAzNTA5NV8xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)



## ③\.在将矢量图片贴到ps的UV里面

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=MzEyODZkMTM3MzgwZjJhOWE3ZTA5YjUwY2E5YTE4MDVfYjJjMzlmZjNmNGEwZGY3ZjhkODI5MDM4Y2ZlZjYwNWRfSUQ6NzYyMDMyOTkwNDI4Njc0NzgzNl8xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)



## ④\.再利用UV贴图重新赋予到三维模型上渲染不同角度。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=OTBiNzUwZDBjYWY2ODQ2N2ZlZWUwNzdlODdjNGY5MGZfYzA0NjExZjA0ZThhNzMyNTA1ZDM2ZGMzZDNhYmEzYmFfSUQ6NzYyMDMzMDc3NTU3ODA3MDIxN18xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=MzQxYzBmMDM1ODQyOTEwMmExYzNjNTY3YzgwN2VlNzVfMTU4N2FjYmNjY2NkZjhmZjU2ZTM4NWYwODcxNDczMDNfSUQ6NzYyMDMzMDg2MzM3Mjk5NTc3OV8xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)

# 3\.利用三维生成品牌帐篷图再生成场景

## **上传到tapnow平台，模型选择Banana Pro，****关键词逻辑：场景氛围 \+ 主体定位 \+ 内容细节 \+ 构图要求**

### **①**\.先定整体场景（大环境框架）

地点：城市公园 / 市区户外广场

背景：茂密绿树 \+ 现代建筑

场景形态：一整排标准化折叠帐篷，构成城市市集摊位集群

### ②\.再定主体帐篷（你的核心目标）

尺寸：10×10ft 折叠帐篷，高度3\.35m

外观：沿用已生成的帐篷结构与品牌图案

位置：置于整排帐篷的中间位置，作为视觉焦点

### ③\.每个摊位摆什么（内容逻辑）

核心帐篷：售卖美式户外快餐饮品，可细化描述为「帐篷下陈列烤架、饮料瓶、调味酱，工作人员现场制作餐品」，风格定位为便捷、美味的街头美食

其他帐篷：分别售卖水果、蔬菜、文创小商品，各帐篷带有对应配色与宣传标语，形成差异化品类展示

### ④\.最后定视角（构图要求）

视角：高角度俯拍 / 鸟瞰视角

拍摄：从高处往下拍

效果：完整拍到整个市集区域，展现摊位布局与人流动态

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=Mjk4OTBlNTIzYTdiMGEzNWE3MDkzNTI5ODFiYjQyZWZfNzg1Y2JlMGNjZTY2OTkwNDVlNjQ2NjJiZWQ4ODVlNDVfSUQ6NzYyMDI2MTI1MTYzMzY3OTU0OF8xNzc5NzU2Nzc3OjE3Nzk4NDMxNzdfVjM)

# 4\.利用生成的图片再生视频

## **上传到tapnow平台，模型选择Kling O1/即梦pro  ，****关键词逻辑：镜头描述逻辑**

**基础镜头**：镜头微微环绕红色品牌帐篷。

**可选进阶镜头**：

- 镜头从市集全景缓慢拉近至红色帐篷，聚焦餐品制作与工作人员互动

- 镜头从红色帐篷拉远，完整展示市集摊位布局与人流动态

- 环绕镜头 \+ 轻微推拉结合，营造沉浸式市集氛围

\[视频增强\-1773632802983\.mp4\]

