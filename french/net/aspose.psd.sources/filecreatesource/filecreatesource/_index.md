---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur FileCreateSource. Initialise une nouvelle instance de la classe FileCreateSource"
type: docs
weight: 10
url: /fr/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

Initialise une nouvelle instance de la classe [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à créer. |

## Exemples

Cet exemple crée un nouveau fichier Image à un emplacement disque spécifié par la propriété Source de l'instance BmpOptions. Si le deuxième paramètre n'est pas passé au constructeur de FileCreateSource, alors, par défaut, le fichier à créer a la propriété IsTemporal définie sur True. Avec IsTemporal défini sur True, aucun fichier ne sera enregistré sur le disque à la fin de l'exécution.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Crée une instance de PsdOptions et définit ses différentes propriétés.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créez une instance de FileCreateSource et assignez‑la comme Source pour l'instance de PsdOptions
//Si le deuxième paramètre n'est pas passé, alors, par défaut, le fichier a IsTemporal défini sur True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Crée une instance de Image 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Effectuez un traitement d'image.
}
```

### Voir aussi

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initialise une nouvelle instance de la classe [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à créer. |
| isTemporal | Booléen | Si défini sur `true`, le fichier créé sera temporaire. |

## Exemples

Cet exemple crée un nouveau fichier Image à un emplacement disque spécifié par la propriété Source de l'instance PsdOptions. Plusieurs propriétés de l'instance PsdOptions sont définies avant la création de l'image réelle. En particulier la propriété Source, qui fait référence à l'emplacement disque réel dans ce cas.

```csharp
[C#]

//Créez une instance de PsdOptions et définissez ses différentes propriétés
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créez une instance de FileCreateSource et assignez‑la comme Source pour l'instance de PsdOptions
//Le deuxième paramètre booléen détermine si le fichier à créer est temporaire (IsTemporal) ou non
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Créez une instance d'Image et initialisez‑la avec une instance de PsdOptions en appelant la méthode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Effectuez un traitement d'image.

    // enregistrez toutes les modifications
    image.Save();
}
```

### Voir aussi

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


