---
title: "Metered.SetMeteredKey"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Metered. Définit la clé publique et privée du mode mesuré. Si vous achetez une licence mesurée lors du démarrage de l'application, cette API doit être appelée normalement, cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence et, si elle est en statut d'évaluation, appeler à nouveau cette API."
type: docs
weight: 40
url: /fr/net/aspose.psd/metered/setmeteredkey/
---
{{< psd/tize >}}
## Metered.SetMeteredKey method

Définit la clé publique et privée mesurée. Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, normalement cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, et si elle est en statut d'évaluation, appeler à nouveau cette API.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | String | clé publique |
| privateKey | String | clé privée |

### Voir aussi

* class [Metered](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


