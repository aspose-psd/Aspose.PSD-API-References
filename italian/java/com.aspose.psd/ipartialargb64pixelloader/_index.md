---
title: "IPartialArgb64PixelLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il caricatore di pixel ARGB a 64 bit."
type: docs
weight: 131
url: /it/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Il caricatore di pixel ARGB a 64 bit.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Elabora i pixel caricati. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Elabora i pixel caricati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei pixel. |
| pixel | long[] | I pixel ARGB a 64 bit. |
| start | [Point](../../com.aspose.psd/point) | Il punto dei pixel iniziali. Se non è uguale a (left,top) significa che non abbiamo un rettangolo completo. |
| end | [Point](../../com.aspose.psd/point) | Il punto dei pixel finali. Se non è uguale a (right,bottom) significa che non abbiamo un rettangolo completo. |

