---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "IColorConverter 메서드. 전달된 데이터를 출력 형식으로 변환합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

전달된 데이터를 출력 형식으로 변환합니다.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | 원본 형식. |
| 데이터 | Byte[] | 소스 데이터입니다. |
| offset | Int32 | 데이터 복사를 시작해야 하는 바이트 단위 오프셋입니다. |
| bitStart | Int32 | 비트 시작 위치입니다. 이 값은 바이트 정렬 값이 아니라 복사를 시작해야 하는 실제 비트임을 유의하십시오. |
| samplesCount | Int32 | 샘플 수입니다. |
| linesCount | Int32 | 라인 수입니다. |
| destFormat | PixelDataFormat | 대상 형식입니다. |
| outputData | Byte[] | 출력 데이터입니다. |
| outputOffset | Int32 | 데이터 복사를 시작해야 하는 출력 오프셋입니다. |

### 반환 값

변환된 바이트 수입니다.

### 또 보기

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


