---
title: Graphics.DrawRectangles
second_title: Referencia de API de Aspose.PSD para .NET
description: Graphics método. Dibuja una serie de rectángulos especificados porRectangleF estructuras.
type: docs
weight: 310
url: /es/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Dibuja una serie de rectángulos especificados por[`RectangleF`](../../rectanglef/) estructuras.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | RectangleF[] | Gama de[`RectangleF`](../../rectanglef/) estructuras que representan los rectángulos a dibujar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *rects* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Dibuja una serie de rectángulos especificados por[`Rectangle`](../../rectangle/) estructuras.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | Rectangle[] | Gama de[`Rectangle`](../../rectangle/) estructuras que representan los rectángulos a dibujar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *rects* es nulo. |

### Ejemplos

Este ejemplo muestra la creación y el uso de objetos Pen. El ejemplo crea una nueva imagen y dibuja rectángulos en la superficie de la imagen.

```csharp
[C#]

//Crear una instancia de Imagen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea una instancia de Graphics e inicialízala con el objeto Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Limpiar la superficie de gráficos con color blanco
    graphics.Clear(Aspose.PSD.Color.White);

    //Crear una instancia de Pen con color Rojo y ancho 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Crear una instancia de HatchBrush y establecer sus propiedades
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Crear una instancia de Pen
    //inicializarlo con objeto HatchBrush y ancho
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Crear opciones de exportación e inicializarlas.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // guarda todos los cambios.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Ver también

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)


