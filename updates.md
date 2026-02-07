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


***

> beta 15-05-2025
- am adaugat joined si age in db (player)
- am adaugat anticheat(ZURI) celalalt nu e testat pe pmmp
- am inceput implementarea noilor spawnere(v2, dar o sa fac main v3)


***

> beta 19-04-2025
- am adaugat spawnerele noi V4(m au omorat, inca nu merg cum trebuie)
- bug fix la clan plot draw
- am adaugat easter eggs
- am adaugat sa poti sparge spawnerele pe protectie de fac
- bug fix la tutorial dungeon(nu puteai avansa, acum trb reparati nr de mobi)
- am adaugat /info(/help)
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs
- bug fixs


***

> release 19-04-2025
- am micit cat silver coins iti trebuie pt fisher skill up
- am micit cat silver coins iti trebuie pt farmer skill up
- am marit cat silver coins iti trebuie pt miner skill up(15.000 -> 30.000 ; 30.000->90.000)
- am scazut pretul la expert rod 15 gold coins -> 5 gold coins
- am modificat la unlock miner: farmer 200->300; fisher 200->150
- am adaugat mai multe CONST uri in FisherHelper
- am adaugat cand vinzi gold fish sa primesti 200 xp si cand vinzi orice alt fish sa primesti (1-4) xp in functie de tier
- am adaugat atunci cand mulgi vaca(nu fail) o sa primesti (1-3) xp in functie de tier
- am modificat clan create level 5->3; join clan level 3->1
- am adaugat in shop mai multe iteme care se pot vinde
- am adaugat zones noi in [/zones]
- am adaugat ca urmatoarele iteme sa se poata vinde in shop (cobblestone, stone, wood logs etc)
- am marit pretul de vanzare la anumite iteme din shop
- am adaugat ca zilnic la daily join sa primesti Kit Silver Points
- am modificat din YouTuber in Famous (deoarece sunt si tiktokeri)
- buff la spawnerele de lvl 1 si 2(spawn speed 30->27; 25->23)
- am scazut pretul de la expert pickaxe 15 gold coins -> 1 gold coins
- am scazut pretul(in silver coins) de la pickaxe advanced(1.500->1.000) si pickaxe expert (3.000->2.000)
- am crescut pretul(in fragments) la backpack advanced(1->7) si la backpack expert(1->7)
- am crescut pretul(in silver coins) la backpack uri (basic: 3.000->5.000; advanced: 5.000->10.000; expert: 15.000->20.000)
- am scazut XP multiplier la cristale (medium: 1.5->1.1; large: 2->1.5; big: 3->1.8)
- bug fix in dungeon cu fly ul


***

> release 21-04-2025
- am scos JobSellEvent si am facut cate un event separat de sell pentru fiecare job
- am adaugat mai multe const uri in MinerHelper
- am facut ca la Miner in sell menu sa ti apara doar crystalele pe care le ai, sa nu mai apara "-"
- bug fix la quest urile legate de sell fish
- daca esti staff mode / owner nu mai iei mute la comenzi
- am scos 2 questuri (gain power si kit points collector)
- am adaugat rewards logs
- am dat nerf la rewards urile de la easter eggs
- am adaugat XP la easter eggs cand dai claim
- am adaugat efecte la claim egg
- am dat buff la rank up silver coins (iti aduga la randmin si max + level ul tau)
- am adaugat mai multe special levels(si la reborn specials)
- am adaugat mai multe reward uri la levelup(special levels)
- cand incepe un event la pvp, set fly flase to all
- heal regen incressed la pvp events
- am adaugat 2 floating text uri, la mineri si la spawn cu top players
- am scazut pretul de upgrade clan deposit (50 -> 20 goldcoins)


***

