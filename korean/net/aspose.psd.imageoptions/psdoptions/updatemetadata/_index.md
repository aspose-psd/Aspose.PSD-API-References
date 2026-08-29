---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdOptions 속성. 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. 값이 true이면 이미지를 저장하는 동안 메타데이터가 업데이트됩니다"
type: docs
weight: 110
url: /ko/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

[update metadata] 여부를 가져오거나 설정합니다. 값이 true이면 이미지를 저장하는 동안 메타데이터가 업데이트됩니다.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` if [update metadata]; otherwise, `false`.

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

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


