---
title: "Clase StringFormat"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.StringFormat. Encapsula información de diseño de texto como la orientación de alineación y la visualización de tabulaciones, manipulaciones como la inserción de elipsis, sustitución de dígitos nacionales y características OpenType. Esta clase no puede heredarse."
type: docs
weight: 6170
url: /es/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Encapsula información de diseño de texto (como alineación, orientación y tabulaciones) manipulaciones de visualización (como inserción de elipsis y sustitución de dígitos nacionales) y características OpenType. Esta clase no puede heredarse.

```csharp
public sealed class StringFormat : DisposableObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Inicializa un nuevo objeto `StringFormat`. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Inicializa un nuevo objeto `StringFormat` a partir del objeto `StringFormat` existente especificado. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Inicializa un nuevo objeto `StringFormat` con la enumeración [`StringFormatFlags`](../stringformatflags/) y el idioma especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Obtiene un objeto `StringFormat` genérico predeterminado. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Obtiene un objeto `StringFormat` tipográfico genérico. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Obtiene o establece la información de alineación de texto en el plano vertical. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Obtiene o establece el identificador de carácter personalizado. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Obtiene o establece el idioma que se usa cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Obtiene o establece el método que se utilizará para la sustitución de dígitos. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Obtiene el número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Obtiene o establece una enumeración [`StringFormatFlags`](../stringformatflags/) que contiene información de formato. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Obtiene o establece el objeto [`HotkeyPrefix`](../hotkeyprefix/) para este objeto `StringFormat`. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Obtiene o establece la alineación de línea en el plano horizontal. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Obtiene o establece la enumeración [`StringTrimming`](../stringtrimming/) para este objeto `StringFormat`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Crea una clonación profunda de este objeto `StringFormat`. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Comprueba si los objetos son iguales. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Obtiene el código hash del objeto actual. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Establece las tabulaciones para este objeto `StringFormat`. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Convierte este objeto `StringFormat` a una cadena legible por humanos. |

### Ver también

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


