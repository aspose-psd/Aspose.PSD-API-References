---
title: IPartialRawDataLoader.Process
second_title: .NET API 참조용 Aspose.PSD
description: IPartialRawDataLoader 방법. 로드된 데이터를 처리합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd/ipartialrawdataloader/process/
---
## Process(Rectangle, byte[], Point, Point) {#process}

로드된 데이터를 처리합니다.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rectangle | Rectangle | 데이터 사각형입니다. |
| data | Byte[] | 원시 데이터. |
| start | Point | 시작 데이터 포인트. (left,top)과 같지 않으면 전체 직사각형이 아니라는 의미입니다. |
| end | Point | 종료 데이터 포인트. (right,bottom)과 같지 않으면 전체 직사각형이 아님을 의미합니다. |

### 또한보십시오

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* 네임스페이스 [Aspose.PSD](../../ipartialrawdataloader/)
* 집회 [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

로드된 데이터를 처리합니다.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rectangle | Rectangle | 데이터 사각형입니다. |
| data | Byte[] | 원시 데이터. |
| start | Point | 시작 데이터 포인트. (left,top)과 같지 않으면 전체 직사각형이 아니라는 의미입니다. |
| end | Point | 종료 데이터 포인트. (right,bottom)과 같지 않으면 전체 직사각형이 아님을 의미합니다. |
| loadOptions | LoadOptions | 로드 옵션. |

### 또한보십시오

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* 네임스페이스 [Aspose.PSD](../../ipartialrawdataloader/)
* 집회 [Aspose.PSD](../../../)


