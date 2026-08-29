---
title: "Klasse GrdmResource"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GrdmResource klasse. Klasse GrdmResource. Bevat informatie over de GradientMap-laag."
type: docs
weight: 2770
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---
{{< psd/tize >}}
## GrdmResource class

Klasse GrdmResource. Bevat informatie over de Gradient-Map-laag.

```csharp
public class GrdmResource : AdjustmentLayerResource
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [GrdmResource](grdmresource/)(int) | Initialiseert een nieuw exemplaar van de `GrdmResource`-klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colormodel/) { get; set; } | Kleurmodel. Wanneer 'Gradient type' = 'Noise', kunnen we 'Color Model' toewijzen aan RGB/SHB/LAB (3/4/6). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/) { get; set; } | Haalt of stelt de kleurpunten in. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/dither/) { get; set; } | Is de gradient geditherd. |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/expansioncount/) { get; set; } | Uitbreidingsaantal ( = 2 voor Photoshop 6.0). |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/) { get; set; } | Modus voor deze gradient bepaalt 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientname/) { get; set; } | Naam van de gradient: Unicode‑string, opgevuld. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolation/) { get; set; } | Interpolatie. Bepaalt gladheid, wanneer 'Gradient Type' = 'Solid' (GradientMode = 0). |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolationmethod/) { get; set; } | Haalt een waarde op of stelt de interpolatiemethode voor de gradient in. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Haalt de laagresource-sleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/length/) { get; } | Haalt de lengte van de laagresource op in bytes. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/maximumcolor/) { get; set; } | Maximumkleur van PixelDataFormat.Rgba64Bpp-formaat. Kleur heeft ARGB-kanalen, elk kanaal is 16‑bit. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/minimumcolor/) { get; set; } | Minkleur van PixelDataFormat.Rgba64Bpp-formaat. Kleur heeft ARGB-kanalen, elk kanaal is 16‑bit. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/) { get; } | Haalt de minimale PSD-versie op die vereist is voor deze resource. Versie 3 is nodig wanneer de interpolatiemethode expliciet wordt opgeslagen. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/reverse/) { get; set; } | Is de gradient omgekeerd. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/) { get; set; } | De seed voor willekeurige getallen die wordt gebruikt om kleuren te genereren voor Noise-gradient. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/) { get; set; } | Ruwheidsfactor Wanneer 'Gradient type' = 'Noise', kunnen we 'Roughness' (0 - 2048) toewijzen. |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/showtransparency/) { get; set; } | Vlag voor het tonen van transparantie Wanneer 'Gradient type' = 'Noise', kunnen we 'Add transparency' op true zetten. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Haalt de handtekening op. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/transparencypoints/) { get; set; } | Haalt of stelt de transparantiepunten in. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/usevectorcolor/) { get; set; } | Vlag voor het gebruiken van vectorkleur. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/save/)(StreamContainer, int) | Slaat resourcegegevens op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/typetoolkey/) | De type-tool-informatiesleutel. |

## Voorbeelden

De volgende code demonstreert ondersteuning van de GrdmResource resource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // controleer huidige waarden
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // Rode kleur voor het tweede kleurpunt van de gradiënt.
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // controleer gewijzigde waarden
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Zie ook

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


