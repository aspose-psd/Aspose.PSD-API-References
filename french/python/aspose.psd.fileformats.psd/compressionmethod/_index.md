---
title: "Énumération CompressionMethod"
type: docs
weight: 2410
url: /fr/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Définit la méthode de compression utilisée pour les données d'image.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| RAW | Pas de compression. Les données d'image sont stockées sous forme d'octets bruts en ordre planaire RGBA.<br/>            Cela signifie que d'abord toutes les données R sont écrites, puis toutes les données G, ensuite toutes les données B et enfin toutes les données A sont écrites. |
| RLE | Les données d'image compressées en RLE commencent par les comptes d'octets pour toutes les lignes de balayage (lignes * canaux), chaque<br/>            compte étant stocké sous forme d'une valeur sur deux octets. Les données compressées en RLE suivent, chaque ligne de balayage étant compressée séparément.<br/>            La compression RLE est le même algorithme de compression utilisé par la routine PackBits de la ROM Macintosh et la norme TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP sans prédiction. |
| ZIP_WITH_PREDICTION | ZIP avec prédiction. |
