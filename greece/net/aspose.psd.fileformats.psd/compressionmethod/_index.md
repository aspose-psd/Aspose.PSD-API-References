---
title: "Απαρίθμηση CompressionMethod"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod απαρίθμηση. Ορίζει τη μέθοδο συμπίεσης που χρησιμοποιείται για τα δεδομένα εικόνας."
type: docs
weight: 1630
url: /el/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Ορίζει τη μέθοδο συμπίεσης που χρησιμοποιείται για δεδομένα εικόνας.

```csharp
public enum CompressionMethod : short
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Raw | `0` | Χωρίς συμπίεση. Τα δεδομένα εικόνας αποθηκεύονται ως ακατέργαστα byte με σειρά RGBA επίπεδη. Αυτό σημαίνει ότι πρώτα γράφονται όλα τα δεδομένα R, μετά όλα τα G, μετά όλα τα B και τέλος όλα τα A. |
| RLE | `1` | Συμπιεσμένα RLE, τα δεδομένα εικόνας ξεκινούν με τις μετρήσεις byte για όλες τις γραμμές σάρωσης (γραμμές * κανάλια), με κάθε μέτρηση αποθηκευμένη ως τιμή δύο byte. Ακολουθούν τα συμπιεσμένα δεδομένα RLE, με κάθε γραμμή σάρωσης να συμπιέζεται ξεχωριστά. Η συμπίεση RLE είναι ο ίδιος αλγόριθμος συμπίεσης που χρησιμοποιείται από τη ρουτίνα PackBits του Macintosh ROM και το πρότυπο TIFF. |
| ZipWithoutPrediction | `2` | ZIP χωρίς πρόβλεψη. |
| ZipWithPrediction | `3` | ZIP με πρόβλεψη. |

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