> release 29-04-2025
- de acum poti scrie in tutorial
- am facut butoanele de la toate joburile cu culoare
- la fisher daca nu ai fragemntele necesare/level etc iti apare Unavailable automat
- bug fix la sell rod expert
- code improvment la randUI
- code improvment la milkUI
- am facut sell fish ul instant(nu mai trb sa confirmi)
- bug fix la efectele de la miner
- am readaugat teleport to mine at crystal respawn
- nerf la goldfish
- buff la silver fish (rand(53,99) -> rand(73,149) silver coins)
- crescute sansele la silver fish de rod advanced si expert
- buff la pufferfish (rand(11,22) -> rand(15,22) silver coins)
- nerf la goldcoins de la miner
- nerf la advanced fragments de la big crystal(0.04 -> 0.03)
- buff small crystal price (rand(1,2) -> rand(1,3))
- nerf la XP multiplier la crystale (large: 1.5->1.3; big: 1.8->1.6)
- buff la special levelup rewards
- am bagat hopperele
- de acum iti poti face clan de la lvl 2 
- cand esti in tutorial iti scrie in chat
- dungeon join level 10 -> 3
- buff pot xp basic 120 -> 200
- buff pot xp orb 3 -> 12
- buff dungeon buy from shop points 2 -> 10
- buff dungeon shop gold coins -> activity points
- buff dungeon shop prices reduced
- nerf la elderul din room 4
- buff la Skeleton King Boss
- buff Skeleton King Boss Rewards (advanced frag 5 -> 10; expert frag 3 -> 5; random enchanted book 3 -> 4)
- buff la vote activity points 2 -> 3
- buff la vote, acum primesti si un activity crate key
- nerf la PIGS (drop xp: rand(0,3) -> 0; drop RAW PORKCHOP: rand(0,3) -> rand(0,2))
- de acum mobi se stacheaza si dupa ce au iesit din spawn
- am scazut preturile din gold shop la: xp ticket 50 -> 30 gold coins; job ticket 50 -> 30 gold coins; dungeon forest key 50 -> 15 gold coins; diamond crate key 50 -> 30 gold coins; 
- nerf la activity shop: vip account 30 -> 15 days; gold account 15 -> 7 days; kit master 100 -> 200 ap; cow core 40 -> 60 ap; zombie core 40 -> 70; skeleton core 40 -> 80 ap; creeper core 70 -> 140 ap; wither skeleton core 90 -> 190 ap
- am adaugat crate activity in activity shop
- buff la XP ticket 80% -> 100%
- nametag ul de la mobi nu se mai vad prin pereti


***
> release 30-04-2025
- bug fix la minigame iti oprea fly ul chiar daca nu erai in arena
- am adaugat shop ul nou
- buff la wither skeleton XP
- heal in toata pvp arena cat sunt eventuri
- nerf la toate kiturile la mancare (64 -> 10)
- am schimbat pretul la majoritatea itemelor din shop


***
> release 03-05-2025
- buff la crate uri (Silver Bank Big Ticket 1.000 -> 5.000 silver coins, SIlver Bank Small Ticket 500 -> 1000 silver coins)
- am adaugat la crate void Extra Big Ticket (10.000 silver coins)
- bug fix la pozitia crate ului activity
- preturile pestilor acum sunt in constante sa le putem folosi in alte parti
- de acum apar si Activity Points in /stats
- shop nerf  (Sweetberry: 3 silver coins/buc -> 2.5 silver coins/buc)
- shop buff (Pumpkin: 4 silver coins/buc -> 5 silver coins/buc; Cactus: 0.25 silver coins/buc -> 0.5 silver coins/buc; Sugarcane: 0.33 silver coins/buc -> 0.41 silver coins/buc)
- minigames buff (Cake: 1 silver coins/slice -> 2 silver coins/slice,  Beast: (hunter winners: top3: 400 silver coins -> 1000 silver coins; top1: +200 silver coins -> +500 silvern coins; beast winner: 700 silver coins -> 2000 silver coins); Mini Koth: (ticks 20 -> 18; winner: time * 5 -> time * 7) )
- bounty buff 5 silver coins -> 15 silver coins
- am adaugat niste informatii in /c daca nu ai clan
- buff lotto win xp 300 -> 2000
- reduced casino level required 5 -> 2
- bug fix la dungeon boss reward
- am adaugat /clan rank XP progress


