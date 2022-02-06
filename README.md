# dataset_bilibili

该数据集收集代码已开源至[github](https://github.com/zhaisc2001/dataset_bilibili)。
数据集下载地址：[Google Drive](https://drive.google.com/drive/folders/1hGFAxqrJJXO9tmn43b_gDJQCoKTi_UNA?usp=sharing)

# 数据集总概
| 名称 | 标注内容 | 类型 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - |  - | - | - |
| Bilibili Daily Hot Videos | 在线视频网站哔哩哔哩单日分区流行视频与普通视频信息 | 分类 | 1500（流行）+9786(普通) | 0/1标签  | csv | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) |

其中包含文件：
## regular_pics
| 名称 | 标注内容 | 类型 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - |  - | - | - |
| regular_pics | 在线视频网站哔哩哔哩单日分区普通视频封面图片 | 分类 | 9773(普通) | 无  | jpg | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
## pop_pics
| 名称 | 标注内容 | 类型 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - |  - | - | - |
| pop_pics | 在线视频网站哔哩哔哩单日分区流行视频封面图片 | 分类 | 1500(流行) | 无  | jpg | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
## regular.json & regular.csv
| 名称 | 标注内容 | 类型 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - |  - | - | - |
| regular.json & regular.csv | 在线视频网站哔哩哔哩单日分区普通视频信息 | 分类 | 9786 | 0/1标签 | json&csv | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

| 属性名称 | 属性备注 | 属性元素数据类型 |
| - | - | - |
| video_bv | 视频bv号 | string |
|tid| 视频分区ID | int |
|get_time| 信息获取时间 | data_time |
|title| 视频标题 | string |
|channel_title | 视频分区名称 | string |
|publish_time| 视频发布时间 | echo_time  |
|authors| 视频作者 | string |
|views| 观看数量 | int |
|danmaku| 弹幕数量 | int|
|likes| 点赞数量 | int|
|coins| 硬币数量 | int|
|shares| 分享数量 | int|
|tags| 视频标签 | string |
|comment_counts| 评论数量 | int|
|description| 描述 | string|
|cover_links| 视频封面图片链接 | string|
|favorite| 收藏数量 | int|
|duration| 视频时长 | int(seconds)|
|pop| 视频是否流行 | bool |
## pop.json & pop.csv
| 名称 | 标注内容 | 类型 | 数量 | 标签格式 | 文件格式 | License |
| - | - | - | - |  - | - | - |
| pop.json & pop.csv | 在线视频网站哔哩哔哩单日分区流行视频信息 | 分类 | 1500 | 0/1标签 | json&csv | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

| 属性名称 | 属性备注 | 属性元素数据类型 |
| - | - | - |
| video_bv | 视频bv号 | string |
|tid| 视频分区ID | int |
|trending_data| 进入排行榜时间 | data_time |
|title| 视频标题 | string |
|channel_title | 视频分区名称 | string |
|publish_time| 视频发布时间 | echo_time  |
|authors| 视频作者 | string |
|views| 观看数量 | int |
|danmaku| 弹幕数量 | int|
|likes| 点赞数量 | int|
|coins| 硬币数量 | int|
|shares| 分享数量 | int|
|tags| 视频标签 | string |
|comment_counts| 评论数量 | int|
|description| 描述 | string|
|cover_links| 视频封面图片链接 | string|
|favorite| 收藏数量 | int|
|duration| 视频时长 | int(seconds)|
|scores| 视频在排行榜的流行分数，只有进入排行榜的视频可以获取该信息 | int|
|pop| 视频是否流行 | bool |

如有疑问，请联系维护者:xiangweixi@hotmail.com
