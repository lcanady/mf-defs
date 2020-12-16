# Convenient Mush-Format definitions

> This repo is under constant change as I run into more patterns that I just don't feel like repeating anymore, haha! I'll try to keep it as stable as I can but.. use at your own risk!

## Object Creation defintions

Definitions related to creating different sorts of objects in-game.

### `@[g]make/thing <name>=<tag>[, <flags>]`

Make a thing with a tag, and set any flags if needed.  If you choose the `@gmake` form, the thing will have a few basic 'global' flags set on top of what you feed the command before it's sent to your master room.

```
@gmake Globals: Staff Globals Object <SGO>=sgo
```
