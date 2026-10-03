# Test run 2026-10-03 21:13:41 (Europe/Budapest)

RUN_STAMP: 2026-10-03 21:13:41

| Test | Result | Duration |
|---|---|---|
| T3 round trip (fresh clone specs repo) | PASS | clone 1 s; specs=21 files, build=5 files |
| T4 build and publish | PASS | build.py 0 s, workbook.py 1 s, site=43 files (22 html incl. index, 21 pdf); clone 1 s, push 3 s; ls-remote == local HEAD |
| T2 cloud update of hello page | PASS | push+verify 2 s; ls-remote == local HEAD |

## Commits pushed
- italiano-b1-test: 3379c76435e21f5bcf3c19d6f982ee80584223c5
- pages-test (T2): f5ae84a2db436397c2eb88186bade944b15aa993

## Errors / notes
- none fatal. Note: specs/ contains a file named "lesson-05 (1).json" (space in name; counted among the 21).
- reportlab was missing and installed with pip (pip root-user warning only).

## specs checksums
| file | bytes | sha256 |
|---|---|---|
| specs/lesson-01.json | 19978 | e3396d98af4a4d4a61c97aacb7916fc49399450004604d8d792f611ebafc852d |
| specs/lesson-02.json | 20154 | bab3b3b4d27ad8d50788a38f1bbbafe5c05f4d6e46007c3331b96279660e4fc5 |
| specs/lesson-03.json | 19879 | 0608083c1a456567750a3180148fe05f98e491b7b0c36aa46a28efbaf23595ca |
| specs/lesson-04.json | 27235 | e682b59fd433f5560f996a0b5062dfd227703d11c11db99b6166c33db1ea5dbb |
| specs/lesson-05 (1).json | 30384 | f86e28188b7ed2d1bba79dc93037169b837b6049303f68858e0edd36d4befe9c |
| specs/lesson-06.json | 33847 | bd57c8a16e7d2182562f1c0af92f9eab7699ab62e9f31b5ffce9a78bcfc07d1d |
| specs/lesson-07.json | 31750 | 53facdc0a8a8a2c303f78c6e8d854df0a78ae8bae1b70ab677c5003e940e3b72 |
| specs/lesson-08.json | 31319 | cee7d412915272915aa6c2aac786e0f92e0789fc0fb9a9dbc8759f2d0be01082 |
| specs/lesson-09.json | 30475 | 3ef4021dfb9025acc020ec78f6c39086938a505d5e648c689ede66c0f0bdfdc8 |
| specs/lesson-10.json | 36876 | de3c33de1aa2b2d607caa71db32c566a8690dd32b2acccc1c7580d684321e949 |
| specs/lesson-11.json | 27293 | 04ffb3f7b5173240497b25dbf77908b1292f8e433731a283a7bd64f7fb093921 |
| specs/lesson-12.json | 24523 | 40ef52aa393e32277f8a14d7455468bcbcc3288357d9bd9a13022772d847bae6 |
| specs/lesson-13.json | 25707 | cce97201c02d7c5984059eafa35519647806ca437f1babae653cd75fc6d566f7 |
| specs/lesson-14.json | 25687 | 500ee01d67123e2d6316ec5a940485fa6c9767d45fcb3ef50c7a81be4bff36e8 |
| specs/lesson-15.json | 27864 | c969a343cd9336b9f36d1c5dc809c3ef6ca18d8f17b9d7fb43e0e1bdd81a4cd0 |
| specs/lesson-16.json | 30454 | 3a02e4815a96d683aafc88666be2ed3e0c7f7114571e618efa5da11e5ae3f59c |
| specs/lesson-17.json | 29058 | d4ea010a03ea4df2edc66a24ca1a1289107b0d09b5900bef1183bf5e4c586feb |
| specs/lesson-18.json | 24932 | 0cda918a3f99d060d36757fe3e0b10836b2a6444bc2656f4c3009057a05d7bf5 |
| specs/lesson-19.json | 24380 | 751687d9fc382c301a7876ebd3da8fb69a340cbe16b7ad7601c65a32c63f92cf |
| specs/lesson-20.json | 26265 | ba7f25ad63bf05bebd1b07a9fbb7e4df8cfa464835572e265c2594e35eba8166 |
| specs/lesson-21.json | 27492 | 8c1d390d7753d7995e9c10c6800d49e26fde47c5253f2a4b5d4737e201aec1c1 |

## curl https://youknowwho1042-alt.github.io/italiano-b1-test/
curl: (56) CONNECT tunnel failed, response 403
000 (informational)
