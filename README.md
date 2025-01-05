# LED stromeček
## Cíl projektu
Cílem projektu je  splnění zadání ze školy:) ale také jsem chtěl využít rasbery pi pico a také se naučit nějaké základy rasbery pi pico. a jako bonus je sestrojení (doufejme) hezké dekorace.
## Z čeho se muj projekt skládá:
Rasbery pi pico: 

![IMG 20250105 134515202](IMG_20250105_134515202.jpg)

použito jakožto řídící jednotka 

Tranzisory:

![IMG 20250105 134421034](IMG_20250105_134421034.jpg)

3x P2N2222A použito jakožto spínač pro větší větve s diodami protože by měli větší proud než je povoleno pro jednotlivé výstupy (GPIOX)

Ochrané rezistory:

![IMG 20250105 134404489](IMG_20250105_134404489.jpg)

330R 9x

10K 2x

10R 7x

1K 2x

220 2x

Ochranné rezistory slouží k ochraně diod proti nadměrnému napětí a proudu.

Led diody:

![IMG 20250105 134347196](IMG_20250105_134347196.jpg)

25x ruzné barvy 

"Chuchvalec" starých elektrických drátů z auta:

![IMG 20250105 134425141](IMG_20250105_134425141.jpg)

## Elektrotechnické schéma:

![Snímek obrazovky 2025-01-05 133855](Snímek%20obrazovky%202025-01-05%20133855.png)
Vytvořeno v Tinkercad
## Verze
### V0.1 NF
Tato verze je NF jako: nefunkční nebo not finished. V teto verzi je hotovo asi 68% projektu diody pripajená pouze anoda katoda v procesu. Tranzistory připájené i s ochranými odpory 
![IMG 20241219 193805434 HDR](IMG_20241219_193805434_HDR.jpg)![IMG 20241219 193809039 HDR](IMG_20241219_193809039_HDR.jpg)![IMG 20241219 193812339](IMG_20241219_193812339.jpg)
### V0.2
Napájení katod a průběžné řešení izolace u jedné z elektrod diody a příprava pripájení Rasbery pi pico a spojování jednotlivých větví více ve videu 

[Video V0.2](https://drive.google.com/file/d/1NQ10m_3WI_LUUCVfmrpTRvGcRcWG3vj5/view?usp=sharing)
