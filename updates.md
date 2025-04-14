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
- am terminat /systems whitelist (ceva basic)
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


***

> alpha 30-11-2024
- niste modificari la Tutorial(obiective 28-11-2024)
- am scos UI ul automat de la fisher(probabil pe viitor o bag din nou cu closeAll)
- am incercat niste fix in setHaybaleBlock(farmer) 
- getRecord nou in GamblingManager(obiective 28-11-2024)
- nu mai poti intra in dungeon daca deja e playing
- bug fix la /casino cand nu ti arata si scorul cand pierzi
- am adaugat defaultEntity
- bug fix la pvp


***

> alpha 01-12-2024
- am adaugat BuyRankEvent
- am adaugat buyRank si daily/weekly rewards pt rankuri
- am facut o schimbare in TimeTask, adaug un event special pt player, pt a putea folosi mai usor(trebuie testata performanta)
- am inceput sa lucrez la sistemul de blacksmith


***

> alpha 07-12-2024
- am adaugat la toate functiile un return(:void/:int/:string etc) automat din PhpStorm(sper ca nu a gresit cv)
- am adaugat in /give optiunea de selecta toti playeri (all, *, @a)
- am adaugat Server Currency in Systems (1 EURO = 100 GOLD COINS)
- am adaugat in /systems donation/confirm/bonus
- am adaugat ca atunci cand cineva doneaza sa apara un embed pe discord si un mesaj in chat
- continui lucrul la sistemul de blacksmith si cel de care e legat(blanaaaaaa!!!!!)
- am adaugat sa primesti si Role pe discord automat cand cumperi rank
- am adaugat ID ul in /stats
- am adaugat sa poti da /stats player
- am adaugat PlayerRebornEvent
- am adaugat sistem de referali


***

> alpha 10-12-2024
- am adaugat o functie noua in LevelManager(getNextSpecialLevel)
- am adaugat 2 functii noi in Account(getLevelById, getRebornById)
- am adaugat analytics la referral
- bug fix la /take
- am terminat sistemul de referral


***

> alpha 12-12-2024
- am adaugat entitate la blacksmith
- am facut ca la FirstDailyEvent sa ti scada fatigue in functie de rank


***

> alpha 11-01-2025
- update la pmmp
- bug fix camera
- enchant effect
- xuid check
- enchant book check
- trambulina la pvp
- bug fix la itemele pe ID(key si pot)


***

> alpha 12-01-2025
- busola la war
- ceva claim gift
- bug fix camera
- enchant effect
- xuid check
- enchant book check
- trambulina la pvp
- bug fix la itemele pe ID(key si pot)


***

> alpha 14-01-2025
- am adaugat isSpecial (daca are VIP si GOLD)
- getRankColor adaugat in GroupsManager
- TextManager::updateNametag added
- am facut la blacksmith sansele
- am adaugat un getMaxFatigue in functie de rank
- un mic buff la rank
- am adaugat repair la blacksmith


***

> alpha 16-01-2025
- am adaugat custom items
- am adaugat map fragments
- am adaugat traveler npc 
- am adaugat storymode pentru insula 
- am facut sistem de waypoint


***

> alpha 17-01-2025
- am adaugat sistem de mark


***

> alpha 24-01-2025
- am terminat Auction House(22-01-2025)
- am terminat a doua misiune de pe insula
- am adaugat no fall dmg la pvp
- am adaugat taxe la auction house si mici schimbari


***

> alpha 07-02-2025
- am terminat sistemul de battlepass
- am optimizat time managerul
- am adaugat cache uri
- am adaugat LuckyFishCatchEvent
- am adaugat DungeonHelper
- am adaugat FisherHelper
- am adaugat MinerHelper
- am adaugat FarmerHelper
- am adaugat PlayerWinWarEvent
- am adaugat PlayerParticipateWarEvent


***

> alpha 08-02-2025
- am adaugat map frag cand omori boss ul de la dungeon
- zona mai mare la waypoint de pe insula
- am adaugat protectie pe insula
- am scos slowness ul dupa ce iei 6haybale de la farmer
- text fix la fisher(catching..)
- depsawn traveler npc de pe insula
- nerf dungeon mobs dmg, buff xp drop
- zid la dungeon quest complet


***

> alpha 09-02-2025
- dungeon bug fix la armura sa dispara cand mori


***

> alpha 12-02-2025
- am adaugat mai multe tipuri de floating text


***

> alpha 10-02-2025
- am adaugat tutorial skip
- small text fixs


***

> alpha 15-02-2025
- am adaugat pvp manager (kills, deaths, kill streak)
- am adaugat bounty
- am fuzionat NotificationManager si ChatText in Notification


***

> alpha 16-02-2025
- am adaugat la bounty nametag si efecte
- am adaugat setari noi in /settings
- am adaugat hp indicator
- modificat build ul de la pvp
- adaugat inca o trembulina la pvp
- BUG FIX la floating text(regandite entitatile)
- cand dai skip la tutorial iti dispare bossbar ul
- nerf la dungeon mobs
- am adaugat zarurile in dice
- /zones din GUI in UI
- remove fixform
- bug fix la scoreboard


***

> alpha 19-02-2025
- sa poti da /tutorial in tutorial
- bug fix dupa ce dai tutorial skip si start din nou
- am adaugat in DefaultsManager un checkPlayerIsIn
- acum poti sa iesi din dungeon cu /dungeon
- am inceput un system de cosmetics
- am adaugat colorated nicknames
- am facut modificari la updateNametag


***

