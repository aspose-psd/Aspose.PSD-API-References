---
title: Class VstkResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VstkResource classe. Classe di risorse VstkResource. Contiene informazioni su Vector Stroke Data. La risorsa deve essere inizializzata con il metodo AssginItems da resourcedata o assegnando valori alle proprietà della classe.
type: docs
weight: 3060
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---
## VstkResource class

Classe di risorse VstkResource. Contiene informazioni su Vector Stroke Data. La risorsa deve essere inizializzata con il metodo AssginItems da resourcedata, o assegnando valori alle proprietà della classe.

```csharp
public class VstkResource : LayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VstkResource](vstkresource/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FillEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillenabled/) { get; set; } | Ottiene o imposta un valore che indica se il riempimento tratto è abilitato. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/psdversion/) { get; } | Ottiene la versione psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/signature/) { get; } | Ottiene la firma. |
| [StrokeEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokeenabled/) { get; set; } | Ottiene o imposta un valore che indica se l'effetto tratto è abilitato. |
| [StrokeStyleBlendMode](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleblendmode/) { get; set; } | Ottiene o imposta la modalità Stroke Blend. |
| [StrokeStyleContent](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylecontent/) { get; set; } | Ottiene o imposta l'entità Stroke. La proprietà determina le impostazioni di riempimento del tratto. |
| [StrokeStyleLineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/) { get; set; } | Ottiene o imposta l'allineamento della linea in stile Stroke. |
| [StrokeStyleLineCapType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecaptype/) { get; set; } | Ottiene o imposta il tipo di limite di linea dello stile del tratto. |
| [StrokeStyleLineCapWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecapwidth/) { get; set; } | Ottiene o imposta la larghezza del limite della linea Stroke. |
| [StrokeStyleLineDashOffset](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashoffset/) { get; set; } | Ottiene o imposta l'offset del trattino della linea dello stile del tratto. |
| [StrokeStyleLineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashset/) { get; set; } | Ottiene o imposta un array di trattini. |
| [StrokeStyleLineJoinType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinejointype/) { get; set; } | Ottiene o imposta il tipo di unione della linea in stile Stroke. |
| [StrokeStyleLineWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/) { get; set; } | Ottiene o imposta la larghezza della linea Stroke. |
| [StrokeStyleMiterLimit](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylemiterlimit/) { get; set; } | Ottiene o imposta il limite dell'angolo dello stile del tratto. |
| [StrokeStyleOpacity](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleopacity/) { get; set; } | Ottiene o imposta l'opacità di Stroke stryle (0-100%). |
| [StrokeStyleResolution](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleresolution/) { get; set; } | Ottiene o imposta la risoluzione in stile Stroke. |
| [StrokeStyleScaleLock](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylescalelock/) { get; set; } | Ottiene o imposta il blocco della scala dello stile Stroke. |
| [StrokeStyleStrokeAdjust](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylestrokeadjust/) { get; set; } | Ottiene o imposta Stroke Adjust. |
| [StrokeStyleVersion](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleversion/) { get; set; } | Ottiene o imposta la versione dello stile del tratto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore del flusso specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/typetoolkey/) | Il tasto informazioni dello strumento testo. |

### Esempi

Il codice seguente illustra il supporto della risorsa VstkResource.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### Guarda anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assemblea [Aspose.PSD](../../)


