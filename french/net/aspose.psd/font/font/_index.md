---
title: Font.Font
second_title: Référence de l'API Aspose.PSD pour .NET
description: Font constructeur. Initialise un nouveauFont qui utilise lexistant spécifiéFont etFontStyle énumération.
type: docs
weight: 10
url: /fr/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Initialise un nouveau[`Font`](../) qui utilise l'existant spécifié[`Font`](../) et[`FontStyle`](../../fontstyle/) énumération.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| prototype | Font | L'existant[`Font`](../) à partir de laquelle créer le nouveau[`Font`](../). |
| newStyle | FontStyle | Le[`FontStyle`](../../fontstyle/) s'appliquer au nouveau[`Font`](../) . Plusieurs valeurs de la[`FontStyle`](../../fontstyle/) l'énumération peut être combinée avec l'opérateur OR. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *prototype* est nul. |

### Voir également

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* espace de noms [Aspose.PSD](../../font/)
* Assemblée [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Initialise un nouveau[`Font`](../) en utilisant une taille spécifiée. Le jeu de caractères est défini surDefault , l'unité graphique àPoint , le style de police àRegular .

```csharp
public Font(string fontName, float emSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne de[`Font`](../) nom. |
| emSize | Single | La taille em, en points, de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, s'évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir également

* class [Font](../)
* espace de noms [Aspose.PSD](../../font/)
* Assemblée [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initialise un nouveau[`Font`](../) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini surDefault , l'unité graphique àPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne de[`Font`](../) nom. |
| emSize | Single | La taille em, en points, de la nouvelle police. |
| style | FontStyle | Le[`FontStyle`](../../fontstyle/) de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, s'évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir également

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* espace de noms [Aspose.PSD](../../font/)
* Assemblée [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initialise un nouveau[`Font`](../) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini surDefault le style est défini surRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne de[`Font`](../) nom. |
| emSize | Single | La taille em de la nouvelle police dans les unités spécifiées par le*unit* paramètre. |
| unit | GraphicsUnit | Le[`GraphicsUnit`](../../graphicsunit/) de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, s'évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir également

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* espace de noms [Aspose.PSD](../../font/)
* Assemblée [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initialise un nouveau[`Font`](../) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne de[`Font`](../) nom. |
| emSize | Single | La taille em de la nouvelle police dans les unités spécifiées par le*unit* paramètre. |
| style | FontStyle | Le[`FontStyle`](../../fontstyle/) de la nouvelle police. |
| unit | GraphicsUnit | Le[`GraphicsUnit`](../../graphicsunit/) de la nouvelle police. |
| characterSet | CharacterSet | Jeu de caractères à utiliser pour cette police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, s'évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir également

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* espace de noms [Aspose.PSD](../../font/)
* Assemblée [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initialise un nouveau[`Font`](../) en utilisant une taille, un style et une unité spécifiés.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontName | String | Une représentation sous forme de chaîne de[`Font`](../) nom. |
| emSize | Single | La taille em de la nouvelle police dans les unités spécifiées par le*unit* paramètre. |
| style | FontStyle | Le[`FontStyle`](../../fontstyle/) de la nouvelle police. |
| unit | GraphicsUnit | Le[`GraphicsUnit`](../../graphicsunit/) de la nouvelle police. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* est inférieur ou égal à 0, s'évalue à l'infini ou n'est pas un nombre valide. |
| ArgumentNullException | *fontName* est nul. |

### Voir également

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* espace de noms [Aspose.PSD](../../font/)
* Assemblée [Aspose.PSD](../../../)


