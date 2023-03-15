---
title: Class XmpPacketWrapper
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Xmp.XmpPacketWrapper 수업. 헤더와 트레일러를 포함하는 직렬화된 xmp 패키지를 포함합니다.
type: docs
weight: 6290
url: /ko/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

헤더와 트레일러를 포함하는 직렬화된 xmp 패키지를 포함합니다.

```csharp
public class XmpPacketWrapper
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | 의 새 인스턴스를 초기화합니다.`XmpPacketWrapper` 클래스. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | 의 새 인스턴스를 초기화합니다.`XmpPacketWrapper` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | 헤더 처리 명령을 가져옵니다. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP 메타를 가져옵니다. 선택사항. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | 배열 가져오기[`XmpPackage`](../xmppackage/) 내부 XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | XMP 구조 내부의 패키지 양을 가져옵니다. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | 트레일러 처리 명령을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | 패키지를 추가합니다. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | 모두 제거[`XmpPackage`](../xmppackage/) 내부 XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | 패키지가 xmp 래퍼에 있는지 여부를 결정합니다. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | 네임스페이스 URI로 패키지를 가져옵니다. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP 패키지를 제거합니다. |

### 비고

한 쌍의 XML 처리 명령(PI)으로 구성된 래퍼가 rdf:RDF 요소 주위에 배치될 수 있습니다.

### 또한보십시오

* 네임스페이스 [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* 집회 [Aspose.PSD](../../)


