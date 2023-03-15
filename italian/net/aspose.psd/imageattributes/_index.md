---
title: Class ImageAttributes
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ImageAttributes classe. AnImageAttributes Loggetto contiene informazioni su come vengono manipolati i colori bitmap e metafile durante il rendering. UNImageAttributes oggetto mantiene diverse impostazioni di regolazione del colore incluse matrici di regolazione del colore matrici di regolazione della scala di grigi valori di correzione della gamma tabelle della mappa dei colori e valori della soglia del colore. Durante il rendering i colori possono essere corretti scuriti schiariti e rimossi. Per applicare tali manipolazioni inizializzare un fileImageAttributesoggetto e passa il percorso di quelloImageAttributes oggetto insieme al percorso di anImage  al metodo DrawImage.
type: docs
weight: 4610
url: /it/net/aspose.psd/imageattributes/
---
## ImageAttributes class

An`ImageAttributes` L'oggetto contiene informazioni su come vengono manipolati i colori bitmap e metafile durante il rendering. UN`ImageAttributes` oggetto mantiene diverse impostazioni di regolazione del colore, incluse matrici di regolazione del colore, matrici di regolazione della scala di grigi, valori di correzione della gamma, tabelle della mappa dei colori e valori della soglia del colore. Durante il rendering, i colori possono essere corretti, scuriti, schiariti e rimossi. Per applicare tali manipolazioni, inizializzare un file`ImageAttributes`oggetto e passa il percorso di quello`ImageAttributes` oggetto (insieme al percorso di an[`Image`](../image/) ) al metodo DrawImage.

```csharp
public sealed class ImageAttributes
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Default_Costruttore |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Cancella la tabella di rimappatura dei colori dei pennelli`ImageAttributes` oggetto. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Cancella la chiave colore (intervallo di trasparenza) per la categoria predefinita. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Cancella la chiave colore (intervallo di trasparenza) per una categoria specificata. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Cancella la matrice di regolazione del colore per la categoria predefinita. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Cancella la matrice di regolazione del colore per una categoria specificata. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Disabilita la correzione gamma per la categoria predefinita. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Disabilita la correzione gamma per una categoria specificata. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Cancella l'impostazione NoOp per la categoria predefinita. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Cancella l'impostazione NoOp per una categoria specificata. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Cancella l'impostazione del canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Cancella l'impostazione del canale di output (ciano-magenta-giallo-nero) per una categoria specificata. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Cancella l'impostazione del profilo colore del canale di output per la categoria predefinita. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Cancella l'impostazione del profilo colore del canale di output per una categoria specificata. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Cancella la tabella di rimappatura dei colori per la categoria predefinita. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Cancella la tabella di rimappatura dei colori per una categoria specificata. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Cancella il valore di soglia per la categoria predefinita. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Cancella il valore di soglia per una categoria specificata. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Imposta la tabella di rimappatura dei colori per la categoria dei pennelli. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Imposta la chiave del colore per la categoria predefinita. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Imposta la chiave del colore (intervallo di trasparenza) per una categoria specificata. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per una categoria specificata. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Imposta la matrice di regolazione del colore per una categoria specificata. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Imposta il valore gamma per la categoria predefinita. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Imposta il valore gamma per una categoria specificata. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Disattiva la regolazione del colore per la categoria predefinita. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Disattiva la regolazione del colore per una categoria specificata. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per una categoria specificata. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Imposta il file del profilo colore del canale di output per la categoria predefinita. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Imposta il file del profilo colore del canale di output per una categoria specificata. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Imposta la tabella di rimappatura dei colori per la categoria predefinita. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Imposta la tabella di rimappatura dei colori per una categoria specificata. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Imposta la soglia (intervallo di trasparenza) per la categoria predefinita. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Imposta la soglia (intervallo di trasparenza) per una categoria specificata. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Imposta la modalità di avvolgimento utilizzata per decidere come affiancare una trama attraverso una forma o ai limiti della forma. Una trama viene affiancata a una forma per riempirla quando la trama è più piccola della forma che sta riempiendo. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come affiancare una trama attraverso una forma o ai limiti della forma. Una trama viene affiancata a una forma per riempirla quando la trama è più piccola della forma che sta riempiendo. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come affiancare una trama attraverso una forma o ai limiti della forma. Una trama viene affiancata a una forma per riempirla quando la trama è più piccola della forma che sta riempiendo. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


