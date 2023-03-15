---
title: Class StringFormat
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.StringFormat clase. Encapsula información de diseño de texto como alineación orientación y tabulaciones manipulaciones de visualización como inserción de puntos suspensivos y sustitución de dígitos nacionales y funciones OpenType. Esta clase no se puede heredar.
type: docs
weight: 5670
url: /es/net/aspose.psd/stringformat/
---
## StringFormat class

Encapsula información de diseño de texto (como alineación, orientación y tabulaciones), manipulaciones de visualización (como inserción de puntos suspensivos y sustitución de dígitos nacionales) y funciones OpenType. Esta clase no se puede heredar.

```csharp
public sealed class StringFormat : DisposableObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Inicializa un nuevo`StringFormat` objeto. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Inicializa un nuevo`StringFormat` objeto del existente especificado`StringFormat` objeto. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Inicializa un nuevo`StringFormat` objeto con el especificado[`StringFormatFlags`](../stringformatflags/) enumeración e idioma. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Obtiene un valor predeterminado genérico`StringFormat` objeto. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Obtiene una tipografía genérica`StringFormat` objeto. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Obtiene o establece información de alineación de texto en el plano vertical. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Obtiene o establece el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Obtiene o establece el método que se utilizará para la sustitución de dígitos. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Obtiene el número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Obtiene o establece un[`StringFormatFlags`](../stringformatflags/) enumeración que contiene información de formato. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Obtiene o establece el[`HotkeyPrefix`](../hotkeyprefix/) objeto para esto`StringFormat` objeto. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Obtiene o establece la alineación de la línea en el plano horizontal. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por el[`PageUnit`](../graphics/pageunit/) propiedad. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Obtiene o establece el[`StringTrimming`](../stringtrimming/) enumeración para esto`StringFormat` objeto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Crea un clon profundo de este`StringFormat` objeto. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Establece tabulaciones para esto`StringFormat` objeto. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Convierte esto`StringFormat` objeto a una cadena legible por humanos. |

### Ver también

* class [DisposableObject](../disposableobject/)
* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


