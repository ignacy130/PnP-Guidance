# ClientObjectExtensions.IsPropertyAvailable Method  
 Check if a property is available on a object   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static bool IsPropertyAvailable(T clientObject, Expression<Func<T, Object>> propertySelector)
```
### Parameters
#### clientObject  
&emsp;&emsp;Type: T  
&emsp;&emsp;Object to operate on  

  

#### propertySelector  
&emsp;&emsp;Type: System.Linq.Expressions.Expression<System.Func<T, System.Object>>  
&emsp;&emsp;Lamda expression containing the properties to check (e.g. w => w.HasUniqueRoleAssignments)  

  

### Return Value
Type: bool  
True if the property is available, false otherwise  


## Remarks
  
## See also
- [ClientObjectExtensions](Microsoft.SharePoint.Client.ClientObjectExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 