# Config on Windows

## powershell

open powershell profile `code $PROFILE`

By file on your local machine

```
oh-my-posh init pwsh --config 'C:\Users\Hamed-Naghdi\AppData\Local\Programs\oh-my-posh\themes\atomic.omp.json' | Invoke-Expression
```

OR by url

```
oh-my-posh init pwsh --config 'url' | Invoke-Expression
```

## bash

open ~/.bashrc (if not exist creat it in your user folder)

By file on your local machine

```
eval "$(oh-my-posh init bash --config 'C:\Users\Hamed-Naghdi\AppData\Local\Programs\oh-my-posh\themes\hamed.omp.json')"
```

OR by url

```
eval "$(oh-my-posh init bash --config 'url')"
```
