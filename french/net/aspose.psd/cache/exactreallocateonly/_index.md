---
title: Cache.ExactReallocateOnly
second_title: Référence de l'API Aspose.PSD pour .NET
description: Cache propriété. Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation nest pas exacte les performances devraient être plus élevées.
type: docs
weight: 50
url: /fr/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être plus élevées.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Valeur de la propriété

`vrai` si la réaffectation est exacte ; sinon,`FAUX` .

### Remarques

La réallocation exacte effectuera la réallocation de mémoire supplémentaire uniquement jusqu'à la limite supérieure spécifiée. Lors du dépassement de la limite supérieure pour la mémoire en mémoire lors de la réallocation, les données mises en cache seront copiées sur le disque si possible. Lors du dépassement de la limite supérieure de la mémoire du disque lors de la réallocation, le l'exception appropriée est levée. Les performances devraient être plus élevées si cette option est désactivée car aucune copie supplémentaire ne sera effectuée si possible, cependant cela peut également conduire à dépasser les limites supérieures spécifiées pour la mémoire ou le disque.

### Voir également

* class [Cache](../)
* espace de noms [Aspose.PSD](../../cache/)
* Assemblée [Aspose.PSD](../../../)


