# M7 Volume

Fork of [omarozt/M9Volume](https://github.com/omarozt/M9Volume) for Samsung Smart Monitor M7 / M70D.

## Change from M9Volume

Discovery used to match only `"M9"` in the `http://<ip>:8001/api/v2/` body, so an M7 was skipped. This also matches M7 / M70 / M8 / M9 / Smart Monitor / Samsung SmartTV, and Settings has a manual IP field.

Everything else is the original M9 Volume app. See that repo for setup and protocol notes.

```sh
./build.sh
```
