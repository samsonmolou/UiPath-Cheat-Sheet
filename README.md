# UiPath Cheat Sheet

## Convert DataTable to Array Of String
```
yourDatatable.AsEnumerable().Select(Function(row) row.Field(Of String)("Text")).ToArray()
```
