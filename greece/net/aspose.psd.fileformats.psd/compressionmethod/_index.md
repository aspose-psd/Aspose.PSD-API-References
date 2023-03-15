---
title: Enum CompressionMethod
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.CompressionMethod αρίθμηση. Καθορίζει τη μέθοδο συμπίεσης που χρησιμοποιείται για δεδομένα εικόνας.
type: docs
weight: 1620
url: /el/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Καθορίζει τη μέθοδο συμπίεσης που χρησιμοποιείται για δεδομένα εικόνας.

```csharp
public enum CompressionMethod : short
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Raw | `0` | Χωρίς συμπίεση. Τα δεδομένα εικόνας αποθηκεύονται ως ακατέργαστα byte σε επίπεδη σειρά RGBA. Αυτό σημαίνει ότι πρώτα γράφονται όλα τα δεδομένα R, μετά γράφονται όλα τα G, μετά όλα τα B και τέλος όλα τα δεδομένα A. |
| RLE | `1` | Το RLE συμπίεση των δεδομένων εικόνας ξεκινά με τις μετρήσεις byte για όλες τις γραμμές σάρωσης (σειρές * κανάλια), με κάθε μέτρηση να αποθηκεύεται ως τιμή δύο byte. Ακολουθούν τα συμπιεσμένα δεδομένα RLE, με κάθε γραμμή σάρωσης συμπιεσμένη χωριστά. Η συμπίεση RLE είναι ο ίδιος αλγόριθμος συμπίεσης που χρησιμοποιείται από το Macintosh ROM ρουτίνας PackBits και το πρότυπο TIFF. |
| ZipWithoutPrediction | `2` | ZIP χωρίς πρόβλεψη. |
| ZipWithPrediction | `3` | ZIP με πρόβλεψη. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* συνέλευση [Aspose.PSD](../../)


