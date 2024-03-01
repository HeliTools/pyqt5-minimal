

### use Pyinstaller
```shell
pyinstaller --exclude-module PyQt5 -D -w --name trends main.py --hidden-import pkgutil --add-data PyQt5:./
```
