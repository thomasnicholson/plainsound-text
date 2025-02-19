# Plainsound Text

A somewhat condensed, Univers-inspired sans serif with integrated Helmholtz-Ellis Just Intonation (HEJI)
accidentals. See section “Typing accidentals” for information on HEJI usage.

Currently in development. Beta versions of regular and bold weights with their italics available. 

![Specimen](Testing/Specimen.png)

## License

Plainsound Text is released under the SIL Open Font License. See LICENSE for more information.

## Language support
(Evaluation by Google’s [Shaperglot](https://github.com/googlefonts/shaperglot?tab=readme-ov-file))

Achinese, Afar, Afrikaans, Alago, Albanian, Alekano, Aleut, Anaang, Ao Naga, Arabic, Chadian Spoken, Aragonese, Aromanian, Asu, Awak, Aymara, Balinese, Banda, West Central, Bangwinji, Bapuku, Basque, Batak Toba, Bedawiyet, Bekwarra, Bemba, Bena, Bench, Benga, Bikol, Bilen, Bislama, Bokobaru, Bosnian, Bube, C’Lela, Cebuano, Chamorro, Chiduruma, Chiga, Chimborazo Highland Quichua, Chokwe, Chuukese, Comorian, Ngazidja, Cornish, Corsican, Crioulo, Upper Guinea, Croatian, Czech, Danish, Dawro, Delaware, Dikaka, Ekajuk, Embu, Esperanto, Estonian, Faroese, Fijian, Filipino, Friulian, Fuliiru, Gagauz, Gamo, Ganda, Gheg Albanian, Gilbertese, Gofa, Gourmanchéma, Gusii, Gwichʼin, Gyele, Haitian Creole, Harari, Hiligaynon, Hmong, Hopi, Hungarian, Icelandic, Iloko, Inari Sami, Indonesian, Innu, Interlingua, Iraqw, Irish, Izere, Jamaican Creole English, Javanese, Jibu, Jola-Fonyi, Kabuverdianu, Kaingang, Kalanga, Kalenjin, Kamba, Karelian, Kashubian, Khasi, Kikuyu, Kimbundu, Kinyarwanda, Kirmanjki, Kituba, Kombe, Kongo, Konjo, Kuanyama, Kunama, Kurdish (Latin), Kutep, Kutu, Kwere, Kʼicheʼ, Lamba, Lango, Uganda, Latgalian, Latin, Latvian, Lele, Ligurian, Lombard, Lomwe, Luba-Lulua, Luguru, Lule Sami, Lunda, Luvale, Luwo, Luyia, Machame, Makhuwa, Makhuwa-Meetto, Makonde, Malagasy, Malay (Latin), Maltese, Mam, Mambila, Nigeria, Mandinka, Mandjak, Mankanya, Manx, Manyika, Maori, Mapuche, Masaaba, Meru, Minangkabau, Mirandese, Mohawk, Morisyen, Muscogee, Mwani, Nara, Ndamba, Ndau, Ndonga, Neapolitan, Ngindo, Ngulu, Niuean, North Ndebele, Northern Sami, Northern Sotho, Northern Tutchone, Norwegian, Norwegian Bokmål, Norwegian Nynorsk, Novial, Nyanja, Nyankole, Nyasa Tonga, Nyemba, Nyoro, Occitan, Ogbah, Okiek, Oromo, Otuho, Palauan, Pampanga, Papiamento, Picard, Piedmontese, Pogolo, Pohnpeian, Pökoot, Portuguese, Prussian, Rarotongan, Rendille, Réunion Creole French, Rinconada Bikol, Romanian, Romansh, Romany, Rombo, Ronga, Rundi, Rwa, Saho, Samburu, Samoan, Sandawe, Sango, Sangu, Sãotomense, Sapiny, Sardinian, Sassarese Sardinian, Scots, Scottish Gaelic, Sena, Serbian (Latin), Seri, Seselwa Creole French, Shambala, Shilluk, Shona, Sidamo, Silesian, Slovak, Slovenian, Soga, Somali, South Ndebele, Southern Sami, Southern Sotho, Southern Tutchone, Spanish, Sranan Tongo, Suba, Sukuma, Sundanese, Swahili, Swahili, Congo, Swati, Swedish, Swiss German, Tahitian, Taita, Takwane, Tedim Chin, Tetum, Tiv, Tok Pisin, Tokelau, Tonga, Tooro, Tsonga, Tsuvadi, Tswana, Tula, Tumbuka, Turkmen (Latin), Tuvalu, Uab Meto, Umbundu, Uyghur (Latin), Venetian, Veps, Vidunda, Volapük, Võro, Vunjo, Walloon, Waray, Warlpiri, Wayuu, Welsh, West Albay Bikol, Western Frisian, Wolaytta (Latin), Wolof, Xavánte, Xhosa, Yao, Yapese, Yasa, Yucateco, Zaghawa, Zande, Zayse, Zaza, Zigula, Zulu

## Typing accidentals

Accidentals are typed as strings beginning with the an asterisk followed by sematic shorthands
relating to otonality vs. utonality (“o” vs. “u”) and prime number identities. These strings
automatically transform as ligatures into the desired accidental.

| Accidental description                               | Unicode | Type this |
| ---------------------------------------------------- | ------- | --------- |
| Flat                                                 | U+E260  | \*f       |
| Natural                                              | U+E261  | \*n       |
| Sharp                                                | U+E262  | \*s       |
| Double sharp                                         | U+E263  | \*S       |
| Double flat                                          | U+E264  | \*F       |
| Double flat with 5-limit comma otonal                | U+E2C0  | \*Fo5     |
| Flat with 5-limit comma otonal                       | U+E2C1  | \*fo5     |
| Natural with 5-limit comma otonal                    | U+E2C2  | \*no5     |
| Sharp with 5-limit comma otonal                      | U+E2C3  | \*so5     |
| Double sharp with 5-limit comma otonal               | U+E2C4  | \*So5     |
| Double flat with 5-limit comma utonal                | U+E2C5  | \*Fu5     |
| Flat with 5-limit comma utonal                       | U+E2C6  | \*fu5     |
| Natural with 5-limit comma utonal                    | U+E2C7  | \*nu5     |
| Sharp with 5-limit comma utonal                      | U+E2C8  | \*su5     |
| Double sharp with 5-limit comma utonal               | U+E2C9  | \*Su5     |
| Double flat with double 5-limit comma otonal (25°)   | U+E2CA  | \*Fo25    |
| Flat with double 5-limit comma otonal (25°)          | U+E2CB  | \*fo25    |
| Natural with double 5-limit comma otonal (25°)       | U+E2CC  | \*no25    |
| Sharp with double 5-limit comma otonal (25°)         | U+E2CD  | \*so25    |
| Double sharp with double 5-limit comma otonal (25°)  | U+E2CE  | \*So25    |
| Double flat with double 5-limit comma utonal (u25)   | U+E2CF  | \*Fu25    |
| Flat with double 5-limit comma utonal (u25)          | U+E2D0  | \*fu25    |
| Natural with double 5-limit comma utonal (u25)       | U+E2D1  | \*nu25    |
| Sharp with double 5-limit comma utonal (u25)         | U+E2D2  | \*su25    |
| Double sharp with double 5-limit comma utonal (u25)  | U+E2D3  | \*Su25    |
| Double flat with triple 5-limit comma otonal (125°)  | U+E2D4  | \*Fo125   |
| Flat with triple 5-limit comma otonal (125°)         | U+E2D5  | \*fo125   |
| Natural with triple 5-limit comma otonal (125°)      | U+E2D6  | \*no125   |
| Sharp with triple 5-limit comma otonal (125°)        | U+E2D7  | \*so125   |
| Double sharp with triple 5-limit comma otonal (125°) | U+E2D8  | \*So125   |
| Double flat with triple 5-limit comma utonal (u125)  | U+E2D9  | \*Fu125   |
| Flat with triple 5-limit comma utonal (u125)         | U+E2DA  | \*fu125   |
| Natural with triple 5-limit comma utonal (u125)      | U+E2DB  | \*nu125   |
| Sharp with triple 5-limit comma utonal (u125)        | U+E2DC  | \*su125   |
| Double sharp with triple 5-limit comma utonal (u125) | U+E2DD  | \*Su125   |
| Septimal comma otonal                                | U+E2DE  | \*o7      |
| Septimal comma utonal                                | U+E2DF  | \*u7      |
| Double septimal comma otonal (49°)                   | U+E2E0  | \*o49     |
| Double septimal comma utonal (u49)                   | U+E2E1  | \*u49     |
| Undecimal quarter tone utonal                        | U+E2E2  | \*u11     |
| Undecimal quarter tone otonal                        | U+E2E3  | \*o11     |
| Tridecimal third tone otonal                         | U+E2E4  | \*o13     |
| Tridecimal third tone utonal                         | U+E2E5  | \*u13     |
| 17-limit schisma otonal                              | U+E2E6  | \*o17     |
| 17-limit schisma utonal                              | U+E2E7  | \*u17     |
| 19-limit schisma utonal                              | U+E2E8  | \*u19     |
| 19-limit schisma otonal                              | U+E2E9  | \*o19     |
| 23-limit comma otonal                                | U+E2EA  | \*o23     |
| 23-limit comma utonal                                | U+E2EB  | \*u23     |
| 31-limit quarter tone otonal                         | U+E2EC  | \*o31     |
| 31-limit quarter tone utonal                         | U+E2ED  | \*u31     |
| Tempered double flat                                 | U+E2F0  | \*Ft      |
| Tempered flat                                        | U+E2F1  | \*ft      |
| Tempered natural                                     | U+E2F2  | \*nt      |
| Tempered sharp                                       | U+E2F3  | \*st      |
| Tempered double sharp                                | U+E2F4  | \*St      |
| Tempered quarter flat                                | U+E2F5  | \*qft     |
| Tempered quarter sharp                               | U+E2F6  | \*qst     |
| 29-limit sixth tone utonal                           | U+EE50  | \*u29     |
| 29-limit sixth tone otonal                           | U+EE51  | \*o29     |
| 37-limit quarter tone utonal                         | U+EE52  | \*u37     |
| 37-limit quarter tone otonal                         | U+EE53  | \*o37     |
| 41-limit comma utonal                                | U+EE54  | \*u41     |
| 41-limit comma otonal                                | U+EE55  | \*o41     |
| 43-limit comma utonal                                | U+EE56  | \*u43     |
| 43-limit comma otonal                                | U+EE57  | \*o43     |
| 47-limit third tone otonal                           | U+EE58  | \*o47     |
| 47-limit third tone utonal                           | U+EE59  | \*u47     |
