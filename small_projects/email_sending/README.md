## packaging cmd
```shell script
pyinstaller -w email_gui.py
```
### install pyinstaller
```shell script
python -m pip install pyinstaller
```
#### issue
- unicode_error
  + `chcp 65001`
  + `pyinstaller -w email_gui.py`
 