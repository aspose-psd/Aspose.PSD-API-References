---
title: "枚举 ReadOnlyMode"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode 枚举。指定加载 PSD 图像时可用的只读模式"
type: docs
weight: 5260
url: /zh/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

指定加载 PSD 图像时可用的只读模式。

```csharp
public enum ReadOnlyMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 未应用只读限制。图像可以被完全修改。 |
| Default | `1` | 默认模式。图像是完全只读的，无法被修改。 |
| MetadataEdit | `2` | 允许编辑图像元数据，同时保持图像内容只读。 |

## 示例

演示使用 ReadOnlyMode.MetadataEdit 编辑和保存 PSD 元数据。

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // 在 ReadOnlyMode 中更改元数据
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // 在 ReadOnlyMode 中保存已更改的元数据
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

### 另请参阅

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


