---
title: "ILayerResourceLoader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "レイヤーリソースローダーです。"
type: docs
weight: 32
url: /ja/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

レイヤーリソースローダーです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | 指定された StreamContainer からレイヤー リソースをロードできるかどうかを判断します。 |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) をロードします。 |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


指定された StreamContainer からレイヤー リソースをロードできるかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psdVersion | int | PSD バージョン。 |

**Returns:**
boolean - 指定された StreamContainer からレイヤー リソースをロードできる場合は true、そうでない場合は false。
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ロード元のストリーム コンテナです。 |
| psdVersion | int | PSD バージョン。 |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
