---
title: "LclrResource クラス"
type: docs
weight: 470
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) クラスの新しいインスタンスを初期化します。 |
| [LclrResource(color)](#LclrResource_color_2) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) クラスの新しいインスタンスを初期化します。 |
| [LclrResource(data)](#LclrResource_data_3) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | レイヤーの色を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) クラスの新しいインスタンスを初期化します。

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | 色。 |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | リソース データ。 |

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

