---
title: "XmpBasicPackage.ContainsKey"
second_title: "Aspose.PSD for .NET API 参考"
description: "XmpBasicPackage 方法。确定指定的键是否包含键"
type: docs
weight: 40
url: /zh/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

确定指定的键是否包含键。

```csharp
public override bool ContainsKey(string key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | String | 要检查的键。 |

### 返回值

如果指定的键包含键，则返回 true。

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


