---
title: "XmpDynamicMediaPackage 类"
type: docs
weight: 70
url: /zh/python-net/aspose.psd.xmp.schemas.xmpdm/xmpdynamicmediapackage/
---

**Summary:** Represents XMP Dynamic Media namespace.

**Module:** [aspose.psd.xmp.schemas.xmpdm](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/)

**Full Name:** aspose.psd.xmp.schemas.xmpdm.XmpDynamicMediaPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpDynamicMediaPackage()](#XmpDynamicMediaPackage__1) | 初始化 XmpDynamicMediaPackage 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | 字符串 | r | 获取命名空间 URI。 |
| 前缀 | 字符串 | r | 获取前缀。 |
| xml_namespace | 字符串 | r | 获取 XML 命名空间。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 添加字符串属性。 |
| clear() | 清除此实例。 |
| [contains_key(key)](#contains_key_key_2) | 确定指定的键是否包含键。 |
| [get_xml_value()](#get_xml_value__3) | 将 XMP 值转换为 XML 表示形式。 |
| [remove(key)](#remove_key_4) | 删除具有指定键的值。 |
| [set_abs_peak_audio_file_path(uri)](#set_abs_peak_audio_file_path_uri_5) | 设置绝对峰值音频文件路径。 |
| [set_alblum(album)](#set_alblum_album_6) | 设置 alblum。 |
| [set_alt_tape_name(alt_tape_name)](#set_alt_tape_name_alt_tape_name_7) | 设置备用磁带名称。 |
| [set_alt_time_code(timecode)](#set_alt_time_code_timecode_8) | 设置备用时间码。 |
| [set_artist(artist)](#set_artist_artist_9) | 设置艺术家。 |
| [set_audio_channel_type(audio_channel_type)](#set_audio_channel_type_audio_channel_type_10) | 设置音频通道类型。 |
| [set_audio_sample_rate(rate)](#set_audio_sample_rate_rate_11) | 设置音频采样率。 |
| [set_audio_sample_type(audio_sample_type)](#set_audio_sample_type_audio_sample_type_12) | 设置音频采样类型。 |
| [set_camera_angle(camera_angle)](#set_camera_angle_camera_angle_13) | 设置相机角度。 |
| [set_camera_label(camera_label)](#set_camera_label_camera_label_14) | 设置相机标签。 |
| [set_camera_move(camera_move)](#set_camera_move_camera_move_15) | 设置相机移动。 |
| [set_client(client)](#set_client_client_16) | 设置客户端。 |
| [set_comment(comment)](#set_comment_comment_17) | 设置评论。 |
| [set_composer(composer)](#set_composer_composer_18) | 设置作曲者。 |
| [set_director(director)](#set_director_director_19) | 设置导演。 |
| [set_director_photography(director_photography)](#set_director_photography_director_photography_20) | 设置摄影导演。 |
| [set_duration(duration)](#set_duration_duration_21) | 设置时长。 |
| [set_engineer(engineer)](#set_engineer_engineer_22) | 设置工程师。 |
| [set_file_data_rate(rate)](#set_file_data_rate_rate_23) | 设置文件数据速率。 |
| [set_genre(genre)](#set_genre_genre_24) | 设置流派。 |
| [set_good(good)](#set_good_good_25) | 设置良好。 |
| [set_instrument(instrument)](#set_instrument_instrument_26) | 设置乐器。 |
| [set_intro_time(intro_time)](#set_intro_time_intro_time_27) | 设置引入时间。 |
| [set_key(key)](#set_key_key_28) | 设置音频的调性。 |
| [set_log_comment(comment)](#set_log_comment_comment_29) | 设置用户的日志评论。 |
| [set_value(key, value)](#set_value_key_value_30) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_31) | 设置 XMP 类型值。 |


### Constructor: XmpDynamicMediaPackage() {#XmpDynamicMediaPackage__1}


```
 XmpDynamicMediaPackage() 
```

初始化 XmpDynamicMediaPackage 类的新实例

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

添加字符串属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | 字符串 | 字符串值。 |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

确定指定的键是否包含键。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 要检查的键。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的键包含键，则返回 true。 |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示形式。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回转换为 XML 表示形式的 XMP 值。 |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

删除具有指定键的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已删除值的 key 的字符串表示形式。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果具有指定键的值已被删除，则返回 true。 |


### Method: set_abs_peak_audio_file_path(uri) {#set_abs_peak_audio_file_path_uri_5}


```
 set_abs_peak_audio_file_path(uri) 
```

设置绝对峰值音频文件路径。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| uri | 字符串 | 文件峰值音频文件的绝对路径。 |

### Method: set_alblum(album) {#set_alblum_album_6}


```
 set_alblum(album) 
```

设置 alblum。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 专辑 | 字符串 | 该专辑。 |

### Method: set_alt_tape_name(alt_tape_name) {#set_alt_tape_name_alt_tape_name_7}


```
 set_alt_tape_name(alt_tape_name) 
```

设置备用磁带名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alt_tape_name | 字符串 | 备用磁带名称。 |

### Method: set_alt_time_code(timecode) {#set_alt_time_code_timecode_8}


```
 set_alt_time_code(timecode) 
```

设置备用时间码。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| timecode | [Timecode](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/timecode) | 时间码。 |

### Method: set_artist(artist) {#set_artist_artist_9}


```
 set_artist(artist) 
```

设置艺术家。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 艺术家 | 字符串 | 该艺术家。 |

### Method: set_audio_channel_type(audio_channel_type) {#set_audio_channel_type_audio_channel_type_10}


```
 set_audio_channel_type(audio_channel_type) 
```

设置音频通道类型。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| audio_channel_type | [AudioChannelType](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/audiochanneltype) | 音频通道类型。 |

### Method: set_audio_sample_rate(rate) {#set_audio_sample_rate_rate_11}


```
 set_audio_sample_rate(rate) 
```

设置音频采样率。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 速率 | int | 音频采样率。 |

### Method: set_audio_sample_type(audio_sample_type) {#set_audio_sample_type_audio_sample_type_12}


```
 set_audio_sample_type(audio_sample_type) 
```

设置音频采样类型。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| audio_sample_type | [AudioSampleType](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/audiosampletype) | 音频采样类型。 |

### Method: set_camera_angle(camera_angle) {#set_camera_angle_camera_angle_13}


```
 set_camera_angle(camera_angle) 
```

设置相机角度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| camera_angle | 字符串 | 相机角度。 |

### Method: set_camera_label(camera_label) {#set_camera_label_camera_label_14}


```
 set_camera_label(camera_label) 
```

设置相机标签。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| camera_label | 字符串 | 相机标签。 |

### Method: set_camera_move(camera_move) {#set_camera_move_camera_move_15}


```
 set_camera_move(camera_move) 
```

设置相机移动。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| camera_move | 字符串 | 相机移动。 |

### Method: set_client(client) {#set_client_client_16}


```
 set_client(client) 
```

设置客户端。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 客户端 | 字符串 | 客户端。 |

### Method: set_comment(comment) {#set_comment_comment_17}


```
 set_comment(comment) 
```

设置评论。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 注释 | 字符串 | 注释。 |

### Method: set_composer(composer) {#set_composer_composer_18}


```
 set_composer(composer) 
```

设置作曲者。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 作曲家 | 字符串 | 作曲家。 |

### Method: set_director(director) {#set_director_director_19}


```
 set_director(director) 
```

设置导演。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 导演 | 字符串 | 导演。 |

### Method: set_director_photography(director_photography) {#set_director_photography_director_photography_20}


```
 set_director_photography(director_photography) 
```

设置摄影导演。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| director_photography | 字符串 | 摄影导演。 |

### Method: set_duration(duration) {#set_duration_duration_21}


```
 set_duration(duration) 
```

设置时长。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| duration | [Time](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/time) | 持续时间。 |

### Method: set_engineer(engineer) {#set_engineer_engineer_22}


```
 set_engineer(engineer) 
```

设置工程师。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 工程师 | 字符串 | 工程师。 |

### Method: set_file_data_rate(rate) {#set_file_data_rate_rate_23}


```
 set_file_data_rate(rate) 
```

设置文件数据速率。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rate | [Rational](/psd/python-net/aspose.psd.xmp.types.derived/rational/) | 文件数据速率（兆字节每秒）。 |

### Method: set_genre(genre) {#set_genre_genre_24}


```
 set_genre(genre) 
```

设置流派。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流派 | 字符串 | 流派。 |

### Method: set_good(good) {#set_good_good_25}


```
 set_good(good) 
```

设置良好。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 好 | bool | 如果设置为 <c>true</c>，则该镜头是保留的。 |

### Method: set_instrument(instrument) {#set_instrument_instrument_26}


```
 set_instrument(instrument) 
```

设置乐器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 仪器 | 字符串 | 该仪器。 |

### Method: set_intro_time(intro_time) {#set_intro_time_intro_time_27}


```
 set_intro_time(intro_time) 
```

设置引入时间。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| intro_time | [Time](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/time) | 引入时间。 |

### Method: set_key(key) {#set_key_key_28}


```
 set_key(key) 
```

设置音频的调性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 音频的调性。可选项包括：C、C#、D、D#、E、F、F#、G、G#、A、A# 和 B。 |

### Method: set_log_comment(comment) {#set_log_comment_comment_29}


```
 set_log_comment(comment) 
```

设置用户的日志评论。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 注释 | 字符串 | 注释。 |

### Method: set_value(key, value) {#set_value_key_value_30}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 要添加的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_31}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 键的字符串表示形式，该键与设置的值关联。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 要设置的值。 |

