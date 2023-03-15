---
title: GraphicsPath.Flatten
second_title: Référence de l'API Aspose.PSD pour .NET
description: GraphicsPath méthode. Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés.
type: docs
weight: 90
url: /fr/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés.

```csharp
public void Flatten()
```

### Voir également

* class [GraphicsPath](../)
* espace de noms [Aspose.PSD](../../graphicspath/)
* Assemblée [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Applique la transformation spécifiée, puis convertit chaque courbe dans cette[`GraphicsPath`](../) en une séquence de segments de ligne connectés.

```csharp
public void Flatten(Matrix matrix)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| matrix | Matrix | UN[`Matrix`](../../matrix/) par lequel transformer ce[`GraphicsPath`](../) avant d'aplatir. |

### Voir également

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* espace de noms [Aspose.PSD](../../graphicspath/)
* Assemblée [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Convertit chaque courbe dans ce[`GraphicsPath`](../) en une séquence de segments de ligne connectés.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| matrix | Matrix | UN[`Matrix`](../../matrix/) par lequel transformer ce[`GraphicsPath`](../) avant d'aplatir. |
| flatness | Single | Spécifie l'erreur maximale autorisée entre la courbe et son approximation aplatie. Une valeur de 0,25 est la valeur par défaut. La réduction de la valeur de planéité augmentera le nombre de segments de ligne dans l'approximation. |

### Voir également

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* espace de noms [Aspose.PSD](../../graphicspath/)
* Assemblée [Aspose.PSD](../../../)


