---
title: "Clase Graphics"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Graphics. Representa los gráficos según el motor gráfico usado en el ensamblado actual"
type: docs
weight: 4780
url: /es/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Representa los gráficos según el motor gráfico usado en el ensamblado actual.

```csharp
public sealed class Graphics
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Graphics](graphics/)(Image) | Inicializa una nueva instancia de la clase `Graphics`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Obtiene o establece la región de recorte. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Obtiene o establece la calidad de composición. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Obtiene la resolución horizontal de este Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Obtiene la resolución vertical de este Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Obtiene la imagen. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Obtiene o establece el modo de interpolación. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Obtiene un valor que indica si los gráficos están en estado de llamada BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Obtiene o establece la escala entre unidades del mundo y unidades de página para este Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Obtiene o establece la unidad de medida usada para las coordenadas de página en este Aspose.PSD.Graphics. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Obtiene o establece opciones de imagen, usadas para crear imágenes vectoriales pintables para dibujar. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Obtiene o establece el modo de suavizado. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Obtiene o establece la sugerencia de renderizado de texto. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Obtiene o establece una copia de la transformación geométrica del mundo para este `Graphics`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Inicia el almacenamiento en caché de las siguientes operaciones gráficas. Los efectos gráficos aplicados después no se aplicarán inmediatamente; en su lugar, el EndUpdate provocará la aplicación de todos los efectos de una vez. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Limpia la superficie gráfica usando el color especificado. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [`Rectangle`](../rectangle/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [`RectangleF`](../rectanglef/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Dibuja una spline Bézier definida por cuatro estructuras [`Point`](../point/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Dibuja una spline Bézier definida por cuatro estructuras [`PointF`](../pointf/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Dibuja una spline Bézier definida por cuatro pares ordenados de coordenadas que representan puntos. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [`PointF`](../pointf/). |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [`Point`](../point/). |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [`PointF`](../pointf/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno Alternado. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [`Point`](../point/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno Alternado. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [`PointF`](../pointf/) usando una tensión especificada. Este método usa el modo de relleno Alternado predeterminado. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [`Point`](../point/) usando una tensión especificada. Este método usa el modo de relleno Alternado predeterminado. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../pointf/). Este método usa una tensión predeterminada de 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [`Point`](../point/). |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../pointf/) usando una tensión especificada. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [`Point`](../point/) usando una tensión especificada. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../pointf/). El dibujo comienza desplazado desde el inicio de la matriz. Este método usa una tensión predeterminada de 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [`Point`](../point/) usando una tensión especificada. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Dibuja una elipse especificada por una estructura [`Rectangle`](../rectangle/) delimitadora. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Dibuja una elipse definida por una estructura [`RectangleF`](../rectanglef/) delimitadora. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Dibuja la [`Image`](./image/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Dibuja la [`Image`](./image/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Dibuja la [`Image`](./image/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Dibuja la imagen especificada, usando su tamaño físico original, en la ubicación especificada por un par de coordenadas. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Dibuja la porción especificada de la *image* especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Dibuja la [`Image`](./image/) especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para ajustarla al rectángulo especificado. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Dibuja una línea que conecta dos estructuras [`Point`](../point/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Dibuja una línea que conecta dos estructuras [`PointF`](../pointf/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [`PointF`](../pointf/). |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [`Point`](../point/). |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Dibuja un [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [`Rectangle`](../rectangle/) y dos líneas radiales. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [`RectangleF`](../rectanglef/) y dos líneas radiales. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Dibuja un polígono definido por una matriz de estructuras [`PointF`](../pointf/). |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Dibuja un polígono definido por una matriz de estructuras [`Point`](../point/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Dibuja un rectángulo especificado por una estructura [`Rectangle`](../rectangle/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Dibuja un rectángulo especificado por una estructura [`RectangleF`](../rectanglef/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Dibuja una serie de rectángulos especificados por estructuras [`RectangleF`](../rectanglef/). |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Dibuja una serie de rectángulos especificados por estructuras [`Rectangle`](../rectangle/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [`Brush`](../brush/) y [`Font`](../font/) especificados. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [`Brush`](../brush/) y [`Font`](../font/) especificados. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [`Brush`](../brush/) y [`Font`](../font/) especificados. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [`Brush`](../brush/) y [`Font`](../font/) usando los atributos de formato del [`StringFormat`](../stringformat/) especificado. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [`Brush`](../brush/) y [`Font`](../font/) usando los atributos de formato del [`StringFormat`](../stringformat/) especificado. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [`Brush`](../brush/) y [`Font`](../font/) usando los atributos de formato del [`StringFormat`](../stringformat/) especificado. |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Finaliza el almacenamiento en caché de las operaciones gráficas iniciadas después de que se llamó a BeginUpdate. Las operaciones gráficas precedentes se aplicarán de una vez al llamar a este método. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [`PointF`](../pointf/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno Alternado. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [`Point`](../point/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno Alternado. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [`PointF`](../pointf/) usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [`Point`](../point/) usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [`PointF`](../pointf/) utilizando el modo de relleno y la tensión especificados. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [`Point`](../point/) utilizando el modo de relleno y la tensión especificados. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [`Rectangle`](../rectangle/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [`RectangleF`](../rectanglef/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Rellena el interior de un [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [`RectangleF`](../rectanglef/) y dos líneas radiales. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [`RectangleF`](../rectanglef/) y dos líneas radiales. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [`PointF`](../pointf/) y Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [`Point`](../point/) y Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [`PointF`](../pointf/) utilizando el modo de relleno especificado. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [`Point`](../point/) utilizando el modo de relleno especificado. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Rellena el interior de un rectángulo especificado mediante una estructura [`Rectangle`](../rectangle/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Rellena el interior de un rectángulo especificado mediante una estructura [`RectangleF`](../rectanglef/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Rellena los interiores de una serie de rectángulos especificados por estructuras [`RectangleF`](../rectanglef/). |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Rellena los interiores de una serie de rectángulos especificados por estructuras [`Rectangle`](../rectangle/). |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Rellena el interior de un [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Multiplica la [`Matrix`](../matrix/) que representa la transformación geométrica local de este `Graphics` por la [`Matrix`](../matrix/) especificada, anteponiendo la [`Matrix`](../matrix/) especificada. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplica la [`Matrix`](../matrix/) que representa la transformación geométrica local de este `Graphics` por la [`Matrix`](../matrix/) especificada en el orden especificado. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Restablece la propiedad [`Transform`](./transform/) a la identidad. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rota la transformación geométrica local en la cantidad especificada en el orden indicado. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Escala la transformación geométrica local en las cantidades especificadas en el orden indicado. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Traslada la transformación geométrica local en las dimensiones especificadas en el orden indicado. |

## Ejemplos

Este ejemplo usa la clase Graphics para crear formas primitivas en la superficie de la Imagen. Para demostrar la operación, el ejemplo crea una nueva Imagen en formato PSD y dibuja formas primitivas en la superficie de la Imagen usando los métodos Draw expuestos por la clase Graphics, luego la exporta al formato de archivo PSD.

```csharp
[C#]

//Crea una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie Graphics
    graphics.Clear(Color.Wheat);

    //Dibuje un arco especificando el objeto Pen con color negro, 
    //un Rectángulo que rodea el arco, ángulo de inicio y ángulo de barrido
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Dibuje una curva Bézier especificando el objeto Pen con color azul y los puntos coordenados.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Dibuje una curva especificando el objeto Pen con color verde y una matriz de puntos
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Dibuje una elipse usando el objeto Pen y un rectángulo circundante
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dibuje una línea 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Dibuje un segmento de pastel
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Dibuje un polígono especificando el objeto Pen con color rojo y una matriz de puntos
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dibuje un rectángulo
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Cree un objeto SolidBrush y establezca sus diversas propiedades
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Dibuje una cadena usando el objeto SolidBrush y la Fuente, en un punto específico
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Cree una instancia de PngOptions y establezca sus diversas propiedades
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Guarda todos los cambios.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


