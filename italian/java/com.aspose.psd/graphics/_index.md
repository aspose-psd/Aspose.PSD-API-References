---
title: "Graphics"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta la grafica in base al motore grafico utilizzato nell'assembly corrente."
type: docs
weight: 49
url: /it/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Rappresenta la grafica in base al motore grafico utilizzato nell'assembly corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Inizializza una nuova istanza della classe  Graphics. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Ottiene il coefficiente di dimensione per lo stile di testo grassetto |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Ottiene il coefficiente di dimensione per lo stile di testo corsivo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Applica l'effetto. |
| [beginUpdate()](#beginUpdate--) | Avvia la memorizzazione nella cache delle seguenti operazioni grafiche. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Cancella la superficie grafica usando il colore specificato. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura  Rectangle. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura  RectangleF. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Disegna una spline Bézier definita da quattro strutture  Point. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Disegna una spline Bézier definita da quattro strutture  PointF. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Disegna una spline Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Disegna una serie di spline Bézier da un array di strutture PointF. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Disegna una serie di spline Bézier da un array di strutture Point. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Disegna una spline cardinal chiusa definita da un array di strutture PointF. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Disegna una spline cardinal chiusa definita da un array di strutture PointF usando una tensione specificata. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Disegna una spline cardinal chiusa definita da un array di strutture Point. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Disegna una spline cardinal chiusa definita da un array di strutture Point usando una tensione specificata. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Disegna una spline cardinal attraverso un array specificato di strutture PointF. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Disegna una spline cardinal attraverso un array specificato di strutture PointF usando una tensione specificata. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Disegna una spline cardinal attraverso un array specificato di strutture PointF. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Disegna una spline cardinal attraverso un array specificato di strutture PointF usando una tensione specificata. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Disegna una spline cardinal attraverso un array specificato di strutture Point. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Disegna una spline cardinal attraverso un array specificato di strutture Point usando una tensione specificata. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Disegna una spline cardinal attraverso un array specificato di strutture Point usando una tensione specificata. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Disegna un'ellisse specificata da una struttura Rectangle di delimitazione. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Disegna un'ellisse definita da un RectangleF . |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Disegna l'image specificata, usando la sua dimensione fisica originale, nella posizione specificata da una coppia di coordinate. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Disegna l'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata da una coppia di coordinate. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Disegna l'immagine specificata senza ridimensionamento e la ritaglia, se necessario, per adattarla al rettangolo specificato. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Disegna una linea che collega due strutture Point. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Disegna una linea che collega due strutture PointF. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Disegna una serie di segmenti di linea che collegano un array di strutture PointF. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Disegna una serie di segmenti di linea che collegano un array di strutture Point. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Disegna un com.aspose.psd.graphicsPath. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Disegna una forma a torta definita da un'ellisse specificata da una struttura Rectangle e due linee radiali. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Disegna una forma a torta definita da un'ellisse specificata da una struttura RectangleF e due linee radiali. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Disegna un poligono definito da un array di strutture PointF. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Disegna un poligono definito da un array di strutture Point. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Disegna un rettangolo specificato da una struttura Rectangle. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Disegna un rettangolo specificato da una struttura RectangleF. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Disegna una serie di rettangoli specificati da strutture RectangleF. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Disegna una serie di rettangoli specificati da strutture Rectangle. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato. |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Disegna la stringa di testo specificata in modo compatibile con Adobe nel rettangolo specificato con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Disegna la stringa di testo specificata in modo compatibile con Adobe nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati. |
| [endUpdate()](#endUpdate--) | Termina la memorizzazione nella cache delle operazioni grafiche avviate dopo la chiamata a BeginUpdate. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.PointF. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.PointF, utilizzando la modalità di riempimento specificata. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.PointF, utilizzando la modalità di riempimento e la tensione specificate. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.Point. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.Point, utilizzando la modalità di riempimento specificata. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.Point, utilizzando la modalità di riempimento e la tensione specificate. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una  com.aspose.psd.Rectangle  struttura. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una  com.aspose.psd.RectangleF  struttura. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Riempie l'interno di un  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una  com.aspose.psd.RectangleF  struttura e due linee radiali. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una  com.aspose.psd.RectangleF  struttura e due linee radiali. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.PointF  strutture e  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.PointF  strutture usando la modalità di riempimento specificata. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.Point  strutture e  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.Point  strutture usando la modalità di riempimento specificata. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Riempie l'interno di un rettangolo specificato da una  Rectangle  struttura. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Riempie l'interno di un rettangolo specificato da una  RectangleF  struttura. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Riempie gli interni di una serie di rettangoli specificati da  RectangleF  strutture. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Riempie gli interni di una serie di rettangoli specificati da  Rectangle  strutture. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Riempie l'interno di una  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Ottiene o imposta la regione di ritaglio. |
| [getCompositingQuality()](#getCompositingQuality--) | Ottiene o imposta la qualità di composizione. |
| [getDpiX()](#getDpiX--) | Ottiene la risoluzione orizzontale di questo  com.aspose.psd.graphics . |
| [getDpiY()](#getDpiY--) | Ottiene la risoluzione verticale di questo  com.aspose.psd.graphics . |
| [getImage()](#getImage--) | Ottiene l'immagine. |
| [getInterpolationMode()](#getInterpolationMode--) | Ottiene o imposta la modalità di interpolazione. |
| [getPageScale()](#getPageScale--) | Ottiene o imposta la scala tra unità di mondo e unità di pagina per questo  com.aspose.psd.graphics . |
| [getPageUnit()](#getPageUnit--) | Ottiene o imposta l'unità di misura usata per le coordinate di pagina in questo  com.aspose.psd.graphics . |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Ottiene o imposta le opzioni immagine, usate per creare immagini vettoriali dipingibili da disegnare. |
| [getSmoothingMode()](#getSmoothingMode--) | Ottiene o imposta la modalità di smussatura. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Ottiene o imposta il suggerimento di rendering del testo. |
| [getTransform()](#getTransform--) | Ottiene o imposta una copia della trasformazione geometrica del mondo per questo  com.aspose.psd.graphics . |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Ottiene un valore che indica se la grafica è nello stato di chiamata BeginUpdate. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Misura la stringa usando la classe [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Misura la stringa. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Misura la stringa di testo specificata con i parametri specificati |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Moltiplica il  com.aspose.psd.Matrix  che rappresenta la trasformazione geometrica locale di questo  com.aspose.psd.Graphics  per il  com.aspose.psd.Matrix  specificato, anteponendo il  com.aspose.psd.matrix  specificato. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Moltiplica il  com.aspose.psd.Matrix  che rappresenta la trasformazione geometrica locale di questo  com.aspose.psd.Graphics  per il  com.aspose.psd.Matrix  specificato nell'ordine specificato. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Reimposta la proprietà  com.aspose.psd.graphics.Transform  a identità. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale dell'importo specificato. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale degli importi specificati. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Ottiene o imposta la regione di ritaglio. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Ottiene o imposta la qualità di composizione. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Ottiene o imposta la modalità di interpolazione. |
| [setPageScale(float value)](#setPageScale-float-) | Ottiene o imposta la scala tra unità di mondo e unità di pagina per questo  com.aspose.psd.graphics . |
| [setPageUnit(int value)](#setPageUnit-int-) | Ottiene o imposta l'unità di misura usata per le coordinate di pagina in questo  com.aspose.psd.graphics . |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Ottiene o imposta le opzioni immagine, usate per creare immagini vettoriali dipingibili da disegnare. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Ottiene o imposta la modalità di smussatura. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Ottiene o imposta il suggerimento di rendering del testo. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Ottiene o imposta una copia della trasformazione geometrica del mondo per questo  com.aspose.psd.graphics . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Inizializza una nuova istanza della classe  Graphics.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine di origine. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Ottiene il coefficiente di dimensione per lo stile di testo grassetto

Utilizzo di numeri magici poiché GDI fornisce sempre la misurazione solo per lo stile Regular.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Ottiene il coefficiente di dimensione per lo stile di testo corsivo

Utilizzo di numeri magici poiché GDI fornisce sempre la misurazione solo per lo stile Regular.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Applica l'effetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| effetto | com.aspose.internal.IEffect | L'effetto da applicare. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Avvia la memorizzazione nella cache delle seguenti operazioni grafiche. Gli effetti grafici applicati successivamente non saranno applicati immediatamente; invece, EndUpdate causerà l'applicazione di tutti gli effetti in una volta.

Nota: gli effetti dopo la chiamata a BeginUpdate non saranno applicati nel caso in cui EndUpdate non venga chiamato.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Cancella la superficie grafica usando il colore specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Il colore con cui cancellare la superficie grafica. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura  Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Penna  che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struttura RectangleF  che definisce i confini dell'ellisse. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro  startAngle  al punto finale dell'arco. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura  RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Penna  che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura RectangleF  che definisce i confini dell'ellisse. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro  startAngle  al punto finale dell'arco. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Penna  che determina il colore, la larghezza e lo stile dell'arco. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| larghezza | float | Larghezza del rettangolo che definisce l'ellisse. |
| altezza | float | Altezza del rettangolo che definisce l'ellisse. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro  startAngle  al punto finale dell'arco. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Penna  che determina il colore, la larghezza e lo stile dell'arco. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| larghezza | int | Larghezza del rettangolo che definisce l'ellisse. |
| altezza | int | Altezza del rettangolo che definisce l'ellisse. |
| startAngle | int | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweepAngle | int | Angolo in gradi misurato in senso orario dal parametro  startAngle  al punto finale dell'arco. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Disegna una spline Bézier definita da quattro strutture  Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Struttura Pen che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [Point](../../com.aspose.psd/point) | Struttura Point che rappresenta il punto di partenza della curva. |
| pt2 | [Point](../../com.aspose.psd/point) | Struttura Point che rappresenta il primo punto di controllo della curva. |
| pt3 | [Point](../../com.aspose.psd/point) | Struttura Point che rappresenta il secondo punto di controllo della curva. |
| pt4 | [Point](../../com.aspose.psd/point) | Struttura Point che rappresenta il punto finale della curva. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Disegna una spline Bézier definita da quattro strutture  PointF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | Struttura PointF che rappresenta il punto di partenza della curva. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | Struttura PointF che rappresenta il primo punto di controllo della curva. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | Struttura PointF che rappresenta il secondo punto di controllo della curva. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | Struttura PointF che rappresenta il punto finale della curva. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Disegna una spline Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della curva. |
| x1 | float | La coordinata x del punto di partenza della curva. |
| y1 | float | La coordinata y del punto di partenza della curva. |
| x2 | float | La coordinata x del primo punto di controllo della curva. |
| y2 | float | La coordinata y del primo punto di controllo della curva. |
| x3 | float | La coordinata x del secondo punto di controllo della curva. |
| y3 | float | La coordinata y del secondo punto di controllo della curva. |
| x4 | float | La coordinata x del punto finale della curva. |
| y4 | float | La coordinata y del punto finale della curva. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Disegna una serie di spline Bézier da un array di strutture PointF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che rappresentano i punti che determinano la curva. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Disegna una serie di spline Bézier da un array di strutture Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  Point  che rappresentano i punti che determinano la curva. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Disegna una spline cardinale chiusa definita da un array di strutture  PointF . Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento  FillMode.Alternate .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che definiscono la spline. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Disegna una spline cardinale chiusa definita da un array di strutture  PointF  utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita  FillMode.Alternate .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Disegna una spline cardinale chiusa definita da un array di strutture  Point . Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento  FillMode.Alternate .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  Point  che definiscono la spline. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Disegna una spline cardinale chiusa definita da un array di strutture  Point  utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita  FillMode.Alternate .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  Point  che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Disegna una spline cardinale attraverso un array specificato di strutture  PointF . Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che definiscono la spline. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Disegna una spline cardinal attraverso un array specificato di strutture PointF usando una tensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che rappresentano i punti che definiscono la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Disegna una spline cardinale attraverso un array specificato di strutture  PointF . Il disegno inizia con uno scostamento dall'inizio dell'array. Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che definiscono la spline. |
| offset | int | Scostamento dal primo elemento nell'array del parametro  points  al punto di partenza nella curva. |
| numberOfSegments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Disegna una spline cardinale attraverso un array specificato di strutture  PointF  utilizzando una tensione specificata. Il disegno inizia con uno scostamento dall'inizio dell'array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che definiscono la spline. |
| offset | int | Scostamento dal primo elemento nell'array del parametro  points  al punto di partenza nella curva. |
| numberOfSegments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Disegna una spline cardinal attraverso un array specificato di strutture Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  Point  che definiscono la spline. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Disegna una spline cardinal attraverso un array specificato di strutture Point usando una tensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  Point  che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Disegna una spline cardinal attraverso un array specificato di strutture Point usando una tensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  Point  che definiscono la spline. |
| offset | int | Scostamento dal primo elemento nell'array del parametro  points  al punto di partenza nella curva. |
| numberOfSegments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Disegna un'ellisse specificata da una struttura Rectangle di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e lo stile dell'ellisse. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struttura  Rectangle  che definisce i confini dell'ellisse. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Disegna un'ellisse definita da un RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e lo stile dell'ellisse. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura RectangleF  che definisce i confini dell'ellisse. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| larghezza | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| larghezza | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| point | [Point](../../com.aspose.psd/point) | Struttura Point che rappresenta la posizione dell'angolo in alto a sinistra dell'immagine disegnata. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| point | [PointF](../../com.aspose.psd/pointf) | Struttura PointF che rappresenta l'angolo in alto a sinistra dell'immagine disegnata. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di origine. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di origine. |
| srcUnit | int | Le unità di misura. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di origine. |
| srcUnit | int | Le unità di misura. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di origine. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di origine. |
| srcUnit | int | Le unità di misura. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Disegna la porzione specificata dell'image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da disegnare. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di origine. |
| srcUnit | int | Le unità di misura. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struttura Rectangle che specifica la posizione e le dimensioni dell'immagine disegnata. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di origine. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphicsUnit | int | L'unità grafica. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di origine. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphicsUnit | int | L'unità grafica. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphicsUnit | int | L'unità grafica. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphicsUnit | int | L'unità grafica. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura RectangleF che specifica la posizione e le dimensioni dell'immagine disegnata. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di origine. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di destinazione. |
| graphicsUnit | int | L'unità grafica. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di origine. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di destinazione. |
| graphicsUnit | int | L'unità grafica da utilizzare. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Gli attributi dell'immagine da utilizzare. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di destinazione. |
| graphicsUnit | int | L'unità grafica. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo di destinazione in cui disegnare. |
| graphicsUnit | int | L'unità grafica. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo in alto a sinistra dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo in alto a sinistra dell'immagine disegnata. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo in alto a sinistra dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo in alto a sinistra dell'immagine disegnata. |
| larghezza | float | Larghezza dell'immagine disegnata. |
| altezza | float | Altezza dell'immagine disegnata. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Disegna l'image specificata, usando la sua dimensione fisica originale, nella posizione specificata da una coppia di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo in alto a sinistra dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo in alto a sinistra dell'immagine disegnata. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Disegna l'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo in alto a sinistra dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo in alto a sinistra dell'immagine disegnata. |
| larghezza | int | Larghezza dell'immagine disegnata. |
| altezza | int | Altezza dell'immagine disegnata. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| point | [Point](../../com.aspose.psd/point) | Struttura Point che specifica l'angolo in alto a sinistra dell'immagine disegnata. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle che specifica l'angolo in alto a sinistra dell'immagine disegnata. Le proprietà X e Y del rettangolo specificano l'angolo in alto a sinistra. Le proprietà Width e Height vengono ignorate. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata da una coppia di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo in alto a sinistra dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo in alto a sinistra dell'immagine disegnata. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo in alto a sinistra dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo in alto a sinistra dell'immagine disegnata. |
| larghezza | int | Il parametro non è utilizzato. |
| altezza | int | Il parametro non è utilizzato. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Disegna l'immagine specificata senza ridimensionamento e la ritaglia, se necessario, per adattarla al rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Il Rectangle in cui disegnare l'immagine. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Disegna una linea che collega due strutture Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della linea. |
| point1 | [Point](../../com.aspose.psd/point) | Struttura Point che rappresenta il primo punto da collegare. |
| point2 | [Point](../../com.aspose.psd/point) | Struttura Point che rappresenta il secondo punto da collegare. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Disegna una linea che collega due strutture PointF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della linea. |
| point1 | [PointF](../../com.aspose.psd/pointf) | Struttura PointF che rappresenta il primo punto da collegare. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Struttura PointF che rappresenta il secondo punto da collegare. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della linea. |
| x1 | float | La coordinata x del primo punto. |
| y1 | float | La coordinata y del primo punto. |
| x2 | float | La coordinata x del secondo punto. |
| y2 | float | La coordinata y del secondo punto. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della linea. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Disegna una serie di segmenti di linea che collegano un array di strutture PointF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture PointF che rappresentano i punti da collegare. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Disegna una serie di segmenti di linea che collegano un array di strutture Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture Point che rappresentano i punti da collegare. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Disegna un com.aspose.psd.graphicsPath.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen che determina il colore, la larghezza e lo stile del percorso. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath da disegnare. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Disegna una forma a torta definita da un'ellisse specificata da una struttura Rectangle e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struttura Rectangle che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | float | Angolo misurato in gradi in senso orario dal parametro startAngle al secondo lato della forma a torta. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Disegna una forma a torta definita da un'ellisse specificata da una struttura RectangleF e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura RectangleF che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | float | Angolo misurato in gradi in senso orario dal parametro startAngle al secondo lato della forma a torta. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della forma a torta. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| larghezza | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | float | Angolo misurato in gradi in senso orario dal parametro startAngle al secondo lato della forma a torta. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile della forma a torta. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| larghezza | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | int | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | int | Angolo misurato in gradi in senso orario dal parametro startAngle al secondo lato della forma a torta. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Disegna un poligono definito da un array di strutture PointF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile del poligono. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  PointF  che rappresentano i vertici del poligono. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Disegna un poligono definito da un array di strutture Point.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile del poligono. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  Point  che rappresentano i vertici del poligono. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Disegna un rettangolo specificato da una struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  Pen  che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura  Rectangle  che rappresenta il rettangolo da disegnare. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Disegna un rettangolo specificato da una struttura RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  Pen  che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura  RectangleF  che rappresenta il rettangolo da disegnare. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  Pen  che determina il colore, la larghezza e lo stile del rettangolo. |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da disegnare. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da disegnare. |
| larghezza | float | La larghezza del rettangolo da disegnare. |
| altezza | float | L'altezza del rettangolo da disegnare. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile del rettangolo. |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da disegnare. |
| larghezza | int | Larghezza del rettangolo da disegnare. |
| altezza | int | Altezza del rettangolo da disegnare. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Disegna una serie di rettangoli specificati da strutture RectangleF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array di strutture  RectangleF  che rappresentano i rettangoli da disegnare. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Disegna una serie di rettangoli specificati da strutture Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array di strutture  Rectangle  che rappresentano i rettangoli da disegnare. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  struttura che specifica l'angolo superiore sinistro del testo disegnato. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  struttura che specifica l'angolo superiore sinistro del testo disegnato. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura com.aspose.psd.RectangleF che specifica la posizione del testo disegnato. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura com.aspose.psd.RectangleF che specifica la posizione del testo disegnato. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Disegna la stringa di testo specificata nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Disegna la stringa di testo specificata in modo compatibile con Adobe nel rettangolo specificato con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati, utilizzando gli attributi di formattazione del com.aspose.psd.stringFormat specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura com.aspose.psd.RectangleF che specifica la posizione del testo disegnato. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Disegna la stringa di testo specificata in modo compatibile con Adobe nella posizione specificata con gli oggetti com.aspose.psd.Brush e com.aspose.psd.Font specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Stringa da disegnare. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font che definisce il formato del testo della stringa. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Termina la memorizzazione nella cache delle operazioni grafiche avviate dopo la chiamata a BeginUpdate. Le operazioni grafiche precedenti verranno applicate immediatamente al momento della chiamata di questo metodo.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.PointF. Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento FillMode.Alternate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture com.aspose.psd.PointF che definiscono la spline. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.PointF utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture com.aspose.psd.PointF che definiscono la spline. |
| modalità di riempimento | int | Membro dell'enumerazione com.aspose.psd.FillMode che determina come viene riempita la curva. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.PointF, utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture com.aspose.psd.PointF che definiscono la spline. |
| modalità di riempimento | int | Membro dell'enumerazione com.aspose.psd.FillMode che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.Point. Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento FillMode.Alternate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture com.aspose.psd.Point che definiscono la spline. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.Point utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture com.aspose.psd.Point che definiscono la spline. |
| modalità di riempimento | int | Membro dell'enumerazione com.aspose.psd.FillMode che determina come viene riempita la curva. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture com.aspose.psd.Point, utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture com.aspose.psd.Point che definiscono la spline. |
| modalità di riempimento | int | Membro dell'enumerazione com.aspose.psd.FillMode che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una  com.aspose.psd.Rectangle  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struttura com.aspose.psd.Rectangle che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una  com.aspose.psd.RectangleF  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura com.aspose.psd.RectangleF che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| larghezza | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| larghezza | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Riempie l'interno di un  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath che rappresenta il percorso da riempire. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una  com.aspose.psd.RectangleF  struttura e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struttura com.aspose.psd.Rectangle che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al secondo lato della sezione a torta. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una  com.aspose.psd.RectangleF  struttura e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura com.aspose.psd.RectangleF che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al secondo lato della sezione a torta. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| larghezza | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al secondo lato della sezione a torta. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| larghezza | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| startAngle | int | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweepAngle | int | Angolo in gradi misurato in senso orario dal parametro startAngle al secondo lato della sezione a torta. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.PointF  strutture e  FillMode.Alternate .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  com.aspose.psd.PointF  che rappresentano i vertici del poligono da riempire. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.PointF  strutture usando la modalità di riempimento specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array di strutture  com.aspose.psd.PointF  che rappresentano i vertici del poligono da riempire. |
| fillMode | int | Membro dell'enumerazione  com.aspose.psd.FillMode  che determina lo stile del riempimento. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.Point  strutture e  FillMode.Alternate .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  com.aspose.psd.Point  che rappresentano i vertici del poligono da riempire. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Riempie l'interno di un poligono definito da un array di punti specificati da  com.aspose.psd.Point  strutture usando la modalità di riempimento specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array di strutture  com.aspose.psd.Point  che rappresentano i vertici del poligono da riempire. |
| fillMode | int | Membro dell'enumerazione  com.aspose.psd.FillMode  che determina lo stile del riempimento. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Riempie l'interno di un rettangolo specificato da una  Rectangle  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pennello  che determina le caratteristiche del riempimento. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struttura Rectangle  che rappresenta il rettangolo da riempire. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Riempie l'interno di un rettangolo specificato da una  RectangleF  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pennello  che determina le caratteristiche del riempimento. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struttura RectangleF  che rappresenta il rettangolo da riempire. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pennello  che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da riempire. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da riempire. |
| larghezza | float | Larghezza del rettangolo da riempire. |
| altezza | float | Altezza del rettangolo da riempire. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pennello  che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da riempire. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da riempire. |
| larghezza | int | Larghezza del rettangolo da riempire. |
| altezza | int | Altezza del rettangolo da riempire. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Riempie gli interni di una serie di rettangoli specificati da  RectangleF  strutture.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pennello  che determina le caratteristiche del riempimento. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array di strutture  Rectangle  che rappresentano i rettangoli da riempire. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Riempie gli interni di una serie di rettangoli specificati da  Rectangle  strutture.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pennello  che determina le caratteristiche del riempimento. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array di strutture  Rectangle  che rappresentano i rettangoli da riempire. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Riempie l'interno di una  com.aspose.psd.region .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush che determina le caratteristiche del riempimento. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region  che rappresenta l'area da riempire. |

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


Ottiene o imposta la regione di ritaglio.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Ottiene o imposta la qualità di composizione.

**Returns:**
int - La qualità di composizione.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Ottiene la risoluzione orizzontale di questo  com.aspose.psd.graphics .

**Returns:**
float - Il valore, in punti per pollice, per la risoluzione orizzontale supportata da questo com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Ottiene la risoluzione verticale di questo  com.aspose.psd.graphics .

**Returns:**
float - Il valore, in punti per pollice, per la risoluzione verticale supportata da questo com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


Ottiene l'immagine.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Ottiene o imposta la modalità di interpolazione.

**Returns:**
int - La modalità di interpolazione.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Ottiene o imposta la scala tra unità di mondo e unità di pagina per questo  com.aspose.psd.graphics .

**Returns:**
float - La scala tra unità del mondo e unità di pagina per questo com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Ottiene o imposta l'unità di misura usata per le coordinate di pagina in questo  com.aspose.psd.graphics .

**Returns:**
int - L'unità di misura usata per le coordinate di pagina in questo com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Ottiene o imposta le opzioni immagine, usate per creare immagini vettoriali dipingibili da disegnare.

Valore: Le opzioni immagine, usate per creare immagini vettoriali dipingibili da disegnare.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Ottiene o imposta la modalità di smussatura.

**Returns:**
int - La modalità di anti-aliasing.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Ottiene o imposta il suggerimento di rendering del testo.

**Returns:**
int - L'indicazione di rendering del testo.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ottiene o imposta una copia della trasformazione geometrica del mondo per questo  com.aspose.psd.graphics .

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


Ottiene un valore che indica se la grafica è nello stato di chiamata BeginUpdate.

**Returns:**
boolean -  True  se la grafica è nello stato di chiamata BeginUpdate; altrimenti,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Misura la stringa usando la classe [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Il font. |
| testo | java.lang.String | Il testo. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Misura la stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Il font. |
|  | testo | java.lang.String | Il testo. |

--------------------

Il risultato GDI è quasi sempre non valido per gli stili Italic e spesso non valido per gli stili Bold. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Misura la stringa di testo specificata con i parametri specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Il testo da misurare. |
| font | [Font](../../com.aspose.psd/font) | The font to measure. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | L'area di layout. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Il formato stringa. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Il recupero della cache dei font privati. |
| useMagicNumbersForStyles | boolean | se impostato su true [usa numeri magici per gli stili]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica il  com.aspose.psd.Matrix  che rappresenta la trasformazione geometrica locale di questo  com.aspose.psd.Graphics  per il  com.aspose.psd.Matrix  specificato, anteponendo il  com.aspose.psd.matrix  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La  com.aspose.psd.Matrix  con cui moltiplicare la trasformazione geometrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica il  com.aspose.psd.Matrix  che rappresenta la trasformazione geometrica locale di questo  com.aspose.psd.Graphics  per il  com.aspose.psd.Matrix  specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La  com.aspose.psd.Matrix  con cui moltiplicare la trasformazione geometrica. |
| ordine | int | Un  com.aspose.psd.MatrixOrder  che specifica in quale ordine moltiplicare le due matrici. |

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


Reimposta la proprietà  com.aspose.psd.graphics.Transform  a identità.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale dell'importo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |
| ordine | int | Un  com.aspose.psd.MatrixOrder  che specifica se aggiungere o anteporre la matrice di rotazione. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale di quantità specificate. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità di scala da applicare alla trasformazione lungo l'asse x. |
| sy | float | La quantità di scala da applicare alla trasformazione lungo l'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità di scala da applicare alla trasformazione lungo l'asse x. |
| sy | float | La quantità di scala da applicare alla trasformazione lungo l'asse y. |
| ordine | int | Un  com.aspose.psd.MatrixOrder  che specifica se aggiungere o anteporre la matrice di scala. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Ottiene o imposta la regione di ritaglio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | La regione di ritaglio. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Ottiene o imposta la qualità di composizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La qualità di composizione. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Ottiene o imposta la modalità di interpolazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di interpolazione. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Ottiene o imposta la scala tra unità di mondo e unità di pagina per questo  com.aspose.psd.graphics .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La scala tra unità del mondo e unità di pagina per questo com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Ottiene o imposta l'unità di misura usata per le coordinate di pagina in questo  com.aspose.psd.graphics .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'unità di misura usata per le coordinate di pagina in questo com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Ottiene o imposta le opzioni immagine, usate per creare immagini vettoriali dipingibili da disegnare.

Valore: Le opzioni immagine, usate per creare immagini vettoriali dipingibili da disegnare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Ottiene o imposta la modalità di smussatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di smussatura. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Ottiene o imposta il suggerimento di rendering del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il suggerimento di rendering del testo. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Ottiene o imposta una copia della trasformazione geometrica del mondo per questo  com.aspose.psd.graphics .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Una copia della  com.aspose.psd.Matrix  che rappresenta la trasformazione geometrica del mondo per questo  com.aspose.psd.graphics. |

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


Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione lungo x. |
| dy | float | Il valore della traslazione lungo y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione lungo x. |
| dy | float | Il valore della traslazione lungo y. |
| ordine | int | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

