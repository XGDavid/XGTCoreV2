# XGTCoreV2 Updates

***

> alpha 16-06-2023
- logs update(3 types: action, clan, economy)
- jobs database updated
- bugs fix

***

> alpha 05-05-2024
- music
- area system
- bugs fix

***

> alpha 12-05-2024
- miner job
- job update/fix
- bug fix
- bug fix
- bug fix
- bug fix
- bug fix
- bug fix
- bug fix
- bug fix

***

> alpha 23-10-2024
- am adaugat functionalitate la perk ul quest (+1 activity points la orice quest)
- am rezolvat un bug de la perk uri, puteai sa cumper perk de lvl 2 la infinit
- adaugat luni in RandomUtils::time_elapsed
- reparat sa apara Online/offline cand intri sa vezi membri din alt clan(Clan List->Clan)
- reparat in member info sa nu mai apara Last online, ci Online/Offline
- in bypass setclan, am adaugat sa ii seteze si ClanJoin la player
- textul modificat din gri in alb de la butoanele din /c
- am adaugat la war, sa ii bage toate itemele in inbox

***

> alpha 24-10-2024
- bug fixs la Clan War, MUULT rau
- daca in clan depozit ai mai mult silver coins decat maximum, sa nu ti mai seteze la maxim(bug fix)
- setarea itemelor in inbox o sa fie fix cand se termina queue time ul
- am adaugat efect negru in freeze war ca la dungeom
- am adaugat si TIE la war, in caz ca ultimii jucatori mor simultan

***

> alpha 28-10-2024
- am adaugat 12 slot uri la war
- Mobs -> DungeonMobs
- adaugati WarMobs
- sa nu piarda xp ul cand moare in war
- score urile de la war ca un CONST in ClanManager
- reparat sistemul de asisturi
- am facut mesajele in player death din war
- dupa war, sa primeasca CI si/sau daca iese in timpul war ului
- lightning animation death in war

*** 

> alpha 28-10-2024
- clan tags colorate la war
- chest uri
- harta de war
- border la war waves
- zonele wave ului automate in functie de centru ul borderului
- timpul de queue la dungeon setat(sa nu mai fie 10, pt teste)
- in war, daca spargi diamante, poti primi rand(1,2), daca spargi lapis, carti cu enchant, daca spargi redstone(potiuni, debuff, buffer)

***

> alpha 29-10-2024
- am adaugat mobi in war
- cand apare borderul pt wave2/3, nu iti mai iei dmg chiar daca iesi din zona wave ului vechi
- daca moare de la mobi in war sa apara anno
- daca omoara mobi primeste +1 score
- daca omoara boss ul primesc un reward


***

> alpha 31-10-2024
- mesaj de info adaugat la inceputul war ului
- reparat ce tine de CameraAPI
- in shop corectat din "ac" in "ap" la activity shop
- scos din libs perWorldInv(am mai pastrat libs urile din el, avem nev pt discordAcc)
- adaugata comanda /take
- am adaugat Motd update task 


***

> alpha 01-11-2024
- am adaugat in /systems -> Motd
- daca e un server boost on, se schimba motd ul
- in stats am facut functia de badges functionala + sortarea lor in functie de data
- am adaugat sa primesti freeze daca pui mai mult de 10 blockuri in protectie(attempt)
- am adaugat la break in protectie sa primesti mai putine mesaje(attempt)
- bug fix la dungeon queue la count()
- am adaugat in /systems Server TPS
- am adaugat old commands: plugins, status, version
- am adaugat comenzi blocate in timpul war ului
- daca ai Private Message off in settings sa nu poti trimite mesaje/primi
- am scos optiunea de turn off dice request din /settings
- am schimbat in lucky fish sa primeasca in inbox daca n are loc in inv si sa nu dea drop
- actualizat spy ul(+ChatText)
- am mutat getDefaultCooldown din TeleportManager in DefaultManager, pentru al putea folosi si in alte parti cu aceeasi functie + schimbat in static function


***

> alpha 03-11-2024
- am adaugat in /list daca esti in war sa ti arate lumea din war + sv count online
- am adaugat un anti spammer, anti badwords, anti command spammer
- am adaugat un fisier in in resours->database->badwords.txt
- am facut ca acest fisier sa fie creat automat si cu un exemplu, in caz ca nu exista
- am inceput sa lucrez la gift codes(bonus system)


