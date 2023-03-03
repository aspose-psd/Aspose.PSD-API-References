---
title: Class ImageAttributes
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.ImageAttributes clase. UnImageAttributes El objeto contiene información sobre cómo se manipulan los colores del mapa de bits y del metarchivo durante la representación. UnImageAttributes El objeto mantiene varias configuraciones de ajuste de color incluidas matrices de ajuste de color matrices de ajuste de escala de grises valores de corrección gamma tablas de mapa de color y valores de umbral de color. Durante el renderizado los colores se pueden corregir oscurecer aclarar y eliminar. Para aplicar tales manipulaciones inicialice unImageAttributesobjeto y pasar el camino de eseImageAttributes objeto junto con la trayectoria de unImage  al método DrawImage.
type: docs
weight: 4610
url: /es/net/aspose.psd/imageattributes/
---
## ImageAttributes class

Un`ImageAttributes` El objeto contiene información sobre cómo se manipulan los colores del mapa de bits y del metarchivo durante la representación. Un`ImageAttributes` El objeto mantiene varias configuraciones de ajuste de color, incluidas matrices de ajuste de color, matrices de ajuste de escala de grises, valores de corrección gamma, tablas de mapa de color y valores de umbral de color. Durante el renderizado, los colores se pueden corregir, oscurecer, aclarar y eliminar. Para aplicar tales manipulaciones, inicialice un`ImageAttributes`objeto y pasar el camino de ese`ImageAttributes` objeto (junto con la trayectoria de un[`Image`](../image/) ) al método DrawImage.

```csharp
public sealed class ImageAttributes
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Constructor predeterminado |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Borra la tabla de reasignación de color del pincel de este`ImageAttributes` objeto. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Borra la clave de color (rango de transparencia) para la categoría predeterminada. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Borra la clave de color (rango de transparencia) para una categoría específica. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Borra la matriz de ajuste de color para la categoría predeterminada. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Borra la matriz de ajuste de color para una categoría específica. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Deshabilita la corrección gamma para la categoría predeterminada. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Deshabilita la corrección gamma para una categoría específica. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Borra la configuración NoOp para la categoría predeterminada. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Borra la configuración de NoOp para una categoría específica. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría específica. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Borra la configuración del perfil de color del canal de salida para la categoría predeterminada. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Borra la configuración del perfil de color del canal de salida para una categoría específica. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Borra la tabla de reasignación de color para la categoría predeterminada. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Borra la tabla de reasignación de colores para una categoría específica. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Borra el valor de umbral para la categoría predeterminada. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Borra el valor de umbral para una categoría específica. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Establece la tabla de reasignación de color para la categoría de pincel. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Establece la clave de color para la categoría predeterminada. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Establece la clave de color (rango de transparencia) para una categoría específica. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría específica. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Establece la matriz de ajuste de color para una categoría específica. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Establece el valor gamma para la categoría predeterminada. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Establece el valor gamma para una categoría específica. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Desactiva el ajuste de color para la categoría predeterminada. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Desactiva el ajuste de color para una categoría específica. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría específica. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Establece el archivo de perfil de color del canal de salida para la categoría predeterminada. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Establece el archivo de perfil de color del canal de salida para una categoría específica. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Establece la tabla de reasignación de colores para la categoría predeterminada. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Establece la tabla de reasignación de colores para una categoría específica. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Establece el umbral (rango de transparencia) para la categoría predeterminada. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Establece el umbral (rango de transparencia) para una categoría específica. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Establece el modo de ajuste que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Establece el modo de ajuste y el color que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Establece el modo de ajuste y el color que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


