# MiniTorch Module 1

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module1/module1/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py tests/test_module.py tests/test_operators.py project/run_manual.py

## Train logs

### Simple 

#### Config:

```commandline
PTS = 50
HIDDEN = 2
RATE = 0.5
```

```commandline
Epoch  10  loss  34.202339086948484 correct 29
Epoch  20  loss  34.07684740054857 correct 29
Epoch  30  loss  34.01798430570014 correct 29
Epoch  40  loss  33.95205136265656 correct 29
Epoch  50  loss  33.857253846365005 correct 29
Epoch  60  loss  33.67131996378011 correct 29
Epoch  70  loss  32.91955722497805 correct 29
Epoch  80  loss  30.82353595670957 correct 36
Epoch  90  loss  25.287375625315775 correct 42
Epoch  100  loss  16.84603154560499 correct 47
Epoch  110  loss  12.360358170227089 correct 46
Epoch  120  loss  12.529301295137854 correct 45
Epoch  130  loss  10.900459986621323 correct 46
Epoch  140  loss  7.859625910122675 correct 48
Epoch  150  loss  7.161187042267067 correct 48
Epoch  160  loss  7.40788456945937 correct 48
Epoch  170  loss  4.833722660346729 correct 49
Epoch  180  loss  2.9805079380835027 correct 50
Epoch  190  loss  2.592285104215287 correct 50
Epoch  200  loss  2.30684151431829 correct 50
Epoch  210  loss  2.0863745561429505 correct 50
Epoch  220  loss  1.903727530342547 correct 50
Epoch  230  loss  1.7694681907153786 correct 50
Epoch  240  loss  1.6585575820999454 correct 50
Epoch  250  loss  1.7975478759019086 correct 49
Epoch  260  loss  3.355136590912195 correct 49
Epoch  270  loss  1.5618351105857766 correct 50
Epoch  280  loss  1.4215680787416554 correct 50
Epoch  290  loss  1.3245375589643567 correct 50
Epoch  300  loss  1.2426670700180558 correct 50
Epoch  310  loss  1.1719978075722017 correct 50
Epoch  320  loss  1.1090494273774418 correct 50
Epoch  330  loss  1.049786405154035 correct 50
Epoch  340  loss  0.9971839909517203 correct 50
Epoch  350  loss  0.9502183573075141 correct 50
Epoch  360  loss  0.9066649751043938 correct 50
Epoch  370  loss  0.8657731053345941 correct 50
Epoch  380  loss  0.8277256720391468 correct 50
Epoch  390  loss  0.786799416944342 correct 50
Epoch  400  loss  0.749705252096832 correct 50
Epoch  410  loss  0.7263310169640351 correct 50
Epoch  420  loss  0.6954118232117085 correct 50
Epoch  430  loss  0.6645046169119181 correct 50
Epoch  440  loss  0.6437291168524345 correct 50
Epoch  450  loss  0.6167177453551141 correct 50
Epoch  460  loss  0.5971277885741836 correct 50
Epoch  470  loss  0.577458456728395 correct 50
Epoch  480  loss  0.5527203105763588 correct 50
Epoch  490  loss  0.5383573215687095 correct 50
Epoch  500  loss  0.5214811090867273 correct 50
```

### Diag 

#### Config:

```commandline
PTS = 50
HIDDEN = 2
RATE = 0.5
```

