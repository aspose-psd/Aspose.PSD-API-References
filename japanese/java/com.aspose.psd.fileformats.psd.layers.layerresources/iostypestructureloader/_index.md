---
title: "IOSTypeStructureLoader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "リソースローダーです。"
type: docs
weight: 84
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

この [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) リソースローダーです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | 指定された StreamContainer から [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) リソースをロードできるかどうかを判断します。 |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) をロードします。 |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


指定された StreamContainer から [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) リソースをロードできるかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |

**Returns:**
boolean - 指定された StreamContainer から [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) リソースをロードできる場合は true、そうでない場合は false。
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ロード元のストリーム コンテナです。 |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
