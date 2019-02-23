# WinRT

## Retrieving properties

| Item           | GetMemberProps | GetMethodProps | GetFieldProps | GetPropertyProps | GetParamProps | GetEventProps |
|----------------|----------------|----------------|---------------|------------------|---------------|---------------|
| ParentToken    | ✓  | ✓ | ✓ | ✓ | ✓ | ✓ |
| Name           |  ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| NameLength     |  ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Attributes     | ✓  | ✓ | ✓ | ✓ | ✓ | ✓ |
| SignatureBlob  | ✓  | ✓ | ✓ | ✓ |   |    |
| SignatureBlobLength | ✓ | ✓ | ✓ | ✓ |    |  |
| CodeRVA        | ✓  | ✓ |   |   |    |    |
| ImplementationFlags | ✓ | ✓ |   |    |   |  |
| CPlusTypeFlag  | ✓  |   | ✓ | ✓ | ✓ |   |
| UVCPConstant   | ✓  |   | ✓ | ✓ | ✓ |   |
| UVCPConstantLength  | ✓ |   | ✓ | ✓ | ✓  |  |
| SetterMethod   |    |   |   | ✓ |   |    |
| GetterMethod   |    |   |   | ✓ |   |    |
| OtherMethod    |    |   |   | ✓ |   | ✓  |
| OtherMethodLength   |   |   |   | ✓ |    | ✓ |
| AddOnMethod    |    |   |   |   |   | ✓  |
| RemoveOnMethod |    |   |   |   |   | ✓  |
| FireMethod     |    |   |   |   |   | ✓  |
