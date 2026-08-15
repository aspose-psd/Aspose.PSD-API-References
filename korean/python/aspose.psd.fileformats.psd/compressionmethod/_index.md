---
title: "CompressionMethod 열거형"
type: docs
weight: 2410
url: /ko/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

이미지 데이터에 사용되는 압축 방식을 정의합니다.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **멤버 이름** | **설명** |
| :- | :- |
| RAW | 압축 없음. 이미지 데이터가 RGBA 평면 순서로 원시 바이트 형태로 저장됩니다.<br/>            즉, 먼저 모든 R 데이터가 기록되고, 그 다음 G, 그 다음 B, 마지막으로 A 데이터가 기록됩니다. |
| RLE | RLE 압축된 이미지 데이터는 모든 스캔 라인(행 * 채널)의 바이트 수로 시작하며, 각<br/> 카운트는 두 바이트 값으로 저장됩니다. RLE 압축 데이터가 뒤따르며, 각 스캔 라인은 별도로 압축됩니다.<br/> RLE 압축은 Macintosh ROM 루틴 PackBits와 TIFF 표준에서 사용되는 동일한 압축 알고리즘입니다. |
| ZIP_WITH_PREDICTION | ZIP 예측 없이. |
| ZIP_WITH_PREDICTION | ZIP 예측 포함. |
