##### Signed by https://keybase.io/jasnell
```
-----BEGIN PGP SIGNATURE-----
Comment: GPGTools - https://gpgtools.org

iQEcBAABCgAGBQJWDMSSAAoJEHNBsVwHCHesTLgIAKXyftvHUfZDkK8u9+AxwHz/
EUyG7CtGZLow0Yox6TT+oaZqPGetopc3FR0rIeLdvWWE/smW/Do0zKO6X3rYW/9H
TbFmfLE16wvjsXky+O0oujbJBV8W87pmoamjtvsK5inAPgNMKyeW5dPbg4j8rDdZ
q9oo5++1HIBCX4n5kah5U13HE8SmAZRa1IJammYhpe+i8fj6ScVoGSwIlmsyep+j
Y/9gngbpN5nWhGUayFdok9VBJmILdpdaS+nBAhEey8TxCmLCgbFxfCPJAItPSdMZ
odfc+/nDttPEzjDE8rKk0T0X7JLxKYwm3G61DQuwlMmBU9alyoRjQUAFyZNi81A=
=piKI
-----END PGP SIGNATURE-----

```

<!-- END SIGNATURES -->

### Begin signed statement 

#### Expect

```
size   exec  file               contents                                                        
             ./                                                                                 
13             .gitignore       16d30e4462189fb14dd611bdb708c510630c576a1f35b9383e89a4352da36c97
93             .jshintrc        ac72baaccc327aca1aa7b22eb98d0eec7b15a69cfc2fe5a568c6f086ba8e2197
21             .npmignore       db7c7703dda761d8eae3d95eb9e06747089ece470e853d11fa942136371e8e8f
               lib/                                                                             
1974             graph.js       06cbf5526061652ffb995188b50eb0c07b9da40969bf4d4ed03c493eff6eef23
272              isiterable.js  b08a75c62c2c034c2307dd28af6957a55794e817096543767967c3ce19a78b48
7798             reasoner.js    66af706cabbdb5b9bc3f1250579b3885f674b01eaca193021c778f0c1c191771
637              reduce.js      51a6367fd9813a55e8b92a1829c41f2c37bb24f2745a5ccb9ca9b1d0d4ec25a8
2371             xsd-graph.js   21a4b1af6a4dba3bcfd75497f0af312689b55ad7643dd30270ba9b73afea1c30
11381          LICENSE          2bcf83b42c65720625611f1fb2922bc9e3face6a22117331a13c9ed9f3af2903
583            package.json     18f0b3702de2d08ea1875ec2a121c402b31c434fc4f8eb715c1a522d2eb2af01
6535           README.md        05cd3f076e2c8f3820766dcde1ad9d75c2528ab5bf1eb98980c304373d2e3554
               test/                                                                            
6743             test.js        190263ffa2b5cc87070dc77ee2fdaa18844d96ae60857846f629c770e415eb3d
100              test.ttl       f8565fdf03792ac477fe70a38f11088b1cfefa4b4efa011d3747a65d539219c7
280            test.js          7005f02591dea7172b94601cae53fb9a6603e57baf2db2a75a24a8cd437f1758
```

#### Ignore

```
/SIGNED.md
```

#### Presets

```
git      # ignore .git and anything as described by .gitignore files
dropbox  # ignore .dropbox-cache and other Dropbox-related files    
kb       # ignore anything as described by .kbignore files          
```

<!-- summarize version = 0.0.9 -->

### End signed statement

<hr>

#### Notes

With keybase you can sign any directory's contents, whether it's a git repo,
source code distribution, or a personal documents folder. It aims to replace the drudgery of:

  1. comparing a zipped file to a detached statement
  2. downloading a public key
  3. confirming it is in fact the author's by reviewing public statements they've made, using it

All in one simple command:

```bash
keybase dir verify
```

There are lots of options, including assertions for automating your checks.

For more info, check out https://keybase.io/docs/command_line/code_signing