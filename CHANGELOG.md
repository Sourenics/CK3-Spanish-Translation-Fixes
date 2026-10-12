# Changelog

## 0.9.2 (beta)

- New thumbnail, matching the style of the author's other mods.

## 0.9.1 (beta)

- **Names of untitled characters are no longer lowercase.** The Spanish text lowercased "title + name" so that titles read naturally ("la condesa Bertha"), which also lowercased the names of characters without a title and kept the article ("la bertha"). New custom localization entries lowercase the title only when there is one and drop the article otherwise ("Bertha", "de Bertha"). This affects 7,948 strings.
- Fixed "Mi mi hermana…" in the template that introduces characters in many events.
- The mod now replaces 8,282 strings in total.

## 0.9.0 (beta)

- First public beta, for game version 1.20.x.
- Fixes 399 strings of the official Spanish localization. The full list, with the part that changed, is in [FIXED_STRINGS.md](FIXED_STRINGS.md).
- **Broken strings (331):** misspelled data functions (`Custon`, `GerHerHim`, `Select_Cstring`, `GetShortUINameU`…), characters that do not exist in their event, gender agreement codes that do not exist in the game (`ES_ElLA`, `ES_SheHe`…), the mistranslated formatter `english_rita_i_suffix` (27 war-god rite names), broken format codes, missing line breaks, leftover English words, wrong keys and arguments passed to functions (35 strings), and 94 strings where plain names (mostly rites) were formatted as concept links and showed as faded, broken links.
- **Spelling and grammar (68):** typos and missing accents.
