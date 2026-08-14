---
title: "PhotoshopPackage クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Summary:** Represents Adobe Photoshop namespace.

**Module:** [aspose.psd.xmp.schemas.photoshop](/psd/python-net/aspose.psd.xmp.schemas.photoshop/)

**Full Name:** aspose.psd.xmp.schemas.photoshop.PhotoshopPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PhotoshopPackage()](#PhotoshopPackage__1) | PhotoshopPackage クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| URGENCY_MAX [static] | int | r | 緊急度の最大値です。 |
| URGENCY_MIN [static] | int | r | 緊急度の最小値です。 |
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
| [set_authors_position(authors_position)](#set_authors_position_authors_position_5) | 作者の位置を設定します。 |
| [set_caption_writer(caption_writer)](#set_caption_writer_caption_writer_6) | キャプションの作成者を設定します。 |
| [set_category(category)](#set_category_category_7) | カテゴリを設定します。 |
| [set_city(city)](#set_city_city_8) | 都市を設定します。 |
| [set_color_mode(color_mode)](#set_color_mode_color_mode_9) | カラーモードを設定します。 |
| [set_country(country)](#set_country_country_10) | 国を設定します。 |
| [set_created_date(created_date)](#set_created_date_created_date_11) | 作成日を設定します。 |
| [set_credit(credit)](#set_credit_credit_12) | クレジットを設定します。 |
| [set_document_ancestors(ancestors)](#set_document_ancestors_ancestors_13) | ドキュメントの祖先を設定します。 |
| [set_headline(headline)](#set_headline_headline_14) | 見出しを設定します。 |
| [set_history(history)](#set_history_history_15) | 履歴を設定します。 |
| [set_icc_profile(icc_profile)](#set_icc_profile_icc_profile_16) | ICC プロファイルを設定します。 |
| [set_instructions(instructions)](#set_instructions_instructions_17) | 指示を設定します。 |
| [set_source(source)](#set_source_source_18) | ソースを設定します。 |
| [set_state(state)](#set_state_state_19) | 状態を設定します。 |
| [set_supplemental_categories(supplemental_categories)](#set_supplemental_categories_supplemental_categories_20) | 補足カテゴリを設定します。 |
| [set_transmission_reference(transmission_reference)](#set_transmission_reference_transmission_reference_21) | 送信参照を設定します。 |
| [set_urgency(urgency)](#set_urgency_urgency_22) | 緊急度を設定します。 |
| [set_value(key, value)](#set_value_key_value_23) | 値を設定します。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | XMP タイプ値を設定します。 |


### Constructor: PhotoshopPackage() {#PhotoshopPackage__1}


```
 PhotoshopPackage() 
```

PhotoshopPackage クラスの新しいインスタンスを初期化します

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


### Method: set_authors_position(authors_position) {#set_authors_position_authors_position_5}


```
 set_authors_position(authors_position) 
```

作者の位置を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| authors_position | string | 著者の位置です。 |

### Method: set_caption_writer(caption_writer) {#set_caption_writer_caption_writer_6}


```
 set_caption_writer(caption_writer) 
```

キャプションの作成者を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| caption_writer | string | キャプションライターです。 |

### Method: set_category(category) {#set_category_category_7}


```
 set_category(category) 
```

カテゴリを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| カテゴリ | string | カテゴリです。 |

### Method: set_city(city) {#set_city_city_8}


```
 set_city(city) 
```

都市を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 都市 | string | 都市名です。 |

### Method: set_color_mode(color_mode) {#set_color_mode_color_mode_9}


```
 set_color_mode(color_mode) 
```

カラーモードを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | カラーモードです。 |

### Method: set_country(country) {#set_country_country_10}


```
 set_country(country) 
```

国を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 国 | string | 国です。 |

### Method: set_created_date(created_date) {#set_created_date_created_date_11}


```
 set_created_date(created_date) 
```

作成日を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| created_date | datetime | 作成日です。 |

### Method: set_credit(credit) {#set_credit_credit_12}


```
 set_credit(credit) 
```

クレジットを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| クレジット | string | クレジットです。 |

### Method: set_document_ancestors(ancestors) {#set_document_ancestors_ancestors_13}


```
 set_document_ancestors(ancestors) 
```

ドキュメントの祖先を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 先祖 | string | 先祖です。 |

### Method: set_headline(headline) {#set_headline_headline_14}


```
 set_headline(headline) 
```

見出しを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 見出し | string | 見出しです。 |

### Method: set_history(history) {#set_history_history_15}


```
 set_history(history) 
```

履歴を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 履歴 | string | 履歴です。 |

### Method: set_icc_profile(icc_profile) {#set_icc_profile_icc_profile_16}


```
 set_icc_profile(icc_profile) 
```

ICC プロファイルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| icc_profile | string | ICCプロファイルです。 |

### Method: set_instructions(instructions) {#set_instructions_instructions_17}


```
 set_instructions(instructions) 
```

指示を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 手順 | string | 手順です。 |

### Method: set_source(source) {#set_source_source_18}


```
 set_source(source) 
```

ソースを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source | string | ソースです。 |

### Method: set_state(state) {#set_state_state_19}


```
 set_state(state) 
```

状態を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 州 | string | 状態。 |

### Method: set_supplemental_categories(supplemental_categories) {#set_supplemental_categories_supplemental_categories_20}


```
 set_supplemental_categories(supplemental_categories) 
```

補足カテゴリを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| supplemental_categories | string | 補足カテゴリ。 |

### Method: set_transmission_reference(transmission_reference) {#set_transmission_reference_transmission_reference_21}


```
 set_transmission_reference(transmission_reference) 
```

送信参照を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| transmission_reference | string | 送信参照。 |

### Method: set_urgency(urgency) {#set_urgency_urgency_22}


```
 set_urgency(urgency) 
```

緊急度を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| urgency | int | 緊急度。 |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 追加された値で識別されるキーの文字列表現です。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 追加する値。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

XMP タイプ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 設定された値で識別されるキーの文字列表現。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 設定する値。 |

