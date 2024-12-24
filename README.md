<h1 align=center>
  <img alt="Close Git Combat" src="https://simnalamburt.github.io/cgitc/emblem.svg">
</h1>

**cgitc** is set of useful git aliases for [bash], [zsh]. It provides
professional and swift git usage.

`cgitc` is designed to work with [`forgit`](https://github.com/wfxr/forgit). It sets up `forgit` aliases using the same naming convention as other `cgitc` aliases. If you use `forgit`, make sure to source `cgitc` before `forgit`.

```
g    = git

gst  = git status
gd   = git diff
gdca = git diff --cached
gc   = git commit -v
gup  = git pull --rebase
glog = git log --oneline --decorate --color --graph
gsta = git stash
gstp = git stash pop

(etc)
```

cgitc is fork of [oh-my-zsh]'s [git plugin].
<br><br>

Installation
--------

You can install cgitc via various plugin managers.

#### Bash

```bash
git clone https://github.com/simnalamburt/cgitc.git --depth=1 ~/.cgitc
cat <<< 'source ~/.cgitc/init.bash' >> ~/.bashrc
```

#### Zsh, [zinit]

```zsh
zinit light simnalamburt/cgitc

# (Optional) It'll be more useful with zsh-expand-all
zinit light simnalamburt/zsh-expand-all
```

<br>

--------
*cgitc* is primarily distributed under the terms of both the [MIT license]
and the [Apache License (Version 2.0)]. *cgitc emblem* © 2017 [XT]. See
[COPYRIGHT] for details.

[bash]: https://www.gnu.org/software/bash/
[zsh]: https://www.zsh.org
[zinit]: https://github.com/zdharma/zinit
[oh-my-zsh]: http://ohmyz.sh
[git plugin]: https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/git/git.plugin.zsh
[MIT license]: LICENSE-MIT
[Apache License (Version 2.0)]: LICENSE-APACHE
[COPYRIGHT]: COPYRIGHT
[XT]: https://e.xtendo.org/
