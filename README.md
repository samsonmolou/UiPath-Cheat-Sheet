# UiPath Cheat Sheet

## Convert DataTable to Array Of String
```csharp
yourDatatable.AsEnumerable().Select(Function(row) row.Field(Of String)("Text")).ToArray()
```

## Initialize Array Of String
```csharp
New String() {}
```
