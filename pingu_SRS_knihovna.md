# SRS analyza

## 1. uvod

API pro skolni knihovnu s priblizne 3000 knih.
Evidace knih (název, autor, žánr, rok vydání, ISBN), pocet knih.
Ctenari jsou zaci a zamestnanci skoly.  

## 2. Analiza zainteresovanych stran
- **Knihovnice** Ma mit pristup a kontrolu nad veskerimi tytuli, muze si zobrazit vypujcky, vsechny prodlouzeni a knihy po terminu odevzdani
muze registrovat ucitele a zaky 
- **Zak** muze si zobrazit knihy, jeho vypujceni a jejich status, ma omezeni na pocet a cas vypujceni knihy. Muze vypujcku prodlouzit
- **Ucitel** 

### featury & omezeni

#### moznosti uzivatele
1. pujceni knihy - pokud je na sklade volna, zak muze mit pujcene max 3 knihy najednou
2. vraceni knihy - 
3. zarezervovani knihy - rezervace zacina v den vraceni knihy na sklad a od te doby rezervace trva po dobu 3 dnu
4. prodlouzeni knihy- prodlouzene knihy jiz nejdou prodlouzit
5. zobrazit knihy
6. zobrazit moje knihy a jejich status

#### moznosti knihovnice
1. zobrazit knihy
2. zobrazit vypujcky
3. zobrazit top knihy
4. zobrazit seznam knih nenavracenych do terminu
5. pridat knihu(konkretni kus)
6. odebrat knihu
7. pridat titul(pod titul patri vicero jednotlivych vitisku)
8. odebrat titul

**Omezeni vsech**
1. vypujcku jde prodlouzit, pouze pokud tato specificka kniha neni zarezervovana

**Omezeni zaka**
1. pujcene max 3 knihy najednou
2. knihu muze mit pujcenou max na dobu 30 dni

