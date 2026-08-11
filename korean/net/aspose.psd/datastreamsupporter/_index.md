---
title: "클래스 DataStreamSupporter"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.DataStreamSupporter 클래스. 데이터 스트림 컨테이너"
type: docs
weight: 750
url: /ko/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

데이터 스트림 컨테이너.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 객체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요하지 않은지를 나타내는 값을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 데이터를 캐시하고 기본 [`DataStreamContainer`](./datastreamcontainer/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | 객체의 데이터를 현재 `DataStreamSupporter`에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | 객체 데이터를 지정된 파일 위치에 저장합니다. |

### 또 보기

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


