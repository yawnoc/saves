# Saves

| Category | Problem | Solution | Link |
| - | - | - | - |
| Android | [Simple Mobile Tools sold out](https://github.com/SimpleMobileTools/General-Discussion/issues/241) | Switch to Fossify | <https://github.com/FossifyOrg> |
| Firefox | [Mozilla deleted promise never to sell personal data](https://github.com/mozilla/bedrock/commit/d459addab846d8144b61939b7f4310eb80c5470e#diff-a24e74e4595fa85440a2f4e7e5dcfe68aba6e1e593aef05a2d35581a91423847L65) | Switch to LibreWolf | <https://www.youtube.com/watch?v=-8bTquKjzos> |
| Firefox | Protocol not shown in URL bar | Set `browser.urlbar.trimURLs` to `false` | |
| Firefox | Search term persists in URL bar | Set `browser.urlbar.showSearchTerms.enabled` to `false` | |
| Firefox | Tab groups | Set `browser.tabs.groups.enabled` and `browser.tabs.groups.smart.enabled` to `false` | |
| Git | Nice diff highlighting | `apt install git-delta` then set `[core] pager = delta --diff-highlight --keep-plus-minus-markers` | <https://github.com/dandavison/delta> |
| HTML | Constructs with no dedicated element | WHATWG common idioms | [Original](https://html.spec.whatwg.org/multipage/semantics-other.html#common-idioms), [Wayback Machine](https://web.archive.org/web/20250723144204/https://html.spec.whatwg.org/multipage/semantics-other.html#common-idioms), [archive.today](https://archive.md/G07TZ) |
| HTML | Local HTML5 validation | `pipx install html5validator` | <https://pypi.org/project/html5validator/> |
| Linux | Bluetooth sound | `apt install libspa-0.2-bluetooth` then reboot | [Original](https://askubuntu.com/questions/1479606/bluetooth-br-connection-profile-unavailable-issue-on-upgrade-to-xubuntu-23-04), [Wayback Machine](https://web.archive.org/web/20250612180733/https://askubuntu.com/questions/1479606/bluetooth-br-connection-profile-unavailable-issue-on-upgrade-to-xubuntu-23-04) |
| Linux | Bootable USB | `fdisk` and `mkfs.ext4` | [Original](https://verahill.blogspot.com/2013/03/361-installing-debian-on-usb-stick-from.html), [Wayback Machine](https://web.archive.org/web/20250723134852/https://verahill.blogspot.com/2013/03/361-installing-debian-on-usb-stick-from.html), [archive.today](https://archive.md/86JqZ) |
| Linux | Calendar weeks start on Monday not Sunday | Edit `/usr/share/i18n/locales/en_AU` to have `first_weekday 1` then `locale-gen en_AU.UTF-8` then reboot | [Original](https://askubuntu.com/questions/1456793/how-to-change-the-first-day-of-week-on-ubuntu-22-04), [Wayback Machine](https://web.archive.org/web/20230308023812/https://askubuntu.com/questions/1456793/how-to-change-the-first-day-of-week-on-ubuntu-22-04), [archive.today](https://archive.md/eJpTg) |
| Linux | The name `org.freedesktop.portal.Desktop` was not provided | `apt install xdg-desktop-portal` etc. | <https://github.com/flatpak/flatpak/issues/5201#issuecomment-1337471997> |
| macOS | Android File Transfer could not connect | Quit Preview (among other apps on macOS) | [Original](https://old.reddit.com/r/GooglePixel/comments/z3d4ok/pixel_7_could_not_connect_to_device_error_usb/), [Wayback Machine](https://web.archive.org/web/20260211080937/https://old.reddit.com/r/GooglePixel/comments/z3d4ok/pixel_7_could_not_connect_to_device_error_usb/), [archive.today](https://archive.md/80y1v) |
| macOS | Python 13 not the default | `brew install python@3.13` then append `export PATH="$(brew --prefix)/opt/python@3.13/libexec/bin:$PATH"` to `~/.zshrc` | [Original](https://apple.stackexchange.com/questions/450303/how-to-make-python-3-11-my-default-python3-with-brew), [Wayback Machine](https://web.archive.org/web/20250419074901/https://apple.stackexchange.com/questions/450303/how-to-make-python-3-11-my-default-python3-with-brew), [archive.today](https://archive.md/HKrqI) |
| macOS | Sane key bindings | `brew install --cask karabiner-elements` then `karabiner-windows-mode` | <https://github.com/rux616/karabiner-windows-mode> |
| macOS | Sane Window switching | `brew install --cask alt-tab` | <https://github.com/lwouis/alt-tab-macos> |
| Physics | Confidence intervals for mean of log-normal | Olsson (2005) | <https://doi.org/10.1080/10691898.2005.11910638> |
| Physics | ECEF to LLA coordinates | Bowring (1976) | <https://doi.org/10.1179/sre.1976.23.181.323> |
| Physics | Significant digit dogma | John Denker on Uncertainty | [Original](https://www.av8n.com/physics/uncertainty.htm), [Wayback Machine](https://web.archive.org/web/20250723141142/https://www.av8n.com/physics/uncertainty.htm), [archive.today](https://archive.md/Y3Pg) |

<!-- | Category | Problem | Solution | [Original](), [Wayback Machine](), [archive.today]() | -->
