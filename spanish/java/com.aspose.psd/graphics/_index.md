---
title: "Graphics"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa los gráficos según el motor gráfico utilizado en el ensamblado actual."
type: docs
weight: 49
url: /es/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Representa los gráficos según el motor gráfico utilizado en el ensamblado actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Inicializa una nueva instancia de la clase Graphics. |
## Campos

| Campo | Descripción |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Obtiene el coeficiente de tamaño del estilo de texto en negrita. |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Obtiene el coeficiente de tamaño del estilo de texto en cursiva. |
## Métodos

| Método | Descripción |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Aplica el efecto. |
| [beginUpdate()](#beginUpdate--) | Inicia el almacenamiento en caché de las siguientes operaciones gráficas. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Borra la superficie gráfica usando el color especificado. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Dibuja un arco que representa una porción de una elipse especificada por una estructura RectangleF. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Dibuja una spline Bézier definida por cuatro estructuras Point. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Dibuja una spline Bézier definida por cuatro estructuras PointF. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Dibuja una spline Bézier definida por cuatro pares ordenados de coordenadas que representan puntos. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dibuja una serie de splines Bézier a partir de una matriz de  PointF  estructuras. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dibuja una serie de splines Bézier a partir de una matriz de  Point  estructuras. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dibuja una spline cardinal cerrada definida por una matriz de  PointF  estructuras. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Dibuja una spline cardinal cerrada definida por una matriz de  PointF  estructuras usando una tensión especificada. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dibuja una spline cardinal cerrada definida por una matriz de  Point  estructuras. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Dibuja una spline cardinal cerrada definida por una matriz de  Point  estructuras usando una tensión especificada. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dibuja una spline cardinal a través de una matriz especificada de  PointF  estructuras. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Dibuja una spline cardinal a través de una matriz especificada de  PointF  estructuras usando una tensión especificada. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Dibuja una spline cardinal a través de una matriz especificada de  PointF  estructuras. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Dibuja una spline cardinal a través de una matriz especificada de  PointF  estructuras usando una tensión especificada. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dibuja una spline cardinal a través de una matriz especificada de  Point  estructuras. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Dibuja una spline cardinal a través de una matriz especificada de  Point  estructuras usando una tensión especificada. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Dibuja una spline cardinal a través de una matriz especificada de  Point  estructuras usando una tensión especificada. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Dibuja una elipse especificada por una estructura de  Rectangle  delimitadora. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Dibuja una elipse definida por un  RectangleF  delimitador. |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Dibuja la  Image  especificada , usando su tamaño físico original, en la ubicación especificada. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Dibuja la  Image  especificada , usando su tamaño físico original, en la ubicación especificada. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Dibuja la  Image  especificada , usando su tamaño físico original, en la ubicación especificada. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Dibuja la imagen especificada, usando su tamaño físico original, en la ubicación especificada por un par de coordenadas. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para ajustarla al rectángulo especificado. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Dibuja una línea que conecta dos  Point  estructuras. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Dibuja una línea que conecta dos  PointF  estructuras. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dibuja una serie de segmentos de línea que conectan una matriz de  PointF  estructuras. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dibuja una serie de segmentos de línea que conectan una matriz de  Point  estructuras. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Dibuja un  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Dibuja una forma de pastel definida por una elipse especificada por una  Rectangle  estructura y dos líneas radiales. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Dibuja una forma de pastel definida por una elipse especificada por una  RectangleF  estructura y dos líneas radiales. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dibuja un polígono definido por una matriz de  PointF  estructuras. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dibuja un polígono definido por una matriz de  Point  estructuras. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Dibuja un rectángulo especificado por una  Rectangle  estructura. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Dibuja un rectángulo especificado por una  RectangleF  estructura. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Dibuja una serie de rectángulos especificados por  RectangleF  estructuras. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Dibuja una serie de rectángulos especificados por  Rectangle  estructuras. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado. |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Dibuja la cadena de texto especificada de forma compatible con Adobe en el rectángulo especificado con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Dibuja la cadena de texto especificada de forma compatible con Adobe en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados. |
| [endUpdate()](#endUpdate--) | Finaliza el almacenamiento en caché de las operaciones gráficas iniciadas después de que se llamó a BeginUpdate. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.PointF  estructuras. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.PointF  estructuras usando el modo de relleno especificado. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.PointF  estructuras usando el modo de relleno especificado y la tensión. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.Point  estructuras. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.Point  estructuras usando el modo de relleno especificado. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.Point  estructuras usando el modo de relleno especificado y la tensión. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura com.aspose.psd.Rectangle. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura com.aspose.psd.RectangleF. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Rellena el interior de un com.aspose.psd.graphicsPath. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Rellena el interior de una porción de pastel definida por una elipse especificada por una estructura com.aspose.psd.RectangleF y dos líneas radiales. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Rellena el interior de una porción de pastel definida por una elipse especificada por una estructura com.aspose.psd.RectangleF y dos líneas radiales. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.PointF y FillMode.Alternate. |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.PointF utilizando el modo de relleno especificado. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.Point y FillMode.Alternate. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.Point utilizando el modo de relleno especificado. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Rellena el interior de un rectángulo especificado por una estructura Rectangle. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Rellena el interior de un rectángulo especificado por una estructura RectangleF. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Rellena los interiores de una serie de rectángulos especificados por estructuras RectangleF. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Rellena los interiores de una serie de rectángulos especificados por estructuras Rectangle. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Rellena el interior de un com.aspose.psd.region. |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Obtiene o establece la región de recorte. |
| [getCompositingQuality()](#getCompositingQuality--) | Obtiene o establece la calidad de composición. |
| [getDpiX()](#getDpiX--) | Obtiene la resolución horizontal de este com.aspose.psd.graphics. |
| [getDpiY()](#getDpiY--) | Obtiene la resolución vertical de este com.aspose.psd.graphics. |
| [getImage()](#getImage--) | Obtiene la imagen. |
| [getInterpolationMode()](#getInterpolationMode--) | Obtiene o establece el modo de interpolación. |
| [getPageScale()](#getPageScale--) | Obtiene o establece la escala entre unidades del mundo y unidades de página para este com.aspose.psd.graphics. |
| [getPageUnit()](#getPageUnit--) | Obtiene o establece la unidad de medida utilizada para las coordenadas de página en este com.aspose.psd.graphics. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Obtiene o establece las opciones de imagen, usadas para crear imágenes vectoriales pintables para dibujar. |
| [getSmoothingMode()](#getSmoothingMode--) | Obtiene o establece el modo de suavizado. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Obtiene o establece la sugerencia de renderizado de texto. |
| [getTransform()](#getTransform--) | Obtiene o establece una copia de la transformación geométrica del mundo para este com.aspose.psd.graphics. |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Obtiene un valor que indica si los gráficos están en estado de llamada BeginUpdate. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Mide la cadena usando la clase [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Mide la cadena. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Mide la cadena de texto especificada con los parámetros especificados |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplica la com.aspose.psd.Matrix que representa la transformación geométrica local de este com.aspose.psd.Graphics por la com.aspose.psd.Matrix especificada, anteponiendo la com.aspose.psd.matrix especificada. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplica la com.aspose.psd.Matrix que representa la transformación geométrica local de este com.aspose.psd.Graphics por la com.aspose.psd.Matrix especificada en el orden especificado. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Restablece la propiedad com.aspose.psd.graphics.Transform a la identidad. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local en la cantidad especificada. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local en la cantidad especificada en el orden indicado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por las cantidades especificadas. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por las cantidades especificadas en el orden indicado. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Obtiene o establece la región de recorte. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Obtiene o establece la calidad de composición. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Obtiene o establece el modo de interpolación. |
| [setPageScale(float value)](#setPageScale-float-) | Obtiene o establece la escala entre unidades del mundo y unidades de página para este com.aspose.psd.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Obtiene o establece la unidad de medida utilizada para las coordenadas de página en este com.aspose.psd.graphics. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Obtiene o establece las opciones de imagen, usadas para crear imágenes vectoriales pintables para dibujar. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Obtiene o establece el modo de suavizado. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Obtiene o establece la sugerencia de renderizado de texto. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Obtiene o establece una copia de la transformación geométrica del mundo para este com.aspose.psd.graphics. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Inicializa una nueva instancia de la clase Graphics.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen de origen. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Obtiene el coeficiente de tamaño del estilo de texto en negrita.

Usando números mágicos ya que GDI siempre proporciona la medida solo para el estilo Regular.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Obtiene el coeficiente de tamaño del estilo de texto en cursiva.

Usando números mágicos ya que GDI siempre proporciona la medida solo para el estilo Regular.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Aplica el efecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| efecto | com.aspose.internal.IEffect | El efecto a aplicar. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Inicia el almacenamiento en caché de las siguientes operaciones gráficas. Los efectos gráficos aplicados después no se aplicarán inmediatamente; en su lugar, EndUpdate provocará la aplicación de todos los efectos a la vez.

Nota: los efectos después de que se llame a BeginUpdate no se aplicarán en caso de que no se llame a EndUpdate.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Borra la superficie gráfica usando el color especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | El color con el que se limpiará la superficie gráfica. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pluma que determina el color, el ancho y el estilo del arco. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Estructura RectangleF que define los límites de la elipse. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Dibuja un arco que representa una porción de una elipse especificada por una estructura RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pluma que determina el color, el ancho y el estilo del arco. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Estructura RectangleF que define los límites de la elipse. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pluma que determina el color, el ancho y el estilo del arco. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| ancho | float | Ancho del rectángulo que define la elipse. |
| alto | float | Altura del rectángulo que define la elipse. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pluma que determina el color, el ancho y el estilo del arco. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| ancho | int | Ancho del rectángulo que define la elipse. |
| alto | int | Altura del rectángulo que define la elipse. |
| startAngle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | int | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Dibuja una spline Bézier definida por cuatro estructuras Point.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  estructura que determina el color, el ancho y el estilo de la curva. |
| pt1 | [Point](../../com.aspose.psd/point) | Point  estructura que representa el punto de inicio de la curva. |
| pt2 | [Point](../../com.aspose.psd/point) | Point  estructura que representa el primer punto de control de la curva. |
| pt3 | [Point](../../com.aspose.psd/point) | Point  estructura que representa el segundo punto de control de la curva. |
| pt4 | [Point](../../com.aspose.psd/point) | Point  estructura que representa el punto final de la curva. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Dibuja una spline Bézier definida por cuatro estructuras PointF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la curva. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  estructura que representa el punto de inicio de la curva. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  estructura que representa el primer punto de control de la curva. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  estructura que representa el segundo punto de control de la curva. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  estructura que representa el punto final de la curva. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Dibuja una spline Bézier definida por cuatro pares ordenados de coordenadas que representan puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la curva. |
| x1 | float | La coordenada x del punto de inicio de la curva. |
| y1 | float | La coordenada y del punto de inicio de la curva. |
| x2 | float | La coordenada x del primer punto de control de la curva. |
| y2 | float | La coordenada y del primer punto de control de la curva. |
| x3 | float | La coordenada x del segundo punto de control de la curva. |
| y3 | float | La coordenada y del segundo punto de control de la curva. |
| x4 | float | La coordenada x del punto final de la curva. |
| y4 | float | La coordenada y del punto final de la curva. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Dibuja una serie de splines Bézier a partir de una matriz de  PointF  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Arreglo de estructuras  PointF  que representan los puntos que determinan la curva. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Dibuja una serie de splines Bézier a partir de una matriz de  Point  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Arreglo de estructuras  Point  que representan los puntos que determinan la curva. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Dibuja una spline cardinal cerrada definida por un arreglo de estructuras  PointF . Este método usa una tensión predeterminada de 0.5 y el modo de relleno  FillMode.Alternate .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Arreglo de estructuras  PointF  que definen la spline. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Dibuja una spline cardinal cerrada definida por un arreglo de estructuras  PointF  usando una tensión especificada. Este método usa el modo de relleno predeterminado  FillMode.Alternate .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Arreglo de estructuras  PointF  que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Dibuja una spline cardinal cerrada definida por un arreglo de estructuras  Point . Este método usa una tensión predeterminada de 0.5 y el modo de relleno  FillMode.Alternate .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Arreglo de estructuras  Point  que definen la spline. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Dibuja una spline cardinal cerrada definida por un arreglo de estructuras  Point  usando una tensión especificada. Este método usa el modo de relleno predeterminado  FillMode.Alternate .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Arreglo de estructuras  Point  que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Dibuja una spline cardinal a través de un arreglo especificado de estructuras  PointF . Este método usa una tensión predeterminada de 0.5.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Arreglo de estructuras  PointF  que definen la spline. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Dibuja una spline cardinal a través de una matriz especificada de  PointF  estructuras usando una tensión especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Arreglo de estructuras  PointF  que representan los puntos que definen la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Dibuja una spline cardinal a través de un arreglo especificado de estructuras  PointF . El dibujo comienza con un desplazamiento desde el inicio del arreglo. Este método usa una tensión predeterminada de 0.5.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Arreglo de estructuras  PointF  que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en el arreglo del parámetro  points  hasta el punto inicial en la curva. |
| numberOfSegments | int | Número de segmentos después del punto inicial que se incluirán en la curva. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Dibuja una spline cardinal a través de un arreglo especificado de estructuras  PointF  usando una tensión especificada. El dibujo comienza con un desplazamiento desde el inicio del arreglo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Arreglo de estructuras  PointF  que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en el arreglo del parámetro  points  hasta el punto inicial en la curva. |
| numberOfSegments | int | Número de segmentos después del punto inicial que se incluirán en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Dibuja una spline cardinal a través de una matriz especificada de  Point  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Arreglo de estructuras  Point  que definen la spline. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Dibuja una spline cardinal a través de una matriz especificada de  Point  estructuras usando una tensión especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Arreglo de estructuras  Point  que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Dibuja una spline cardinal a través de una matriz especificada de  Point  estructuras usando una tensión especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y la altura de la curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Arreglo de estructuras  Point  que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en el arreglo del parámetro  points  hasta el punto inicial en la curva. |
| numberOfSegments | int | Número de segmentos después del punto inicial que se incluirán en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Dibuja una elipse especificada por una estructura de  Rectangle  delimitadora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la elipse. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Estructura Rectangle que define los límites de la elipse. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Dibuja una elipse definida por un  RectangleF  delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la elipse. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Estructura RectangleF que define los límites de la elipse. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la elipse. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| ancho | float | Ancho del rectángulo delimitador que define la elipse. |
| alto | float | Altura del rectángulo delimitador que define la elipse. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la elipse. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| ancho | int | Ancho del rectángulo delimitador que define la elipse. |
| alto | int | Altura del rectángulo delimitador que define la elipse. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Dibuja la  Image  especificada , usando su tamaño físico original, en la ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| point | [Point](../../com.aspose.psd/point) | Estructura Point que representa la ubicación de la esquina superior izquierda de la imagen dibujada. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Dibuja la  Image  especificada , usando su tamaño físico original, en la ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| point | [PointF](../../com.aspose.psd/pointf) | Estructura PointF que representa la esquina superior izquierda de la imagen dibujada. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo de origen. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo de origen. |
| srcUnit | int | Las unidades de medida. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo de origen. |
| srcUnit | int | Las unidades de medida. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Los atributos de la imagen. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de origen. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de origen. |
| srcUnit | int | Las unidades de medida. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Dibuja la porción especificada de la  image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a dibujar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de origen. |
| srcUnit | int | Las unidades de medida. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Los atributos de la imagen. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Estructura Rectangle que especifica la ubicación y el tamaño de la imagen dibujada. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | El rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | El rect destination. |
| graphicsUnit | int | La unidad gráfica. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | El rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | El rect destination. |
| graphicsUnit | int | La unidad gráfica. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Los atributos de la imagen. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de destino. |
| graphicsUnit | int | La unidad gráfica. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de destino. |
| graphicsUnit | int | La unidad gráfica. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Los atributos de la imagen. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Estructura RectangleF que especifica la ubicación y el tamaño de la imagen dibujada. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | El rect source. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | El rect destination. |
| graphicsUnit | int | La unidad gráfica. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo de origen. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo de destino. |
| graphicsUnit | int | La unidad gráfica a usar. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Los atributos de la imagen a usar. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo de destino. |
| graphicsUnit | int | La unidad gráfica. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo de destino en el que dibujar. |
| graphicsUnit | int | La unidad gráfica. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Los atributos de la imagen. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Dibuja la  Image  especificada , usando su tamaño físico original, en la ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| ancho | float | Ancho de la imagen dibujada. |
| alto | float | Altura de la imagen dibujada. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Dibuja la imagen especificada, usando su tamaño físico original, en la ubicación especificada por un par de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Dibuja la  Image  especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| ancho | int | Ancho de la imagen dibujada. |
| alto | int | Altura de la imagen dibujada. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| point | [Point](../../com.aspose.psd/point) | Point  estructura que especifica la esquina superior izquierda de la imagen dibujada. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  que especifica la esquina superior izquierda de la imagen dibujada. Las propiedades X e Y del rectángulo especifican la esquina superior izquierda. Las propiedades Width y Height se ignoran. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| ancho | int | El parámetro no se utiliza. |
| alto | int | El parámetro no se utiliza. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para ajustarla al rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | La imagen con la que dibujar. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | El  Rectangle en el que dibujar la imagen. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Dibuja una línea que conecta dos  Point  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la línea. |
| point1 | [Point](../../com.aspose.psd/point) | Point  estructura que representa el primer punto a conectar. |
| point2 | [Point](../../com.aspose.psd/point) | Point  estructura que representa el segundo punto a conectar. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Dibuja una línea que conecta dos  PointF  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la línea. |
| point1 | [PointF](../../com.aspose.psd/pointf) | PointF  estructura que representa el primer punto a conectar. |
| point2 | [PointF](../../com.aspose.psd/pointf) | PointF  estructura que representa el segundo punto a conectar. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la línea. |
| x1 | float | La coordenada x del primer punto. |
| y1 | float | La coordenada y del primer punto. |
| x2 | float | La coordenada x del segundo punto. |
| y2 | float | La coordenada y del segundo punto. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la línea. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Dibuja una serie de segmentos de línea que conectan una matriz de  PointF  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de  PointF  estructuras que representan los puntos a conectar. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Dibuja una serie de segmentos de línea que conectan una matriz de  Point  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | [Point\[\]](../../com.aspose.psd/point) | Matriz de  Point  estructuras que representan los puntos a conectar. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Dibuja un  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen  que determina el color, el ancho y el estilo de la ruta. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath  para dibujar. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Dibuja una forma de pastel definida por una elipse especificada por una  Rectangle  estructura y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| startAngle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweepAngle | float | Ángulo medido en grados en sentido horario desde el  startAngle  parámetro hasta el segundo lado de la forma de pastel. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Dibuja una forma de pastel definida por una elipse especificada por una  RectangleF  estructura y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| startAngle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweepAngle | float | Ángulo medido en grados en sentido horario desde el  startAngle  parámetro hasta el segundo lado de la forma de pastel. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la forma de pastel. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| ancho | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| alto | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| startAngle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweepAngle | float | Ángulo medido en grados en sentido horario desde el  startAngle  parámetro hasta el segundo lado de la forma de pastel. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  que determina el color, el ancho y el estilo de la forma de pastel. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| ancho | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| alto | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| startAngle | int | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweepAngle | int | Ángulo medido en grados en sentido horario desde el  startAngle  parámetro hasta el segundo lado de la forma de pastel. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Dibuja un polígono definido por una matriz de  PointF  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen que determina el color, el ancho y el estilo del polígono. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de estructuras PointF que representan los vértices del polígono. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Dibuja un polígono definido por una matriz de  Point  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen que determina el color, el ancho y el estilo del polígono. |
| points | [Point\[\]](../../com.aspose.psd/point) | Matriz de estructuras Point que representan los vértices del polígono. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Dibuja un rectángulo especificado por una  Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un Pen que determina el color, el ancho y el estilo del rectángulo. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una estructura Rectangle que representa el rectángulo a dibujar. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Dibuja un rectángulo especificado por una  RectangleF  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un Pen que determina el color, el ancho y el estilo del rectángulo. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una estructura RectangleF que representa el rectángulo a dibujar. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un Pen que determina el color, el ancho y el estilo del rectángulo. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| ancho | float | El ancho del rectángulo a dibujar. |
| alto | float | La altura del rectángulo a dibujar. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen que determina el color, el ancho y el estilo del rectángulo. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| ancho | int | Ancho del rectángulo a dibujar. |
| alto | int | Altura del rectángulo a dibujar. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Dibuja una serie de rectángulos especificados por  RectangleF  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Matriz de estructuras RectangleF que representan los rectángulos a dibujar. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Dibuja una serie de rectángulos especificados por  Rectangle  estructuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Matriz de estructuras Rectangle que representan los rectángulos a dibujar. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF estructura que especifica la esquina superior izquierda del texto dibujado. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF estructura que especifica la esquina superior izquierda del texto dibujado. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | estructura com.aspose.psd.RectangleF que especifica la ubicación del texto dibujado. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | estructura com.aspose.psd.RectangleF que especifica la ubicación del texto dibujado. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Dibuja la cadena de texto especificada en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Dibuja la cadena de texto especificada de forma compatible con Adobe en el rectángulo especificado con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados usando los atributos de formato del  com.aspose.psd.stringFormat  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | estructura com.aspose.psd.RectangleF que especifica la ubicación del texto dibujado. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Dibuja la cadena de texto especificada de forma compatible con Adobe en la ubicación especificada con los objetos  com.aspose.psd.Brush  y  com.aspose.psd.Font  especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | Cadena a dibujar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font que define el formato de texto de la cadena. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Finaliza el almacenamiento en caché de las operaciones gráficas iniciadas después de que se llamó a BeginUpdate. Las operaciones gráficas precedentes se aplicarán de una vez al invocar este método.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras com.aspose.psd.PointF. Este método usa una tensión predeterminada de 0.5 y el modo de relleno FillMode.Alternate.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de estructuras com.aspose.psd.PointF que definen la spline. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras com.aspose.psd.PointF usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de estructuras com.aspose.psd.PointF que definen la spline. |
| modo de relleno | int | Miembro de la enumeración com.aspose.psd.FillMode que determina cómo se rellena la curva. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.PointF  estructuras usando el modo de relleno especificado y la tensión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un com.aspose.psd.Brush que determina las características del relleno. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de estructuras com.aspose.psd.PointF que definen la spline. |
| modo de relleno | int | Miembro de la enumeración com.aspose.psd.FillMode que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras com.aspose.psd.Point. Este método usa una tensión predeterminada de 0.5 y el modo de relleno FillMode.Alternate.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [Point\[\]](../../com.aspose.psd/point) | Matriz de estructuras com.aspose.psd.Point que definen la spline. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras com.aspose.psd.Point usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [Point\[\]](../../com.aspose.psd/point) | Matriz de estructuras com.aspose.psd.Point que definen la spline. |
| modo de relleno | int | Miembro de la enumeración com.aspose.psd.FillMode que determina cómo se rellena la curva. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Rellena el interior de una curva spline cardinal cerrada definida por una matriz de  com.aspose.psd.Point  estructuras usando el modo de relleno especificado y la tensión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [Point\[\]](../../com.aspose.psd/point) | Matriz de estructuras com.aspose.psd.Point que definen la spline. |
| modo de relleno | int | Miembro de la enumeración com.aspose.psd.FillMode que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura com.aspose.psd.Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | estructura com.aspose.psd.Rectangle que representa el rectángulo delimitador que define la elipse. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura com.aspose.psd.RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | estructura com.aspose.psd.RectangleF que representa el rectángulo delimitador que define la elipse. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| ancho | float | Ancho del rectángulo delimitador que define la elipse. |
| alto | float | Altura del rectángulo delimitador que define la elipse. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| ancho | int | Ancho del rectángulo delimitador que define la elipse. |
| alto | int | Altura del rectángulo delimitador que define la elipse. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Rellena el interior de un com.aspose.psd.graphicsPath.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath que representa la ruta a rellenar. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Rellena el interior de una porción de pastel definida por una elipse especificada por una estructura com.aspose.psd.RectangleF y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | estructura com.aspose.psd.Rectangle que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el segundo lado de la sección de pastel. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Rellena el interior de una porción de pastel definida por una elipse especificada por una estructura com.aspose.psd.RectangleF y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | estructura com.aspose.psd.RectangleF que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el segundo lado de la sección de pastel. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| ancho | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| alto | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el segundo lado de la sección de pastel. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| ancho | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| alto | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| startAngle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweepAngle | int | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el segundo lado de la sección de pastel. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.PointF y FillMode.Alternate.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de estructuras  com.aspose.psd.PointF  que representan los vértices del polígono a rellenar. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.PointF utilizando el modo de relleno especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Matriz de estructuras  com.aspose.psd.PointF  que representan los vértices del polígono a rellenar. |
| fillMode | int | Miembro de la enumeración  com.aspose.psd.FillMode  que determina el estilo del relleno. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.Point y FillMode.Alternate.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [Point\[\]](../../com.aspose.psd/point) | Matriz de estructuras  com.aspose.psd.Point  que representan los vértices del polígono a rellenar. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras com.aspose.psd.Point utilizando el modo de relleno especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| points | [Point\[\]](../../com.aspose.psd/point) | Matriz de estructuras  com.aspose.psd.Point  que representan los vértices del polígono a rellenar. |
| fillMode | int | Miembro de la enumeración  com.aspose.psd.FillMode  que determina el estilo del relleno. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Rellena el interior de un rectángulo especificado por una estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pincel que determina las características del relleno. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Estructura Rectangle que representa el rectángulo a rellenar. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Rellena el interior de un rectángulo especificado por una estructura RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pincel que determina las características del relleno. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Estructura RectangleF que representa el rectángulo a rellenar. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pincel que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| ancho | float | Ancho del rectángulo a rellenar. |
| alto | float | Altura del rectángulo a rellenar. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pincel que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| ancho | int | Ancho del rectángulo a rellenar. |
| alto | int | Altura del rectángulo a rellenar. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Rellena los interiores de una serie de rectángulos especificados por estructuras RectangleF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pincel que determina las características del relleno. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Matriz de estructuras  Rectangle  que representan los rectángulos a rellenar. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Rellena los interiores de una serie de rectángulos especificados por estructuras Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pincel que determina las características del relleno. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Matriz de estructuras  Rectangle  que representan los rectángulos a rellenar. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Rellena el interior de un com.aspose.psd.region.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush que determina las características del relleno. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region que representa el área a rellenar. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


Obtiene o establece la región de recorte.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Obtiene o establece la calidad de composición.

**Returns:**
int - La calidad de composición.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Obtiene la resolución horizontal de este com.aspose.psd.graphics.

**Returns:**
float - El valor, en puntos por pulgada, para la resolución horizontal soportada por este com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Obtiene la resolución vertical de este com.aspose.psd.graphics.

**Returns:**
float - El valor, en puntos por pulgada, para la resolución vertical soportada por este com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


Obtiene la imagen.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Obtiene o establece el modo de interpolación.

**Returns:**
int - El modo de interpolación.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Obtiene o establece la escala entre unidades del mundo y unidades de página para este com.aspose.psd.graphics.

**Returns:**
float - La escala entre unidades del mundo y unidades de página para este com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Obtiene o establece la unidad de medida utilizada para las coordenadas de página en este com.aspose.psd.graphics.

**Returns:**
int - La unidad de medida utilizada para las coordenadas de página en este com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Obtiene o establece las opciones de imagen, usadas para crear imágenes vectoriales pintables para dibujar.

Valor: Las opciones de imagen, usadas para crear imágenes vectoriales pintables para dibujar.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Obtiene o establece el modo de suavizado.

**Returns:**
int - El modo de suavizado.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Obtiene o establece la sugerencia de renderizado de texto.

**Returns:**
int - La sugerencia de renderizado de texto.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene o establece una copia de la transformación geométrica del mundo para este com.aspose.psd.graphics.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


Obtiene un valor que indica si los gráficos están en estado de llamada BeginUpdate.

**Returns:**
boolean -  True  si los gráficos están en estado de llamada BeginUpdate; de lo contrario,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Mide la cadena usando la clase [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | La fuente. |
| texto | java.lang.String | El texto. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Mide la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | La fuente. |
|  | texto | java.lang.String | El texto. |

--------------------

El resultado GDI casi siempre no es válido para estilos Cursiva y a menudo no es válido para estilos Negrita. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Mide la cadena de texto especificada con los parámetros especificados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | java.lang.String | El texto a medir. |
| font | [Font](../../com.aspose.psd/font) | La fuente a medir. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | El área de diseño. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | El formato de cadena. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Obtener la caché de fuentes privadas. |
| useMagicNumbersForStyles | boolean | si se establece en  true  [use magic numbers for styles]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica la com.aspose.psd.Matrix que representa la transformación geométrica local de este com.aspose.psd.Graphics por la com.aspose.psd.Matrix especificada, anteponiendo la com.aspose.psd.matrix especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La  com.aspose.psd.Matrix  por la cual multiplicar la transformación geométrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica la com.aspose.psd.Matrix que representa la transformación geométrica local de este com.aspose.psd.Graphics por la com.aspose.psd.Matrix especificada en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La  com.aspose.psd.Matrix  por la cual multiplicar la transformación geométrica. |
| orden | int | Un  com.aspose.psd.MatrixOrder  que especifica en qué orden multiplicar las dos matrices. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Restablece la propiedad com.aspose.psd.graphics.Transform a la identidad.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local por la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local en la cantidad especificada en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |
| orden | int | Un  com.aspose.psd.MatrixOrder  que especifica si se debe añadir o anteponer la matriz de rotación. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la que escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la que escalar la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por las cantidades especificadas en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la que escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la que escalar la transformación en la dirección del eje y. |
| orden | int | Un  com.aspose.psd.MatrixOrder  que especifica si se debe añadir o anteponer la matriz de escala. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Obtiene o establece la región de recorte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | La región de recorte. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Obtiene o establece la calidad de composición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La calidad de composición. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Obtiene o establece el modo de interpolación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de interpolación. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Obtiene o establece la escala entre unidades del mundo y unidades de página para este com.aspose.psd.graphics.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La escala entre unidades del mundo y unidades de página para este com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Obtiene o establece la unidad de medida utilizada para las coordenadas de página en este com.aspose.psd.graphics.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La unidad de medida utilizada para las coordenadas de página en este com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Obtiene o establece las opciones de imagen, usadas para crear imágenes vectoriales pintables para dibujar.

Valor: Las opciones de imagen, usadas para crear imágenes vectoriales pintables para dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Obtiene o establece el modo de suavizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de suavizado. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Obtiene o establece la sugerencia de renderizado de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La sugerencia de renderizado de texto. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Obtiene o establece una copia de la transformación geométrica del mundo para este com.aspose.psd.graphics.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Una copia de la  com.aspose.psd.Matrix  que representa la transformación geométrica del mundo para este  com.aspose.psd.graphics . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| orden | int | El orden (anteponer o añadir) en el que aplicar la traslación. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

