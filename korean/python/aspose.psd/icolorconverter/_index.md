---
title: "IColorConverter 클래스"
type: docs
weight: 1690
url: /ko/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | 전달된 데이터를 출력 형식으로 변환합니다. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

전달된 데이터를 출력 형식으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | 소스 형식. |
| 데이터 | byte | 소스 데이터. |
| offset | int | 데이터 복사를 시작해야 하는 바이트 단위 오프셋. |
| bit_start | int | 비트 시작 위치. 이 값은 바이트 정렬 값이 아니라 복사를 시작해야 하는 실제 비트임을 유의하십시오. |
| samples_count | int | 샘플 수. |
| lines_count | int | 라인 수. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | 대상 형식. |
| output_data | byte | 출력 데이터. |
| output_offset | int | 데이터 복사를 시작해야 하는 출력 오프셋. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 변환된 바이트 수입니다. |


