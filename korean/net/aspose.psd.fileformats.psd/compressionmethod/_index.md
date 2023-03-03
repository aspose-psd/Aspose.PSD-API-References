---
title: Enum CompressionMethod
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.CompressionMethod 열거형. 이미지 데이터에 사용되는 압축 방법을 정의합니다.
type: docs
weight: 1620
url: /ko/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

이미지 데이터에 사용되는 압축 방법을 정의합니다.

```csharp
public enum CompressionMethod : short
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Raw | `0` | 압축 없음. RGBA 평면 순서로 원시 바이트로 저장된 이미지 데이터입니다. |
| RLE | `1` | RLE 압축 이미지 데이터는 각 스캔 라인(행 * 채널)에 대한 바이트 수로 시작하며 각 수는 2바이트 값으로 저장됩니다. 각 스캔 라인이 개별적으로 압축된 RLE 압축 데이터가 이어집니다. RLE 압축은 Macintosh ROM 루틴 PackBits 및 TIFF 표준에서 사용하는 것과 동일한 압축 알고리즘입니다. |
| ZipWithoutPrediction | `2` | 예측 없는 ZIP. |
| ZipWithPrediction | `3` | ZIP(예측 포함). |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 집회 [Aspose.PSD](../../)


