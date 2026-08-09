---
title: "PsdOptions.RemoveGlobalTextEngineResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdOptions 属性。获取或设置一个值，指示是否移除全局文本引擎资源。该选项用于某些带有文本层的 PSD 文件，仅在处理后因缺少字体导致无法在 Adobe Photoshop 中打开时使用。使用此选项后，用户需要在 Photoshop 打开的文件中依次执行 “菜单 Text → 处理缺失字体”。完成该操作后，所有文本将再次显示。请注意，此操作可能导致最终布局出现一些变化。"
type: docs
weight: 90
url: /zh/net/aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/
---
{{< psd/tize >}}
## PsdOptions.RemoveGlobalTextEngineResource property

获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本图层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本图层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 "Text" -> "Process absent fonts"。该操作完成后，所有文本将再次出现。请注意，此操作可能导致部分最终布局的更改。

```csharp
public bool RemoveGlobalTextEngineResource { get; set; }
```

### Property Value

`true` 如果 [remove global text engine resource]；否则，`false`。

### 另请参阅

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


