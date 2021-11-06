# built on ubuntu 64 bit

This is a custom adjustment of bsc's p2p code that should help you sync up faster

i use this config: (can probably drop the nat=none)

```bash
./geth \
    --config ./config.toml \
    --syncmode=fast \
    --verbosity=3 \
    --nat=none \
    --v5disc \
    --datadir=./node \
    --cache=48934 \
    --maxpeers 750
```
