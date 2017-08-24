http://flight-manual.atom.io/hacking-atom/sections/publishing/

$ git add .
$ git add commit -m 'message'
$ apm publish major/minor/patch
$ git tag 'v1.0.3'
$ git push && git push --tags
