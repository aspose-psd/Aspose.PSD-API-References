---
title: "Clase ImageAttributes"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageAttributes. Un objeto ImageAttributes contiene información sobre cómo se manipulan los colores de mapas de bits y metafiles durante el renderizado. Un objeto ImageAttributes mantiene varios ajustes de color, incluidos matrices de ajuste de color, matrices de ajuste de escala de grises, valores de corrección gamma, tablas de mapa de colores y valores de umbral de color. Durante el renderizado, los colores pueden corregirse, oscurecerse, aclararse y eliminarse. Para aplicar dichas manipulaciones, inicializa un objeto ImageAttributes y pasa la ruta de ese objeto ImageAttributes junto con la ruta de una Image al método DrawImage."
type: docs
weight: 5080
url: /es/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

Un objeto `ImageAttributes` contiene información sobre cómo se manipulan los colores de mapas de bits y metafiles durante el renderizado. Un objeto `ImageAttributes` mantiene varios ajustes de color, incluidos matrices de ajuste de color, matrices de ajuste de escala de grises, valores de corrección gamma, tablas de mapa de colores y valores de umbral de color. Durante el renderizado, los colores pueden corregirse, oscurecerse, aclararse y eliminarse. Para aplicar dichas manipulaciones, inicializa un objeto `ImageAttributes` y pasa la ruta de ese objeto `ImageAttributes` (junto con la ruta de un [`Image`](../image/)) al método DrawImage.

```csharp
public sealed class ImageAttributes
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageAttributes](imageattributes/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Borra la tabla de remapeo de color del pincel de este objeto `ImageAttributes`. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Borra la clave de color (rango de transparencia) para la categoría predeterminada. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Borra la clave de color (rango de transparencia) para una categoría especificada. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Borra la matriz de ajuste de color para la categoría predeterminada. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Borra la matriz de ajuste de color para una categoría especificada. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Desactiva la corrección gamma para la categoría predeterminada. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Desactiva la corrección gamma para una categoría especificada. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Borra la configuración NoOp para la categoría predeterminada. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Borra la configuración NoOp para una categoría especificada. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Borra la configuración del perfil de color del canal de salida para la categoría predeterminada. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Borra la configuración del perfil de color del canal de salida para una categoría especificada. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Borra la tabla de remapeo de color para la categoría predeterminada. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Borra la tabla de remapeo de color para una categoría especificada. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Borra el valor de umbral para la categoría predeterminada. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Borra el valor de umbral para una categoría especificada. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Establece la tabla de remapeo de color para la categoría de pincel. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Establece la clave de color para la categoría predeterminada. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Establece la clave de color (rango de transparencia) para una categoría especificada. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría especificada. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Establece la matriz de ajuste de color para una categoría especificada. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Establece el valor gamma para la categoría predeterminada. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Establece el valor gamma para una categoría especificada. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Desactiva el ajuste de color para la categoría predeterminada. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Desactiva el ajuste de color para una categoría especificada. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Establece el archivo de perfil de color del canal de salida para la categoría predeterminada. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Establece el archivo de perfil de color del canal de salida para una categoría especificada. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Establece la tabla de remapeo de color para la categoría predeterminada. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Establece la tabla de remapeo de color para una categoría especificada. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Establece el umbral (rango de transparencia) para la categoría predeterminada. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Establece el umbral (rango de transparencia) para una categoría especificada. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Establece el modo de ajuste que se utiliza para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Establece el modo de ajuste y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Establece el modo de ajuste y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


