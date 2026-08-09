---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdOptions 属性。获取或设置一个值，指示是否更新元数据。如果该值为 true，则在保存图像时会更新元数据"
type: docs
weight: 110
url: /zh/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

获取或设置一个值，指示是否 [update metadata]。如果该值为 true，保存图像时元数据将被更新。

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` 如果 [update metadata]；否则为 `false`。

## 示例

下面的代码演示了使用 UpdateMetadata 选项来更新 xmp 数据中的 CreatorTool 值。

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // 如果您希望 creator tool 发生更改，请确保 "UpdateMetadata" 属性设置为 true。默认情况下已设置为 true。
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // 正在保存图像。
    image.Save(path, psdOptions);

    // 在代码中检查 creator tool。
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // 这里将更新 creator tool 信息。
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### 另请参阅

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


