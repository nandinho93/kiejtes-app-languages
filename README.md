# Kiejtés App - Language Files

Ez a repository tartalmazza a Kiejtés alkalmazás összes nyelvfájlját.

## Támogatott nyelvek

- Francia (francia_szavak.json)
- Német (nemet_szavak.json)
- Spanyol (spanyol_szavak.json)
- Olasz (olasz_words.json)
- Portugál (portugál_words.json)
- Orosz (orosz_words.json)
- Kínai (kínai_words.json)
- Japán (japán_words.json)
- Koreai (koreai_words.json)
- Arab (arab_words.json)
- Hindi (hindi_words.json)
- Török (török_words.json)
- Lengyel (lengyel_words.json)
- Holland (holland_words.json)
- Svéd (svéd_words.json)
- Cseh (cseh_words.json)
- Horvát (horvát_words.json)
- Szlovák (slovak_szavak.json)
- Szlovén (slovenian_szavak.json)

## Fájlformátum

Minden fájl tartalmazza:
- `language`: A nyelv kódja
- `display_name`: A nyelv megjelenítendő neve
- `words`: Szógyűjtemény tömb
- `version`: Verzió szám
- `created_at`: Létrehozás dátuma

### Szó struktúra

```json
{
  "word": "Bonjour",
  "phonetic": "/bonˈʒuʁ/",
  "example_sentence": "Bonjour, comment allez-vous?",
  "category": "Alapszókincs",
  "difficulty": "beginner",
  "hungarian_translation": "Helló"
}
```

## Használat

Ezeket a fájlokat a Kiejtés Flutter alkalmazás dinamikusan tölti le GitHub Raw URL-ekről.

Raw URL formátum:
```
https://raw.githubusercontent.com/[USERNAME]/[REPO]/main/[FILENAME]
```

## Verzió

v1.0.0
