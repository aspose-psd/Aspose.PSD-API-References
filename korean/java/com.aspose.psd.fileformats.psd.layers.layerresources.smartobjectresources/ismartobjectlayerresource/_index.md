---
title: "ISmartObjectLayerResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 파일에서 스마트 오브젝트 레이어 리소스에 대한 정보를 포함하는 ISmartObjectLayerResource 인터페이스를 정의합니다."
type: docs
weight: 18
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/ismartobjectlayerresource/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public interface ISmartObjectLayerResource extends IPlacedLayerResource
```

ISmartObjectLayerResource 인터페이스를 정의합니다. 이 인터페이스는 PSD 파일의 스마트 오브젝트 레이어 리소스에 대한 정보를 포함합니다. 또한 Adobe\\ufffd Photoshop\\ufffd 이미지에서 Sold 및 Sole 리소스를 지정하는 마크업 인터페이스이기도 합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPlacedId()](#getPlacedId--) | PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다. |
### getPlacedId() {#getPlacedId--}
```
public abstract UUID getPlacedId()
```


PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다.

값: 이 스마트 오브젝트 레이어 리소스의 고유 식별자.

**Returns:**
java.util.UUID
### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public abstract void setPlacedId(UUID value)
```


PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다.

값: 이 스마트 오브젝트 레이어 리소스의 고유 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

