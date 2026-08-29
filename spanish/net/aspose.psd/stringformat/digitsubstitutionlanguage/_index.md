---
title: "StringFormat.DigitSubstitutionLanguage"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad StringFormat. Obtiene o establece el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales."
type: docs
weight: 60
url: /es/net/aspose.psd/stringformat/digitsubstitutionlanguage/
---
{{< psd/tize >}}
## StringFormat.DigitSubstitutionLanguage property

Obtiene o establece el idioma que se usa cuando los dígitos locales se sustituyen por dígitos occidentales.

```csharp
public int DigitSubstitutionLanguage { get; set; }
```

### Property Value

Un identificador de idioma de Soporte de Idioma Nacional (NLS) que identifica el idioma que se usará cuando los dígitos locales se sustituyan por dígitos occidentales. Puede pasar la propiedad LCID de un objeto CultureInfo como el identificador de idioma NLS. Por ejemplo, suponga que crea un objeto CultureInfo pasando la cadena "ar-EG" al constructor de CultureInfo. Si pasa la propiedad LCID de ese objeto CultureInfo junto con el método StringDigitSubstitute tradicional, entonces los dígitos árabe-indios se sustituirán por dígitos occidentales en tiempo de visualización.

## Observaciones

El setter se introduce para el método obsoleto SetDigitSubstitution.

### Ver también

* class [StringFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


