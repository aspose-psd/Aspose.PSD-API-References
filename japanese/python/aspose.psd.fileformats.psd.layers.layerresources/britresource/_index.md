---
title: "BritResource クラス"
type: docs
weight: 120
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [BritResource()](#BritResource__1) | 新しい [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) クラスのインスタンスを初期化します。 |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | 新しい [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) クラスのインスタンスを初期化します。 |
| [BritResource(bytes)](#BritResource_bytes_3) | 新しい [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) クラスのインスタンスを初期化します。<br/>            PSD フォーマットの仕様には以下の記述が含まれます：<br/>            2 明るさ<br/>            2 コントラスト<br/>            2 明るさとコントラストの平均値<br/>            1 Lab カラーのみ<br/>            これは、CgEd が使用されている最新の PSD（CS5 以降）では使用されません。CgEd は情報プロパティを保存します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| 明るさを取得または設定します。<br/>            推奨範囲 1 - 1.5<br/>            デフォルト値 = 1.15 | short | r/w | 明るさを取得または設定します。 |
| コントラスト | short | r/w | コントラストを取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| lab_color | bool | r/w | [lab color] かどうかを示す値を取得または設定します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| mean_value_for_brightness_and_contrast | short | r/w | 明るさとコントラストの平均値を取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

新しい [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) クラスのインスタンスを初期化します。

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

新しい [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 明るさを取得または設定します。<br/>            推奨範囲 1 - 1.5<br/>            デフォルト値 = 1.15 | short | 明るさです。 |
| コントラスト | short | コントラストです。 |
| mean_value_for_brightness_and_contrast | short | 明るさとコントラストの平均値です。 |
| lab_color | bool | 設定が <c>true</c> の場合 [lab color]。 |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

新しい [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) クラスのインスタンスを初期化します。<br/>            PSD フォーマットの仕様には以下の記述が含まれます：<br/>            2 明るさ<br/>            2 コントラスト<br/>            2 明るさとコントラストの平均値<br/>            1 Lab カラーのみ<br/>            これは、CgEd が使用されている最新の PSD（CS5 以降）では使用されません。CgEd は情報プロパティを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| バイト | byte | バイトです。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

リソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

