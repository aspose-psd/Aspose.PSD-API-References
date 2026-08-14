---
title: "InfxResource クラス"
type: docs
weight: 420
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) クラスの新しいインスタンスを初期化します。 |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) クラスの新しいインスタンスを初期化します。 |
| [InfxResource(data)](#InfxResource_data_3) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) クラスの新しいインスタンスを初期化します。<br/>            カスタムまたは不明な値で |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| blend_interior_elements | bool | r/w | [blend interior elements] が有効かどうかを示す値を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 指定されたストリームコンテナを保存します。 |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) クラスの新しいインスタンスを初期化します。

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| blend_interior_elements | bool | <c>true</c> に設定された場合、[blend interior elements]。 |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) クラスの新しいインスタンスを初期化します。<br/>            カスタムまたは不明な値で

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | リソース データ。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

指定されたストリームコンテナを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

