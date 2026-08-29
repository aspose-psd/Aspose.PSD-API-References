---
title: "Κλάση License"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.License κλάση. Παρέχει μεθόδους για την αδειοδότηση του στοιχείου"
type: docs
weight: 5540
url: /el/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

Παρέχει μεθόδους για την άδεια του στοιχείου.

```csharp
public class License
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [License](license/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Αδειοδοτεί το στοιχείο. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Αδειοδοτεί το στοιχείο. |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στο φάκελο που περιέχει το στοιχείο, στο φάκελο που περιέχει το καλούντα σύνολο, στο φάκελο του κύριου συνόλου και, στη συνέχεια, στους ενσωματωμένους πόρους του καλούντα συνόλου.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


