# Source Templates for Rider and ReSharper
This adds context aware macros for users of Rider and ReSharper.

## Available templates
### `[object].log`
Wraps the object into a `Debug.Log` statement.
```cs
Application.version.log
```
will result in 
```cs
Debug.Log($"Application.version: {Application.version}");
```
### `[object].wlog`
same as `[object].log` but using `Debug.LogWarning`
### `[object].elog`
same as `[object].log` but using `Debug.LogError`
