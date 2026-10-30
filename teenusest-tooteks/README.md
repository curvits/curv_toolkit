# Teenusest tooteks

Claude'i skill, mis aitab teenusettevõtte omanikul pakendada oma teenuse 2 kuni 3 selgeks paketiks, enne kui ta läheb turunduse ja kodulehe juurde.

## Kellele

Omanikule, kelle teenus on hea, aga:
- klient ei saa kohe aru, miks valida just teid
- müük käib peamiselt soovituste peal
- turundus ei hakka tööle, sest pole selge, mida turundada

## Mis juhtub

Neli etappi:

1. **Mõista.** Ärimudel täna, sihtrühmad, konkurendid.
2. **Kuula.** Ideaalklient, persoonad, kliendiintervjuud, ostuteekond.
3. **Ehita.** Väärtuspakkumine, paketid, hinnaloogika.
4. **Testi.** Paketid päris klientide ette, parandused, brief turunduspartnerile.

Tulemuseks on pakendamise tööleht, 2 kuni 3 testitud paketti ja brief, mille saad anda turunduspartnerile.

Töö alguses ja lõpus joonistab Claude sinu ärimudeli lõuendi: "Täna" ja "Pärast pakendamist". Nõrgad kohad, muutused ja oletused on märgitud värviga, nii et näed ühe pilguga, mis muutus. Lõuendi saad avada brauseris, salvestada ja printida.

## Mis on sinu töö

Claude juhib, küsib ja paneb kirja. Sina teed valikud ja räägid klientidega. Kliendiintervjuud ja testvestlused teed ise. See on kogu töö kõige väärtuslikum osa ja seda ei saa kellelegi teisele anda.

Arvesta:
- 3 kuni 4 tundi vestlust Claude'iga
- 6 kuni 8 kliendiintervjuud
- 5 testvestlust
- 2 kuni 4 nädalat kalendriaega

## Mida see EI tee

Turundus, reklaamid, kanalite valik, liidide prognoosid, koduleht. Skill annab sisu: mida ja kellele pakkuda. Turunduspartner otsustab, kuidas ja kus seda öelda.

## Kuidas kasutada

### Variant A: skillina (soovitatud)

1. Loo konto [claude.ai](https://claude.ai) lehel. Sobib ka tasuta konto.
2. Seadetes (**Settings > Capabilities**) lülita sisse failide loomine ja koodi käivitamine ("Code execution and file creation").
3. Lae alla fail [teenusest-tooteks.zip](https://github.com/curvits/curv_toolkit/raw/main/teenusest-tooteks/teenusest-tooteks.zip).
4. Claude'is ava **Customize > Skills**, vajuta **+**, siis **Create skill** ja **Upload a skill**. Vali ZIP-fail.
5. Loo Claude'is projekt ja lisa sinna oma materjalid: teenuste kirjeldus, veebileht, hinnakiri, varasemad pakkumised.
6. Ava projektis uus vestlus ja kleebi sinna:

```
Kasuta skilli teenusest-tooteks.

Tahan oma teenuse pakendada 2 kuni 3 paketiks. Lisasin projekti oma materjalid. Loe need läbi, tee kokkuvõte ja joonista meie ärimudeli lõuend täna. Seejärel juhenda mind samm-sammult edasi.
```

Täpsemad juhised: [Use skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)

### Variant B: projektina

Kui skille ei saa kasutada, loo Claude'is uus projekt. Kopeeri faili [`skill/SKILL.md`](skill/SKILL.md) sisu projekti juhistesse ja lisa kausta [`skill/references`](skill/references) neli faili projekti failideks.

### Nõuanne

Too esimesse vestlusesse kaasa kõik, mis sul olemas on: veebileht, teenuste kirjeldus, hinnakiri, varasemad pakkumised. Mida rohkem Claude ette teab, seda vähem pead kordama.

Hoia tööleht alles. Kui jätkad hiljem uues vestluses, too tööleht kaasa ja Claude jätkab sealt, kus pooleli jäi.

## Autor

Liina Kurvits, Curv Consulting ([curv.ee](https://curv.ee))

Vabalt kasutatav. Kui jagad edasi või muudad, palun viita autorile.

[Kõik Curvi tööriistad](../README.md)
