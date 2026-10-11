# Fixed strings (0.9.1)

Every Spanish string this mod replaces, with the part that changed. 8282 strings in total.

Keys are the vanilla localization keys. "Before" is the text shipped with the game; "After" is the text in this mod.

## Broken strings (8214)

### Misspelled data functions

These made the game print the raw code, or nothing, instead of a name or a word.

| Key | Before | After |
|---|---|---|
| `best_friend_helped_pen_memory` | `GetShortUINamenNoTooltip` | `GetShortUINameNoTooltip` |
| `rival_insulted_dynasty_corresponding` | `GetShortUINamenNoTooltip` | `GetShortUINameNoTooltip` |
| `rival_knocked_hat_corresponding` | `[CHARACTERGetShortUIName]` | `[CHARACTER.GetShortUIName]` |
| `rival_knocked_hat_corresponding` | `'os hicisteis '` | `'os hicisteis'` |
| `EXAMINATION_WOULD_TAKE` | `Select_Cstring( Character.Islocalplayer` | `Select_CString( Character.IsLocalPlayer` |
| `msg_passive_learned_rite_desc` | `[riteEl]` | `[rite\|lE]` |
| `msg_hor_learned_tenet_cranial_trophies_desc` | `[rite\|lEl]` | `[rite\|lE]` |
| `petition_liege_decision_option_wedding` | `[ceremonial_house\|lEl]` | `[ceremonial_house\|lE]` |
| `setting_coronation_laws_no_imperial_uncrowned_desc` | `[tier_title\|lE]` | `[title_tier\|lE]` |
| `house_relation_reason_festival_increase_desc` | `target_char.Female` | `target_char.IsFemale` |
| `form_brunei_kingdom_decision_effects_de_jure_tt_b` | `[berau_duchy.GetName]` | `[berau_county.GetNameNoTier]` |
| `hunt.1015.desc` | `hated_participant` | `murder_target` |
| `festival.019.desc` | `[play_planner.FirstName]` | `[play_planner.GetFirstName]` |
| `learning_theology.3055.desc.victory.hired_actor` | `GetFaith.GetHighGodName]` | `GetFaith.HighGodName]` |
| `pledge_loyalty_to_liege.0601.desc.liege_dead_me` | `pledge_loyalty_to_liege_scopeCustom` | `pledge_loyalty_to_liege_scope.Custom` |
| `pledge_loyalty_to_liege.0601.desc.liege_dead_me` | `pledge_loyalty_to_liege_scopeGetTitledFirstName` | `pledge_loyalty_to_liege_scope.GetTitledFirstName` |
| `pledge_loyalty_to_liege.0601.desc.liege_imprisoned_me` | `pledge_loyalty_to_liege_scopeCustom` | `pledge_loyalty_to_liege_scope.Custom` |
| `pledge_loyalty_to_liege.0601.desc.liege_imprisoned_me` | `pledge_loyalty_to_liege_scopeGetTitledFirstName` | `pledge_loyalty_to_liege_scope.GetTitledFirstName` |
| `pledge_loyalty_to_liege.0601.desc.liege_imprisoned` | `pledge_loyalty_to_liege_scopeCustom` | `pledge_loyalty_to_liege_scope.Custom` |
| `coronation_events.0301.b.tooltip` | `GetsecondNameNoTooltip` | `GetFirstNameNoTooltip` |
| `mandala_realm_contract_0011_desc` | `GetNameNoToooltip` | `GetNameNoTooltip` |
| `emperor_imperial_examination.200.desc` | `.Custon('ES_ElLa')` | `.Custom('ES_ElLa')` |
| `emperor_imperial_examination.300.desc` | `.Custon('ES_ElLa')` | `.Custom('ES_ElLa')` |
| `noble_family_domicile_buildings_converted` | `former_noble.` | `former_noble_family_head.` |
| `tgp_ceremonial_liege_events.0040.desc` | `mí[ROOT.Char.Custom(ES_OA)]` | `mí[inquirer.Custom('ES_OA')]` |
| `SITUATION_DYNASTIC_CYCLE_FROM_UNSTABLE_ERA` | `\|llE]` | `\|lE]` |
| `tgp_movement_events.0040.desc` | `GetTitledFirstNameNoTooltip\|ll]` | `GetTitledFirstNameNoTooltip\|l]` |
| `tribute_mission.1005.t.bunga_mas` | `GetTitledFirstNameNoTooltip\|ll]` | `GetTitledFirstNameNoTooltip\|l]` |
| `max_fabricate_hook_schemes_add` | `GetTypeName\|ll]` | `GetTypeName\|l]` |
| `scheme_potential_suzerain_might_join_war_tt` | `CHARACTER1.IsFemale` | `CHARACTER.IsFemale` |
| `tgp_genpei_character.1010.desc.intro` | `previous_emperor.` | `old_emperor.` |
| `struggle_persia_ending_rekindle_iran_decision_region_control_tt` | `_percent_value')\|l0]` | `_percent_value')\|0]` |
| `subsume_province_recipient_scheming_against_you_tt` | `[recipiente.` | `[recipient.` |
| `uses_doctrine_first` | `[Faith_DOCTRINE.GetName(Faith.Self)\|l]` | `[DoctrineType.GetDescriptiveName( Faith.Self )\|l]` |
| `pam_theocratic_ruler_events.0002.desc` | `GerHerHim` | `GetHerHim` |
| `flawless_mandala_trials_memory` | `una sucesión divina digna para [previous_mandala.Char.Custom('ES_ElLa')] [previous_mandala_ruler.GetTitledFirstName]` | `de forma impecable una sucesión divina digna [previous_mandala_ruler.Custom('ES_DelDela')] [previous_mandala_ruler.GetTitledFirstName\|l]` |
| `DEMAND_OBEDIENCE_INTERACTION_HERD_ACCEPTANCE` | `$VALUE=+0$` | `$VALUE\|=+0$` |
| `DEMAND_OBEDIENCE_INTERACTION_MILITARY_MIGHT_ACCEPTANCE` | `$VALUE=+0$` | `$VALUE\|=+0$` |
| `rf_eastern_opinion` | `Opinión de $rf_eastern_adherent_plural$` | `Opinión $rf_eastern_adherent$` |

