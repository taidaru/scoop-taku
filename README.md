# scoop-taku

[Scoop](https://scoop.sh) bucket for [Taku](https://github.com/taidaru/taku) —
a task runner powered by Rust and scripted in Lua.

## Install

```powershell
scoop bucket add taku https://github.com/taidaru/scoop-taku
scoop install taku
```

## Updating

```powershell
scoop update taku
```

To pin a specific version:

```powershell
scoop install taku@0.1.4
```

The manifest is updated automatically by the [release pipeline](https://github.com/taidaru/taku/blob/main/.github/workflows/scoop.yml)
on every Taku release. Issues and pull requests belong in the
[main repository](https://github.com/taidaru/taku).
