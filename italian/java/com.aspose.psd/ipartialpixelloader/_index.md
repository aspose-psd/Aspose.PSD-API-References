---
title: "IPartialPixelLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Conforma ai pixel caricati parzialmente."
type: docs
weight: 132
url: /it/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Conforma ai pixel caricati parzialmente.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Elabora i pixel caricati. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Elabora i pixel caricati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei pixel. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | I pixel. |
| start | [Point](../../com.aspose.psd/point) | Il punto dei pixel iniziali. Se non è uguale a (left,top) significa che non abbiamo un rettangolo completo. |
| end | [Point](../../com.aspose.psd/point) | Il punto dei pixel finali. Se non è uguale a (right,bottom) significa che non abbiamo un rettangolo completo. |

