http://flight-manual.atom.io/hacking-atom/sections/publishing/

Do not manually update version in package.json because apm does that for you.

$ git add .
$ git commit -m 'message'
$ apm publish major/minor/patch
