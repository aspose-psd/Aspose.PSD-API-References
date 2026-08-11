---
title: "SmartObjectProvider.ConvertToSmartObject"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SmartObjectProvider 메서드. 레이어를 포함된 스마트 오브젝트로 변환합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd/smartobjectprovider/converttosmartobject/
---
{{< psd/tize >}}
## ConvertToSmartObject(params int[]) {#converttosmartobject_1}

레이어를 임베디드 스마트 객체로 변환합니다.

```csharp
public SmartObjectLayer ConvertToSmartObject(params int[] layerNumbers)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerNumbers | Int32[] | 레이어 번호. |

### 반환 값

생성된 [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 인스턴스.

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 변환할 레이어가 없습니다. 또는 레이어 번호가 범위를 벗어났습니다. |

### 또 보기

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## ConvertToSmartObject(Layer[]) {#converttosmartobject}

레이어를 임베디드 스마트 객체로 변환합니다.

```csharp
public SmartObjectLayer ConvertToSmartObject(Layer[] layers)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 레이어 | Layer[] | 레이어들입니다. |

### 반환 값

생성된 [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 인스턴스.

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 변환할 레이어가 없습니다. |

### 또 보기

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