***

> alpha 07-11-2024
- am adaugat obsidian breaker cu tnt (2 dmg normal, 1 dmg in apa, total hp 10)
- sa nu mai poti interactiona cu anumite blockuri in protectie
- bug fix la floating text
- lista de perk uri din clan -> perks sa fie colorata in functie de perk
- modificat timpul pt care iti apare UI ul de la dungeon
- bug fix la dungeon queue timer
- adaugat Played time in /stats
- adauagt in /staff (usage) mai multe informatii
- text fixs in /panel si in warn ban screen
- bug fixs la /take (nu era trecut ca take, lipseau niste notificari)
- am inceput sa lucrez la whitelist


***

> alpha 09-11-2024
> - am terminat /systems whitelist (ceva basic)
- am scos din reward urile de la dungoen Rocket Fragments(le vom adauga in viitor)
- am adaugat un lore informativ la spawner frag si core


***

> alpha 10-11-2024
- am inceput sistemul de tutorial
- am adugat un PlayerKillStackableMobEvent, pentru a verifica cand moara un stackable mob pt tutoriar, trb testat ceva cu progresul
- am adaugat in Account functia defaultAccount, pentru a seta lucrurile default
- am adauat JobGetEvent


***


> alpha 11-11-2024
- am adaugat in FarmerCollectEvent -> milk
- am adaugat FeedCowEvent
- default silvercoins -> 300


***

> alpha 16-11-2024
- ZombieFIghter -> GhoulFighter + skin 
- ambient cave sound in dungeon
- doar daca ai rank poti opri sounds notification din /settings
- sound cand dai /fish
- am terminat 95% sistemul de Tutorial


***

> alpha 17-11-2024
- am adaugat remove All Tpa Request
- buf fix queue timerul la dungeon
- bug fix dungeon banned commands


***

> alpha 19-11-2024
- dungeon mobs nu ti mai scad din durabilitatea armuri
- in /home sa scrie si [/home delete] pt delete
- am adauagt in /shop optiunea de a cumpara mai multe home slot uri
- LoginEvent + ChatEvent => DefaultsEvent
- am adaugat join, quit, death message(events)
- am adaugat niste particule in Defaults
- am facut ca nu poti pune/crafta anvil/enchantment table


***

> alpha 20-11-2024 (in seara asta plec la ambasada)
- bug fix la quests, daca sunt inregistrate doar 3 quest uri, iar jucatorul are nevoie de 5, sv nu mai primeste freeze
- bug fix la cele 2 questuri de la NetheriteQuest
- bug fix la miner, am restabilit zona unde poti sparge
- am adaugat TradeCompleteEvent
- am adaugat quest uri noi pt Gambling si Trade
- am inceput sa dau un update comenzilor de /debug, dar nu cred ca le voi termina vreodata
- acm daca esti in war poti sa ti dai upgrade la armura cu netherite chiar daca nu ai nivelul necesar
- daca e in tutorial sa nu poata inchide UI-ul de la sell fish/farmer
- in protectie nu mai poti interactiona cu nimic


***

> alpha 26-11-2024
- bug fix la /setgroup
- bug fix la /fly
- am adaugat particule in spawner(doar cand pui spawnerul jos, nush ce are de dispar dupa, pis pe el NBT)
- bug fix la combat isTagged(se apela functia la secunda dupa ce loveai pe cineva din cauza scoreboard ului)
- bug fix la butonul de dungeon(level<reborn)
- am adugat la crate o animatie in care iti arata itemul (thanks Hebbinkpro\MagicCrates)
- bug fix la pozitia camerelor la crate animation
- am inceput in /stats -> skills


***

> alpha 28-11-2024
- am adaugat skill si la quest uri, daca ai skill 2 primesti +1 activity point
- adaugate prices in normal shop
- buff la kit uri
- am adaugat 2 comenzi noi in debug(changeState si testCrate)
- am adaugat CONSTante pt tickete sa fie mai usor
- fixat textul de la crate uri
- reparat ceva la war(sper sa nu mai dea crash), resetarea mapei doar dupa 5secunde
