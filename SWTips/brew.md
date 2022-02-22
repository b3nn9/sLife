~~~
% /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" 
% echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/gomdol/.zprofile
gomdol@beongaegomdol-ui-MacBookPro ~ % eval "$(/opt/homebrew/bin/brew shellenv)"
gomdol@beongaegomdol-ui-MacBookPro ~ % brew help
Example usage:
  brew search TEXT|/REGEX/
  brew info [FORMULA|CASK...]
  brew install FORMULA|CASK...
  brew update
  brew upgrade [FORMULA|CASK...]
  brew uninstall FORMULA|CASK...
  brew list [FORMULA|CASK...]

Troubleshooting:
  brew config
  brew doctor
  brew install --verbose --debug FORMULA|CASK

Contributing:
  brew create URL [--no-fetch]
  brew edit [FORMULA|CASK...]

Further help:
  brew commands
  brew help [COMMAND]
  man brew
  https://docs.brew.sh
gomdol@beongaegomdol-ui-MacBookPro ~ %
~~~

~~~
% /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" 
==> Checking for `sudo` access (which may request your password)...
Password:
Sorry, try again.
Password:
==> This script will install:
/opt/homebrew/bin/brew
/opt/homebrew/share/doc/homebrew
/opt/homebrew/share/man/man1/brew.1
/opt/homebrew/share/zsh/site-functions/_brew
/opt/homebrew/etc/bash_completion.d/brew
/opt/homebrew
==> The following new directories will be created:
/opt/homebrew/bin
/opt/homebrew/etc
/opt/homebrew/include
/opt/homebrew/lib
/opt/homebrew/sbin
/opt/homebrew/share
/opt/homebrew/var
/opt/homebrew/opt
/opt/homebrew/share/zsh
/opt/homebrew/share/zsh/site-functions
/opt/homebrew/var/homebrew
/opt/homebrew/var/homebrew/linked
/opt/homebrew/Cellar
/opt/homebrew/Caskroom
/opt/homebrew/Frameworks
==> The Xcode Command Line Tools will be installed.

Press RETURN to continue or any other key to abort:
==> /usr/bin/sudo /bin/mkdir -p /opt/homebrew
==> /usr/bin/sudo /usr/sbin/chown root:wheel /opt/homebrew
==> /usr/bin/sudo /bin/mkdir -p /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /bin/chmod ug=rwx /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /bin/chmod go-w /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions
==> /usr/bin/sudo /usr/sbin/chown gomdol /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /usr/bin/chgrp admin /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /usr/sbin/chown -R gomdol:admin /opt/homebrew
==> /usr/bin/sudo /bin/mkdir -p /Users/gomdol/Library/Caches/Homebrew
==> /usr/bin/sudo /bin/chmod g+rwx /Users/gomdol/Library/Caches/Homebrew
==> /usr/bin/sudo /usr/sbin/chown -R gomdol /Users/gomdol/Library/Caches/Homebrew
==> Searching online for the Command Line Tools
==> /usr/bin/sudo /usr/bin/touch /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
==> Installing Command Line Tools for Xcode-13.2
==> /usr/bin/sudo /usr/sbin/softwareupdate -i Command\ Line\ Tools\ for\ Xcode-13.2
Software Update Tool

Finding available software

