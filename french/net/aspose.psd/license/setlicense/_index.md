---
title: "License.SetLicense"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode License. Licence le composant"
type: docs
weight: 20
url: /fr/net/aspose.psd/license/setlicense/
---
{{< psd/tize >}}
## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licenseName)
```

## Remarques

Essaie de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier qui contient l'assembly du composant Aspose.

3. Le dossier qui contient l'assembly appelant du client.

4. Le dossier qui contient l'assembly d'entrée (démarrage).

5. Une ressource intégrée dans l'assembly appelant du client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Chemin explicite.

2. Une ressource intégrée dans l'assembly appelant du client.

## Exemples

Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Peut être un nom de fichier complet ou court ou le nom d'une ressource intégrée. Utilisez une chaîne vide pour passer en mode d'évaluation.

### Voir aussi

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

Licence le composant.

```csharp
public void SetLicense(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Un flux qui contient la licence. |

## Remarques

Utilisez cette méthode pour charger une licence à partir d'un flux.

## Exemples

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Voir aussi

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