```commandline
Epoch  10  loss  22.095104050980467 correct 42
Epoch  20  loss  21.98032027454865 correct 42
Epoch  30  loss  21.937377594157322 correct 42
Epoch  40  loss  21.893548177949118 correct 42
Epoch  50  loss  21.844698616979542 correct 42
Epoch  60  loss  21.787156746338262 correct 42
Epoch  70  loss  21.716512605437856 correct 42
Epoch  80  loss  21.62714236513522 correct 42
Epoch  90  loss  21.51164732782366 correct 42
Epoch  100  loss  21.360135398808918 correct 42
Epoch  110  loss  21.159241980079326 correct 42
Epoch  120  loss  20.890678159161755 correct 42
Epoch  130  loss  20.528828694168393 correct 42
Epoch  140  loss  20.036316847537 correct 42
Epoch  150  loss  19.355123207862214 correct 42
Epoch  160  loss  18.3882607397464 correct 42
Epoch  170  loss  16.9656435832129 correct 42
Epoch  180  loss  14.822488465325579 correct 42
Epoch  190  loss  11.861731098526526 correct 43
Epoch  200  loss  9.355048376504143 correct 45
Epoch  210  loss  7.823627054251121 correct 48
Epoch  220  loss  6.75208812743793 correct 48
Epoch  230  loss  5.935789747827934 correct 49
Epoch  240  loss  5.4503555604897524 correct 50
Epoch  250  loss  4.841863737750263 correct 49
Epoch  260  loss  4.420389622420615 correct 50
Epoch  270  loss  3.994228939149722 correct 49
Epoch  280  loss  3.68219718794474 correct 50
Epoch  290  loss  3.393171863198427 correct 49
Epoch  300  loss  3.160431385992116 correct 50
Epoch  310  loss  2.956157835493893 correct 50
Epoch  320  loss  2.773916838372704 correct 50
Epoch  330  loss  2.6093810143879623 correct 50
Epoch  340  loss  2.4595033176337284 correct 50
Epoch  350  loss  2.3220623004472616 correct 50
Epoch  360  loss  2.1953899385094706 correct 50
Epoch  370  loss  2.0781991010585488 correct 50
Epoch  380  loss  1.9694699216624727 correct 50
Epoch  390  loss  1.8683731014119629 correct 50
Epoch  400  loss  1.7742173698012824 correct 50
Epoch  410  loss  1.6864132005642243 correct 50
Epoch  420  loss  1.6044476473300817 correct 50
Epoch  430  loss  1.527866840220811 correct 50
Epoch  440  loss  1.4562637610171383 correct 50
Epoch  450  loss  1.389269640081115 correct 50
Epoch  460  loss  1.3265478234003536 correct 50
Epoch  470  loss  1.267789315046677 correct 50
Epoch  480  loss  1.2127094523677828 correct 50
Epoch  490  loss  1.1610453473019482 correct 50
Epoch  500  loss  1.1125538483815407 correct 50

```
### Split 

#### Config:

```commandline
PTS = 50
HIDDEN = 8
RATE = 0.5
```

```commandline
Epoch  10  loss  33.2915179531932 correct 26
Epoch  20  loss  30.753756358977235 correct 35
Epoch  30  loss  28.808501901667608 correct 39
Epoch  40  loss  26.928173918958855 correct 42
Epoch  50  loss  25.974643735649277 correct 42
Epoch  60  loss  30.20699192546085 correct 32
Epoch  70  loss  32.3642208373841 correct 30
Epoch  80  loss  26.737127963770316 correct 35
Epoch  90  loss  22.83566504395506 correct 36
Epoch  100  loss  19.956820236335954 correct 42
Epoch  110  loss  22.68857009307473 correct 38
Epoch  120  loss  26.537093559008436 correct 35
Epoch  130  loss  18.477006311075716 correct 41
Epoch  140  loss  18.62475532407374 correct 39
Epoch  150  loss  18.884159780694496 correct 39
Epoch  160  loss  17.980799084209504 correct 40
Epoch  170  loss  13.560162664575234 correct 45
Epoch  180  loss  15.68331955900914 correct 42
Epoch  190  loss  11.685536655906752 correct 45
Epoch  200  loss  13.170895557157415 correct 43
Epoch  210  loss  11.156692912677105 correct 44
Epoch  220  loss  12.542568563494504 correct 44
Epoch  230  loss  10.538972276967103 correct 46
Epoch  240  loss  9.133607543069727 correct 46
Epoch  250  loss  7.785141947290236 correct 47
Epoch  260  loss  8.709613229729321 correct 47
Epoch  270  loss  6.601762597181814 correct 48
Epoch  280  loss  7.622844216379582 correct 47
Epoch  290  loss  16.017175430181368 correct 44
Epoch  300  loss  11.33085935629851 correct 44
Epoch  310  loss  9.440424893602124 correct 45
Epoch  320  loss  5.383362632405606 correct 48
Epoch  330  loss  3.1285492510896025 correct 50
Epoch  340  loss  2.8333356657618887 correct 50
Epoch  350  loss  3.623827654365503 correct 49
Epoch  360  loss  11.838648003938523 correct 45
Epoch  370  loss  3.0031739133977933 correct 49
Epoch  380  loss  2.06291826782773 correct 50
Epoch  390  loss  1.8050837730524558 correct 50
Epoch  400  loss  1.6284451648196892 correct 50
Epoch  410  loss  1.5016543352474263 correct 50
Epoch  420  loss  1.3959277825758318 correct 50
Epoch  430  loss  1.3082781592910715 correct 50
Epoch  440  loss  1.2319566549325787 correct 50
Epoch  450  loss  1.1642583308203023 correct 50
Epoch  460  loss  1.0974107170767051 correct 50
Epoch  470  loss  1.0407991228295406 correct 50
Epoch  480  loss  0.9983476605755714 correct 50
Epoch  490  loss  0.9631189390876965 correct 50
Epoch  500  loss  0.9315907921948834 correct 50
```

