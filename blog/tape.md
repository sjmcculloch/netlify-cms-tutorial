---
path: flex
date: 2020-05-20T07:05:22.763Z
title: Tape
---
ok

```csharp
// include somewhere in your class - available to all methods.
private static readonly ILog Logger = LoggerSource.Instance.GetLogger(typeof(MyClassName));

try
{
    // cause some error
}
catch (Exception exc)
{
    Logger.Error(exc);
}
```

![](/assets/wagner-ball-hawk.jpg)