Also, in 43 relationship descriptions `GetShortUINameU` was changed to `GetShortUIName|U` (missing `|`), and in 27 war-god rite names the non-existent formatter `english_rita_i_suffix` was changed to `english_rite_i_suffix`:

<details><summary>Affected keys</summary>

`THEY_GET_TITLE`, `ate_well`, `banished_demons`, `banned_brawling`, `burned_puppets`, `competed_in_archery`, `d_fertilitygodname_rite`, `d_fertilitygodname_rite_adherent`, `d_fertilitygodname_rite_adherent_plural`, `d_fertilitygodname_rite_adj`, `d_householdgodname_rite`, `d_householdgodname_rite_adherent`, `d_householdgodname_rite_adherent_plural`, `d_householdgodname_rite_adj`, `d_knowledgegodname_rite`, `d_knowledgegodname_rite_adherent`, `d_knowledgegodname_rite_adherent_plural`, `d_knowledgegodname_rite_adj`, `d_nightgodname_rite`, `d_nightgodname_rite_adherent`, `d_nightgodname_rite_adherent_plural`, `d_nightgodname_rite_adj`, `d_trickstergodname_rite`, `d_trickstergodname_rite_adherent`, `d_trickstergodname_rite_adherent_plural`, `d_trickstergodname_rite_adj`, `d_wargodname_rite_adherent`, `d_wargodname_rite_adherent_plural`, `d_wargodname_rite_adj`, `d_wealthgodname_rite`, `d_wealthgodname_rite_adherent`, `d_wealthgodname_rite_adherent_plural`, `d_wealthgodname_rite_adj`, `delegated_ritual`, `demanded_compensation_for_mishap`, `edified_a_child`, `ejected_priestess`, `forgave_mishap`, `fought_for_fortune`, `friend_bonded_over_baijiu`, `friend_historical`, `friend_invited_priestess_corresponding`, `friend_same_movement_reason`, `gained_lucky_fan_fragment`, `is_any_movement_leader_tt_global`, `is_any_movement_leader_tt_global_not`, `keen_eye_for_business`, `listened_to_chaplain`, `lover_shared_baijiu`, `lover_shared_baijiu_corresponding`, `made_offering`, `make_movement_leader_effect_desc_first`, `make_movement_leader_effect_desc_global`, `make_movement_leader_effect_desc_third`, `observed_crowd`, `observed_dance`, `paraded_troops`, `planned_play`, `rewarded_brawlers`, `rival_despised_mutual_coronation`, `rival_despised_mutual_coronation_corresponding`, `rival_foreign_threat`, `rival_foreign_threat_corresponding`, `served_with_humility`, `spied_on_wishes`, `studied_martial_motions`, `talked_down_chaplain`, `village_draft`, `wished_for_prosperity`, `wished_for_vigor`

</details>

### Characters that do not exist in the event

