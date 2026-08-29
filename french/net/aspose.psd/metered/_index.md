---
title: "Classe Metered"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Metered. Fournit des méthodes pour définir la clé mesurée"
type: docs
weight: 5610
url: /fr/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Fournit des méthodes pour définir la clé mesurée.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Détermine si l'objet spécifié est égal à cette instance. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Obtient le nom du produit. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Définit la clé publique et privée mesurée. Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, normalement cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, et si elle est en statut d'évaluation, appeler à nouveau cette API. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Obtient le crédit de consommation |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Obtient la taille du fichier de consommation |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Vérifie si le mode mesuré est sous licence |

## Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


