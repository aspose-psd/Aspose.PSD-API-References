---
title: "Font.Font"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur Font. Initialise un nouveau Font qui utilise le Font existant spécifié et l'énumération FontStyle."
type: docs
weight: 10
url: /fr/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Initialise un nouveau [`Font`](../) qui utilise le [`Font`](../) existant spécifié et l'énumération [`FontStyle`](../../fontstyle/).

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| prototype | Font | Le [`Font`](../) existant à partir duquel créer le nouveau [`Font`](../). |
| newStyle | FontStyle | Le [`FontStyle`](../../fontstyle/) à appliquer au nouveau [`Font`](../). Plusieurs valeurs de l'énumération [`FontStyle`](../../fontstyle/) peuvent être combinées avec l'opérateur OR. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *prototype* est nul. |

### Voir aussi

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Initialise un nouveau [`Font`](../) en utilisant une taille spécifiée. Le jeu de caractères est défini sur Default, l'unité graphique sur Point, le style de police sur Regular.

```csharp
public Font(string fontName, float emSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne du nom du [`Font`](../). |
| emSize | Single | La taille en em, en points, de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir aussi

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initialise un nouveau [`Font`](../) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur Default, l'unité graphique sur Point.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne du nom du [`Font`](../). |
| emSize | Single | La taille en em, en points, de la nouvelle police. |
| style | FontStyle | Le [`FontStyle`](../../fontstyle/) de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir aussi

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initialise un nouveau [`Font`](../) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur Default, le style est défini sur Regular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne du nom du [`Font`](../). |
| emSize | Single | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre *unit*. |
| unit | GraphicsUnit | L'[`GraphicsUnit`](../../graphicsunit/) de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir aussi

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initialise un nouveau [`Font`](../) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne du nom du [`Font`](../). |
| emSize | Single | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre *unit*. |
| style | FontStyle | Le [`FontStyle`](../../fontstyle/) de la nouvelle police. |
| unit | GraphicsUnit | L'[`GraphicsUnit`](../../graphicsunit/) de la nouvelle police. |
| characterSet | CharacterSet | Un jeu de caractères à utiliser pour cette police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir aussi

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initialise un nouveau [`Font`](../) en utilisant une taille, un style et une unité spécifiés.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne du nom du [`Font`](../). |
| emSize | Single | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre *unit*. |
| style | FontStyle | Le [`FontStyle`](../../fontstyle/) de la nouvelle police. |
| unit | GraphicsUnit | L'[`GraphicsUnit`](../../graphicsunit/) de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir aussi

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


