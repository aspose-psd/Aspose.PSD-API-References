---
title: "Clase FontSettings"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FontSettings. Configuración de fuentes del renderizador de formatos vectoriales PSD generales."
type: docs
weight: 4760
url: /es/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Configuración de fuentes del renderizador de formatos vectoriales PSD generales.

```csharp
public static class FontSettings
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Obtiene o establece el nombre predeterminado de la fuente. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Obtiene o establece un valor que indica si [obtener fuente alternativa]. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Borra todas las sustituciones de fuentes. |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Obtiene el nombre de fuente de Adobe por el nombre de la familia de fuentes. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Obtiene las carpetas predeterminadas de fuentes. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Obtiene la matriz de sustituciones de fuentes por el nombre de la fuente. |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Words busca fuentes TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Obtiene la fuente de sustitución más adecuada. Si todas las sustituciones no están permitidas, se devolverá la primera fuente permitida y disponible. Si no hay fuentes disponibles, se devolverá la fuente del argumento. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Determina si [la fuente está permitida] [el nombre de fuente especificado]. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Elimina el archivo de caché de fuentes. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Restablece la carpeta de fuentes y el nombre de fuente predeterminado al valor predeterminado del sistema. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Restringe el uso de fuentes mediante una lista de fuentes. Por favor, verifique los nombres reales de las fuentes antes de la restricción. Establezca la lista de fuentes permitidas a Null para eliminar las restricciones. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Establece la lista de sustituciones de fuentes. Si una fuente no está permitida, se buscará una sustitución. La primera fuente de la lista se usará primero. Si también está restringida, se seleccionará la siguiente fuente de la lista. Si la fuente no tiene sustituciones o todas las sustituciones no están permitidas, se usará la primera fuente permitida de la lista de fuentes permitidas. Si no hay fuentes permitidas y disponibles, la biblioteca intentará usar la fuente predeterminada del sistema aunque no esté permitida. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Este es un acceso directo a [`SetFontsFolders`](./setfontsfolders/) para establecer solo un directorio de fuentes. No se realizan comprobaciones en la carpeta de fuentes. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Establece las carpetas desde donde se cargan las fuentes TrueType y borra todas las fuentes cargadas. No se realizan comprobaciones en las carpetas de fuentes. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Actualiza la caché de fuentes para archivos PSD que contienen capas de texto. Este método garantiza que las fuentes de la carpeta fontsFolder mediante el método FontSettings.SetFontsFolder(fontsFolder) o después de restablecer fuentes usando FontSettings.Reset() se tengan en cuenta al procesar archivos PSD. Por favor, use este método cada vez que se llame a FontSettings.SetFontsFolder(fontsFolder) o FontSettings.Reset() para imágenes PSD. Sin llamar a este método no hay garantía de que las fuentes se actualicen. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


