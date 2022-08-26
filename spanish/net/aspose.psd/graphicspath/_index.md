---
title: GraphicsPath
second_title: Referencia de API de Aspose.PSD para .NET
description: Representa una serie de líneas y curvas conectadas. Esta clase no se puede heredar.
type: docs
weight: 4250
url: /es/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Representa una serie de líneas y curvas conectadas. Esta clase no se puede heredar.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds) { get; } | Obtiene o establece los límites del objeto. |
| [Figures](../../aspose.psd/graphicspath/figures) { get; } | Obtiene las cifras de la ruta. |
| [FillMode](../../aspose.psd/graphicspath/fillmode) { get; set; } | Obtiene o establece un[`FillMode`](../fillmode) enumeración que determina cómo los interiores de las formas en este[`GraphicsPath`](../graphicspath) están llenos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure)(Figure) | Agrega una nueva figura. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures)(Figure[]) | Agrega nuevas figuras. |
| [AddPath](../../aspose.psd/graphicspath/addpath#addpath)(GraphicsPath) | Agrega el especificado[`GraphicsPath`](../graphicspath) a este camino. |
| [AddPath](../../aspose.psd/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Agrega el especificado[`GraphicsPath`](../graphicspath) a este camino. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone)() | Realiza una clonación profunda de esta ruta de gráficos. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten)() | Convierte cada curva de esta ruta en una secuencia de segmentos de línea conectados. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten_1)(Matrix) | Aplica la transformación especificada y luego convierte cada curva en este[`GraphicsPath`](../graphicspath) en una secuencia de segmentos de línea conectados. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten_2)(Matrix, float) | Convierte cada curva en este[`GraphicsPath`](../graphicspath) en una secuencia de segmentos de línea conectados. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds#getbounds)(Matrix) | Obtiene los límites del objeto. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Obtiene los límites del objeto. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible)(Point) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_2)(PointF) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_6)(float, float) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_4)(int, int) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) en la región de recorte visible del especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) , usando el especificado[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure)(Figure) | Elimina una figura. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures)(Figure[]) | Elimina figuras. |
| [Reset](../../aspose.psd/graphicspath/reset)() | Vacía la ruta de gráficos y establece el[`FillMode`](../fillmode) aAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse)() | Invierte el orden de figuras, formas y puntos en cada forma de este[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.psd/graphicspath/transform)(Matrix) | Aplica la transformación especificada a la forma. |
| [Warp](../../aspose.psd/graphicspath/warp#warp)(PointF[], RectangleF) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.psd/graphicspath/widen#widen)(Pen) | Agrega un contorno adicional a la ruta. |
| [Widen](../../aspose.psd/graphicspath/widen#widen_1)(Pen, Matrix) | Agrega un esquema adicional al[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.psd/graphicspath/widen#widen_2)(Pen, Matrix, float) | Reemplaza esto[`GraphicsPath`](../graphicspath) con curvas que encierran el área que se rellena cuando la pluma especificada dibuja esta ruta. |

### Ejemplos

Estos ejemplos hacen uso de las clases GraphicsPath y Graphics para crear y manipular figuras en una superficie de imagen. El ejemplo crea una nueva imagen y dibuja rutas con la ayuda de la clase GraphicsPath. Al final, se llama al método DrawPath expuesto por la clase Graphics para representar las rutas en la superficie. Finalmente, la imagen se exporta a formato de archivo Tiff.

```csharp
[C#]

//Crear una instancia de Imagen 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crear e inicializar una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Borrar superficie gráfica
    graphics.Clear(Color.Wheat);

    //Crear una instancia de la clase GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crear una instancia de la clase Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Agregar formas al objeto Figura
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Agregar objeto Figura a GraphicsPath
    graphicspath.AddFigure(figure);

    //Dibujar ruta con objeto Pluma de color Negro
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Crear una instancia de TiffOptions y establecer sus diversas propiedades
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // guarda todos los cambios.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ver también

* class [ObjectWithBounds](../objectwithbounds)
* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