> alpha 20-02-2025
- am modificat timpul al /fish dupa ce ai dat fail 10 -> 5
- am adaugat K/D in stats
- am adaugat Gems(o sa fie folosite pentru cosmetice)
- am adaugat in RandomUtils::number(int) (nu stiu de ce n am facut asta de la inceput)
- am facut KillMessages si KillScreenText


***

> beta 21-02-2025
- am adaugat noul shop
- am modificat zona la /fish
- am adaugat min level la /ah
- bug fix de text la /dice
- am adaugat UI ul pt insula
- am adaugat /bounties
- am adaugat /tpa pe chat
- bug fix la create island
- am adaugat mai multe verificari la checkPlayerIsIn
- bug fix island first mission
- am adaugat break flag la Mark
- am schimbat din MarkPosition in MarkLocation
- am adaugat Mark uri in tutorial
- am adaugat /anno
- am adaugat mesaje informative
- reparat bug /pay
- adaugat protectie pt PHP_INT_MAX
- reparat un sql


***

> beta 24-02-2025
- am adaugat label uri la /c
- am reparat timpul nou(lipseau 2 taskuri)
- am adaugat commands in groups si am mutat comenzile acolo
- daca ai ytb mode on sa nu mai vezi Admin Notifications
- am adaugat /cc
- nerf la boss king si quest mobs din dungeon
- cred ca am scos toate error_log urile
- am adaugat comenzi de /area
- am fuzionat Combat si Pvp -> Pvp
- am adaugat ceva verificari pt tnt uri


***

> beta 25-02-2025
- am arhivat job farmer vechi
- am dat REWORK la Farmer Job
- acum poti zbura si la farmer job
- am adaugat sound atunci cand nu poti sa spargi un block in protectie


***

> beta 01-03-2025
- am adaugat in systems sa poti dezactiva Dungeon, Gambling, Jobs
- am modificat questurile si misiunile pentru noul job farmer
- am adaugat rewardurile la Diamond Crate
- am adaugat smithing table functional (ceva skema)
- de acum la Blacksmith iti dai upgrade la itemele de diamond -> netherite (min lvl: 25)
- am adaugat pe server NETHERITE UPGRADE TEMPLATE
- am adaugat pe server ARMOR TRIM uri
- am sters NetheriteManager 
- am adaugat NetheriteUtils
- am adaugat in War Events metoda veche de Netherite Upgrade
- am adaugat cand se spawneaza Skeleton King sa se auda mob.skeleton.convert_to_stray
- am schimbat la job farmer din 32->64


***

> beta 13-03-2025
- am inceput sistemul de socketuri
- am adaugat health boost socket
- am adaugat Job boost socket
- am adaugat XP boost socket
- am fixat XP boost ticketul (acum e functional)
- am adaugat peste tot constant de TICKETS din Manager(pana acum scriai manual numele ticketului)


***

> beta 14-03-2025
- am modificat la kit uri sa ti dea prima data tools dupa armor
- am adaugat Activity Crate Socket
- am adaugat Negative Effect Reduction Socket
- am adaugat Blindness, Weakness, Hunger, Diamond Crate, Dungeon Crate, Void Crate, BattlePass Socket
- am terminat sistemul de Sockets


***

> beta 15-03-2025
- am adaugat Runner Socket(speed out of combat)
- am adaugat in Notification screenAnimation si lighting


***

> beta 20-03-2025
- am adaugat Kill Effects
- am adauga research pentru cosmetice
- am adaugat log uri de Give
- am adaugat log uri de Crate
- am adaugat reward urile la crate dungeon


***

> beta 22-03-2025
- am adaugat reward urile la void crate
- am adaugat cratelogs la toate reward urile de la crate uri
- am adaugat PlayerGainActivityPointsEvent
- am schimbat in CrateBattlePass si in BattlePassMission treaba cu id urile(am adaugat un documentar la ce am facut)
- am adaugat misiuniile pentru battlepass week 1
- am adaugat PlayerGainBountyEvent
- am adaugat PlayerClaimBountyEvent
- bug fix la PlayerFarmerCollectEvent


***

> beta 04-04-2025
- am adaugat webhook uri cu log uri
- am adaugat max level la enchanted book upgrade in blacksmith
- am adaugat mai multe verificari in BlacksmithSession
- am adaugat convertToRoman
- am adaugat enchanter
- am facut niste modificari in ExperimentsManager


***

> beta 06-04-2025
- am adaugat Skill la Enchanter
- am facut modificari la cum primeste Random Enchanted Books
- am adaugat Research Enchanted Book
- am adaugat Research Booster (sanse de 100% succes la research)
- am adaugat meniul pentru Research


***

> beta 08-04-2025
- am facut functionala functia sendCrateAnno(exista si nu era folosita) acum trimite un mesaj daca rewardul era cu sansa mai mica de 25%
- am inceput sa lucrez la pvp update(am facut mini koth)


***

> beta 09-04-2025
- am adaugat Minigames
- am adaugat la Minigames: Cake, Beast si KOTL
- am adus modificari la ClanEvents
- am adaugat copy si paste in debug cu state id uri in functie de coordonate
- ceva bug fixs


***

> beta 13-04-2025
- am adaugat sounds la minigameuri
- am adaugat build prin spawn
- am reparat fly ul
- am adaugat Languages
- am facut tutorialul nou
- update la TeleportToIslandEvent si TeleportTask sa fie mai practic
- am adaugat la Beast Mode inca un effect clear Darkness
- am adaugat o misiune noua pe insula
- am adaugat wizard tower pe insula
- am setat mobii in dungeon
- am adaugat sa nu poti trage cu arcul in protectie


***

> beta 14-04-2025
- am facut update la Waypoint
- am adaugat floating pt farmer
- am adaugat border la harta (20.000x20.000)
- ver si pl devin publice, nu avem ce ascunde
