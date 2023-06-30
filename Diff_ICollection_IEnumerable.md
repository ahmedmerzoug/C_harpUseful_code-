IEnumerable<>  :  for a list of objects that only needs to be iterated through
Source : http://msdn.microsoft.com/en-us/library/system.collections.ienumerable.aspx

ICollection<> : for a list of objects that needs to be iterated through and modified
Source : http://msdn.microsoft.com/en-us/library/92t2ye13.aspx

List<> : for a list of objects that needs to be iterated through, modified, sorted, etc
Source : https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.list-1?view=net-7.0&redirectedfrom=MSDN

From a more specific standpoint, lazy loading comes in to play with choosing the type. By default, navigation properties in Entity Framework come with change tracking and are proxies. 
In order for the dynamic proxy to be created as a navigation property, the virtual type must implement ICollection.
