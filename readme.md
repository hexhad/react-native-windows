# WINDOWS CONFIG
```
npx react-native init <projectName> --template react-native@^0.70.0
```
```
cd projectName
```

### WINDOWS
```
npx react-native-windows-init --overwrite
```

RES : https://microsoft.github.io/react-native-windows/docs/getting-started

## Make sure you have enabled "Windows Developer Mode"
Apps & features > Optional features > Add or Clarify Windows Developer Mode

### run this on powershell with Admin permission

```
Set-ExecutionPolicy Unrestricted -Scope Process -Force;
iex (New-Object System.Net.WebClient).DownloadString('https://aka.ms/rnw-deps.ps1')
```

RES : https://microsoft.github.io/react-native-windows/docs/rnw-dependencies

# FINALLY

```
npx react-native run-windows
```