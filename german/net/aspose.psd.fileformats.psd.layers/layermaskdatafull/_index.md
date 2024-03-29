---
title: Class LayerMaskDataFull
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull klas. Definiert die LayerMaskDataFullKlasse die Informationen zu den Maskendaten in der PSDDatei layer enthält wenn die Ebene sowohl Ebenen als auch Vektormasken enthält. Ansonsten ALayerMaskDataShort wird verwendet. Die ImageData enthält die Rastermaske und die gerasterte Vektormaske kombiniert. Die ImageDataBytelänge sollte gleich MaskRectangle.Width  MaskRectangle.HeightEigenschaften sein.
type: docs
weight: 2250
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Definiert die LayerMaskDataFull-Klasse, die Informationen zu den Maskendaten in der PSD-Datei layer enthält, wenn die Ebene sowohl Ebenen- als auch Vektormasken enthält. Ansonsten A[`LayerMaskDataShort`](../layermaskdatashort/) wird verwendet. Die ImageData enthält die Rastermaske und die gerasterte Vektormaske kombiniert. Die ImageData-Bytelänge sollte gleich MaskRectangle.Width * MaskRectangle.Height-Eigenschaften sein.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Ruft die Hintergrundfarbe ab oder legt sie fest. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Ruft die Maskenposition der unteren Ebene ab oder legt sie fest. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Ruft die Größe der Maskendaten der Ebenenmaske ab. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Ruft die Standardfarbe ab oder legt sie fest. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Ruft die umschließende untere Rastermaskenposition in der PSD-Bildebene ab oder legt sie fest. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Ruft die umschließende linke Rastermaskenposition in der Ebene der PSD-Datei ab oder legt sie fest. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Ruft die Position der umschließenden rechten Rastermaske in der Ebene der PSD-Datei ab oder legt sie fest. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Ruft die umschließende obere Position der Rastermaske in der PSD-Bildebene ab oder legt sie fest. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Ruft die Ebenenmasken-Flags ab oder setzt sie. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Ruft die Ebenenmaskendaten (oder die kombinierte / endgültige Maske, wenn eine Vektormaske vorhanden ist) in der PSD-Datei ab oder legt sie fest. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Ruft die Position der linken Ebenenmaske ab oder legt sie fest. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Holt oder setzt die Maske[`Rectangle`](../../aspose.psd/rectangle/)der Ebenenmaske in der PSD-Datei. Es nimmt linke, rechte, obere und untere Eigenschaften und erstellt[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Ermittelt oder setzt die Ebenenmasken-Flags, die für die Benutzer-/Rastermaske verwendet werden. Für die Vektormaske wird die Eigenschaft Flags verwendet. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Ruft die Position der richtigen Ebenenmaske ab oder legt sie fest. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Ruft die Maskenposition der obersten Ebene ab oder legt sie fest. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Ruft die Benutzer-(Raster-)Maskendaten einer Ebene in der PSD-Datei ab oder legt sie fest. (Es gibt eine bewertete Vektormaske in der MaskData-Eigenschaft). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Ruft das (einschließende) Rechteck der Benutzermaske in der PSD-Bildebene ab oder legt es fest.. |

### Siehe auch

* class [LayerMaskData](../layermaskdata/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Montage [Aspose.PSD](../../)


