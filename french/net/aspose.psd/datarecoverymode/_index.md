---
title: "Enum DataRecoveryMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.DataRecoveryMode enum. Le mode de récupération des données"
type: docs
weight: 740
url: /fr/net/aspose.psd/datarecoverymode/
---
{{< psd/tize >}}
## DataRecoveryMode enumeration

Le mode de récupération des données.

```csharp
public enum DataRecoveryMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Aucune récupération de données n'est implicite. Chaque fois que le format de fichier contient des données corrompues, l'exception appropriée est levée. |
| ConsistentRecover | `1` | Le mode de récupération cohérent tente de récupérer toutes les données tant que la corruption ne casse pas le format de fichier et permet un traitement ultérieur correct. |
| MaximalRecover | `2` | Le mode de récupération maximal récupère toutes les données même si le format de fichier a une structure corrompue et le traitement ultérieur peut entraîner des effets inattendus. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


