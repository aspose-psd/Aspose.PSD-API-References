---
title: Layer.Save
second_title: Référence de l'API Aspose.PSD pour .NET
description: Layer méthode. Enregistre les données de lobjet dans le flux spécifié.
type: docs
weight: 370
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

Enregistre les données de l'objet dans le flux spécifié.

```csharp
public override void Save(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel enregistrer les données de l'objet. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Nous ne devrions pas appeler la méthode Save sans les options Image |

### Voir également

* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |

### Voir également

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier dans lequel enregistrer les données de l'objet. |
| overWrite | Boolean | si réglé sur`vrai` écraser le contenu du fichier, sinon l'ajout se produira. |

### Voir également

* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel enregistrer les données de l'image. |
| optionsBase | ImageOptionsBase | Les options de sauvegarde. |
| boundsRectangle | Rectangle | L'image de destination délimite le rectangle. Définissez le rectangle vide pour utiliser les limites de la source. |

### Voir également

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |
| boundsRectangle | Rectangle | L'image de destination délimite le rectangle. Définissez le rectangle vide pour utiliser les limites de la source. |

### Voir également

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)


