---
title: "Classe GrdmResource"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GrdmResource. Classe GrdmResource. Contiene informazioni sul layer GradientMap."
type: docs
weight: 2770
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---
{{< psd/tize >}}
## GrdmResource class

Classe GrdmResource. Contiene informazioni sul layer Gradient-Map.

```csharp
public class GrdmResource : AdjustmentLayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GrdmResource](grdmresource/)(int) | Inizializza una nuova istanza della classe `GrdmResource`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colormodel/) { get; set; } | Modello di colore. Quando 'Gradient type' = 'Noise', possiamo assegnare 'Color Model' a RGB/SHB/LAB (3/4/6). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/) { get; set; } | Ottiene o imposta i punti di colore. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/dither/) { get; set; } | Il gradiente è dithertizzato. |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/expansioncount/) { get; set; } | Conteggio di espansione ( = 2 per Photoshop 6.0). |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/) { get; set; } | La modalità per questo gradiente determina 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientname/) { get; set; } | Nome del gradiente: stringa Unicode, riempita. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolation/) { get; set; } | Interpolazione. Determina la fluidità, quando 'Gradient Type' = 'Solid' (GradientMode = 0). |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolationmethod/) { get; set; } | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/maximumcolor/) { get; set; } | Colore massimo del formato PixelDataFormat.Rgba64Bpp. Il colore ha canali ARGB, ogni canale è a 16 bit. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/minimumcolor/) { get; set; } | Colore minimo del formato PixelDataFormat.Rgba64Bpp. Il colore ha canali ARGB, ogni canale è a 16 bit. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/) { get; } | Ottiene la versione minima di PSD richiesta per questa risorsa. La versione 3 è necessaria quando il metodo di interpolazione è memorizzato esplicitamente. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/reverse/) { get; set; } | Il gradiente è invertito. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/) { get; set; } | Il seme del numero casuale usato per generare i colori per il gradiente Noise. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/) { get; set; } | Fattore di rugosità Quando 'Gradient type' = 'Noise', possiamo assegnare 'Roughness' (0 - 2048). |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/showtransparency/) { get; set; } | Flag per mostrare la trasparenza Quando 'Gradient type' = 'Noise', possiamo assegnare 'Add transparency' a true. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Ottiene la firma. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/transparencypoints/) { get; set; } | Ottiene o imposta i punti di trasparenza. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/usevectorcolor/) { get; set; } | Flag per l'uso del colore vettoriale. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/save/)(StreamContainer, int) | Salva i dati della risorsa nel contenitore di stream specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce una stringa che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/typetoolkey/) | La chiave delle informazioni dello strumento di tipo. |

## Esempi

Il codice seguente dimostra il supporto della risorsa GrdmResource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // controlla i valori attuali
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // Colore rosso per il secondo punto di colore del gradiente
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // controlla i valori modificati
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

### Vedi anche

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


