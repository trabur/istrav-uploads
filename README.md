ISTRAV UPLOADS
========

use this file/folder stucture:
```bash
# ./{domain}/{state}/**/*.png
```

cdn vars:
- https://rawcdn.githack.com/<user>/<repo-name>/<latest-commit-hash>/<domain>/<state>/<file>
- https://rawcdn.githack.com/<uploads>/<domain>/<state>/<file>

cdn example:
- https://rawcdn.githack.com/trabur/istrav-uploads/cb72242401122ad21876bdc16fff309d01a29aca/istrav.com/production/heic1901a.jpg

```bash
# uploads = trabur/istrav-uploads/master
# domain = printedbasics.com
# state = production
# file = coffee-cup.jpg
# https://gitcdn.xyz/repo/{uploads}/{domain}/{state}/{file}
```

command to get latest commit hash:
```bash
$ git rev-parse HEAD
```
