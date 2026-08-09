---
title: "Image.GetOriginalOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Image. Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode Save, l'image PNG de sortie sera générée avec 8 bits par pixel. Pour éviter cela et enregistrer une image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode Save en tant que deuxième paramètre."
type: docs
weight: 190
url: /fr/net/aspose.psd/image/getoriginaloptions/
---
{{< psd/tize >}}
## Image.GetOriginalOptions method

Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [`Save`](../../datastreamsupporter/save/), l'image PNG de sortie sera générée avec 8 bits par pixel. Pour éviter cela et enregistrer une image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [`Save`](../save/) en tant que deuxième paramètre.

```csharp
public virtual ImageOptionsBase GetOriginalOptions()
```

### Valeur de retour

Les options basées sur les paramètres du fichier original.

### Voir aussi

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


