---
title: FileCreateSource.FileCreateSource
second_title: Référence de l'API Aspose.PSD pour .NET
description: FileCreateSource constructeur. Initialise une nouvelle instance duFileCreateSource classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Initialise une nouvelle instance du[`FileCreateSource`](../) classe.

```csharp
public FileCreateSource(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à créer. |

### Exemples

Cet exemple crée un nouveau fichier image à un emplacement du disque spécifié par la propriété Source de l'instance BmpOptions. Si le deuxième paramètre n'est pas passé au constructeur de FileCreateSource, alors par défaut le fichier à créer a la propriété IsTemporal définie sur True. Avec IsTemporal défini sur True, aucun fichier ne sera enregistré sur le disque à la fin de l'exécution.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
// Crée une instance de PsdOptions et définit ses différentes propriétés
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de PsdOptions
// Si le deuxième paramètre n'est pas passé, alors par défaut le fichier a IsTemporal défini sur True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

// Crée une instance de Image 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // faire du traitement d'image
}
```

### Voir également

* class [FileCreateSource](../)
* espace de noms [Aspose.PSD.Sources](../../filecreatesource/)
* Assemblée [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initialise une nouvelle instance du[`FileCreateSource`](../) classe.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à créer. |
| isTemporal | Boolean | Si réglé sur`vrai` le fichier créé sera temporel. |

### Exemples

Cet exemple crée un nouveau fichier Image à un emplacement de disque spécifié par la propriété Source de l'instance PsdOptions. Plusieurs propriétés pour l'instance PsdOptions sont définies avant de créer l'image réelle. Surtout la propriété Source, qui fait référence à l'emplacement réel du disque dans ce cas.

```csharp
[C#]

//Créer une instance de PsdOptions et définir ses différentes propriétés
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de PsdOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est temporel ou non
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Créer une instance de Image et l'initialiser avec une instance de PsdOptions en appelant la méthode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // faire du traitement d'image

    // Enregistrer toutes les modifications
    image.Save();
}
```

### Voir également

* class [FileCreateSource](../)
* espace de noms [Aspose.PSD.Sources](../../filecreatesource/)
* Assemblée [Aspose.PSD](../../../)


