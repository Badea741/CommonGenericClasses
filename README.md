# CommonGenericClasses

## Base generic implementation using Repository & Unit of work Design Pattern of CRUD operations in .NET Standard 2.1

# Installation
CLI
``` cli
 dotnet add package CommonGenericClasses --version 7.0.0
```
PM 
``` cli
Install-Package CommonGenericClasses -Version 7.0.0
```

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



