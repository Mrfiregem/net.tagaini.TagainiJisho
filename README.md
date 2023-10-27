# Tagaini Jisho

> A free Japanese dictionary and learning assistant

---

This is a flatpak-builder manifest used to install Tagaini Jisho, a Qt5 tool to help learn Japanese. Since this is my first time creating a flatpak package, I'll gladly accept pull requests.

## Install

```sh
git clone https://github.com/Mrfiregem/net.tagaini.TagainiJisho.git
cd net.tagaini.TagainiJisho
flatpak-builder --user --install --force-clean build-dir net.tagaini.TagainiJisho.yml
```

Note that the checksums of the dictionary files may be incorrect if they've been updated recently. Just modify the `sha256` field of the dictionary in `net.tagaini.TagainiJisho.yml` to solve the issue.