Downloading Command Line Tools for Xcode
Downloaded Command Line Tools for Xcode
Installing Command Line Tools for Xcode
Done with Command Line Tools for Xcode
Done.
==> /usr/bin/sudo /usr/bin/xcode-select --switch /Library/Developer/CommandLineTools
==> /usr/bin/sudo /bin/rm -f /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
==> Downloading and installing Homebrew...
remote: Enumerating objects: 203419, done.
remote: Counting objects: 100% (202/202), done.
remote: Compressing objects: 100% (163/163), done.
remote: Total 203419 (delta 77), reused 110 (delta 33), pack-reused 203217
Receiving objects: 100% (203419/203419), 55.79 MiB | 6.64 MiB/s, done.
Resolving deltas: 100% (149892/149892), done.
From https://github.com/Homebrew/brew
 * [new branch]          deprecate_disable                    -> origin/deprecate_disable
 * [new branch]          deprecate_formula_each               -> origin/deprecate_formula_each
 * [new branch]          formula_remove_include_on_os         -> origin/formula_remove_include_on_os
 * [new branch]          master                               -> origin/master
 * [new branch]          update_report_only_installed_default -> origin/update_report_only_installed_default
 * [new tag]             0.1                                  -> 0.1
 * [new tag]             0.2                                  -> 0.2
 * [new tag]             0.3                                  -> 0.3
 * [new tag]             0.4                                  -> 0.4
 * [new tag]             0.5                                  -> 0.5
 * [new tag]             0.6                                  -> 0.6
 * [new tag]             0.7                                  -> 0.7
 * [new tag]             0.7.1                                -> 0.7.1
 * [new tag]             0.8                                  -> 0.8
 * [new tag]             0.8.1                                -> 0.8.1
 * [new tag]             0.9                                  -> 0.9
 * [new tag]             0.9.1                                -> 0.9.1
 * [new tag]             0.9.2                                -> 0.9.2
 * [new tag]             0.9.3                                -> 0.9.3
 * [new tag]             0.9.4                                -> 0.9.4
 * [new tag]             0.9.5                                -> 0.9.5
 * [new tag]             0.9.8                                -> 0.9.8
 * [new tag]             0.9.9                                -> 0.9.9
 * [new tag]             1.0.0                                -> 1.0.0
 * [new tag]             1.0.1                                -> 1.0.1
 * [new tag]             1.0.2                                -> 1.0.2
 * [new tag]             1.0.3                                -> 1.0.3
 * [new tag]             1.0.4                                -> 1.0.4
 * [new tag]             1.0.5                                -> 1.0.5
 * [new tag]             1.0.6                                -> 1.0.6
 * [new tag]             1.0.7                                -> 1.0.7
 * [new tag]             1.0.8                                -> 1.0.8
 * [new tag]             1.0.9                                -> 1.0.9
 * [new tag]             1.1.0                                -> 1.1.0
 * [new tag]             1.1.1                                -> 1.1.1
 * [new tag]             1.1.10                               -> 1.1.10
 * [new tag]             1.1.11                               -> 1.1.11
 * [new tag]             1.1.12                               -> 1.1.12
 * [new tag]             1.1.13                               -> 1.1.13
 * [new tag]             1.1.2                                -> 1.1.2
 * [new tag]             1.1.3                                -> 1.1.3
 * [new tag]             1.1.4                                -> 1.1.4
 * [new tag]             1.1.5                                -> 1.1.5
 * [new tag]             1.1.6                                -> 1.1.6
 * [new tag]             1.1.7                                -> 1.1.7
 * [new tag]             1.1.8                                -> 1.1.8
 * [new tag]             1.1.9                                -> 1.1.9
 * [new tag]             1.2.0                                -> 1.2.0
 * [new tag]             1.2.1                                -> 1.2.1
 * [new tag]             1.2.2                                -> 1.2.2
 * [new tag]             1.2.3                                -> 1.2.3
 * [new tag]             1.2.4                                -> 1.2.4
 * [new tag]             1.2.5                                -> 1.2.5
 * [new tag]             1.2.6                                -> 1.2.6
 * [new tag]             1.3.0                                -> 1.3.0
 * [new tag]             1.3.1                                -> 1.3.1
 * [new tag]             1.3.2                                -> 1.3.2
 * [new tag]             1.3.3                                -> 1.3.3
 * [new tag]             1.3.4                                -> 1.3.4
 * [new tag]             1.3.5                                -> 1.3.5
 * [new tag]             1.3.6                                -> 1.3.6
 * [new tag]             1.3.7                                -> 1.3.7
 * [new tag]             1.3.8                                -> 1.3.8
 * [new tag]             1.3.9                                -> 1.3.9
 * [new tag]             1.4.0                                -> 1.4.0
 * [new tag]             1.4.1                                -> 1.4.1
 * [new tag]             1.4.2                                -> 1.4.2
 * [new tag]             1.4.3                                -> 1.4.3
 * [new tag]             1.5.0                                -> 1.5.0
 * [new tag]             1.5.1                                -> 1.5.1
 * [new tag]             1.5.10                               -> 1.5.10
 * [new tag]             1.5.11                               -> 1.5.11
 * [new tag]             1.5.12                               -> 1.5.12
 * [new tag]             1.5.13                               -> 1.5.13
 * [new tag]             1.5.14                               -> 1.5.14
 * [new tag]             1.5.2                                -> 1.5.2
 * [new tag]             1.5.3                                -> 1.5.3
 * [new tag]             1.5.4                                -> 1.5.4
 * [new tag]             1.5.5                                -> 1.5.5
 * [new tag]             1.5.6                                -> 1.5.6
 * [new tag]             1.5.7                                -> 1.5.7
 * [new tag]             1.5.8                                -> 1.5.8
 * [new tag]             1.5.9                                -> 1.5.9
 * [new tag]             1.6.0                                -> 1.6.0
 * [new tag]             1.6.1                                -> 1.6.1
 * [new tag]             1.6.10                               -> 1.6.10
 * [new tag]             1.6.11                               -> 1.6.11
 * [new tag]             1.6.12                               -> 1.6.12
 * [new tag]             1.6.13                               -> 1.6.13
 * [new tag]             1.6.14                               -> 1.6.14
 * [new tag]             1.6.15                               -> 1.6.15
 * [new tag]             1.6.16                               -> 1.6.16
 * [new tag]             1.6.17                               -> 1.6.17
 * [new tag]             1.6.2                                -> 1.6.2
 * [new tag]             1.6.3                                -> 1.6.3
 * [new tag]             1.6.4                                -> 1.6.4
 * [new tag]             1.6.5                                -> 1.6.5
 * [new tag]             1.6.6                                -> 1.6.6
 * [new tag]             1.6.7                                -> 1.6.7
 * [new tag]             1.6.8                                -> 1.6.8
 * [new tag]             1.6.9                                -> 1.6.9
 * [new tag]             1.7.0                                -> 1.7.0
 * [new tag]             1.7.1                                -> 1.7.1
 * [new tag]             1.7.2                                -> 1.7.2
 * [new tag]             1.7.3                                -> 1.7.3
 * [new tag]             1.7.4                                -> 1.7.4
 * [new tag]             1.7.5                                -> 1.7.5
 * [new tag]             1.7.6                                -> 1.7.6
 * [new tag]             1.7.7                                -> 1.7.7
 * [new tag]             1.8.0                                -> 1.8.0
 * [new tag]             1.8.1                                -> 1.8.1
 * [new tag]             1.8.2                                -> 1.8.2
 * [new tag]             1.8.3                                -> 1.8.3
 * [new tag]             1.8.4                                -> 1.8.4
 * [new tag]             1.8.5                                -> 1.8.5
 * [new tag]             1.8.6                                -> 1.8.6
 * [new tag]             1.9.0                                -> 1.9.0
 * [new tag]             1.9.1                                -> 1.9.1
 * [new tag]             1.9.2                                -> 1.9.2
 * [new tag]             1.9.3                                -> 1.9.3
 * [new tag]             2.0.0                                -> 2.0.0
 * [new tag]             2.0.1                                -> 2.0.1
 * [new tag]             2.0.2                                -> 2.0.2
 * [new tag]             2.0.3                                -> 2.0.3
 * [new tag]             2.0.4                                -> 2.0.4
 * [new tag]             2.0.5                                -> 2.0.5
 * [new tag]             2.0.6                                -> 2.0.6
 * [new tag]             2.1.0                                -> 2.1.0
 * [new tag]             2.1.1                                -> 2.1.1
 * [new tag]             2.1.10                               -> 2.1.10
 * [new tag]             2.1.11                               -> 2.1.11
 * [new tag]             2.1.12                               -> 2.1.12
 * [new tag]             2.1.13                               -> 2.1.13
 * [new tag]             2.1.14                               -> 2.1.14
 * [new tag]             2.1.15                               -> 2.1.15
 * [new tag]             2.1.16                               -> 2.1.16
 * [new tag]             2.1.2                                -> 2.1.2
 * [new tag]             2.1.3                                -> 2.1.3
 * [new tag]             2.1.4                                -> 2.1.4
 * [new tag]             2.1.5                                -> 2.1.5
 * [new tag]             2.1.6                                -> 2.1.6
 * [new tag]             2.1.7                                -> 2.1.7
 * [new tag]             2.1.8                                -> 2.1.8
 * [new tag]             2.1.9                                -> 2.1.9
 * [new tag]             2.2.0                                -> 2.2.0
 * [new tag]             2.2.1                                -> 2.2.1
 * [new tag]             2.2.10                               -> 2.2.10
 * [new tag]             2.2.11                               -> 2.2.11
 * [new tag]             2.2.12                               -> 2.2.12
 * [new tag]             2.2.13                               -> 2.2.13
 * [new tag]             2.2.14                               -> 2.2.14
 * [new tag]             2.2.15                               -> 2.2.15
 * [new tag]             2.2.16                               -> 2.2.16
 * [new tag]             2.2.17                               -> 2.2.17
 * [new tag]             2.2.2                                -> 2.2.2
 * [new tag]             2.2.3                                -> 2.2.3
 * [new tag]             2.2.4                                -> 2.2.4
 * [new tag]             2.2.5                                -> 2.2.5
 * [new tag]             2.2.6                                -> 2.2.6
 * [new tag]             2.2.7                                -> 2.2.7
 * [new tag]             2.2.8                                -> 2.2.8
 * [new tag]             2.2.9                                -> 2.2.9
 * [new tag]             2.3.0                                -> 2.3.0
 * [new tag]             2.4.0                                -> 2.4.0
 * [new tag]             2.4.1                                -> 2.4.1
 * [new tag]             2.4.10                               -> 2.4.10
 * [new tag]             2.4.11                               -> 2.4.11
 * [new tag]             2.4.12                               -> 2.4.12
 * [new tag]             2.4.13                               -> 2.4.13
 * [new tag]             2.4.14                               -> 2.4.14
 * [new tag]             2.4.15                               -> 2.4.15
 * [new tag]             2.4.16                               -> 2.4.16
 * [new tag]             2.4.2                                -> 2.4.2
 * [new tag]             2.4.3                                -> 2.4.3
 * [new tag]             2.4.4                                -> 2.4.4
 * [new tag]             2.4.5                                -> 2.4.5
 * [new tag]             2.4.6                                -> 2.4.6
 * [new tag]             2.4.7                                -> 2.4.7
 * [new tag]             2.4.8                                -> 2.4.8
 * [new tag]             2.4.9                                -> 2.4.9
 * [new tag]             2.5.0                                -> 2.5.0
 * [new tag]             2.5.1                                -> 2.5.1
 * [new tag]             2.5.10                               -> 2.5.10
 * [new tag]             2.5.11                               -> 2.5.11
 * [new tag]             2.5.12                               -> 2.5.12
 * [new tag]             2.5.2                                -> 2.5.2
 * [new tag]             2.5.3                                -> 2.5.3
 * [new tag]             2.5.4                                -> 2.5.4
 * [new tag]             2.5.5                                -> 2.5.5
 * [new tag]             2.5.6                                -> 2.5.6
 * [new tag]             2.5.7                                -> 2.5.7
 * [new tag]             2.5.8                                -> 2.5.8
 * [new tag]             2.5.9                                -> 2.5.9
 * [new tag]             2.6.0                                -> 2.6.0
 * [new tag]             2.6.1                                -> 2.6.1
 * [new tag]             2.6.2                                -> 2.6.2
 * [new tag]             2.7.0                                -> 2.7.0
 * [new tag]             2.7.1                                -> 2.7.1
 * [new tag]             2.7.2                                -> 2.7.2
 * [new tag]             2.7.3                                -> 2.7.3
 * [new tag]             2.7.4                                -> 2.7.4
 * [new tag]             2.7.5                                -> 2.7.5
 * [new tag]             2.7.6                                -> 2.7.6
 * [new tag]             2.7.7                                -> 2.7.7
 * [new tag]             3.0.0                                -> 3.0.0
 * [new tag]             3.0.1                                -> 3.0.1
 * [new tag]             3.0.10                               -> 3.0.10
 * [new tag]             3.0.11                               -> 3.0.11
 * [new tag]             3.0.2                                -> 3.0.2
 * [new tag]             3.0.3                                -> 3.0.3
 * [new tag]             3.0.4                                -> 3.0.4
 * [new tag]             3.0.5                                -> 3.0.5
 * [new tag]             3.0.6                                -> 3.0.6
 * [new tag]             3.0.7                                -> 3.0.7
 * [new tag]             3.0.8                                -> 3.0.8
 * [new tag]             3.0.9                                -> 3.0.9
 * [new tag]             3.1.0                                -> 3.1.0
 * [new tag]             3.1.1                                -> 3.1.1
 * [new tag]             3.1.10                               -> 3.1.10
 * [new tag]             3.1.11                               -> 3.1.11
 * [new tag]             3.1.12                               -> 3.1.12
 * [new tag]             3.1.2                                -> 3.1.2
 * [new tag]             3.1.3                                -> 3.1.3
 * [new tag]             3.1.4                                -> 3.1.4
 * [new tag]             3.1.5                                -> 3.1.5
 * [new tag]             3.1.6                                -> 3.1.6
 * [new tag]             3.1.7                                -> 3.1.7
 * [new tag]             3.1.8                                -> 3.1.8
 * [new tag]             3.1.9                                -> 3.1.9
 * [new tag]             3.2.0                                -> 3.2.0
 * [new tag]             3.2.1                                -> 3.2.1
 * [new tag]             3.2.10                               -> 3.2.10
 * [new tag]             3.2.11                               -> 3.2.11
 * [new tag]             3.2.12                               -> 3.2.12
 * [new tag]             3.2.13                               -> 3.2.13
 * [new tag]             3.2.14                               -> 3.2.14
 * [new tag]             3.2.15                               -> 3.2.15
 * [new tag]             3.2.16                               -> 3.2.16
 * [new tag]             3.2.17                               -> 3.2.17
 * [new tag]             3.2.2                                -> 3.2.2
 * [new tag]             3.2.3                                -> 3.2.3
 * [new tag]             3.2.4                                -> 3.2.4
 * [new tag]             3.2.5                                -> 3.2.5
 * [new tag]             3.2.6                                -> 3.2.6
 * [new tag]             3.2.7                                -> 3.2.7
 * [new tag]             3.2.8                                -> 3.2.8
 * [new tag]             3.2.9                                -> 3.2.9
 * [new tag]             3.3.0                                -> 3.3.0
 * [new tag]             3.3.1                                -> 3.3.1
 * [new tag]             3.3.10                               -> 3.3.10
 * [new tag]             3.3.11                               -> 3.3.11
 * [new tag]             3.3.12                               -> 3.3.12
 * [new tag]             3.3.13                               -> 3.3.13
 * [new tag]             3.3.14                               -> 3.3.14
 * [new tag]             3.3.15                               -> 3.3.15
 * [new tag]             3.3.16                               -> 3.3.16
 * [new tag]             3.3.2                                -> 3.3.2
 * [new tag]             3.3.3                                -> 3.3.3
 * [new tag]             3.3.4                                -> 3.3.4
 * [new tag]             3.3.5                                -> 3.3.5
 * [new tag]             3.3.6                                -> 3.3.6
 * [new tag]             3.3.7                                -> 3.3.7
 * [new tag]             3.3.8                                -> 3.3.8
 * [new tag]             3.3.9                                -> 3.3.9
