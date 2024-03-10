# AtCoder Contest Archive

## Setup

```
$ cargo compete <contest>
```

> [!NOTE]
> `<contest>`: e.g. `abc300`, `arc170`

## Test and Submit

```
$ cd <contest>
$ cargo compete test <problem>
...
$ cargo compete submit
```

> [!NOTE]
> `<problem>`: e.g. `a`, `b`

## Initial Setup

install `cargo-compete`
```
$ cargo install cargo-compete
```

> [!NOTE]
> `cargo-update` を使っているなら，次のようにアップデートできる．
> ```
> $ cargo install-update -a
> ```

### AtCoder 2023 Language Update

edition 2018
toolchain 1.70.0

- `ac-library-rs`
- `once_cell`
- `static_assertions`
- `varisat`
- `memoise`
- `argio`
- `bitvec`
- `counter`
- `hashbag`
- `pathfinding`
- `recur-fn`
- `indexing`
- `amplify`
- `amplify_derive`
- `amplify_num`
- `easy-ext`
- `multimap`
- `btreemultimap`
- `bstr`
- `az`
- `glidesort`
- `tap`
- `omniswap`
- `multiversion`
- `num`
- `num-bigint`
- `num-complex`
- `num-integer`
- `num-iter`
- `num-rational`
- `num-traits`
- `num-derive`
- `ndarray`
- `nalgebra`
- `alga`
- `libm`
- `rand`
- `getrandom`
- `rand_chacha`
- `rand_core`
- `rand_hc`
- `rand_pcg`
- `rand_distr`
- `petgraph`
- `indexmap`
- `regex`
- `lazy_static`
- `ordered-float`
- `ascii`
- `permutohedron`
- `superslice`
- `itertools`
- `itertools-num`
- `maplit`
- `either`
- `im-rc`
- `fixedbitset`
- `bitset-fixed`
- `proconio`
- `text_io`
- `rustc-hash`
- `smallvec`
