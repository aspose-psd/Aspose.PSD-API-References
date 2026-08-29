---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "XmpBasicPackage 메서드. 값을 설정합니다"
type: docs
weight: 120
url: /ko/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

값을 설정합니다.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | String | 추가된 값으로 식별되는 키의 문자열 표현. |
| 값 | IXmlValue | 추가할 값. |

## 예제

다음 코드는 UpdateMetadata 옵션을 사용하여 xmp 데이터의 CreatorTool 값을 업데이트하는 예시를 보여줍니다.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // CreatorTool을 변경하려면 "UpdateMetadata" 속성이 true로 설정되어 있는지 확인하십시오. 기본값은 true입니다.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // 이미지를 저장하는 중. 
    image.Save(path, psdOptions);

    // 코드에서 CreatorTool을 확인합니다.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // 여기에 업데이트된 CreatorTool 정보가 표시됩니다.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### 또 보기

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


