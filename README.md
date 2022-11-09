# [.NET uninstall tool](https://learn.microsoft.com/en-us/dotnet/core/additional-tools/uninstall-tool?tabs=macos)

## Install tool

```
wget -c https://github.com/dotnet/cli-lab/releases/download/1.5.255402/dotnet-core-uninstall.tar.gz
tar -zxf dotnet-core-uninstall.tar.gz
./dotnet-core-uninstall -h
```

## List

```
./dotnet-core-uninstall list

./dotnet-core-uninstall remove 7.0.100-preview.6.22352.1 --sdk
```

## Issue

- https://stackoverflow.com/questions/74353277/uninstall-net-core-sdk-7-0
- https://github.com/dotnet/cli-lab/issues/230