### Xor 

#### Config:

```commandline
PTS = 50
HIDDEN = 10
RATE = 0.5
```

```commandline
Epoch  10  loss  29.700503050609917 correct 35
Epoch  20  loss  28.279640539515057 correct 35
Epoch  30  loss  29.101801608295077 correct 34
Epoch  40  loss  28.0091826747676 correct 34
Epoch  50  loss  27.912557457101602 correct 34
Epoch  60  loss  28.164001042748534 correct 34
Epoch  70  loss  27.132047073849943 correct 34
Epoch  80  loss  26.573515883961747 correct 35
Epoch  90  loss  25.108695025038575 correct 37
Epoch  100  loss  25.24675452274744 correct 35
Epoch  110  loss  24.86574700801264 correct 36
Epoch  120  loss  23.226530013044567 correct 37
Epoch  130  loss  22.353233283421435 correct 37
Epoch  140  loss  21.189849610964274 correct 37
Epoch  150  loss  19.986044909550568 correct 37
Epoch  160  loss  18.962063071106922 correct 38
Epoch  170  loss  15.705749389745778 correct 41
Epoch  180  loss  15.702888335183802 correct 41
Epoch  190  loss  13.583405764393586 correct 45
Epoch  200  loss  14.399046674774937 correct 44
Epoch  210  loss  13.209790559567223 correct 45
Epoch  220  loss  12.04324277741329 correct 45
Epoch  230  loss  12.001896900880087 correct 45
Epoch  240  loss  10.773222262002543 correct 45
Epoch  250  loss  10.676060679986849 correct 45
Epoch  260  loss  10.1738160415903 correct 45
Epoch  270  loss  10.051101891509136 correct 45
Epoch  280  loss  9.055828971360686 correct 46
Epoch  290  loss  8.750053907988168 correct 46
Epoch  300  loss  9.184936371803495 correct 46
Epoch  310  loss  8.114258803277641 correct 46
Epoch  320  loss  8.259943050688113 correct 46
Epoch  330  loss  7.816459659534264 correct 46
Epoch  340  loss  7.826217927462673 correct 46
Epoch  350  loss  7.629840196878506 correct 46
Epoch  360  loss  7.3799514844238026 correct 47
Epoch  370  loss  7.168065557679006 correct 47
Epoch  380  loss  7.4405411788071065 correct 47
Epoch  390  loss  6.853015522456267 correct 47
Epoch  400  loss  6.7526913120056005 correct 47
Epoch  410  loss  6.69161941402938 correct 47
Epoch  420  loss  6.648534944122759 correct 47
Epoch  430  loss  6.723272895858393 correct 47
Epoch  440  loss  6.660490101394006 correct 47
Epoch  450  loss  6.186803822685075 correct 47
Epoch  460  loss  6.140207340503344 correct 47
Epoch  470  loss  6.032831819709032 correct 47
Epoch  480  loss  5.990862681106113 correct 47
Epoch  490  loss  6.063028157057107 correct 47
Epoch  500  loss  5.8335117738473015 correct 47
```
