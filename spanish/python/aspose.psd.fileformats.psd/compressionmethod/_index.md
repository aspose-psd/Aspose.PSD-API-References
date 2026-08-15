---
title: "Enumeración CompressionMethod"
type: docs
weight: 2410
url: /es/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Define el método de compresión utilizado para los datos de imagen.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Descripción** |
| :- | :- |
| RAW | Sin compresión. Los datos de la imagen se almacenan como bytes sin procesar en orden planar RGBA.<br/>            Eso significa que primero se escribe todo el dato R, luego todo el dato G, luego todo el dato B y finalmente todo el dato A. |
| RLE | Los datos de imagen comprimidos con RLE comienzan con los recuentos de bytes para todas las líneas de escaneo (filas * canales), con cada<br/>            recuento almacenado como un valor de dos bytes. A continuación se encuentran los datos comprimidos con RLE, con cada línea de escaneo comprimida por separado.<br/>            La compresión RLE es el mismo algoritmo de compresión utilizado por la rutina PackBits del ROM de Macintosh y el estándar TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP sin predicción. |
| ZIP_WITH_PREDICTION | ZIP con predicción. |
