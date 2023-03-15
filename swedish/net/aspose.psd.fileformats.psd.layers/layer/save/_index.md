---
title: Layer.Save
second_title: Aspose.PSD för .NET API-referens
description: Layer metod. Sparar objektets data till den angivna strömmen.
type: docs
weight: 370
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

Sparar objektets data till den angivna strömmen.

```csharp
public override void Save(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att spara objektets data till. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Vi bör inte anropa Spara-metoden utan bildalternativ |

### Se även

* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| options | ImageOptionsBase | Alternativen. |

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Sparar objektets data till den angivna filplatsen.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att spara objektets data till. |
| overWrite | Boolean | om inställt på`Sann` överskriv filens innehåll, annars kommer append att ske. |

### Se även

* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen att spara bildens data till. |
| optionsBase | ImageOptionsBase | Spara alternativen. |
| boundsRectangle | Rectangle | Målbilden avgränsar rektangeln. Ställ in den tomma rektangeln för användningskällans gränser. |

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| options | ImageOptionsBase | Alternativen. |
| boundsRectangle | Rectangle | Målbilden avgränsar rektangeln. Ställ in den tomma rektangeln för användningskällans gränser. |

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)


