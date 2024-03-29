---
title: Class PhflResourceVersion2
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 klas. Klasse PhflResource. Ressource der Belichtungsanpassungsebene 2 Version   3  oder   2  12 Jeweils 4 Byte für XYZFarbe nur in Version 3 10 2 Byte Farbraum gefolgt von 4  2 Byte Farbkomponente nur in Version 2 4 Dichte 1 Leuchtkraft erhalten
type: docs
weight: 2900
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
## PhflResourceVersion2 class

Klasse PhflResource. Ressource der Belichtungsanpassungsebene 2 Version ( = 3 ) oder ( = 2 ) 12 Jeweils 4 Byte für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 * 2 Byte Farbkomponente (nur in Version 2) 4 Dichte 1 Leuchtkraft erhalten

```csharp
public class PhflResourceVersion2 : PhflResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | Initialisiert eine neue Instanz von`PhflResourceVersion2` Klasse. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | Initialisiert eine neue Instanz von`PhflResourceVersion2` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | Ruft den Farbraum ab. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | Ruft die A-Komponente von color ab oder setzt sie |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | Holt oder setzt die B-Komponente |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | Liest oder setzt die L-Komponente von color |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Ruft die Dichte ab oder legt sie fest. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Helligkeit beibehalten]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ruft die Signatur ab. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | Ruft die Version ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | Ruft die Farbe ab. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | Legt die RGB-Farbe fest. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