| Key | Before | After |
|---|---|---|
| `msg_passive_learned_tenet_abroad_desc` | `passive_learn_hor.GetRite.GetName\|El]` | `passive_learn_source.GetRite.GetName\|l]` |
| `msg_passive_learned_doctrine_abroad_desc` | `passive_learn_hor.GetRite.GetName\|El]` | `passive_learn_source.GetRite.GetName\|l]` |
| `IS_A_CHILD_REASON` | secondary_recipient | recipient |
| `TAKE_THE_VOWS_AMBITIOUS` | owner.Self | recipient.Self |
| `COUNCILLOR_IS_YOUR_FRIEND` | `es amig[recipient.Custom('ES_OA')] tuy[recipient.Custom('ES_OA')]:` | `es amig[councillor.Custom('ES_OA')] tuy[councillor.Custom('ES_OA')]` |
| `fp3_sunder_the_caliphate_same_faith_vassal_hook_tt` | recipient.IsLocalPlayer | sunderer.IsLocalPlayer |
| `ach_coronation.0013.desc_conversation.nice.5` | `[claim.Custom('ES_ElLa')]` | `[claimant.Custom('ES_ElLa')]` |
| `pam_secular_faith_events.0024.a` | rival.IsFemale | rival_character.IsFemale |
| `pam_secular_faith_events.0024.a` | `[rival.Custom('ES_OA')]!` | `[rival_character.Custom('ES_OA')]»!` |
| `journey_events.30.desc` | And(character.IsFemale | And(character_1.IsFemale |
| `greeting_foreign_ruler_negative` | `[target.Custom('ES_AlAla')\|U]` | `[second.Custom('ES_AlAla')\|U]` |
| `feast.7110.desc.entourage` | dummy_gender.IsFemale | my_knight.IsFemale |
| `action_hegemonic_tributary_has_low_subject_standing_suzerain_desc` | `[house_relation.GetName] [recipient.GetPrimaryTitle.Custom('GetTierIcon')]` | `[recipient.GetPrimaryTitle.Custom('GetTierIcon')][recipient.GetUIName]` |
| `scheme_odds.realm_size` | target_character. | target. |
| `scheme_odds.target_suzerain_has_greater_radiance` | target_character. | target. |
| `SCHEME_TARGET_REALM_SIZE` | target_character. | target. |
| `SUZERAIN_HAS_GREATER_RADIANCE` | target_character. | target. |
| `best_friend_died_desc` | deceased_pal. | dead_relation. |
| `best_friend_died_desc_second_perspective` | deceased_pal. | dead_relation. |
| `best_friend_died_desc_third_perspective` | deceased_pal. | dead_relation. |
| `greeting_family_liked_plain` | `[crush.Custom('ES_OA')]` | `[second.Custom('ES_OA')]` |
| `expected_to_pay_tribute` | Select_CString(tributary_loc.IsLocalPlayer | Select_CString(SCOPE.sC('tributary_loc').IsLocalPlayer |
| `SUCCESSION_ELECTION_WINDOW_NOMINATE` | `[nominate]` | `Nominar` |
| `marriage_effect.1001.a` | `mí[secondary_actor.Custom('ES_OA')]` | `mí[SCOPE.sC('spouse').Custom('ES_OA')]` |
| `accolade_find_successor_fail_notification_tooltip` | `un[liegeless_knight.Custom('ES_XA')] $knight` | `un $knight` |
| `prison.1002.rats.desc` | `[exploitable_vassal.Custom('ES_AlAla')]` | `[recipient.Custom('ES_AlAla')]` |
| `feast_events_flavor.0001.desc.bad` | `apreciad[relation.Custom('ES_OA')]` | `apreciad[relation_target.Custom('ES_OA')]` |
| `tgp_travel_events.0035.desc.outro` | farmer. | farmer_char. |
| `tgp_travel_events.0041.f` | `tutor[farmer.Custom('ES_XA')]` | `tutor[farmer_child.Custom('ES_XA')]` |
| `tgp_travel_events.0041.g` | `[farmer.Custom('ES_ElLa')\|U]` | `[farmer_child.Custom('ES_ElLa')\|U]` |
| `tgp_travel_events.0041.g.tt` | `[farmer.Custom('ES_ElLa')\|U]` | `[farmer_child.Custom('ES_ElLa')\|U]` |
| `coronation_spouse_despised_modifier` | host.IsLocalPlayer | owner.IsLocalPlayer |
| `coronation_spouse_despised_modifier` | host.GetShortUIName | owner.GetShortUIName |
| `court.8010.e` | `descarad[suspicious.Custom('ES_OA')]` | `descarad[underequipped.Custom('ES_OA')]` |
| `court_position_management_event.0001.desc.one_candidate` | candidate.Custom | candidate_1.Custom |
| `court_position_management_event.0002.desc.one_candidate` | candidate.Custom | candidate_1.Custom |
| `learning_theology.3054.b` | `Custom2('RelationToMeShort', family)]` | `Custom2('RelationToMeShort', family_actor)]` |
| `court.8197.desc` | `[travel_leader.GetHerHim]` | `[position_holder.GetHerHim]` |
| `court.8197.desc` | facilidad y velocidad. | facilidad y velocidad! |
| `court.8198.desc` | `list[antiquarian.Custom('ES_OA')]` | `list[position_holder.Custom('ES_OA')]` |
| `court.7700.a` | `¡Ladr[eunuch.Custom('ES_OnOna')]! ¡Guardias, capturad a est[eunuch.Custom('ES_EA')] granuja!` | `¡Al ladrón! ¡Guardias, capturad a ese granuja!` |
| `lover.1001.desc` | `[friend_receiving_gift.Custom('GetCourt')\|l]` | `[ROOT.Char.Custom('GetCourt')\|l]` |
| `lover.1002.desc` | `[friend_receiving_gift.Custom('GetCourt')\|l]` | `[ROOT.Char.Custom('GetCourt')\|l]` |
| `petition_liege.0601.desc.liege_imprisoned_me` | `[homage_liege.Custom('ES_AlAla')]` | `[petition_liege.Custom('ES_AlAla')]` |
| `pilgrimage.4002.desc` | `buscador[mystic.Custom('ES_XA')]` | `buscador[2010_mystic.Custom('ES_XA')]` |
| `mystic_lifestyle.1009.opening` | `Estimad[mystic.Custom('ES_OA')]` | `Estimad[SCOPE.sC('mystic').Custom('ES_OA')]` |
| `hunt.1081.c.rival` | `Maldit[inspiration_sponsor.Custom('ES_OA')]` | `Maldit[murderer.Custom('ES_OA')]` |
| `scheme_critical_moments.1215.a_discovered` | `Maldit[inspiration_sponsor.Custom('ES_OA')]` | `Maldit[owner.Custom('ES_OA')]` |
| `mpo_hunt.0050.a` | Select_CString(hunter,IsFemale | Select_CString(hunter.IsFemale |
| `holder_has_military_appointment_tt` | first.GetShortUIName | THIS.Char.GetShortUIName |
| `roman_restoration.0132.desc` | `sin su pastor[pope.Custom('ES_XA')]` | `sin pastor` |
| `hold_court.3010.a` | excellent_skill_option.IsFemale | unconventional_preacher.IsFemale |
| `hold_court.3010.b` | excellent_skill_option.IsFemale | unconventional_preacher.IsFemale |
| `ep3_contract_event.0095.a_2` | `[Select_CString(And(supporter.IsFemale, supporter_2.IsFemale), 'las', 'los')]` | `los` |
| `tournament_events.9004.desc` | `un[falconer.Custom('ES_XA')]` | `un[falconer_1.Custom('ES_XA')]` |
| `bp2_yearly.2015.desc` | `[Select_CString( hostage.IsFemale, 'la abusona', 'el abusón' )] de [bully.GetFirstName]` | `[Select_CString( bully.IsFemale, 'la abusona', 'el abusón' )] de [bully.GetFirstName]` |
| `bp2_yearly.2022.desc.next_target` | `list[new_target.Custom('ES_OA')]` | `list[new_murder_target.Custom('ES_OA')]` |
| `imperial_examination.4060.desc_learning` | potential_rival. | promising_lowborn. |
| `imperial_examination.4060.a.success` | potential_rival. | promising_lowborn. |
| `bp1_yearly.5708.start` | `[seduced_rival.GetHerHim]` | `[heathen_friend.GetHerHim]` |
| `tournament_champion_qualify_desc` | `campe[champion.Custom('ES_OnOna')]` | `campe[contest_champion.Custom('ES_OnOna')]` |
| `tournament_champion_qualify_multi_desc` | `campe[champion.Custom('ES_OnOna')]` | `campe[contest_champion.Custom('ES_OnOna')]` |
| `tournament_champion_qualify_fail_desc` | `campe[champion.Custom('ES_OnOna')]` | `campe[contest_champion.Custom('ES_OnOna')]` |
| `ep2_wedding.9015.tt` | `[Character.LocalPlayerString(` | `[ROOT.Char.LocalPlayerString(` |
| `ep3_governor_yearly.3001.b` | `un[defector.Custom('ES_XA')]` | `un[governor.Custom('ES_XA')]` |
| `pam_interactions_events.0097.a` | `[target_title.GetNameNoTierNoTooltip]` | `[target.GetNameNoTierNoTooltip]` |
| `appoint_co_emperor_interaction.tt.enter_co_emperorship_with_secondary_recipient` | secret_owner.IsFemale | secondary_recipient.IsFemale |
| `building_vatapi_caves_01_destination_desc` | GetBuildingType('vatapi_caves_01') | GetBuilding('vatapi_caves_01') |
| `bp2_yearly.5053.b.success` | `[angry.GetHerHim\|U] convences` | `Te creen` |
| `bp2_yearly.5053.b.failure` | `No [angry.GetHerHim] convences` | `No te creen` |
| `pam_theocratic_ruler_events.0002.b.success` | `Mi cortesía se [foreign_ruler.GerHerHim] gana` | `Mi cortesía se los gana` |

### Broken gender agreement codes

| Key | Before | After |
|---|---|---|
| `tgp_travel_events.0040.desc.outro` | Custom('AlAla') | Custom('ES_AlAla') |
| `raiding.0004.desc.spared_plundered` | Custom('ES_DelDel') | Custom('ES_DelDela') |
| `tgp_dynastic_cycle.0061.t` | Custom('ElLa') | Custom('ES_ElLa') |
| `tgp_dynastic_cycle.0062.desc.interloper` | `.Custom('WomanMan')]` | `.GetWomanMan]` |
| `filial_piety_request_child_gold_notification` | Custom('OA') | Custom('ES_OA') |
| `emperor_imperial_examination.600.desc` | `un[examination_character_2.Custom('ES_OA')] de [examination_character_2.GetHerHim]s examinandos, [examination_character_2.Custom('ES_Ella')]` | `un[examination_character_2.Custom('ES_OA')] de los examinandos, [examination_character_2.Custom('ES_ElLa')]` |
| `emperor_imperial_examination.600.desc` | `delante de [examination_character_2.GetSheHe]` | `delante de [examination_character_2.Custom('ES_ElElla')]` |
| `ep2_locale_events.3002.desc` | `[lech1.Custom('ES_SheHe')]` | `[lech1.Custom('ES_ElElla')]` |
| `ep2_locale_events.3002.desc` | in fragranti | in fraganti |
| `msg_clerical_region_independence_title` | Custom('ES_ElLA') | Custom('ES_ElLa') |
| `divorced_recipient_desc` | Custom('ES_ElLA') | Custom('ES_ElLa') |
| `divorced_recipient_desc_second_perspective` | Custom('ES_ElLA') | Custom('ES_ElLa') |
| `divorced_recipient_desc_third_perspective` | Custom('ES_ElLA') | Custom('ES_ElLa') |
| `pam_great_projects_events.0003.desc` | Custom('ES_ElLA') | Custom('ES_ElLa') |
| `imperial_examination.4070.a.failure` | `[parent.Custom('GetMotherFather')]` | `[parent.GetMotherFather]` |
| `pam_clergy_events.0010.desc.intro` | `[actor.Custom('GetMotherFather')]` | `[actor.GetMotherFather]` |
| `pam_clergy_events.0060.desc.hof_outro` | `[new_prelate.Custom('GetMotherFather')]` | `[new_prelate.GetMotherFather]` |
| `pledge_defender` | `[great_holy_war.GetFaith.Custom('GHWName')\|l]` | `[great_holy_war.GetFaith.GHWName\|l]` |
| `ach_yearly_events.1003.desc` | `[liege.Custom('FighterTermPlural')]` | `[liege.Custom('GetFighterTermPlural')]` |
| `ach_yearly_events.1003.desc` | a tomar las riendas de este desastre y a convertirlo en un guantelete para golpear. | a tomar con mano de hierro las riendas de este desastre. |

### Format codes, line breaks and leftover English

| Key | Before | After |
|---|---|---|
| `tour_travel.3002.desc` | `todos murieron en vuestra #EMPyour guerra#!` | `todos murieron en #EMP vuestra guerra#!` |
| `travel_events.2010.desc` | De repente, un chillido | \n\nDe repente, un chillido |
| `hunt.9001.spoils` | Dejamos la parte | \n\nDejamos la parte |
| `celestial_government_desc` | `$game_concept_celestial_government_desc$` | `\n$game_concept_celestial_government_desc$` |
| `PIETY_WITH_BALANCE_TOOLTIP` | `/mes\n#T` | `/mes\n\n#T` |
| `UNLOCK_DYNASTY_PERK_TOOLTIP` | `]\n#I Haz` | `]\n\n#I Haz` |
| `game_concept_extended_family_desc` | `Los parientes de un personaje son:\n$BULLET_WITH_TAB$Primos\n$BULLET_WITH_TAB$Tíos\n$BULLET_WITH_TAB$Sobrinos` | `La familia extensa de un personaje incluye:\n$BULLET_WITH_TAB$Primos y primas\n$BULLET_WITH_TAB$Tíos\n$BULLET_WITH_TAB$Tías\n$BULLET_WITH_TAB$Sobrinos\n$BULLET_WITH_TAB$Sobrinas` |
| `refound_pandidakterion_decision_desc` | `fundó el the [Glossary` | `fundó el [Glossary` |
| `refound_pandidakterion_decision_desc` | Muchos siglos han pasado desde entonces. | Muchos siglos han pasado desde entonces y los tiempos han cambiado. |
| `court.8170.desc.intro_religious` | `«[criminal.GetFirstName] the [criminal.Custom('GetCrime')\|U]»` | `[criminal.GetFirstName]` |
| `guest_description.duchy_claim.desc` | `sobre un un [duchy` | `sobre un [duchy` |
| `ep3_camp_party.2000.compassionate` | `#EMP es#! es la recompensa` | `#EMP es#! la recompensa` |
| `MyCharacterIntroductionNoComma` | `mi [ROOT.Char.Custom2('MyCharacterIntroductionNoComma', SCOPE.sC('second'))]` | `[ROOT.Char.Custom2('MyCharacterIntroductionNoComma', SCOPE.sC('second'))]` |

### Wrong keys and arguments

| Key | Before | After |
|---|---|---|
| `commission_artifact_decision_option_crown` | GetNumberOfArtifactsForSlotTypeString( 'casco' ) | GetNumberOfArtifactsForSlotTypeString( 'helmet' ) |
| `recruit_bookmaker_cooldown_tt` | 'recruit_bookmaker_liege_cooldown' | 'recruit_bookmaker_cooldown' |
| `recruit_court_gardener_cooldown_tt` | 'recruit_gardener_cooldown' | 'recruit_court_gardener_cooldown' |
| `recruit_foreign_emissary_cooldown_tt` | VarRemaining( 'recruit_foreign_emissary_cooldown' ) | VarRemaining( 'foreign_emissary_engineer_cooldown' ) |
| `culture_parameter_block_printing_university_bonuses` | HasDlcFeature( 'legends' ) | HasDlcFeature( 'wards_and_wardens' ) |
| `ECUMENICAL_COUNCIL_PLANNER_TENET_SELECT_TOOLTIP` | GetNameNoTooltip( Faith.Self ) | GetNameNoTooltip( Rite.Self ) |
| `learning_oath_1_decision_desc_extra` | 'stewardship_oath_1_timer' | 'learning_oath_1_timer' |
| `purge_pretenders_oath_decision_desc_extra` | IsOngoingCoronationOath('purge_pretenders') | IsOngoingCoronationOath('purge_pretenders_oath') |
| `devaraja_recipient_piety_level` | actor.GetPietyLevel | recipient.GetPietyLevel |
| `celestial_movement_power_promote_interaction.tt.agent_focus_balance` | 'agent_political_gabbler' | 'agent_gabbler' |
| `celestial_movement_power_slander_interaction.tt.agent_focus_balance` | 'agent_political_gabbler' | 'agent_gabbler' |
| `start_coerce_contribution_interaction.tt.agent_focus_success` | 'agent_cleiric' | 'agent_cleric' |
| `start_leverage_contribution_interaction.tt.agent_focus_success` | 'agent_cleiric' | 'agent_cleric' |
| `c_jingzhao_tooltip` | 'tgp_silk_road_occident_region' | 'tgp_silk_road_china_region' |
| `c_khiva_tooltip` | 'region_silk_road_proper_central_transcaspia' | 'region_silk_road_proper_transcaspia' |
| `celestial_movement_demands_interaction.hold_examinations_cooldown` | 'movement_recently_requested_examination' | 'movement_recently_requested_examinations' |
| `SCHEME_TARGET_LAZY` | GetName( owner ) | GetName( target ) |
| `SCHEME_TARGET_DILIGENT` | GetName( owner ) | GetName( target ) |
| `mpo_decisions_events.0100.d.unlocked` | 'trade_yurt_01' | 'herd_trade_yurt_01' |
| `custom_southern_russia_expand_steppe_tt` | 'ghw_region_southern_russsia' | 'ghw_region_southern_russia' |
| `fund_inspiration.1051.desc.hide` | 'animal_skull_type' | 'animal_hide_type' |
| `add_known_tenet_third` | GetPlayer.GetFaith | Character.GetRite |
| `religious_decision.0211_anachoresis_tt` | GetPlayer.GetFaith | GetPlayer.GetRite |
| `pam_anachoresis_meditation_toast` | GetPlayer.GetFaith | GetPlayer.GetRite |
| `pam_evangelize_tenet_carnal_exaltation` | 'tenet_khachkar' | 'tenet_carnal_exaltation' |
| `pam_decision_events.0011.desc.permitted` | pam_tenet_stance_issuer.GetFaith | pam_tenet_stance_issuer.GetRite |
| `pam_decision_events.0011.desc.prohibited` | pam_tenet_stance_issuer.GetFaith | pam_tenet_stance_issuer.GetRite |
| `pam_decision_events.0011.desc.fallback` | pam_tenet_stance_issuer.GetFaith | pam_tenet_stance_issuer.GetRite |
| `fervor_gain_pam_tenet_prohibited` | pam_tenet_stance_issuer.GetFaith | pam_tenet_stance_issuer.GetRite |
| `fervor_loss_pam_tenet_permitted` | pam_tenet_stance_issuer.GetFaith | pam_tenet_stance_issuer.GetRite |
| `puppet_action_description_puppet_action_demand_conversion_player_ruler` | 'demand_conversion_vassal_ruler_interaction' | 'demand_conversion_player_ruler_interaction' |
| `feature_brooch_adornment_runes` | 'decoration_material_gem' | 'decoration_material_wire' |
| `brooch_adornment_gems` | GetFlagName('crown_gem') | GetFlagName('adornment_gem') |
| `artifact_necklace_description` | GetFeatureText( 'crown_decoration' ) | GetFeatureText( 'decoration_material_gem' ) |
| `rite_growth.0010.desc.differing.doctrine` | `[differing_doctrine.GetDescriptiveName\|l]` | `[differing_doctrine.GetDescriptiveName( new_rite.GetFaith.Self )\|l]` |

### Concept links on plain names

The `E` format flag turns a word into a link to a game concept (the underlined terms with a tooltip). In 96 Spanish strings it was applied to plain names (rites, weapons, accolades, blocs…), which are not concepts, so the name was shown as a broken, faded link. No official translation does this. The `E` was removed and the rest of the formatting kept (for example `[diverged_rite.GetName|El]` → `[diverged_rite.GetName|l]`). Strings that also needed other fixes are listed in their own sections too.

<details><summary>Affected keys</summary>

`CHARACTER_RITE_EQUAL_FIRST`, `CHARACTER_RITE_EQUAL_THIRD`, `FAITH_VIEW_FOLLOWING`, `LANDED_TITLE_RITE_EQUAL_GLOBAL`, `LANDED_TITLE_RITE_EQUAL_THIRD`, `NOT_CHARACTER_RITE_EQUAL_FIRST`, `NOT_CHARACTER_RITE_EQUAL_THIRD`, `NOT_LANDED_TITLE_RITE_EQUAL_GLOBAL`, `NOT_LANDED_TITLE_RITE_EQUAL_THIRD`, `NOT_PROVINCE_RITE_EQUAL_GLOBAL`, `NOT_PROVINCE_RITE_EQUAL_THIRD`, `NOT_RITE_THEY_HAS_DOCTRINE`, `PERSONAL_BELIEFS_VIEW_FOLLOWING`, `PROVINCE_RITE_EQUAL_GLOBAL`, `PROVINCE_RITE_EQUAL_THIRD`, `THEY_GAINED_GLORY_EFFECT`, `THEY_GAIN_GLORY_EFFECT`, `THEY_LOSE_GLORY_EFFECT`, `THEY_LOST_GLORY_EFFECT`, `THEY_RITE_HAS_DOCTRINE`, `ZEALOUS_PROSELYTIZER_REASON`, `activity_tour_host_desc`, `all_members_of_root_confederation_in_attendance`, `all_members_of_second_confederation_in_attendance`, `apa_passive_religious_learning_guest_tt`, `apa_passive_religious_learning_host_tt`, `apa_passive_religious_learning_pilgrimage_pool_tt`, `change_maa_regiment_size_third`, `change_maa_regiment_size_third_neg`, `change_maa_regiment_size_third_past`, `change_maa_regiment_size_third_past_neg`, `change_maa_troops_count_third`, `change_maa_troops_count_third_neg`, `domicile_building_parameter_domicile_building_is_university`, `estate_cathedral_teach_kids_tt`, `eunuch_will_be_given_a_position_tt`, `fervor_gain_pam_rite_consolidated`, `fervor_loss_pam_rite_diverged`, `landed_title_rite_not_equal`, `msg_holy_site_abandoned_by_character_desc`, `msg_holy_site_demoted_by_character_desc`, `msg_hor_learned_doctrine_concubines_desc`, `msg_hor_learned_doctrine_consanguinity_unrestricted_desc`, `msg_hor_learned_doctrine_desc`, `msg_hor_learned_doctrine_deviancy_virtuous_desc`, `msg_hor_learned_doctrine_funeral_mummification_desc`, `msg_hor_learned_doctrine_funeral_sky_burial_desc`, `msg_hor_learned_doctrine_kinslaying_accepted_desc`, `msg_hor_learned_doctrine_polygamy_desc`, `msg_hor_learned_doctrine_witchcraft_virtuous_desc`, `msg_hor_learned_tenet_adorcism_desc`, `msg_hor_learned_tenet_cranial_trophies_desc`, `msg_hor_learned_tenet_desc`, `msg_hor_learned_tenet_exaltation_of_pain_desc`, `msg_hor_learned_tenet_gruesome_festivals_desc`, `msg_hor_learned_tenet_hedonistic_desc`, `msg_hor_learned_tenet_human_sacrifice_desc`, `msg_hor_learned_tenet_ritual_cannibalism_desc`, `msg_hor_learned_tenet_sacrificial_ceremonies_desc`, `msg_hor_learned_tenet_takamin_desc`, `msg_hor_learned_tenet_warmonger_desc`, `msg_passive_learned_doctrine_concubines_desc`, `msg_passive_learned_doctrine_consanguinity_unrestricted_desc`, `msg_passive_learned_doctrine_desc`, `msg_passive_learned_doctrine_funeral_mummification_desc`, `msg_passive_learned_doctrine_funeral_sky_burial_desc`, `msg_passive_learned_doctrine_kinslaying_accepted_desc`, `msg_passive_learned_doctrine_pilgrimage_rite_desc`, `msg_passive_learned_doctrine_polygamy_desc`, `msg_passive_learned_doctrine_witchcraft_virtuous_desc`, `msg_passive_learned_rite_abroad_desc`, `msg_passive_learned_rite_desc`, `msg_passive_learned_tenet_adorcism_desc`, `msg_passive_learned_tenet_cranial_trophies_desc`, `msg_passive_learned_tenet_desc`, `msg_passive_learned_tenet_exaltation_of_pain_desc`, `msg_passive_learned_tenet_gruesome_festivals_desc`, `msg_passive_learned_tenet_hedonistic_desc`, `msg_passive_learned_tenet_human_sacrifice_desc`, `msg_passive_learned_tenet_pilgrimage_rite_desc`, `msg_passive_learned_tenet_ritual_cannibalism_desc`, `msg_passive_learned_tenet_sacrificial_ceremonies_desc`, `msg_passive_learned_tenet_takamin_desc`, `msg_passive_learned_tenet_warmonger_desc`, `not_rite_has_tenet_first`, `not_rite_has_tenet_third`, `pam_create_great_schism_effect_tt`, `pam_tenet_events.0004.a.tt.consolidated`, `pam_tenet_events.0004.a.tt.diverged`, `pam_tenet_events.0004.desc.backward_doctrine`, `pam_tenet_events.0004.desc.backward_tenet`, `pam_tenet_events.0004.desc.forward_doctrine`, `pam_tenet_events.0004.desc.forward_tenet`, `rite_has_tenet_first`, `rite_has_tenet_third`, `study_faith_nothing_left_to_learn_tt`

</details>

### Names of untitled characters in lowercase

The Spanish text writes a character's title and name in lowercase, so that the title reads naturally mid-sentence: `[ROOT.Char.Custom('ES_ElLa')] [ROOT.Char.GetTitledFirstName|l]` gives "la condesa Bertha". When the character has no title, the name itself was lowercased and the article kept: "la bertha", "de la bertha". This affected **7948 strings**, too many to list here.

The mod adds 27 custom localization entries (`common/customizable_localization/stf_titled_name_custom_loc.txt`) that lowercase the title only when the character has one, and drop the article otherwise:

| Before | Titled character | Untitled character (before → now) |
|---|---|---|
| `[X.Custom('ES_ElLa')] [X.GetTitledFirstName\|l]` | la condesa Bertha | la bertha → Bertha |
| `[X.Custom('ES_DelDela')] [X.GetTitledFirstName\|l]` | de la condesa Bertha | de la bertha → de Bertha |
| `[X.Custom('ES_AlAla')] [X.GetTitledFirstName\|l]` | a la condesa Bertha | a la bertha → a Bertha |
| `[X.GetTitledFirstName\|l]` | condesa Bertha | bertha → Bertha |

A character counts as titled when they hold a primary title or are married to someone who holds one, the same rule the vanilla Spanish `ES_only_el_GetTitledFirstName` uses. The same applies to the `NoTooltip`, `Regnal` and `Nicknamed` variants.

## Spelling and grammar (68)

### Typos

| Key | Before | After |
|---|---|---|
| `pam_the_christian_church.0057.desc.eastern` | bien recibida, peros sus | bien recibida, pero sus |
| `tribute_mission.1002.personality.cynical` | al tiemp que | al tiempo que |
| `tgp_east_asia_decision_events.0020.desc` |  haciaa un futuro |  hacia un futuro |
| `fp2_yearly.1006.desc` | carretera donden venden | carretera donde venden |
| `single_combat.0041.desc.sc_attacker.expert_onslaught.injury` | lo basatnte fuerte | lo bastante fuerte |
| `SITUATION_LIST_SITUATION_PHASE` | acutal: | actual: |
| `scheme_apa_positive_0181_modifier_desc` | Hay que ncontrar | Hay que encontrar |
| `ep3_laamps.6016.ending` | Su rosto empalidece | Su rostro empalidece |
| `fp3_decision.0009.desc` | mi posicion importará | mi posición importará |
| `ep3_laamp_flavour_ewan.0011.desc.chaste` | una desagracia | una desgracia |
| `fp1_yearly.2400.desc` | `de caracter [` | `de carácter [` |
| `spouse.2011.desc` | intentaa arregarlo | intentaba arreglarlo |
| `fp2_yearly.8004.c` | un verdaderp fastidio | un verdadero fastidio |
| `event_window_widget_harrying_tooltip_widget` | probabildad | probabilidad |
| `ep3_laamp_decision_event.1040.desc_outro_return_01` | intenta convnecer | intenta convencer |
| `contest_events.1540.desc` | mi postura y encoque | mi postura y enfoque |
| `contest_events.1541.desc` | su postura y encoque | su postura y enfoque |
| `yearly.3001.b` | acusaré publicamente | acusaré públicamente |
| `pam_generic_events.0004.desc` | El reciento de | El recinto de |
| `ep3_laamps.6021.desc` | Sin embaro, | Sin embargo, |
| `laamp_base_contract_schemes.0661.desc` | en su diputa sobre | en su disputa sobre |
| `travel_events.4023.desc.intro` | las armas contras los | las armas contra los |
| `game_rule.1101.desc.outro.present` | `al ejercito [` | `al ejército [` |
| `gracious_host_impeccable_guest_perk_3_effect` | por el numero de | por el número de |
| `commission_epic.2002.desc` | la ultima persona | la última persona |
| `pilgrimage.3301.c` | contra el ritá que | contra el rito que |
| `pam_mended_great_schism_military_dynasty_modifier_desc` | ha sando la ruptura | ha sanado la ruptura |
| `artifact_joyeuse_description` | del impero carolingio | del imperio carolingio |
| `yearly.7053.b_pouch.desc` | una bosa de monedas | una bolsa de monedas |
| `az_tour.1006.desc.b` | banquetes y edas! | sedas y banquetes! |
| `intrigue_temptation.3010.start.desc` | me encuentro en la misma noche, en la misma posada | me encuentro en la misma mesa, en la misma posada |
| `intrigue_temptation.3010.start.desc` | `y del/ dela cautivador[bar_servant.Custom('ES_XA')]` | `y [bar_servant.Custom('ES_DelDela')] cautivador[bar_servant.Custom('ES_XA')]` |
| `intrigue_temptation.3010.start.desc` | Llevas toda a noche | Llevas toda la noche |
| `single_combat.0031.desc.sc_attacker.feint_and_stab.fatality` | un susurro rondo. | un susurro ronco. |

### Missing accents

| Key | Before | After |
|---|---|---|
| `rationality_explanation` | es mas probable | es más probable |
| `board_games.0001.desc.opponent_winning.trait.content` | partida mas encantadora | partida más encantadora |
| `game_concept_co_monarchy_desc` | acceso mas fácil | acceso más fácil |
| `laamp_base_contract_schemes.6002.desc` | trabajo mas magnífico | trabajo más magnífico |
| `laamp_base_contract_schemes.2311.desc.business.council_chamber` | personas mas importantes | personas más importantes |
| `single_combat.0041.desc.opponent_response.strict_guard` | Es mas por suerte | Es más por suerte |
| `building_hagios_demetrios_desc` | santuario mas importante | santuario más importante |
| `building_murex_farm_04_desc` | trabajo mas eficiente | trabajo más eficiente |
| `bwow_fundementalist_tooltip` | volverá mas fundamentalista | volverá más fundamentalista |
| `diarchy.2241.b.tt.success` | haces mas raudos | haces más raudos |
| `travel_danger_events.1013.c` | se pierda mas gente | se pierda más gente |
| `intrigue_scheme_ongoing.5006.a` | efecto mas curioso | efecto más curioso |
| `pilgrimage.5401.desc` | saber mas de | saber más de |
| `intrigue_scheming.1801.b` | nada mas que | nada más que |
| `yearly.7052.desc_unconvinced` | las mas horribles | las más horribles |
| `bp1_yearly.3004.desc` | Un año mas, | Un año más, |
| `coronation_events.1000.tyrant.desc` | nada mas que | nada más que |
| `ep2_locale_events.2510.b` | nada mas útil | nada más útil |
| `depose_desc_general` | candidato mas adecuado | candidato más adecuado |
| `fp2_yearly.1008.desc` | queso mas increíble | queso más increíble |
| `laamp_base_learning_contract_events.4001.d.flavor.unwind` | hacer mas cuando | hacer más cuando |
| `ep3_contract_event.0093.desc_taxes` | exige mas aún | exige más aún |
| `introduce_a_new_fashion_at_court_decision_desc` | afirmar se mas elegante | afirmar ser más elegante |
| `religious_decision.0002.desc_alone` | cada más mas deprisa | cada vez más deprisa |
| `tribal.1204.desc_fast` | El publico ruge | El público ruge |
| `tgp_governor_contract_event.0029.a` | el orden publico | el orden público |
| `prelude_events.0170.a.success` | El publico queda | El público queda |
| `ep3_sent_help_to_east_modifier` | Enviado ejercito a ayudar | Ejército enviado en ayuda |

### Grammar

| Key | Before | After |
|---|---|---|
| `BattlePoIHistoricalDescHastings` | al trono del Inglaterra | al trono de Inglaterra |
| `BattlePoIHistoricalDescHastings` | le constaba | le costaba |
| `BattlePoIHistoricalDescLechfeld` | unas perdidas abrumadoras | unas pérdidas abrumadoras |
| `BattlePoIHistoricalDescFeiRiver` | el estado antiguo estado Qin | el antiguo estado Qin |
| `game_concept_aptitude_desc` | lo eficiente que es distintos papeles | lo eficiente que es en distintos papeles |
| `hunt.4900.befriend` | `El [activity.Custom('GetAnimalChargeParticipleKill')] del animal se relaja` | `El animal se relaja` |
| `ep1_flavor.2040.desc.gold` | `«Este/a [exotic_blade.Custom('ArtifactBaseWeaponType')\|l] sin par` | `«Esta pieza sin par` |
| `FACTION_ESCALATED_PEASANT_DYNAMIC_NAME` | `de color [ROOT.Faction.GetSpecialCharacter.Custom('GetTurbanRebellionColor')]` | `de [ROOT.Faction.GetSpecialCharacter.Custom('GetTurbanRebellionColor')\|l]` |
| `peasant_leader_title_name` | `de color [ROOT.Char.Custom('GetTurbanRebellionColor')]` | `de [ROOT.Char.Custom('GetTurbanRebellionColor')\|l]` |

