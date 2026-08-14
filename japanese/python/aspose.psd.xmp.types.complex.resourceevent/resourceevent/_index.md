---
title: "ResourceEvent クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Summary:** Containing dimensions for a drawn object.

**Module:** [aspose.psd.xmp.types.complex.resourceevent](/psd/python-net/aspose.psd.xmp.types.complex.resourceevent/)

**Full Name:** aspose.psd.xmp.types.complex.resourceevent.ResourceEvent

**Inheritance:** IXmpType, ComplexTypeBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ResourceEvent()](#ResourceEvent__1) | ResourceEvent クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| action | string | r/w | アクションを取得または設定します。 |
| action_date | datetime | r/w | アクション日付を取得または設定します。 |
| changed | string | r/w | 前回のイベント履歴以降に変更されたリソースの部分のセミコロン区切りリストを取得または設定します。 |
| instance_id | Guid | r/w | xmpMM:InstanceId の値を取得または設定します。 |
| namespace_uri | string | r | デフォルトの名前空間 URI を取得します。 |
| parameters | string | r/w | アクションの追加説明を取得または設定します。 |
| プレフィックス | string | r | プレフィックスを取得します。 |
| sofware_agent_name | string | r/w | ソフトウェアエージェント名を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 形式で含まれる文字列の値を取得します。 |


### Constructor: ResourceEvent() {#ResourceEvent__1}


```
 ResourceEvent() 
```

ResourceEvent クラスの新しいインスタンスを初期化します

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 形式で含まれる文字列の値を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XMP 形式で含まれる文字列の値を返します。 |