***
> release 10-05-2025
- daca ai socketXp si primesti 0 xp din el, acum o sa primesti 1 garantat
- am reparat questul "Milker"
- am adauagt eventuri noi(PlayerNormalShopSpentEvent, PlayerGoldShopSpentEvent, PlayerSuccessfullyResearchEvent etc)
- am modificat BattlePass manager sa nu mai foloseasca cache(cea mai mare porcarie pe care am facut o cu cahce)


***
> release 18-05-2025
- bug fix la battlepass
- am micit zona de la minigame ul CAKE
- am marit profitul de la minigame ul CAKE 2 -> 3
- am adaugat sa poti vinde cookie 0 -> 3
- am adaugat sa poti vinde carnea prajita
- bug fix la dungeon floating text
- bug fix la ceva nume de tiere din BP
- buff la dungeon socket 30% -> 50%
- buff clan xp default XP get 100% -> 150%
- dungeon key system reworked
- buff dungeon forest pot reward(advanced fragments 1 -> 10; expert fragments 1 -> 5; xp bottle 8 -> 16; kit gold points 3 -> 5; dungeon crate key 3% -> 5%; )
- buff dungeon forest boss reward(pig spawner core removed; silver coins: rand(700, 1200) -> rand(2000, 3000); enchanted random book 4 -> 8; forest dungeon key 2 -> 5)
- dungeon forest buff (activty shop key 10 -> 4, trader prices are now all 20 activity points)
- dungeon forest nerf (penalty points for team 20 -> 250; penalty points for player 120 -> 800; penalty fail 10 -> 500, trader reduce seconds removed)
- buff void crate (golden apple 12 -> 32; zombie spawner core 15% -> 20%; creeper spawner core added with 15%)
- buff dungeon crate (5 dungeon forest key added with 40%)
- acum iti seteaza automat public chat dupa ce se termina un dungeon
- anticheat added
- am adaugat un rod la jobul fisher pe care poti da click 
- fixed sa nu ti mai dea questurile de la miner daca nu le ai unlocked
- battlepass missions bug fixed
- o gramada de bug fixs
- dungeon forest key price in activity shop 10 -> 4
- dungeon forest key amount in gold shop 1 -> 2


***
> release 25-05-2025
- bug fix la wither spawn
- bug fixs battlepass week 3 missions
- rework fisher
- reopen la casino


***
> alpha 2 07-02-2026
- rescrisa toata baza de date din sqlite in mysql*
- adaugam password si auth
- rescrisa toata clasa Account*
- rescris tot sitemul de Settings*
- rescris tot sitemul de Log uri, separat logurile din Clan*
- inceput reformat tot core ul, fiecare sistem sa aiba SystemListener in system foolder root(acum e in /events)
- clean-up la defaults si multe fisiere, cod comentat, .old fisiere
- am adaugat ReferralEvent, BonusCollectEvent, InboxReceiveEvent, InboxClaimEvent
- am scos sa nu mai poti vedea logurile din joc, totul o sa fie pe panel
- rescris tot sistemul de inbox*
- rescris Shop ul, acum e pe MySQL*
- am adaugat DailyStats(pentru a face Chart uri pe zile cu nr playeri  etc ca nu exista un API public pe net)
- multe bug fix uri la casino*
- adaugat Mines in casino*
- rescris logica de la Quest-uri(acum se salveaza in baza de date)*
- QoL la Auctions System(acum ai acelasi inventar, nu mai trebuie deschis non stop cand faci un change)*
- am adaugat sa ti scoata un Afk Count cand te joci la Casino
- am scos functiile legate de Factions din Teleport System si code bump
- am scos functiile legate de Factions din Clan System si code bump
- am mutat War ul in propriul sau System