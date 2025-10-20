# Dispansasjonssoeknad - generert kode

### Demo av generert kode fra [dispensasjonssoeknad.xsd](https://skjema.ft.dibk.no/dispensasjonssoeknad/v1/dispensasjonssoeknad.xsd)

XSD fil fra DiBK: https://skjema.ft.dibk.no/

Vi tester her ut generering av C# kode fra xsd-filen dispensasjonssoeknad.xsd.

Generering er gjort på OSX vha dotnet xscgen tool.

Vi kjørte kommandoen: 

```
xscgen dispensasjonssoeknad.xsd -c -o GeneratedClasses
```

#### Generert kode
C# kodefilen `No.Dibk.Ft.Skjema.Dispensasjonssoeknad.V1.cs` som er generert ligger i mappen _Dispensasjonssoeknad/GeneratedClasses_
