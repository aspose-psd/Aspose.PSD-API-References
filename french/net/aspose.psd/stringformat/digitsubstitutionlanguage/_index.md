---
title: StringFormat.DigitSubstitutionLanguage
second_title: Référence de l'API Aspose.PSD pour .NET
description: StringFormat propriété. Obtient ou définit la langue utilisée lorsque des chiffres locaux sont remplacés par des chiffres occidentaux.
type: docs
weight: 50
url: /fr/net/aspose.psd/stringformat/digitsubstitutionlanguage/
---
## StringFormat.DigitSubstitutionLanguage property

Obtient ou définit la langue utilisée lorsque des chiffres locaux sont remplacés par des chiffres occidentaux.

```csharp
public int DigitSubstitutionLanguage { get; set; }
```

### Valeur de la propriété

Un identifiant de langue National Language Support (NLS) qui identifie la langue qui sera utilisée lorsque des chiffres locaux sont remplacés par des chiffres occidentaux. Vous pouvez passer leLCID propriété d'unCultureInfo objet comme identifiant de langue NLS. Par exemple, supposons que vous créez unCultureInfo objet en passant la chaîne "ar-EG" à unCultureInfo constructeur. Si vous passez leLCID propriété de celui-ciCultureInfo objet avec. Traditional auStringDigitSubstitute) method, , les chiffres arabo-indiens seront remplacés par les chiffres occidentaux au moment de l'affichage.

### Remarques

Le setter est introduit pour la méthode obsolète SetDigitSubstitution.

### Voir également

* class [StringFormat](../)
* espace de noms [Aspose.PSD](../../stringformat/)
* Assemblée [Aspose.PSD](../../../)


