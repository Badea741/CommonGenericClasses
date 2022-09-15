# CommonGenericClasses

## Base generic implementation using repository and unit of work design pattern to crud operations in .NET Standard 2.1

# Installation
 `dotnet add package CommonGenericClasses --version 7.0.0`

# Usage
```using CommonGenericClasses;```

# Code sample
```
using CommonGenericClasses;
public class PlayerRepository : BaseRepo<Player>
{
    public PlayerRepository(DbContext db) : base(db)
    {
    }
}



