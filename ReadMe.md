# Building to Simply.com
If you want to run your dotnet core application on simply.com, you have to build it like this:

```
dotnet publish --configuration Release --runtime win-x86 --nologo --self-contained
```