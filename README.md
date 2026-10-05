<!-- tyhp-readme:start -->
# tyhpdef/illuminate-hashing

Tyhp type definitions for `illuminate/hashing` `13.32.0`.

```bash
composer require --dev tyhpdef/illuminate-hashing:13.32.0
```

This is a metapackage. Composer also installs `tyhpdef/illuminate-hashing-impl` (type files).
Require **this** name, not `tyhpdef/illuminate-hashing-impl`.

See https://tyhplang.com.

## Maintain `illuminate/hashing`? Ship the types yourself

If you are a Packagist maintainer of `illuminate/hashing`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/illuminate-hashing-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `illuminate/hashing` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/illuminate-hashing": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `illuminate/hashing` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `illuminate/hashing` with a real constraint,
   `"replace": { "tyhpdef/illuminate-hashing": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `illuminate/hashing` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/illuminate-hashing` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
