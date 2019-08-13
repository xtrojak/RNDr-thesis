# RNDr thesis

1. intro
   - vysvetlit sysbio veci, problem scalability zapisu a tiez analyzy
   - predstavit rule-based ako koncept ktory sa na to zameriava, ale stale neriesi
   - obecny ciel umoznenie analyz rule-based systemov nejakym efektivnym sposobom
   - motivacia aj skrz CMP?
2. definicia rule-based formalizmu
   - matematicky obecne ako to mam na papieroch s obecnymi rate funkciami
   - obecne co to je, v com su vyhody
   - definovat semantiku ako nieco explicitne (asi DTMC/CTMC/cokolvek chceme)
3. state of the art
   - existujuce jazyky (aj ten nas)
   - vyzdvihnut nas jazyk, ale riesime veci obecne
   - problem ich abstrakcie a preco sa tazko analyzuju
   - naco je dobra staticka analyza
   - model checking simulacnym/statistickym sposobom, preco nedostatocna, chceme garancie
   - NFsim a aj ine veci uz urobene pre rule-based
   - su nejake chybajuce veci, medzi nimi analyza ale aj popis na urovni abstrakcie nasho jazyka
4. ciel -- niektore, idealne vsetky z tychto:
   - vyvoj jazyka pre CMP (v praktickych cieloch musi byt povedane, platforma si vyzaduje tento jazyk, proste sa tam pouziva)
   - model checking
   - explicitna synteza parametrov
   - symbolicky pristup
   - staticka analyza ako alternativny pristup
5. co je urobene
   - vyvoj CMP (CMSB16 ecyano publikacia?)
   - definicia jazyka (SASB18 - preco sme ho robili? ina abstrakcia vhodna na nieco, co sa musi ukazat ze dava zmysel)
   - vybrane staticke analyzy vyuzivajuce specialnu abstrakciu (SASB18)
   - rozsirenie o kvantitativnu zlozku (neopublikovane, chceme riesit?)

- diza o Chromare - potencialne zdroje
- Matejov proposal - pekne intro