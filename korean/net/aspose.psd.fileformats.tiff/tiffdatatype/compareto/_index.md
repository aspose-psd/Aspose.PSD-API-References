---
title: "TiffDataType.CompareTo"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "TiffDataType 메서드. 현재 인스턴스를 동일한 유형의 다른 객체와 비교하고, 현재 인스턴스가 정렬 순서에서 다른 객체보다 앞서거나 뒤에 있거나 같은 위치에 있는지를 나타내는 정수를 반환합니다."
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.tiff/tiffdatatype/compareto/
---
{{< psd/tize >}}
## TiffDataType.CompareTo method

현재 인스턴스를 동일한 유형의 다른 객체와 비교하고, 현재 인스턴스가 정렬 순서에서 앞에 있는지, 뒤에 있는지, 혹은 같은 위치에 있는지를 나타내는 정수를 반환합니다.

```csharp
public int CompareTo(object obj)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | Object | 이 인스턴스와 비교할 객체. |

### 반환 값

비교되는 객체들의 상대적 순서를 나타내는 32비트 부호 있는 정수입니다. 반환값은 다음과 같은 의미를 가집니다: Value Meaning
Less than zero 이 인스턴스는 *obj*보다 작습니다.
Zero 이 인스턴스는 *obj*와 같습니다.
Greater than zero 이 인스턴스는 *obj*보다 큽니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | 예상되는 TiffDataType 유형입니다. |

### 또 보기

* class [TiffDataType](../)
* namespace [Aspose.PSD.FileFormats.Tiff](../../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../../)


