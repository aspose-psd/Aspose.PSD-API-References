---
title: "IOSTypeStructureLoader"
second_title: "Java용 Aspose.PSD API 참조"
description: "리소스 로더입니다."
type: docs
weight: 84
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 리소스 로더입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | 지정된 StreamContainer에서 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 리소스를 로드할 수 있는지 여부를 결정합니다. |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)를 로드합니다. |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


지정된 StreamContainer에서 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 리소스를 로드할 수 있는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

**Returns:**
boolean - 지정된 StreamContainer에서 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 리소스를 로드할 수 있으면 true, 그렇지 않으면 false.
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 로드할 스트림 컨테이너입니다. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
