---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété Cache. Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures."
type: docs
weight: 50
url: /fr/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` si la réallocation est exacte ; sinon, `false`.

## Remarques

La réallocation exacte effectuera la réallocation de mémoire supplémentaire uniquement jusqu'à la limite supérieure spécifiée. Lors du passage de la limite supérieure pour la mémoire en cours d'exécution pendant la réallocation, les données en cache seront copiées sur le disque si possible. Lors du passage de la limite supérieure pour la mémoire disque pendant la réallocation, l'exception appropriée est levée. Les performances devraient être supérieures si cette option est désactivée, car aucune copie supplémentaire ne sera effectuée si possible ; cependant, cela peut également entraîner le dépassement des limites supérieures spécifiées pour la mémoire ou le disque.

### Voir aussi

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


