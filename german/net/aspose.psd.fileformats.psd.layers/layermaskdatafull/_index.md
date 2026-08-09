---
title: "Klasse LayerMaskDataFull"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull Klasse. Definiert die Klasse LayerMaskDataFull, die Informationen über die Maskendaten in der PSD‑Dateiebene enthält, wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat. Andernfalls wird ein LayerMaskDataShort verwendet. ImageData enthält die Rastermaske und die gerasterte Vektormaske kombiniert. Die Länge der ImageData‑Bytes sollte den Eigenschaften MaskRectangle.Width * MaskRectangle.Height entsprechen."
type: docs
weight: 2450
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Definiert die Klasse LayerMaskDataFull, die Informationen über die Maskendaten in der PSD-Dateiebene enthält, wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat. Andernfalls wird ein [`LayerMaskDataShort`](../layermaskdatashort/) verwendet. Die ImageData enthält die Rastermaske und die gerasterte Vektormaske kombiniert. Die Länge der ImageData‑Bytes sollte den Eigenschaften MaskRectangle.Width * MaskRectangle.Height entsprechen.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Liest oder setzt die Hintergrundfarbe. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Liest oder setzt die Position der unteren Ebenenmaske. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Liest die Größe der Maskendaten der Ebenenmaske. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Liest oder setzt die Standardfarbe. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Liest oder setzt die umschließende untere Position der Rastermaske in der PSD‑Bildebene. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Liest oder setzt die umschließende linke Position der Rastermaske in der PSD‑Dateiebene. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Liest oder setzt die umschließende rechte Position der Rastermaske in der PSD‑Dateiebene. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Liest oder setzt die umschließende obere Position der Rastermaske in der PSD‑Bildebene. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Liest oder setzt die Flags der Ebenenmaske. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Liest oder setzt die Ebenenmaskendaten (oder kombinierte / finale Maske, falls eine Vektormaske vorhanden ist) in der PSD‑Datei. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Liest oder setzt die linke Position der Ebenenmaske. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Liest oder setzt das Masken-[`Rectangle`](../../aspose.psd/rectangle/) der Ebenenmaske in der PSD‑Datei. Es verwendet die Eigenschaften links, rechts, oben und unten und erzeugt ein [`Rectangle`](../../aspose.psd/rectangle/). |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Liest oder setzt die Ebenenmasken‑Flags, die für die Benutzer‑/Rastermaske verwendet werden. Für die Vektormaske wird die Eigenschaft Flags verwendet. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Liest oder setzt die rechte Position der Ebenenmaske. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Liest oder setzt die obere Position der Ebenenmaske. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Liest oder setzt die Benutzermaskendaten (Raster) einer Ebene in der PSD‑Datei. (In der Eigenschaft MaskData befindet sich eine gerasterte Vektormaske). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Liest oder setzt das Benutzer‑Masken‑Rechteck (umschließend) in der PSD‑Bildebene.. |

### Siehe auch

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


