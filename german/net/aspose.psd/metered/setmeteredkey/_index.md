---
title: "Metered.SetMeteredKey"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Metered-Methode. Legt den gemessenen öffentlichen und privaten Schlüssel fest. Wenn Sie eine gemessene Lizenz beim Start der Anwendung erwerben, sollte diese API normalerweise aufgerufen werden; das ist ausreichend. Sollte jedoch ständig das Hochladen von Verbrauchsdaten fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf."
type: docs
weight: 40
url: /de/net/aspose.psd/metered/setmeteredkey/
---
{{< psd/tize >}}
## Metered.SetMeteredKey method

Setzt den öffentlichen und privaten gemessenen Schlüssel. Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch das Hochladen von Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | String | öffentlicher Schlüssel |
| privateKey | String | privater Schlüssel |

### Siehe auch

* class [Metered](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


