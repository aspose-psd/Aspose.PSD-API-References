---
title: "StringFormat.DigitSubstitutionLanguage"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété StringFormat. Obtient ou définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux."
type: docs
weight: 60
url: /fr/net/aspose.psd/stringformat/digitsubstitutionlanguage/
---
{{< psd/tize >}}
## StringFormat.DigitSubstitutionLanguage property

Obtient ou définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux.

```csharp
public int DigitSubstitutionLanguage { get; set; }
```

### Property Value

Un identifiant de langue National Language Support (NLS) qui identifie la langue qui sera utilisée lorsque les chiffres locaux sont remplacés par des chiffres occidentaux. Vous pouvez transmettre la propriété LCID d'un objet CultureInfo comme identifiant de langue NLS. Par exemple, supposons que vous créez un objet CultureInfo en passant la chaîne "ar-EG" à un constructeur CultureInfo. Si vous transmettez la propriété LCID de cet objet CultureInfo avec la méthode StringDigitSubstitute, alors les chiffres arabes-indic seront substitués aux chiffres occidentaux au moment de l'affichage.

## Remarques

Le mutateur est introduit pour la méthode obsolète SetDigitSubstitution.

### Voir aussi

* class [StringFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


