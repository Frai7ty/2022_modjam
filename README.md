# 2022 Modjam (Need Better Mod Name :D)
Rules to note.

- You are not allowed to impede or change the mechanics of vanilla events. There's nothing saying you can't expand on them, however.
- A single reasonably balanced mid-game crisis, that may not use assets from or reminiscent of any other IP. May use the Stellaris IP, or “borrow” generic ideas.
- Ie: Having a race that lives only on asteroids and space stations is okay, calling them “Belters” (The Expanse), or using a ship asset of the USS Enterprise, would not be acceptable.
- Submission of a design document, outlining what your crisis does, and planned features, story beats, etc. Please include at least 3 features to highlight for social media teases (Deadline: December 23rd)
- See the template Design Document here: http://pdxint.at/35gdRei
- Any localisations required by their additions in English

All files should be signed at the top with the filename and the list of contributors and follow the naming scheme:
-  `Modabbreviation_filename` -- abbreviations should be shorter than the word abbreviation 😀
-  Submitted Crises must be able to be allowed to spawn via a global flag. This flag should be `modabbreviation_allowed`.
-  Submitted crises must set a global flag while in progress, and remove the flag when they’ve been resolved, this flag should be `modabbreviation_in_progress`. 
-  If the submitted crisis is not appropriate to fire more than once, the crisis must set a flag that they’ve fired, this flag should be`Modabbreviation_fired`
-  Crises must also set a generic global flag while they’re in progress, this flag should be `midgame_crisis_ongoing` and remove said flag when they’ve been resolved
-  Submitted crisis must be able to be fired by calling a scripted effect, this scripted effect should be named:
-  `Begin_crisis_modabbreviation` - this effect will be fired in country scope on the global event country
-  Mod authors will host their individual mods on the workshop and be responsible for upkeep and maintenance until the end of the Mod Jam (continued support is at the individual modder’s discretion)
-  Modders may use the C6 or Khorgis Khan portraits, with appropriate credit.
-  Modders may use content from publicly posted tutorials or “free to use” content, with appropriate credit. For example, anything posted in the #shared-art and #shared-resources channels on the Stellaris Modding Den.
-  Must include the provided spawning script, and replace `yourmod` in all places, including filenames

Optional:
-  Announce that you are participating after the mod jam begins on social media
-  Reasonable overwrites will be supported upon request (Deadline for overwrites: December 23rd). Modders may be asked to supply scripts for their overwrites.
-  Reasonable: overwriting the can_bombard_planet game_rule
-  Unreasonable: overwriting a large number of buildings, ship_sizes, planet_classes, technologies, etc. 

Not Permitted:
-  contain NSFW, Sexually Suggestive or inappropriate content. 
-  contain racial slurs, attacks upon ethnicity, religion, race, nationality, gender, sexual orientation, or other personal and/or non-controllable identifying subjects.
-  reference real-world places, events, or peoples
-  Unlock features that would be otherwise gated behind a DLC (can require a DLC however)
-  Impede the operation of vanilla game-mechanics, events, etc.
-  Block or impede the operation of another crisis via script.
-  Overwrites of vanilla files/keys/etc that are not listed above in Optional
-  May not use anything created before the mod jam starts (with the exception of those listed above)
-  May not alter gameplay while the crisis is not active (eg. may not change a define, or add visible content when it is not active, anything added by the crisis can remain after it becomes inactive)
-  May not add more than 10 lines of non-avoidable errors to the error log
-  May not run pulse events when not active (must fail at the trigger)
-  May not list another mod as a requirement to work
