---
title: "Layer.Save"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Layer-metod. Sparar objektets data till den angivna strömmen"
type: docs
weight: 390
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

Sparar objektets data till den angivna strömmen.

```csharp
public override void Save(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen att spara objektets data till. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Vi bör inte anropa Save-metoden utan bildalternativ |

### Se även

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| alternativ | ImageOptionsBase | Alternativen. |

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Sparar objektets data till den angivna filplatsen.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen för att spara objektets data till. |
| overWrite | Boolean | om den är satt till `true` skrivs filens innehåll över, annars läggs till. |

### Se även

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen att spara bildens data till. |
| optionsBase | ImageOptionsBase | Sparaalternativen. |
| boundsRectangle | Rectangle | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| alternativ | ImageOptionsBase | Alternativen. |
| boundsRectangle | Rectangle | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


