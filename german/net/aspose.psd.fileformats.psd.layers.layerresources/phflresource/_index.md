---
title: Class PhflResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource klas. Klasse PhflResource. Ressource der Belichtungsanpassungsebene 2 Version   3  oder   2  12 Jeweils 4 Byte für XYZFarbe nur in Version 3 10 2 Byte Farbraum gefolgt von 4  2 Byte Farbkomponente nur in Version 2 4 Dichte 1 Leuchtkraft erhalten
type: docs
weight: 2890
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Klasse PhflResource. Ressource der Belichtungsanpassungsebene 2 Version ( = 3 ) oder ( = 2 ) 12 Jeweils 4 Byte für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 * 2 Byte Farbkomponente (nur in Version 2) 4 Dichte 1 Leuchtkraft erhalten

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Ruft die Dichte ab oder legt sie fest. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Helligkeit beibehalten]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ruft die Signatur ab. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Ruft die Version ab. Standard ist 2 oder 3 |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Ruft die Farbe des RGB ab. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Legt die RGB-Farbe fest. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


