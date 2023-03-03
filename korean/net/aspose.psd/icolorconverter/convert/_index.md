---
title: IColorConverter.Convert
second_title: .NET API 참조용 Aspose.PSD
description: IColorConverter 방법. 전달된 데이터를 출력 형식으로 변환합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

전달된 데이터를 출력 형식으로 변환합니다.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | 소스 형식입니다. |
| data | Byte[] | 소스 데이터입니다. |
| offset | Int32 | 데이터 복사가 시작되어야 하는 오프셋(바이트)입니다. |
| bitStart | Int32 | 비트 시작. 이 값은 바이트 정렬 값이 아니라 복사가 시작되어야 하는 실제 비트입니다. |
| samplesCount | Int32 | 샘플이 중요합니다. |
| linesCount | Int32 | 줄이 중요합니다. |
| destFormat | PixelDataFormat | 대상 형식입니다. |
| outputData | Byte[] | 출력 데이터. |
| outputOffset | Int32 | 데이터 복사가 시작되어야 하는 출력 오프셋입니다. |

### 반환 값

변환된 바이트 수입니다.

### 또한보십시오

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* 네임스페이스 [Aspose.PSD](../../icolorconverter/)
* 집회 [Aspose.PSD](../../../)


