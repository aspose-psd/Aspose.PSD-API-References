---
title: Class DataStreamSupporter
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.DataStreamSupporter 수업. 데이터 스트림 컨테이너입니다.
type: docs
weight: 740
url: /ko/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

데이터 스트림 컨테이너입니다.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 개체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 개체의 데이터가 현재 캐시되어 있고 데이터 읽기가 필요하지 않은지 여부를 나타내는 값을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 데이터를 캐시하고 기본에서 추가 데이터 로드가 수행되지 않도록 합니다.[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | 객체의 데이터를 현재`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | 개체의 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |

### 또한보십시오

* class [DisposableObject](../disposableobject/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


