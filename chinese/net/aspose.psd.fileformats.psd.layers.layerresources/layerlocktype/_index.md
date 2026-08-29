---
title: "枚举 LayerLockType"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType 枚举。图层锁定选项。"
type: docs
weight: 2890
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
{{< psd/tize >}}
## LayerLockType enumeration

图层锁定选项

```csharp
[Flags]
public enum LayerLockType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 无图层锁定 |
| LockTransparentPixels | `1` | 部分锁定图层 - 将编辑限制在图层的不透明部分。此选项等同于早期 Photoshop 版本中的“保留透明度”选项。 |
| LockImagePixels | `2` | 部分锁定图层 - 防止使用绘画工具修改图层像素。 |
| LockPosition | `4` | 部分锁定图层 - 防止图层像素被移动。 |
| LockAll | `7` | 锁定图层的所有属性。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


