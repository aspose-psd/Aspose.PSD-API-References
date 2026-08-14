---
title: "ArtBResource クラス"
type: docs
weight: 50
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/
---

**Summary:** The Artboard info data for [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ArtBResource

**Inheritance:** BaseArtboardInfoResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ArtBResource()](#ArtBResource__1) | ArtBResource クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| artboard_background_type | int | r/w | 取得または設定します [ArtBResource.artboard_background_type](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 取得または設定します [ArtBResource.color](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) のアイテムを取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | <inheritdoc /> |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: ArtBResource() {#ArtBResource__1}


```
 ArtBResource() 
```

ArtBResource クラスの新しいインスタンスを初期化します

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

