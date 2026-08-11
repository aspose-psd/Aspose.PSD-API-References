---
title: "클래스 XmpPacketWrapper"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Xmp.XmpPacketWrapper 클래스. 헤더와 트레일러를 포함한 직렬화된 xmp 패키지를 포함합니다"
type: docs
weight: 6790
url: /ko/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

헤더와 트레일러를 포함한 직렬화된 xmp 패키지를 포함합니다.

```csharp
public class XmpPacketWrapper
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | `XmpPacketWrapper` 클래스의 새 인스턴스를 초기화합니다. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | `XmpPacketWrapper` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | 헤더 처리 지시문을 가져옵니다. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP 메타를 가져옵니다. 선택 사항입니다. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | XMP 내부의 [`XmpPackage`](../xmppackage/) 배열을 가져옵니다. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | XMP 구조 내부의 패키지 수를 가져옵니다. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | 트레일러 처리 지시문을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | 패키지를 추가합니다. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | XMP 내부의 모든 [`XmpPackage`](../xmppackage/)을 제거합니다. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | 패키지가 xmp 래퍼에 존재하는지 여부를 결정합니다. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | 네임스페이스 URI로 패키지를 가져옵니다. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP 패키지를 제거합니다. |

## 비고

XML 처리 지시문(PIs) 한 쌍으로 구성된 래퍼는 rdf:RDF 요소 주위에 배치될 수 있습니다.

### 또 보기

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


