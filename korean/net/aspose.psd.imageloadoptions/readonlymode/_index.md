---
title: "Enum ReadOnlyMode"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode 열거형. PSD 이미지를 로드할 때 사용할 수 있는 읽기 전용 모드를 지정합니다."
type: docs
weight: 5260
url: /ko/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

PSD 이미지를 로드할 때 사용할 수 있는 읽기 전용 모드를 지정합니다.

```csharp
public enum ReadOnlyMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 읽기 전용 제한이 적용되지 않습니다. 이미지를 완전히 수정할 수 있습니다. |
| Default | `1` | 기본 모드. 이미지는 완전히 읽기 전용이며 수정할 수 없습니다. |
| MetadataEdit | `2` | 이미지 콘텐츠는 읽기 전용으로 유지하면서 이미지 메타데이터 편집을 허용합니다. |

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

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


