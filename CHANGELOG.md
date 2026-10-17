# Changelog

## 0.9.4 (beta)

- Checked against CK3 1.20.1.1. This hotfix rewrote much of the Spanish translation of By God Alone.
- 33 strings that Paradox rewrote in 1.20.1.1 are now based on the new text, so the mod no longer brings back the old translation: the heresy news events, ecumenical council and investiture council events, holy myron, the naturism decision, scripture study outcomes, petitions to the head of faith, a feast event and the antipope decision, among others. The fix for untitled characters' names is kept in all of them.
- Removed the three `heresy_light.notification.*.tt` strings, which no longer exist in the game.
- 3 new strings with the untitled-names bug are now fixed: `character_will_leave_court_holy_order`, `pam_theocratic_ruler_events.0006.desc` and `pam_schism_seat_head_of_faith_tt`.
- Fixed new mistakes in the rewritten texts: a missing opening question mark, "divida" instead of "dividida", "recibirles" for a single visitor, and "el/la … vacío/a" in a mourning event.
- The mod still replaces 8,273 strings in total.

## 0.9.3 (beta)

- Checked against CK3 1.20.1.
- Paradox fixed 9 of the strings this mod corrected, in the same way; the mod no longer replaces them: `add_known_tenet_third`, `bp2_yearly.2015.desc`, `ECUMENICAL_COUNCIL_PLANNER_TENET_SELECT_TOOLTIP`, `greeting_family_liked_plain`, `pam_anachoresis_meditation_toast`, the three `pam_decision_events.0011.desc` texts and `religious_decision.0211_anachoresis_tt`. Paradox also fixed the wrong character in `greeting_foreign_ruler_negative`.
- 5 strings rewritten by Paradox in 1.20.1 are now based on the new text, so the mod no longer brings back the old version: the two populist faction demands (now name the rite's adherents), the excommunication petition tooltip (now also works when someone else travels), the antipope event and the first-stone event for great projects. The fix for untitled characters' names is kept in all of them.
- The mod now replaces 8,273 strings in total.

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
