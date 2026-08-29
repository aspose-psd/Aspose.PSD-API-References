---
title: "Layer.Save"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Layer. Enregistre les données de l'objet dans le flux spécifié"
type: docs
weight: 390
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

Enregistre les données de l'objet dans le flux spécifié.

```csharp
public override void Save(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel enregistrer les données de l'objet. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Nous ne devrions pas appeler la méthode Save sans options d'image |

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |

### Voir aussi

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier pour enregistrer les données de l'objet. |
| overWrite | Booléen | si défini sur `true` réécrit le contenu du fichier, sinon une addition sera effectuée. |

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux où enregistrer les données de l'image. |
| optionsBase | ImageOptionsBase | Les options d'enregistrement. |
| boundsRectangle | Rectangle | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites de la source. |

### Voir aussi

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |
| boundsRectangle | Rectangle | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites de la source. |

### Voir aussi

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


