# A repo for when I feel computer crazy

[![github doesnt allow unicode in repo names and i dont like that](http://img.youtube.com/vi/E7NiANnriGc/0.jpg)](http://www.youtube.com/watch?v=E7NiANnriGc "")

Please steal these ideas and share them with me.

# Older Ideas

- man files should be emeded in executables
  - could easily add a ELF metadata section for this
- CLI autocomplete should be described in BNF and embeded in executables

# ９月１５日

- CLI programs should output HTML/CSS to be rendered by web terminals
  - this should have W3C standard :^)
- create a window manager in HTML/CSS w/ windows as iframes
- create desktop manager based around web standards -- qt/gnome should die
- create a slack alternative that is CLI first
  - share terminal/error/file_location/code_snippet with...
  - view images/videos w/ web terminal integration
  - record/share/replay CLI steps
  - graphql api and stable HTML5 interface for tinkering
  - handle full git PR process via terminal
- create a standard dotfile for jump key preferences (tfw dvorak T.T)

I'm forgetting something and it is driving me computer crazy...

Time for a drink :+1:

# １０月０８日

- old idea, but still want: Docker meta language
  - REPO <url>: upload to repo
  - TAG <string>: add tag on upload
  - UNIQUETAG <string>: don't overwrite tags
  - SOURCE <filename>: evaluate another dockerfile
  - TEST <string>: fail build on failure, discard changes on success
  - SHELL <string>: choose interactive shell for RUN commands
  - SQUASH: copy data to new image
  - ATOMIC <bool>: specify commands as not creating new fs layers
  - ATOMIC <cmd>: append command to previous layer
  - INSTALL <tool> <package> <version>: update listing, install package with normal tool (nix, apt, *any*, etc), delete cache
  - PIN <tool>: use same cache for all layers
  - MEMRUN <path> <args>: run executable from host in docker image (ramdisk? temp folder? volume?)
  - CHIMAGE <image>: create new image, copy previous created/changed files
  - HOST RUN <string>: run command on host
  - WEBHOOK <url> <payload>: hit some endpoint
- simple binary repo based on docker images
  - example: `my_tool --pip luastyle` or `my_tool mediainfo`

# 4月06日

- make shell functions check and install deps
- make all shell functions speak json when non-interactive
  - or just make terminals speak json already :sigh:
