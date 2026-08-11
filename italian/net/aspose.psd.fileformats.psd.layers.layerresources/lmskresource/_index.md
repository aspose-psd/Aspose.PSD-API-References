---
title: "Classe LmskResource"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource. La risorsa LMsk"
type: docs
weight: 3020
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

La risorsa LMsk.

```csharp
public class LmskResource : LayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LmskResource](lmskresource/)() | Inizializza una nuova istanza della classe `LmskResource`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Ottiene il componente colore 1. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Ottiene il componente colore 2. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Ottiene il componente colore 3. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Ottiene il componente colore 4. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Ottiene lo spazio colore. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Ottiene il flag. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Ottiene l'opacità. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Ottiene la versione minima di psd richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Ottiene la firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore di stream specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce una stringa che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | La chiave delle informazioni dello strumento di tipo. |

## Osservazioni

Questa risorsa contiene l'ID dello spazio colore, che si riferisce a un tipo specifico di spazio colore, e 4 componenti colore. A seconda dell'ID, i componenti colore hanno significati diversi. Se il tipo di spazio colore non richiede quattro valori, i componenti extra sono indefiniti e sempre scritti come zero. Componenti colore per tipo di spazio colore: RGB - i primi tre componenti sono rosso, verde e blu. HSB - i primi tre componenti sono tonalità, saturazione e luminosità. CMYK - i quattro componenti sono ciano, magenta, giallo e nero. Lab - i primi tre componenti sono luminosità, crominanza a e crominanza b. Grayscale - il primo componente è il valore di grigio, da 0...10000.

## Esempi

Il codice seguente dimostra come modificare le Opzioni di visualizzazione della Maschera di livello su immagini a 16 bit modificando le proprietà di LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Carica immagine a 16 bit.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Trova LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Verifica le proprietà di LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Modifica le proprietà di LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Salva l'immagine.
    image.Save(outputPsd);
}
```

### Vedi anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


