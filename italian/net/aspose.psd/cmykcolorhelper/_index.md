---
title: Class CmykColorHelper
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.CmykColorHelper classe. Metodi helper per lavorare con il colore CMYK presentato come un valore intero a 32 bit con segno. Fornisce lAPI simile aCmykColorstruct. È più leggero perché il colore CMYK è presentato proprio come Int32 piuttosto che struttura con campi interni. Preferisci utilizzare i metodi statici di questa classe quando possibile invece del deprecato CmykColor struct.
type: docs
weight: 280
url: /it/net/aspose.psd/cmykcolorhelper/
---
## CmykColorHelper class

Metodi helper per lavorare con il colore CMYK presentato come un valore intero a 32 bit con segno. Fornisce l'API simile a[`CmykColor`](../cmykcolor/)struct. È più leggero perché il colore CMYK è presentato proprio come Int32 piuttosto che struttura con campi interni. Preferisci utilizzare i metodi statici di questa classe quando possibile invece del deprecato [`CmykColor`](../cmykcolor/) struct.

```csharp
public static class CmykColorHelper
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Crea CMYK da valori di ciano, magenta, giallo e nero a 32 bit. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Ottiene il valore del componente ciano. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Ottiene il valore del componente nero. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Ottiene il valore del componente magenta. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Ottiene il valore del componente giallo. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | La conversione dal colore CMYK al colore ARGB. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | La conversione dai colori CMYK ai colori ARGB. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | La conversione dai colori CMYK ai colori ARGB. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | La conversione dal colore CMYK al colore ARGB utilizzando la conversione Icc con profili predefiniti. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | La conversione dai colori CMYK ai colori ARGB utilizzando la conversione Icc con profili predefiniti. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | La conversione dal colore CMYK al colore ARGB utilizzando la conversione Icc con profilo personalizzato. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | La conversione dai colori CMYK ai colori ARGB utilizzando la conversione Icc con profili personalizzati. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | La conversione dal colore ARGB al colore CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | La conversione dai colori ARGB ai colori CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | La conversione dal colore ARGB al colore CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | La conversione dai colori ARGB ai colori CMYK. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Converte RGB in CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | La conversione dal colore ARGB al colore CMYK utilizzando la conversione Icc con profili predefiniti. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | La conversione dai colori ARGB ai colori CMYK utilizzando la conversione Icc con profili predefiniti. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | La conversione dal colore ARGB al colore CMYK utilizzando la conversione Icc con profili personalizzati. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | La conversione dai colori ARGB ai colori CMYK utilizzando la conversione Icc con profili personalizzati. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Converte RGB in CMYK utilizzando profili ICC personalizzati. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


