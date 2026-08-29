---
title: "ILayerResourceLoader"
second_title: "Java용 Aspose.PSD API 참조"
description: "레이어 리소스 로더."
type: docs
weight: 32
url: /ko/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

레이어 리소스 로더.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | 지정된 StreamContainer에서 레이어 리소스를 로드할 수 있는지 여부를 결정합니다. |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)을 로드합니다. |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


지정된 StreamContainer에서 레이어 리소스를 로드할 수 있는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| psdVersion | int | PSD 버전. |

**Returns:**
boolean - 지정된 StreamContainer에서 레이어 리소스를 로드할 수 있으면 true, 그렇지 않으면 false.
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 로드할 스트림 컨테이너입니다. |
| psdVersion | int | PSD 버전. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
