---
title: "Enumerasi CompressionMethod"
type: docs
weight: 2410
url: /id/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Mendefinisikan metode kompresi yang digunakan untuk data gambar.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nama anggota** | **Deskripsi** |
| :- | :- |
| RAW | Tidak ada kompresi. Data gambar disimpan sebagai byte mentah dalam urutan planar RGBA.<br/>            Artinya pertama semua data R ditulis, kemudian semua data G, kemudian semua data B, dan akhirnya semua data A ditulis. |
| RLE | Data gambar terkompresi RLE dimulai dengan hitungan byte untuk semua baris pemindaian (baris * kanal), dengan setiap<br/>            hitungan disimpan sebagai nilai dua byte. Data terkompresi RLE berikutnya, dengan setiap baris pemindaian dikompresi secara terpisah.<br/>            Kompresi RLE adalah algoritma kompresi yang sama yang digunakan oleh rutin ROM Macintosh PackBits dan standar TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP tanpa prediksi. |
| ZIP_WITH_PREDICTION | ZIP dengan prediksi. |
