---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode GraphicsPath. Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés"
type: docs
weight: 90
url: /fr/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés.

```csharp
public void Flatten()
```

### Voir aussi

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Applique la transformation spécifiée puis convertit chaque courbe de ce [`GraphicsPath`](../) en une séquence de segments de ligne connectés.

```csharp
public void Flatten(Matrix matrix)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | Matrix | Une [`Matrix`](../../matrix/) permettant de transformer ce [`GraphicsPath`](../) avant l'aplatissement. |

### Voir aussi

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Convertit chaque courbe de ce [`GraphicsPath`](../) en une séquence de segments de ligne connectés.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | Matrix | Une [`Matrix`](../../matrix/) permettant de transformer ce [`GraphicsPath`](../) avant l'aplatissement. |
| planéité | Single | Spécifie l'erreur maximale autorisée entre la courbe et son approximation aplatie. Une valeur de 0,25 est la valeur par défaut. Réduire la valeur de planéité augmentera le nombre de segments de ligne dans l'approximation. |

### Voir aussi

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


