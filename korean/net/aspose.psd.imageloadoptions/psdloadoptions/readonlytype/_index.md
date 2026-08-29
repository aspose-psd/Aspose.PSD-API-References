---
title: "PsdLoadOptions.ReadOnlyType"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdLoadOptions 속성. PSD 이미지를 로드할 때 사용되는 읽기 전용 모드를 가져오거나 설정합니다."
type: docs
weight: 80
url: /ko/net/aspose.psd.imageloadoptions/psdloadoptions/readonlytype/
---
{{< psd/tize >}}
## PsdLoadOptions.ReadOnlyType property

PSD 이미지를 로드할 때 사용되는 읽기 전용 모드를 가져오거나 설정합니다.

```csharp
public ReadOnlyMode ReadOnlyType { get; set; }
```

### Property Value

다음 중 하나인 [`ReadOnlyMode`](../readonlymode/) 값:

* !:ReadOnlyMode.None – No restrictions. Image content can be modified.
* !:ReadOnlyMode.Default – The image is fully read-only.
* !:ReadOnlyMode.MetadataEdit – Only metadata can be edited (such as [`ImageResources`](../../../aspose.psd.fileformats.psd/psdimage/imageresources/)), while image pixel content remains read-only.

## 예제

ReadOnlyMode.MetadataEdit를 사용하여 PSD 메타데이터를 편집하고 저장하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // ReadOnlyMode에서 메타데이터 변경
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // ReadOnlyMode에서 변경된 메타데이터 저장
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### 또 보기

* enum [ReadOnlyMode](../../readonlymode/)
* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


