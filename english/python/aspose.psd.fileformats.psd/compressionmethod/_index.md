---
title: CompressionMethod Enumeration
type: docs
weight: 2350
url: /python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Defines the compression method used for image data.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.8.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| RAW | No compression. The image data stored as raw bytes in RGBA planar order.<br/>            That means that first all R data is written, then all G is written, then all B and finally all A data is written. |
| RLE | RLE compressed the image data starts with the byte counts for all the scan lines (rows * channels), with each<br/>            count stored as a two-byte value. The RLE compressed data follows, with each scan line compressed separately.<br/>            The RLE compression is the same compression algorithm used by the Macintosh ROM routine PackBits and the TIFF standard. |
| ZIP_WITHOUT_PREDICTION | ZIP without prediction. |
| ZIP_WITH_PREDICTION | ZIP with prediction. |
