# httpnotify

httpnotify is a client-server background service written in C#.
It supports any system that can run notify-send and .NET (Core).


## Compilation
To compile, or build httpnotify, enter the directory in which the .sln file is located (src).
After this, run the following command:
```bash
dotnet build
```

The output will be located at `src/HttpNotify.Client/bin/netX.Y/Debug/HttpNotify.Client` and
`src/HttpNotify.Server/bin/netX.Y/Debug/HttpNotify.Server` respectively.
