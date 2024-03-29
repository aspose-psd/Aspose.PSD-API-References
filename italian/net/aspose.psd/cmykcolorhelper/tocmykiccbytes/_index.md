---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD per riferimento API .NET
description: CmykColorHelper metodo. Converte RGB in CMYK utilizzando profili ICC personalizzati.
type: docs
weight: 120
url: /it/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Converte RGB in CMYK utilizzando profili ICC personalizzati.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | Int32[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | Int32 | L'indice iniziale del colore RGB. |
| length | Int32 | Il numero di pixel RGB da convertire. |
| rgbIccStream | Stream | Il flusso del profilo RGB. |
| cmykIccStream | Stream | Il flusso del profilo CMYK. |

### Valore di ritorno

I colori CMYK presentati come un array di byte.

### Guarda anche

* class [CmykColorHelper](../)
* spazio dei nomi [Aspose.PSD](../../cmykcolorhelper/)
* assemblea [Aspose.PSD](../../../)


