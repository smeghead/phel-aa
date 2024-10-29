# phel-aa

Convert png images to ASCII art.

## Development

### Open shell

```bash
docker compose build
docker compose run --rm php_cli bash
```

### Run

```bash
composer phel-aa tests/PHP-logo.png
``````````````````````_______````````````````````````
`````````````__w%%w@@@@=@@@@@@@<=@]U0m__`````````````
`````````_wX1@@@@@@@@@@@====@@@@@@@@@@@@MA*_`````````
``````_%w@@@@@@@@@@@@@@|mmm_@@@@@@@@@@@@@@@@=i.``````
````_j@@@@@@@@@@@@@@@@@~mms@@@@@@@@@@@@@@@@@@@@_`````
``_w=@@@@@@_mmmmmmmg_==mmmmmmmmm.=~mmmmmmmm.m@@@@a-``
`_V@@@@@@@|Mmm****mmms|mmm"""_mmm-mmm***_Mmme<@@@@b*`
`s@@@@@@@@`mmK<@@@_mmm_mms@@@|mmm`mmm~@@@|mmm~@@@@@i`
~@@@@@@@@]_mm|@@@@_mmsJmm|@@@~mmr_mmz@@@@`mmQ_@@@@@]*
`@@@@@@@@]mmm`'`-~mmm.Mmm_@@]Jmm|mmm|'```mmm_@@@@@@||
`%@@@@@@@`mmmmmmmmm_@`mmrq@@|mmm`mmmmmmmmm"_@@@@@@@i`
``C@@@@@@_mm|____@@@@____@@@____~mmr_____=@@@@@@@@&``
````%=@@]Mmm~@@@@@@@@@@@@@@@@@@]Jmm|@@@@@@@@@@@@d|```
`````"9@|```@@@@@@@@@@@@@@@@@@@]```_@@@@@@@@@>i*`````
````````m%@=@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@2ri````````
````````````00%m@@@@@@@@@@@@@@@@@@@@@mddr-```````````
``````````````````^Ok%mQm@mmd5iii***`````````````````
```

### Test

```bash
# vendor/bin/phel test
```

