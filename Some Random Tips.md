# Random Helpful Tips

## Import from a different directory:

```python
sys.path.append('<newpath'>)
from namegoeshere.py import *
```

or
```python
sys.path.append('<newpath'>)
import namegoeshere.py
```
---

## Reload Import
Import only works once per session. Any imports afterwards do nothing even if new content is saved.  

To run the file again in the same session without restarting session:
```python
from imp import reload 
reload(scriptnamegoeshere) 
```
After this can just use `reload(scriptnamegoeshere)` to use file with changes.

---

## VSCode Keyboard Shortcuts
- Comment out code block: `ctrl + k + c`
- Uncomment out code block: `ctrl + k + u`

- New window: `ctrl + shift + n`

---
## Git Commands
- Add specific file to staging area: `git add filename`
- Add everything in directory to staging area: `git add --all`
- Commit to local repo: `git commit -m "write commit msg here"`
- Push to remote repo: `git push`
- Push to remote repo with specific branch: `git push origin branchname`

### not sure: 
- `git reset`
- `git restart`
- `git status`

## Bash Commands
- `ls` list files and folders in directory
- `pwd` current directory path