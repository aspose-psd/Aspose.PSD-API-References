---
title: "열거형 CompressionMethod"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod 열거형. 이미지 데이터에 사용되는 압축 방법을 정의합니다"
type: docs
weight: 1630
url: /ko/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

이미지 데이터에 사용되는 압축 방식을 정의합니다.

```csharp
public enum CompressionMethod : short
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Raw | `0` | 압축 없음. 이미지 데이터가 RGBA 평면 순서의 원시 바이트로 저장됩니다. 즉, 먼저 모든 R 데이터가 기록되고, 그 다음 G, 그 다음 B, 마지막으로 A 데이터가 기록됩니다. |
| RLE | `1` | RLE 압축된 이미지 데이터는 모든 스캔 라인(행 * 채널)의 바이트 수로 시작하며, 각 카운트는 2바이트 값으로 저장됩니다. 그 뒤에 RLE 압축 데이터가 따라오며, 각 스캔 라인은 별도로 압축됩니다. RLE 압축은 Macintosh ROM 루틴 PackBits와 TIFF 표준에서 사용되는 동일한 압축 알고리즘입니다. |
| ZipWithoutPrediction | `2` | 예측 없이 ZIP. |
| ZipWithPrediction | `3` | 예측을 사용한 ZIP. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


