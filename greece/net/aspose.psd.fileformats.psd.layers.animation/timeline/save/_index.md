---
title: "Timeline.Save"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Timeline method. Αποθηκεύει τα PsdImages και τα δεδομένα Timeline στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης"
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στην καθορισμένη τοποθεσία αρχείου στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου. |
| επιλογές | ImageOptionsBase | Οι επιλογές. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη εξαγωγής του Timeline σε εικόνα Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στο καθορισμένο ρεύμα στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStream | Stream | Η ροή εξόδου. |
| επιλογές | ImageOptionsBase | Οι επιλογές. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη εξαγωγής του Timeline σε εικόνα Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


