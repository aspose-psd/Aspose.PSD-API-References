---
title: "클래스 XmpPackage"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Xmp.XmpPackage 클래스. XMP 패키지의 기본 추상화를 나타내는 XmpPackage 클래스를 정의합니다"
type: docs
weight: 6770
url: /ko/net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

XMP 패키지의 기본 추상화를 나타내는 XmpPackage 클래스를 정의합니다.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | 지정된 키와 함께 Object를 가져오거나 설정합니다. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | XMP 패키지의 키를 가져옵니다. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | 네임스페이스 URI를 가져옵니다. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | 접두사를 가져옵니다. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | XML 네임스페이스를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | 값을 추가합니다. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | 이 인스턴스를 초기화합니다. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | 지정된 키에 키가 포함되어 있는지 확인합니다. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | XMP 값을 XML 표현으로 변환합니다. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | 지정된 키와 함께 값을 제거합니다. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | 값을 설정합니다. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | XMP 유형 값을 설정합니다. |

### 또 보기

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


