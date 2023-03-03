---
title: Enum LayerLockType
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType 枚举. 图层锁定选项
type: docs
weight: 2580
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
## LayerLockType enumeration

图层锁定选项

```csharp
[Flags]
public enum LayerLockType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `0` | 无图层锁定 |
| LockTransparentPixels | `1` | 部分锁定图层 - 将编辑限制在图层的不透明部分。 此选项等同于早期版本的 Photoshop 中的“保留透明度”选项。 |
| LockImagePixels | `2` | 部分锁定图层 - 防止使用绘画工具修改图层的像素。 |
| LockPosition | `4` | 部分锁定图层 - 防止移动图层的像素。 |
| LockAll | `7` | 锁定层的所有属性 |

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


