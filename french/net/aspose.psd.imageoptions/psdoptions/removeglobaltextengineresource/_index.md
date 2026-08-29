---
title: "PsdOptions.RemoveGlobalTextEngineResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdOptions. Obtient ou définit une valeur indiquant s'il faut supprimer la ressource du moteur de texte global. Utilisé pour certains fichiers PSD à couches de texte uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après le traitement, généralement en raison de polices manquantes dans les calques de texte. Après avoir utilisé cette option, l'utilisateur doit, dans le fichier ouvert avec Photoshop, choisir le menu Texte → Traiter les polices manquantes. Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner des modifications du rendu final."
type: docs
weight: 90
url: /fr/net/aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/
---
{{< psd/tize >}}
## PsdOptions.RemoveGlobalTextEngineResource property

Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement lié aux calques de texte avec polices manquantes). Après avoir utilisé cette option, l'utilisateur doit effectuer dans le fichier ouvert avec Photoshop : Menu \"Text\" -&gt; \"Process absent fonts\". Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner des modifications de la mise en page finale.

```csharp
public bool RemoveGlobalTextEngineResource { get; set; }
```

### Property Value

`true` si [remove global text engine resource] ; sinon, `false`.

### Voir aussi

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


