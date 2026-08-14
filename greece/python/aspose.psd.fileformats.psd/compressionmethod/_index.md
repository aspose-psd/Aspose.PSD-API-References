---
title: "CompressionMethod Απαρίθμηση"
type: docs
weight: 2410
url: /el/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Ορίζει τη μέθοδο συμπίεσης που χρησιμοποιείται για τα δεδομένα εικόνας.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Όνομα μέλους** | **Περιγραφή** |
| :- | :- |
| RAW | Χωρίς συμπίεση. Τα δεδομένα εικόνας αποθηκεύονται ως ακατέργαστα byte σε σειρά RGBA.<br/>            Αυτό σημαίνει ότι πρώτα γράφονται όλα τα δεδομένα R, μετά όλα τα G, μετά όλα τα B και τέλος όλα τα δεδομένα A. |
| RLE | Τα δεδομένα εικόνας συμπιεσμένα με RLE ξεκινούν με τις μετρήσεις byte για όλες τις γραμμές σάρωσης (γραμμές * κανάλια), με κάθε<br/>            μέτρηση αποθηκευμένη ως τιμή δύο byte. Τα συμπιεσμένα δεδομένα RLE ακολουθούν, με κάθε γραμμή σάρωσης συμπιεσμένη ξεχωριστά.<br/>            Η συμπίεση RLE είναι ο ίδιος αλγόριθμος συμπίεσης που χρησιμοποιείται από τη ρουτίνα Macintosh ROM PackBits και το πρότυπο TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP χωρίς πρόβλεψη. |
| ZIP_WITH_PREDICTION | ZIP με πρόβλεψη. |
