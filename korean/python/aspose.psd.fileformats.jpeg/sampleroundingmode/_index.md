---
title: "SampleRoundingMode 열거형"
type: docs
weight: 70
url: /ko/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

n비트 값을 8비트 값으로 변환하는 방법을 정의합니다.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **멤버 이름** | **설명** |
| :- | :- |
| EXTRAPOLATE | 8비트 값을 n비트에 맞게 외삽합니다(1 < n < 8).<br/>            가능한 모든 8비트 값의 수는 1 << 8 = 256이며, 0부터 255까지입니다.<br/>            가능한 모든 n비트 값의 수는 1 << n이며, 0부터 (1 << n) - 1까지입니다.<br/>            일부 8비트 값 V8에 해당하는 가장 합리적인 n비트 값 Vn은 Vn = V8 >> (8 - n)와 같습니다. |
| TRUNCATE | 8비트 값을 n비트에 맞게 잘라냅니다(1 < n < 8).<br/>            가능한 모든 n비트 값의 수는 1 << n이며, 0부터 (1 << n) - 1까지입니다.<br/>            일부 8비트 값 V8에 해당하는 가장 합리적인 n비트 값 Vn은 Vn = V8 & ((1 << n) - 1)와 같습니다. |
