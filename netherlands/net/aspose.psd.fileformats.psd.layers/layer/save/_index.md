---
title: Layer.Save
second_title: Aspose.PSD voor .NET API-referentie
description: Layer methode. Slaat de gegevens van het object op in de opgegeven stream.
type: docs
weight: 370
url: /nl/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

Slaat de gegevens van het object op in de opgegeven stream.

```csharp
public override void Save(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream waarin de gegevens van het object moeten worden opgeslagen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | We moeten de Save-methode niet aanroepen zonder Image-opties |

### Zie ook

* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| options | ImageOptionsBase | De opties. |

### Zie ook

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Slaat de objectgegevens op naar de opgegeven bestandslocatie.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om de gegevens van het object op te slaan. |
| overWrite | Boolean | indien ingesteld op`WAAR` overschrijf de inhoud van het bestand, anders vindt append plaats. |

### Zie ook

* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream waarin de gegevens van de afbeelding moeten worden opgeslagen. |
| optionsBase | ImageOptionsBase | De bewaaropties. |
| boundsRectangle | Rectangle | De bestemmingsafbeelding begrenst de rechthoek. Stel de lege rechthoek in voor gebruiksbrongrenzen. |

### Zie ook

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| options | ImageOptionsBase | De opties. |
| boundsRectangle | Rectangle | De bestemmingsafbeelding begrenst de rechthoek. Stel de lege rechthoek in voor gebruiksbrongrenzen. |

### Zie ook

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)


