---
title: "Layer.Save"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Layer-Methode. Speichert die Daten des Objekts in den angegebenen Stream"
type: docs
weight: 390
url: /de/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

Speichert die Objektdaten in den angegebenen Stream.

```csharp
public override void Save(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream, in dem die Daten des Objekts gespeichert werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wir sollten die Save‑Methode nicht ohne Bildoptionen aufrufen. |

### Siehe auch

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| Optionen | ImageOptionsBase | Die Optionen. |

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Speichert die Objektdaten am angegebenen Speicherort.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |
| overWrite | Boolean | Wenn auf `true` gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Siehe auch

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream, in dem die Bilddaten gespeichert werden. |
| optionsBase | ImageOptionsBase | Die Speicheroptionen. |
| boundsRectangle | Rectangle | Das Ziel‑Bild‑Grenzrechteck. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| Optionen | ImageOptionsBase | Die Optionen. |
| boundsRectangle | Rectangle | Das Ziel‑Bild‑Grenzrechteck. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


