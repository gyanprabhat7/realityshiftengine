### Python

```
winget install -e --id Python.Python.3.10
```

### PIP

```
python -m ensurepip
```

### GIT

```
winget install -e --id Git.Git
```

### FFmpeg

```
winget install -e --id Gyan.FFmpeg
```

Reboot your system in order for FFmpeg to function properly.

```
shutdown /r
```

### Toolset

#### Microsoft Visual C++ 2015 Redistributable

```
winget install -e --id Microsoft.VCRedist.2015+.x64
```

#### Microsoft Visual Studio 2022 build tools

During installation, ensure to select the Desktop Development with C++ package.

```
winget install -e --id Microsoft.VisualStudio.2022.BuildTools --override "--wait --add Microsoft.VisualStudio.Workload.NativeDesktop --includeRecommended"
```


