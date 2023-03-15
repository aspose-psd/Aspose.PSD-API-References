---
title: Layer.Save
second_title: Aspose.PSD für .NET-API-Referenz
description: Layer methode. Speichert die Daten des Objekts im angegebenen Stream.
type: docs
weight: 370
url: /de/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

Speichert die Daten des Objekts im angegebenen Stream.

```csharp
public override void Save(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wir sollten die Save-Methode nicht ohne Image-Optionen aufrufen |

### Siehe auch

* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| options | ImageOptionsBase | Die Optionen. |

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Speichert die Daten des Objekts am angegebenen Dateispeicherort.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Speichern der Objektdaten. |
| overWrite | Boolean | wenn eingestellt`WAHR` den Dateiinhalt überschreiben, andernfalls wird angehängt. |

### Siehe auch

* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem die Bilddaten gespeichert werden sollen. |
| optionsBase | ImageOptionsBase | Die Speicheroptionen. |
| boundsRectangle | Rectangle | Das Zielbild umgrenzt ein Rechteck. Legen Sie das leere Rechteck für die Verwendung von Quellgrenzen fest. |

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| options | ImageOptionsBase | Die Optionen. |
| boundsRectangle | Rectangle | Das Zielbild umgrenzt ein Rechteck. Legen Sie das leere Rechteck für die Verwendung von Quellgrenzen fest. |

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)


