---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ImageAttributes. Définit le mode d'enroulement utilisé pour décider comment répéter une texture sur une forme ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit."
type: docs
weight: 210
url: /fr/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

Définit le mode d'enroulement utilisé pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | WrapMode | Un élément de [`WrapMode`](../../wrapmode/) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |

### Voir aussi

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | WrapMode | Un élément de [`WrapMode`](../../wrapmode/) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |
| color | Color | Un objet [`ImageAttributes`](../) qui spécifie la couleur des pixels à l'extérieur d'une image rendue. Cette couleur est visible si le paramètre mode est réglé sur Clamp et que le rectangle source passé à DrawImage est plus grand que l'image elle-même. |

### Voir aussi

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | WrapMode | Un élément de [`WrapMode`](../../wrapmode/) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |
| couleur | Couleur | Un objet couleur qui spécifie la couleur des pixels à l'extérieur d'une image rendue. Cette couleur est visible si le paramètre mode est réglé sur Clamp et que le rectangle source passé à DrawImage est plus grand que l'image elle-même. |
| clamp | Booléen | Ce paramètre n'a aucun effet. Réglez-le sur false. |

### Voir aussi

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


