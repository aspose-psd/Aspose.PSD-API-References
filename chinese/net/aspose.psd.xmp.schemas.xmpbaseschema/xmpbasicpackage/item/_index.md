---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD for .NET API 参考"
description: "XmpBasicPackage 属性。获取或设置具有指定键的 Object"
type: docs
weight: 20
url: /zh/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

获取或设置具有指定键的 Object。

```csharp
public override object this[string key] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 键 | 标识值的键。 |

### 返回值

返回具有指定键的 Object。

### Property Value

该 Object。

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


