---
title: "IPartialRawDataLoader"
second_title: "Java용 Aspose.PSD API 참조"
description: "부분 데이터 로더입니다."
type: docs
weight: 133
url: /ko/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

부분 데이터 로더입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | 로드된 데이터를 처리합니다. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | 로드된 데이터를 처리합니다. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


로드된 데이터를 처리합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 데이터 사각형. |
| 데이터 | byte[] | 원시 데이터. |
| start | [Point](../../com.aspose.psd/point) | 시작 데이터 포인트. (left,top)과 같지 않으면 전체 사각형이 아님을 의미합니다. |
| end | [Point](../../com.aspose.psd/point) | 끝 데이터 포인트. (right,bottom)과 같지 않으면 전체 사각형이 아님을 의미합니다. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


로드된 데이터를 처리합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 데이터 사각형. |
| 데이터 | byte[] | 원시 데이터. |
| start | [Point](../../com.aspose.psd/point) | 시작 데이터 포인트. (left,top)과 같지 않으면 전체 사각형이 아님을 의미합니다. |
| end | [Point](../../com.aspose.psd/point) | 끝 데이터 포인트. (right,bottom)과 같지 않으면 전체 사각형이 아님을 의미합니다. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

