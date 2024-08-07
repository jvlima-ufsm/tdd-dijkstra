
# TDD - Algoritmo de Dijkstra

Este é o código exemplo do trabalho usando TDD (*Test Driven Development*) com o framework C++ [Catch2](https://github.com/catchorg/Catch2/tree/v2.x).


O framework Catch2 consegue ser utilizado apenas com o arquivo header [catch.hpp](catch.hpp) sem necessidade de instalação.

**NÃO MODIFIQUE OS TESTES** 

Todos os testes estão prontos no arquivo [dijkstra.cpp](dijkstra.cpp). A compilação e teste pode ser feita com os comandos:
```
$ g++ -Wall -std=c++11 -o dijkstra dijkstra.cpp  catch_amalgamated.cpp
```

A saída resumida do teste (código exemplo):
```
$ ./dijkstra --reporter compact --success
dijkstra.cpp:186: passed: g.caminhoMinimo(1,2) == false for: false == false
dijkstra.cpp:201: failed: res.size() == 3 for: 0 == 3
dijkstra.cpp:217: failed: res.size() == 2 for: 0 == 2
dijkstra.cpp:228: failed: res == resp for: {  } == { 5, 7, 2, 6 }
dijkstra.cpp:238: failed: res == resp for: {  } == { 4, 7, 3 }
dijkstra.cpp:248: failed: res == resp for: {  }
==
{ 10, 106, 179, 79, 51, 18, 35, 12, 121, 158, 249, 189, 150, 190, 247 }
dijkstra.cpp:259: failed: res == resp for: {  }
==
{ 2, 1, 22, 165, 162, 167, 164, 171, 190, 191, 336 (0x150), 338 (0x152), 343 (0x157), 344 (0x158), 340 (0x154), 347 (0x15b), 348 (0x15c), 335 (0x14f), 515 (0x203), 407 (0x197), 524 (0x20c), 582 (0x246), 589 (0x24d), 596 (0x254), 628 (0x274), 630 (0x276), 648 (0x288), 1217 (0x4c1), 1218 (0x4c2), 1237 (0x4d5), 1239 (0x4d7), 1252 (0x4e4), 1253 (0x4e5), 1258 (0x4ea), 1259 (0x4eb), 1260 (0x4ec), 1354 (0x54a), 1360 (0x550), 1365 (0x555), 1364 (0x554), 1381 (0x565), 1382 (0x566), 1426 (0x592), 1429 (0x595), 1736 (0x6c8), 1740 (0x6cc), 1741 (0x6cd), 1744 (0x6d0), 1745 (0x6d1), 1786 (0x6fa), 1785 (0x6f9), 1791 (0x6ff), 1799 (0x707), 1800 (0x708), 1808 (0x710), 1813 (0x715), 1814 (0x716), 1815 (0x717), 2028 (0x7ec), 1935 (0x78f), 1936 (0x790), 2052 (0x804), 2055 (0x807), 1966 (0x7ae), 2056 (0x808), 2057 (0x809), 2422 (0x976), 2360 (0x938), 2358 (0x936), 2359 (0x937), 2361 (0x939), 2364 (0x93c), 2395 (0x95b), 2396 (0x95c), 2397 (0x95d), 2400 (0x960), 2407 (0x967), 2411 (0x96b), 2506 (0x9ca), 2632 (0xa48), 2633 (0xa49), 2638 (0xa4e), 2594 (0xa22), 2642 (0xa52), 2658 (0xa62), 2659 (0xa63), 2660 (0xa64), 2670 (0xa6e), 2673 (0xa71), 2841 (0xb19), 2844 (0xb1c), 2856 (0xb28), 2857 (0xb29), 2863 (0xb2f), 2864 (0xb30), 3337 (0xd09) }
Failed 6 test cases, failed 6 assertions.
```

