# Lua C library

This is a port of [Lua](https://lua.org) library for [pacc](https://github.com/PoetaKodu/pacc) build tool.

## Installation guide

Add `lua@5.4.3` to your `cpackage.json` dependencies,
then use command

```bash
pacc install
```

### Example config

```json
{
	"name": "MyTestLuaApp",
	"type": "app",
	"language": "C++20",
	"dependencies": [ "lua@5.4.3" ]
}
```

## Original note

This is Lua 5.4.3, released on 15 Mar 2021.

For installation instructions, license details, and
further information about Lua, see doc/readme.html.

