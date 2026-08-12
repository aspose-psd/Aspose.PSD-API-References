---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Справочник API Aspose.PSD для .NET"
description: "PsdLoadOptions property. Получает или задаёт, сохранять ли с отрисованным изображением с искажением или без него"
type: docs
weight: 30
url: /ru/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Получает или задает, сохранять ли с отрендеренным изображением, с искажением или без него.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` — отрисовать изображение с искажением, `false`.

## Примеры

Следующий код демонстрирует рендеринг эффекта Warp.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### См. также

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


