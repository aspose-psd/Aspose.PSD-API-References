---
title: "IColorConverter"
second_title: "Java용 Aspose.PSD API 참조"
description: "컬러 변환기입니다."
type: docs
weight: 116
url: /ko/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

컬러 변환기입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | 전달된 데이터를 출력 형식으로 변환합니다. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


전달된 데이터를 출력 형식으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 소스 형식. |
| 데이터 | byte[] | 원본 데이터. |
| 오프셋 | int | 데이터 복사를 시작해야 하는 바이트 단위 오프셋. |
| bitStart | int | 비트 시작 위치. 이 값은 바이트 정렬 값이 아니라 복사가 시작되어야 하는 실제 비트임을 유의하십시오. |
| samplesCount | int | 샘플 수. |
| linesCount | int | 라인 수. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 대상 형식. |
| outputData | byte[] | 출력 데이터. |
| outputOffset | int | 데이터 복사를 시작해야 하는 출력 오프셋. |

**Returns:**
int - 변환된 바이트 수.
