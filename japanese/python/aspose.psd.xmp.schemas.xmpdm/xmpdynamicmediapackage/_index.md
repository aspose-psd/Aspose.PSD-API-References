---
title: "XmpDynamicMediaPackage クラス"
type: docs
weight: 70
url: /ja/python-net/aspose.psd.xmp.schemas.xmpdm/xmpdynamicmediapackage/
---

**Summary:** Represents XMP Dynamic Media namespace.

**Module:** [aspose.psd.xmp.schemas.xmpdm](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/)

**Full Name:** aspose.psd.xmp.schemas.xmpdm.XmpDynamicMediaPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpDynamicMediaPackage()](#XmpDynamicMediaPackage__1) | XmpDynamicMediaPackage クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| namespace_uri | string | r | 名前空間 URI を取得します。 |
| プレフィックス | string | r | プレフィックスを取得します。 |
| xml_namespace | string | r | XML 名前空間を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 文字列プロパティを追加します。 |
| clear() | このインスタンスをクリアします。 |
| [contains_key(key)](#contains_key_key_2) | 指定されたキーがキーを含むかどうかを判定します。 |
| [get_xml_value()](#get_xml_value__3) | XMP 値を XML 表現に変換します。 |
| [remove(key)](#remove_key_4) | 指定されたキーの値を削除します。 |
| [set_abs_peak_audio_file_path(uri)](#set_abs_peak_audio_file_path_uri_5) | 絶対ピーク音声ファイルのパスを設定します。 |
| [set_alblum(album)](#set_alblum_album_6) | alblum を設定します。 |
| [set_alt_tape_name(alt_tape_name)](#set_alt_tape_name_alt_tape_name_7) | 代替テープ名を設定します。 |
| [set_alt_time_code(timecode)](#set_alt_time_code_timecode_8) | 代替タイムコードを設定します。 |
| [set_artist(artist)](#set_artist_artist_9) | アーティストを設定します。 |
| [set_audio_channel_type(audio_channel_type)](#set_audio_channel_type_audio_channel_type_10) | オーディオチャンネルタイプを設定します。 |
| [set_audio_sample_rate(rate)](#set_audio_sample_rate_rate_11) | オーディオサンプルレートを設定します。 |
| [set_audio_sample_type(audio_sample_type)](#set_audio_sample_type_audio_sample_type_12) | オーディオサンプルタイプを設定します。 |
| [set_camera_angle(camera_angle)](#set_camera_angle_camera_angle_13) | カメラ角度を設定します。 |
| [set_camera_label(camera_label)](#set_camera_label_camera_label_14) | カメララベルを設定します。 |
| [set_camera_move(camera_move)](#set_camera_move_camera_move_15) | カメラの動きを設定します。 |
| [set_client(client)](#set_client_client_16) | クライアントを設定します。 |
| [set_comment(comment)](#set_comment_comment_17) | コメントを設定します。 |
| [set_composer(composer)](#set_composer_composer_18) | 作曲者を設定します。 |
| [set_director(director)](#set_director_director_19) | 監督を設定します。 |
| [set_director_photography(director_photography)](#set_director_photography_director_photography_20) | 撮影監督を設定します。 |
| [set_duration(duration)](#set_duration_duration_21) | 期間を設定します。 |
| [set_engineer(engineer)](#set_engineer_engineer_22) | エンジニアを設定します。 |
| [set_file_data_rate(rate)](#set_file_data_rate_rate_23) | ファイルデータレートを設定します。 |
| [set_genre(genre)](#set_genre_genre_24) | ジャンルを設定します。 |
| [set_good(good)](#set_good_good_25) | 良さを設定します。 |
| [set_instrument(instrument)](#set_instrument_instrument_26) | 楽器を設定します。 |
| [set_intro_time(intro_time)](#set_intro_time_intro_time_27) | イントロ時間を設定します。 |
| [set_key(key)](#set_key_key_28) | オーディオの音楽キーを設定します。 |
| [set_log_comment(comment)](#set_log_comment_comment_29) | ユーザーのログコメントを設定します。 |
| [set_value(key, value)](#set_value_key_value_30) | 値を設定します。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_31) | XMP タイプ値を設定します。 |


### Constructor: XmpDynamicMediaPackage() {#XmpDynamicMediaPackage__1}


```
 XmpDynamicMediaPackage() 
```

XmpDynamicMediaPackage クラスの新しいインスタンスを初期化します

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

文字列プロパティを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 追加された値で識別されるキーの文字列表現です。 |
| 値 | string | 文字列値です。 |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

指定されたキーがキーを含むかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | チェックするキーです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたキーがキーを含む場合は true を返します。 |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP 値を XML 表現に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XML 表現に変換された XMP 値を返します。 |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

指定されたキーの値を削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 削除された値で識別されるキーの文字列表現です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたキーの値が削除された場合は true を返します。 |


### Method: set_abs_peak_audio_file_path(uri) {#set_abs_peak_audio_file_path_uri_5}


```
 set_abs_peak_audio_file_path(uri) 
```

絶対ピーク音声ファイルのパスを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| uri | string | ファイルのピークオーディオファイルへの絶対パスです。 |

### Method: set_alblum(album) {#set_alblum_album_6}


```
 set_alblum(album) 
```

alblum を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| album | string | アルバムです。 |

### Method: set_alt_tape_name(alt_tape_name) {#set_alt_tape_name_alt_tape_name_7}


```
 set_alt_tape_name(alt_tape_name) 
```

代替テープ名を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| alt_tape_name | string | 代替テープ名です。 |

### Method: set_alt_time_code(timecode) {#set_alt_time_code_timecode_8}


```
 set_alt_time_code(timecode) 
```

代替タイムコードを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| timecode | [Timecode](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/timecode) | タイムコードです。 |

### Method: set_artist(artist) {#set_artist_artist_9}


```
 set_artist(artist) 
```

アーティストを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| アーティスト | string | アーティストです。 |

### Method: set_audio_channel_type(audio_channel_type) {#set_audio_channel_type_audio_channel_type_10}


```
 set_audio_channel_type(audio_channel_type) 
```

オーディオチャンネルタイプを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| audio_channel_type | [AudioChannelType](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/audiochanneltype) | オーディオチャンネルタイプです。 |

### Method: set_audio_sample_rate(rate) {#set_audio_sample_rate_rate_11}


```
 set_audio_sample_rate(rate) 
```

オーディオサンプルレートを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| レート | int | オーディオサンプルレートです。 |

### Method: set_audio_sample_type(audio_sample_type) {#set_audio_sample_type_audio_sample_type_12}


```
 set_audio_sample_type(audio_sample_type) 
```

オーディオサンプルタイプを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| audio_sample_type | [AudioSampleType](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/audiosampletype) | オーディオサンプルタイプです。 |

### Method: set_camera_angle(camera_angle) {#set_camera_angle_camera_angle_13}


```
 set_camera_angle(camera_angle) 
```

カメラ角度を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| camera_angle | string | カメラの角度です。 |

### Method: set_camera_label(camera_label) {#set_camera_label_camera_label_14}


```
 set_camera_label(camera_label) 
```

カメララベルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| camera_label | string | カメラのラベルです。 |

### Method: set_camera_move(camera_move) {#set_camera_move_camera_move_15}


```
 set_camera_move(camera_move) 
```

カメラの動きを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| camera_move | string | カメラの動きです。 |

### Method: set_client(client) {#set_client_client_16}


```
 set_client(client) 
```

クライアントを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| クライアント | string | クライアントです。 |

### Method: set_comment(comment) {#set_comment_comment_17}


```
 set_comment(comment) 
```

コメントを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| コメント | string | コメントです。 |

### Method: set_composer(composer) {#set_composer_composer_18}


```
 set_composer(composer) 
```

作曲者を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| コンポーザー | string | コンポーザーです。 |

### Method: set_director(director) {#set_director_director_19}


```
 set_director(director) 
```

監督を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 監督 | string | 監督です。 |

### Method: set_director_photography(director_photography) {#set_director_photography_director_photography_20}


```
 set_director_photography(director_photography) 
```

撮影監督を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| director_photography | string | 撮影監督です。 |

### Method: set_duration(duration) {#set_duration_duration_21}


```
 set_duration(duration) 
```

期間を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| duration | [Time](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/time) | 期間。 |

### Method: set_engineer(engineer) {#set_engineer_engineer_22}


```
 set_engineer(engineer) 
```

エンジニアを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| エンジニア | string | エンジニアです。 |

### Method: set_file_data_rate(rate) {#set_file_data_rate_rate_23}


```
 set_file_data_rate(rate) 
```

ファイルデータレートを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rate | [Rational](/psd/python-net/aspose.psd.xmp.types.derived/rational/) | ファイルのデータレート（メガバイト/秒）です。 |

### Method: set_genre(genre) {#set_genre_genre_24}


```
 set_genre(genre) 
```

ジャンルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ジャンル | string | ジャンルです。 |

### Method: set_good(good) {#set_good_good_25}


```
 set_good(good) 
```

良さを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 良好 | bool | <c>true</c> に設定すると、ショットはキーパーになります。 |

### Method: set_instrument(instrument) {#set_instrument_instrument_26}


```
 set_instrument(instrument) 
```

楽器を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 楽器 | string | その楽器。 |

### Method: set_intro_time(intro_time) {#set_intro_time_intro_time_27}


```
 set_intro_time(intro_time) 
```

イントロ時間を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| intro_time | [Time](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/time) | イントロ時間。 |

### Method: set_key(key) {#set_key_key_28}


```
 set_key(key) 
```

オーディオの音楽キーを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | オーディオの音階です。次のいずれか: C, C#, D, D#, E, F, F#, G, G#, A, A#, B。 |

### Method: set_log_comment(comment) {#set_log_comment_comment_29}


```
 set_log_comment(comment) 
```

ユーザーのログコメントを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| コメント | string | コメントです。 |

### Method: set_value(key, value) {#set_value_key_value_30}


```
 set_value(key, value) 
```

値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 追加された値で識別されるキーの文字列表現です。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 追加する値。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_31}


```
 set_xmp_type_value(key, value) 
```

XMP タイプ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 設定された値で識別されるキーの文字列表現。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 設定する値。 |

