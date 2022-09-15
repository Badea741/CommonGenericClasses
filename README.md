# CommonGenericClasses

## Base generic implementation using repository and unit of work design pattern of crud operations in .NET Standard 2.1

# Installation
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



