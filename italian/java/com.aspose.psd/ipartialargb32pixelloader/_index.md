---
title: "IPartialArgb32PixelLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Conforma ai pixel ARGB a 32 bit caricati parzialmente."
type: docs
weight: 130
url: /it/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Conforma ai pixel ARGB a 32 bit caricati parzialmente.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Elabora i pixel caricati. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Elabora i pixel caricati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei pixel. |
| pixel | int[] | I pixel in formato argb |
| start | [Point](../../com.aspose.psd/point) | Il punto dei pixel iniziali. Se non è uguale a (left,top) significa che non abbiamo un rettangolo completo. |
| end | [Point](../../com.aspose.psd/point) | Il punto dei pixel finali. Se non è uguale a (right,bottom) significa che non abbiamo un rettangolo completo. |

