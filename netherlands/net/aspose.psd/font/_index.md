---
title: Class Font
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Font klas. Definieert een bepaald formaat voor tekst inclusief lettertype grootte en stijlkenmerken. Deze klasse kan niet worden geërfd.
type: docs
weight: 4280
url: /nl/net/aspose.psd/font/
---
## Font class

Definieert een bepaald formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken. Deze klasse kan niet worden geërfd.

```csharp
public sealed class Font
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initialiseert een nieuw`Font` dat gebruik maakt van de gespecificeerde bestaande`Font` En[`FontStyle`](../fontstyle/) opsomming. |
| [Font](font/#constructor_1)(string, float) | Initialiseert een nieuw`Font` een opgegeven maat gebruiken. De tekenset is ingesteld opDefault , de grafische eenheid naarPoint , de lettertypestijl aanRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initialiseert een nieuw`Font` met behulp van een opgegeven grootte en stijl. De tekenset is ingesteld opDefault , de grafische eenheid naarPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initialiseert een nieuw`Font` met behulp van een gespecificeerde maat en eenheid. De tekenset is ingesteld opDefault is de stijl ingesteld opRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initialiseert een nieuw`Font` met een opgegeven grootte, stijl en eenheid. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initialiseert een nieuw`Font` met behulp van een gespecificeerde grootte, stijl, eenheid en tekenset. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Krijgt een waarde die aangeeft of dit`Font` is vetgedrukt. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Haalt een bytewaarde op die de tekenset specificeert die dit`Font` gebruikt. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Krijgt een waarde die aangeeft of dit`Font`is cursief. |
| [Name](../../aspose.psd/font/name/) { get; } | Krijgt de gezichtsnaam hiervan`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Krijgt de em-maat hiervan`Font` gemeten in de eenheden gespecificeerd door de[`Unit`](./unit/) eigenschap. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Krijgt een waarde die aangeeft of dit`Font` specificeert een horizontale lijn door het lettertype. |
| [Style](../../aspose.psd/font/style/) { get; } | Krijgt hiervoor stijlinformatie`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Krijgt een waarde die aangeeft of dit`Font` is onderstreept. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Krijgt de maateenheid hiervoor`Font` . |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Maakt hiervan een exacte diepe kopie`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Geeft aan of het opgegeven object een`Font` en heeft dezelfde eigenschapswaarden als deze`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Krijgt de hash-code hiervoor`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Retourneert hiervan een door mensen leesbare tekenreeksrepresentatie`Font` . |

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van de klasse Font en SolidBrush om tekenreeksen op het afbeeldingsoppervlak te tekenen. In het voorbeeld wordt een nieuwe afbeelding gemaakt en vormen getekend met behulp van Figuren en GraphicsPath

```csharp
[C#]

//Maakt een exemplaar van Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Creëert en initialiseert een instantie van de klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Wist grafisch oppervlak
    graphics.Clear(Color.Wheat);

    //Maakt een exemplaar van Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // Maak een exemplaar van SolidBrush met rode kleur
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Teken een string
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // creëer exportopties.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // sla alle veranderingen op
    image.Save("C:\\temp\\output.gif", options);
}
```

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


