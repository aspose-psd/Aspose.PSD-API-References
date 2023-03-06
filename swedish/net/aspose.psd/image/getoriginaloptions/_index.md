---
title: Image.GetOriginalOptions
second_title: Aspose.PSD för .NET API-referens
description: Image metod. Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNGbild med 1 bit per pixel och sedan spara den med hjälp av Save metod kommer den utgående PNGbilden med 8bitar per pixel att produceras. För att undvika det och spara PNGbild med 1bit per pixel använd den här metoden för att få motsvarande sparalternativ och skicka dem tillSavemetod som den andra parametern.
type: docs
weight: 180
url: /sv/net/aspose.psd/image/getoriginaloptions/
---
## Image.GetOriginalOptions method

Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../datastreamsupporter/save/) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../save/)metod som den andra parametern.

```csharp
public virtual ImageOptionsBase GetOriginalOptions()
```

### Returvärde

Alternativen baserade på de ursprungliga filinställningarna.

### Se även

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)


