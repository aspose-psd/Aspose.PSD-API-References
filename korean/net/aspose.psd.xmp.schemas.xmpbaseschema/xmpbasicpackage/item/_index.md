---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "XmpBasicPackage 속성. 지정된 키로 객체를 가져오거나 설정합니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

지정된 키와 함께 Object를 가져오거나 설정합니다.

```csharp
public override object this[string key] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| 키 | 값을 식별하는 키입니다. |

### 반환 값

지정된 키에 해당하는 객체를 반환합니다.

### Property Value

객체입니다.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


