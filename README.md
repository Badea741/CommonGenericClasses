# CommonGenericClasses

## Base generic implementation using Repository & Unit of Work Design Pattern of CRUD operations in .NET 6.0

# Installation
CLI
``` cli
 dotnet add package CommonGenericClasses --version 7.1.2
```
PM 
``` cli
Install-Package CommonGenericClasses -Version 7.1.2
```
## note : for netstandard2.1 use version 7.0.0

# Usage
``` C#
using CommonGenericClasses;
```

# Code sample
```C#
using CommonGenericClasses;
public class PlayerRepository : BaseRepo<Player>
{
    public PlayerRepository(DbContext db) : base(db)
    {
    }
}
```
Now all CRUD operations are available for `PlayerRepository`
# Source code 
### https://github.com/Badea741/CommonGenericClasses