HEAD is now at 01506f120 Merge pull request #12907 from iMichka/certs
==> Tapping homebrew/core
remote: Enumerating objects: 1146788, done.
remote: Counting objects: 100% (73/73), done.
remote: Compressing objects: 100% (35/35), done.
remote: Total 1146788 (delta 41), reused 67 (delta 38), pack-reused 1146715
Receiving objects: 100% (1146788/1146788), 448.40 MiB | 6.01 MiB/s, done.
Resolving deltas: 100% (792743/792743), done.
From https://github.com/Homebrew/homebrew-core
 * [new branch]              master     -> origin/master
HEAD is now at 2000b444d69 libsecret: update 0.20.5 bottle.
Warning: /opt/homebrew/bin is not in your PATH.
  Instructions on how to configure your shell for Homebrew
  can be found in the 'Next steps' section below.
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/gomdol/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh

gomdol@beongaegomdol-ui-MacBookPro ~ %
~~~

~~~
% brew install cask                                                                              
==> Downloading https://ghcr.io/v2/homebrew/core/gmp/manifests/6.2.1_1
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gmp/blobs/sha256:a43a2ae4c44d90626b835a968a32327c8b8bbf754ec1d2590f8ac656c71dace9
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:a43a2ae4c44d90626b835a968a32327c8b8bbf754ec1d2590f8ac656c7
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/coreutils/manifests/9.0_1
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/coreutils/blobs/sha256:e7d849e225505512eaa003bfa599bed9b17d935467e3d33f13ff44017118ab41
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:e7d849e225505512eaa003bfa599bed9b17d935467e3d33f13ff440171
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/ca-certificates/manifests/2022-02-01
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/ca-certificates/blobs/sha256:40e00f88df310bc2dc42aefb3e834c0a3022f125fecdf21f26431d12a104dbc0
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:40e00f88df310bc2dc42aefb3e834c0a3022f125fecdf21f26431d12a1
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/bdw-gc/manifests/8.0.6
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/bdw-gc/blobs/sha256:55bdbcc825a5f4657ca307ed0a002e8cd07bb1635148962ff9187aca4b7dcb9c
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:55bdbcc825a5f4657ca307ed0a002e8cd07bb1635148962ff9187aca4b
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libffi/manifests/3.4.2
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libffi/blobs/sha256:6a3605cff713d45e0500ef01c0f082d1b4d31d70cd2400b5856443050a44a056
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:6a3605cff713d45e0500ef01c0f082d1b4d31d70cd2400b5856443050a
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/m4/manifests/1.4.19
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/m4/blobs/sha256:8e9fa0d7d946f7c38e1a6f596aab3169d2440fccd34ec321b9a032d903ec951c
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:8e9fa0d7d946f7c38e1a6f596aab3169d2440fccd34ec321b9a032d903
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libtool/manifests/2.4.6_4
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libtool/blobs/sha256:51902377c9a9595aa62838170d43102ca12bfc0c2f926b78ea380220edfc271e
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:51902377c9a9595aa62838170d43102ca12bfc0c2f926b78ea380220ed
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libunistring/manifests/1.0
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libunistring/blobs/sha256:b8b2f6fe30eefd002bf0dbb5fc0e5c6dc0d5f9b9219f4d6fcddc48e3bc229b23
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:b8b2f6fe30eefd002bf0dbb5fc0e5c6dc0d5f9b9219f4d6fcddc48e3bc
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/pkg-config/manifests/0.29.2_3
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/pkg-config/blobs/sha256:2af9bceb60b70a259f236f1d46d2bb24c4d0a4af8cd63d974dde4d76313711e0
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:2af9bceb60b70a259f236f1d46d2bb24c4d0a4af8cd63d974dde4d7631
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/readline/manifests/8.1.2
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/readline/blobs/sha256:9d9d9512c80c6ae7c8281da84533222d90cb5e06accdfa98e0bff37672793cec
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:9d9d9512c80c6ae7c8281da84533222d90cb5e06accdfa98e0bff37672
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/guile/manifests/3.0.8
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/guile/blobs/sha256:dc6e5dccbc34d5171fba0bc0a0f96381dad52a9837b6f0a1aa6eba2851b6137d
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:dc6e5dccbc34d5171fba0bc0a0f96381dad52a9837b6f0a1aa6eba2851
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gettext/manifests/0.21
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gettext/blobs/sha256:6e2c829031949c0cbd758d0701ed62c191387736e76a98a046c0619907632225
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:6e2c829031949c0cbd758d0701ed62c191387736e76a98a046c0619907
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libidn2/manifests/2.3.2
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libidn2/blobs/sha256:fcc51d2c385b19d647da5a53f7041f13f97d2c1119a7cbbfd8433e9e55bf5012
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:fcc51d2c385b19d647da5a53f7041f13f97d2c1119a7cbbfd8433e9e55
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libtasn1/manifests/4.18.0
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libtasn1/blobs/sha256:f85aa10d1320087405fd8b5c17593c6238bac842c6714edd09194f28e8e9f25d
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:f85aa10d1320087405fd8b5c17593c6238bac842c6714edd09194f28e8
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/nettle/manifests/3.7.3
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/nettle/blobs/sha256:c47b2e4721e5c8347194e3dad066bf00fc6b5d28cb4082f53535dba76a1ed658
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:c47b2e4721e5c8347194e3dad066bf00fc6b5d28cb4082f53535dba76a
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/p11-kit/manifests/0.24.1
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/p11-kit/blobs/sha256:a1c85ddc587d4b0e6ad38f7b58420ed0fc4a1ccdb038bee1451d9d81fc3fb434
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:a1c85ddc587d4b0e6ad38f7b58420ed0fc4a1ccdb038bee1451d9d81fc
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/1.1/manifests/1.1.1m
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/1.1/blobs/sha256:b3a02096abab03b1571f37d8d1f7ff89675a96be649495f434d8817047c3765e
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:b3a02096abab03b1571f37d8d1f7ff89675a96be649495f434d8817047
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libevent/manifests/2.1.12
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libevent/blobs/sha256:4867e07fed355e41bf50f9f44e29307c0004387dd49f743e3b387478572dc8a8
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:4867e07fed355e41bf50f9f44e29307c0004387dd49f743e3b38747857
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libnghttp2/manifests/1.46.0
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libnghttp2/blobs/sha256:7676ac3fa660ac5c0f08715d77edb7bbe68bfbe2853697271fcb9a32fb9caad7
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:7676ac3fa660ac5c0f08715d77edb7bbe68bfbe2853697271fcb9a32fb
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/unbound/manifests/1.15.0
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/unbound/blobs/sha256:915c6b513b276b18eb083839926aade01b36f78a8bf89039696e2ed4f31b571b
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:915c6b513b276b18eb083839926aade01b36f78a8bf89039696e2ed4f3
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gnutls/manifests/3.7.3
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gnutls/blobs/sha256:64e98c4d7ae8140c87befc258efde25b817e0d02e9be019f848482eae080ed28
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:64e98c4d7ae8140c87befc258efde25b817e0d02e9be019f848482eae0
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/jansson/manifests/2.14
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/jansson/blobs/sha256:f8a132e116364ead3e428b1ad39768791f7a11ad26c07f5040c41d3514b7dea2
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:f8a132e116364ead3e428b1ad39768791f7a11ad26c07f5040c41d3514
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/emacs/manifests/27.2
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/emacs/blobs/sha256:89d8ecc54baa2d25ffed5cb54ed2f4a088c8b7907446bbf320bf2334adacef72
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:89d8ecc54baa2d25ffed5cb54ed2f4a088c8b7907446bbf320bf2334ad
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/cask/manifests/0.8.7
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/cask/blobs/sha256:bd85befe31659e948617b988ed604d70199af9e7dd22dcfc8be6d76ecd92ee0b
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:bd85befe31659e948617b988ed604d70199af9e7dd22dcfc8be6d76ecd
######################################################################## 100.0%
==> Installing dependencies for cask: gmp, coreutils, ca-certificates, bdw-gc, libffi, m4, libtool, libunistring, pkg-config, readline, guile, gettext, libidn2, libtasn1, nettle, p11-kit, openssl@1.1, libevent, libnghttp2, unbound, gnutls, jansson and emacs
==> Installing cask dependency: gmp
==> Pouring gmp--6.2.1_1.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/gmp/6.2.1_1: 21 files, 3.2MB
==> Installing cask dependency: coreutils
==> Pouring coreutils--9.0_1.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/coreutils/9.0_1: 480 files, 13.1MB
==> Installing cask dependency: ca-certificates
==> Pouring ca-certificates--2022-02-01.all.bottle.tar.gz
==> Regenerating CA certificate bundle from keychain, this may take a while...
🍺  /opt/homebrew/Cellar/ca-certificates/2022-02-01: 3 files, 213.4KB
==> Installing cask dependency: bdw-gc
==> Pouring bdw-gc--8.0.6.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/bdw-gc/8.0.6: 69 files, 1.7MB
==> Installing cask dependency: libffi
==> Pouring libffi--3.4.2.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libffi/3.4.2: 17 files, 673.3KB
==> Installing cask dependency: m4
==> Pouring m4--1.4.19.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/m4/1.4.19: 13 files, 742.4KB
==> Installing cask dependency: libtool
==> Pouring libtool--2.4.6_4.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libtool/2.4.6_4: 75 files, 3.7MB
==> Installing cask dependency: libunistring
==> Pouring libunistring--1.0.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libunistring/1.0: 56 files, 5.0MB
==> Installing cask dependency: pkg-config
==> Pouring pkg-config--0.29.2_3.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/pkg-config/0.29.2_3: 11 files, 676.4KB
==> Installing cask dependency: readline
==> Pouring readline--8.1.2.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/readline/8.1.2: 48 files, 1.7MB
==> Installing cask dependency: guile
==> Pouring guile--3.0.8.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/guile/3.0.8: 846 files, 62.6MB
==> Installing cask dependency: gettext
==> Pouring gettext--0.21.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/gettext/0.21: 1,953 files, 20.6MB
==> Installing cask dependency: libidn2
==> Pouring libidn2--2.3.2.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libidn2/2.3.2: 77 files, 885.4KB
==> Installing cask dependency: libtasn1
==> Pouring libtasn1--4.18.0.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libtasn1/4.18.0: 61 files, 662.7KB
==> Installing cask dependency: nettle
==> Pouring nettle--3.7.3.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/nettle/3.7.3: 89 files, 2.8MB
==> Installing cask dependency: p11-kit
==> Pouring p11-kit--0.24.1.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/p11-kit/0.24.1: 67 files, 3.9MB
==> Installing cask dependency: openssl@1.1
==> Pouring openssl@1.1--1.1.1m.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/openssl@1.1/1.1.1m: 8,081 files, 18MB
==> Installing cask dependency: libevent
==> Pouring libevent--2.1.12.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libevent/2.1.12: 57 files, 2.1MB
==> Installing cask dependency: libnghttp2
==> Pouring libnghttp2--1.46.0.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libnghttp2/1.46.0: 13 files, 690.0KB
==> Installing cask dependency: unbound
==> Pouring unbound--1.15.0.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/unbound/1.15.0: 58 files, 5.8MB
==> Installing cask dependency: gnutls
==> Pouring gnutls--3.7.3.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/gnutls/3.7.3: 1,280 files, 11.0MB
==> Installing cask dependency: jansson
==> Pouring jansson--2.14.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/jansson/2.14: 11 files, 228.4KB
==> Installing cask dependency: emacs
==> Pouring emacs--27.2.arm64_monterey.bottle.tar.gz
🍺  /opt/homebrew/Cellar/emacs/27.2: 4,012 files, 104.3MB
==> Installing cask
==> Pouring cask--0.8.7.all.bottle.tar.gz
==> Caveats
Emacs Lisp files have been installed to:
  /opt/homebrew/share/emacs/site-lisp/cask
==> Summary
🍺  /opt/homebrew/Cellar/cask/0.8.7: 15 files, 150.2KB
==> Running `brew cleanup cask`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Caveats
==> cask
Emacs Lisp files have been installed to:
  /opt/homebrew/share/emacs/site-lisp/cask
gomdol@beongaegomdol-ui-MacBookPro ~ %
~~~
