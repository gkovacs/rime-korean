# rime-hapanese

## About

This is a layout for typing in Korean. Supports both Hangul and Hanja.


## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `gkovacs/rime-korean` using plum:

```bash
bash rime-install gkovacs/rime-korean
```

Finally edit `default.custom.yaml` and add `korean` to the schema list:

```bash
patch:
  schema_list:
    - schema: korean
```

Now reload RIME and it should appear under your layouts.

## Layout

See `korean.dict.yaml` for details on the romanization convention. In a nutshell:

q or x = ng
y = eu

