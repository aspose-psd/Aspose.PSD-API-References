---
title: "JpegLsInterleaveMode 열거형"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Jpeg.JpegLsInterleaveMode 열거형. 다중 구성 요소 색상 픽셀 데이터에 대한 인터리브 모드를 정의합니다."
type: docs
weight: 1520
url: /ko/net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/
---
{{< psd/tize >}}
## JpegLsInterleaveMode enumeration

다중 구성 요소(색상) 픽셀 데이터에 대한 인터리브 모드를 정의합니다.

```csharp
public enum JpegLsInterleaveMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 데이터가 인코딩되어 구성 요소별로 저장됩니다: RRRGGGBBB. |
| Line | `1` | 인터리브 모드는 라인 단위입니다. 각 구성 요소의 전체 라인이 다음 라인으로 이동하기 전에 인코딩됩니다. |
| Sample | `2` | 데이터는 샘플 단위로 인코딩되고 저장됩니다. 컬러 이미지의 경우 이 형식은 RGBRGBRGB와 같습니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


