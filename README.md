# XGTCoreV2
A new version of XGTCore with [@sLeeD](github.com/xXGeorgeXDR0)\
[![wakatime](https://wakatime.com/badge/user/a98d5df2-62b5-4525-9b86-6c42049b3403.svg)](https://wakatime.com/@a98d5df2-62b5-4525-9b86-6c42049b3403)

[GoldenCraft Playlist](https://www.youtube.com/watch?v=EAE7p1YhjEY&list=PLdLn7VdXmaO-qypbTS1BmHXqJdtkwrbXa)

[GoldenCraft Discord](https://discord.gg/uNexe75)

[GoldenCraft Panel](https://gcpanel.ddns.net/)

03-02-2023 | Start\
07-05-2023 | incerc sa conectez github-ul cu phpstorm :D\
05-06-2023 | XGTCoreV2 Updated to PMMP 5, now XGTCoreV2 PMMP4 is arhived\
16-6-2023 | Mare update la baza de date\
24-06-2023 | Lucram la Clan System, mai putin de o luna pana la Open-Beta\
01-07-2023 | Incerc sa termin Clan Systemul si curand sa incep alt job\
05-03-2024 | Am revenit, am terminat Clan System, am adaugat un PerWorldInv in libs\
05-05-2024 | Am bagat muzica, am facut Area System

***

> ## **Todo** 

- [x] Systems
- [x] Text
- [x] Notifications
- [x] Economy
- [x] Level
- [x] Settings
- [x] Tickets
- [x] Groups
- [x] Ranks
  - [ ] Update
- [ ] Jobs
  - [x] Fisher
  - [x] Farmer
  - [ ] Miner
- [x] Logs
  - [x] updated | 20-06-2023
- [x] Clan | working | -> 60% 24-06-2023 | 90% 01-07-2023  | 05-03-2024
- [x] Database update(player data, clan data, jobs data) | 16-06-2023
- [ ] Teleport System Update
- [ ] Old Commands Update
- [ ] Gold Shop
- [ ] Dungeons
- [ ] Daily Quests
- [ ] Player Activity(online time)
- [ ] Battlepas
- [ ] Storymode
- [ ] Crates
- [ ] Vote
- [ ] Events
- [ ] Kits
- [ ] Experiments(enchants)
- [ ] Staff
- [ ] Gambling
- [ ] Achievements
- [ ] Badges
- [ ] Warnings
- [x] Area
- [ ] Tutorial

***


> ## **Clan System** (5-6-2023)
Minim level 10-15 pentru clan.
Minim level 3 pentru a primi invite, clanul o aiba 10 sloturi cu tot cu liderul.

### Clan Levels

    Rank 1: din start | clan deposit(silver coins 50.000), 0 Clan Power
    Rank 2: 50.000 clan XP, 20.000 clan silver coins, minim 3 membri, 100 Clan Power | unlock: clan perks tier 1, clan missions(soon), clan wars, clan deposit(silver coins +5.000, gold coins +50)
    Rank 3: 75.000 clan XP, 50.000 clan silver coins, 80 clan gold coins, minim 5 membri, 300 Clan Power | unlock: clan job, clan perks tier 2, clan missions +5(soon), clan deposit(silver coins +5.000, gold coins +50)
    Rank 4: 100.000 clan XP, 75.000 clan silver coins, 120 clan gold coins, minim 5 membri, 500 Clan Power | unlock: clan perks tier 3, clan missions +5(soon), clan deposit(silver coins +5.000, gold coins +50), +3 sloturi 
    Rank 5: 200.000 clan XP, 150.000 clan silver coins, 200 clan gold coins, minim 5 membri, 1000 Clan Power | unlock: clan perks tier 4, clan missions +5(soon), clan deposit(silver coins +5.000, gold coins +50)

### Clan Perks

- Tier 1: Worker Perk(+3% jobboost), Food Perk(saturation, in zona teritoriului), Speed Perk(speed I, in zona teritoriului), Glowing Perk(in zona teritoriului)
- Tier 2: Quests Perk(+5% reward daily quests), Worker Perk 2(+8% jobboost), Heal Regen Perk(regeneration I 6/10 sec, in zona teritoriului), Haste Perk(haste I, in zona teritoriulului)
- Tier 3: Speed Perk 2(speed 2, in zona teritoriului), Haste 2(haste II, in zona teritoriului), Flyer Perk(in zona
  teritorilui)
- Tier 4: Strength Perk(in zona teritoriului, strength I 3 sec), Poison Perk(daca intra un inamic pe teritoriu sa aiba o
  sansa de 10% sa primeasca poison 10 secunde, cooldown 2min)

### Clan Job

    Liderul poate sa si aleaga un Job de pe server care sa ii reprezinte clanul.
    - +6-10%(in functie de rankul clanului) job boost la jobul respectiv.
    - +5-10%(in functie de rankul clanului) XP, la practicarea jobului(removed)
    - +10-20%(in functie de rankul clanului) job rewards(silver coins) care merg in seiful clanului de la jobul respectiv(default 100%)

### Clan Deposit

    Depozitul creste in functie de rankul clanului(gratis) sau cumparand cu clan gold coins din clan shop de catre lider.
    Fiecare player poate depozita Gold Coins, iar Silver Coins urile se pot face doar din job(cand playerul face un job, 100% din totalul jobului intra si in depozitul clanului, fara ca el sa piarda ceva)

### Clan Wars

    In fiecare duminica, de la o anumita ora, liderul impreuna cu membrii online, pot sa participe la Clan Wars.
    O arena, unde Fiecare clan este impartit intr o zona, ei au la dispozitie 10 minute sa mineze si sa si faca niste iteme/mini baza, iar dupa acele 10 minute incepe bataie, pana la LSM. Clanul ultimului player, castiga.
    Alta varianta, tot o arena, 10 minute loot, dupa fiecare clan are un HP de 30, de fiecare data cand un jucator moare din acel clan => -1hp clan. 0hp clan = out, clanul care ramane cu hp castiga.
    Rewards: ....

### Clan Shop

    Liderul poate cumpara cu Clan Gold Coins si cu Clan Silver Coins obiecte din clan shop.
    - +1 Clan Slot(max 12)
    - Deposit Upgrade(50.000 silver coins, 500 gold coins)
    - +5% mai mult silver coins de la job uri(max 25%)
    - +5% mai mult XP de la playeri(max 25%)
    - +5 Plot Size Upgrade(max 40, def 25)
    - Clan Rank Up

### Clan Database (removed/changed)

```
leader
name
description
creation
slots
level
xp
necessary
silver
gold
job
perks
wins
loses
world
x
y
z
```

> ## **Fisher** (7-5-2023)

  ### __**Rod's**__

     Classic Rod
     - craft: 300 silver coins
     - /fish
     - 100 durabilitate
     - 20% sansa sa pierzi pestele 

    Advenced Rod
      - craft: tier II, 500 silver coins, 3 advanced fragments
      - 150-220 durabilitate
      - 10% sanse sa pierzi
      - +5% sanse sa prinzi pesti mai buni, -5% sa prinzi pesti slabi
      - +1% sansa la silverfish si goldfish

    Expert Rod
      - craft: tier II, 750 silver coins, 20 gold coins, 5 expert fragments
      - 70-100 durabilitate
      - 0% sanse sa pierzi 
      - +15% sanse pesti mai buni, -10% sanse pesti mai slabi
      - +3% sansa silverfish, +1% sansa goldfish
      - Lucky Fish

  ### Tiers
    Tier I
      - basic rod
      - Salmon(43%), Cod(35%), Pufferfish(x15%), Silverfish(7%)
    Tier II
      - 30.000 silver coins
      - basic rod, advanced rod
      - Salmon(28%), Cod(22%), Tuna(15%), Trout(13%), Pufferfish(x10%), Silverfish(10%), Goldfish(x2%) 
    Tier III
      - 100.000 silver coins
      - advanced rod, expert rod
      - Salmon(19%), Cod(18%), Tuna(17%), Trout(14%), Perch(9%), Pufferfish(x5%), Silverfish(13%), Goldfish(x5%) 
    Tier MAX - Cand dai [/fish] sa ai optiunea de Lucky Fish
      - expert rod
      - Trout(30%), Perch(30%), Pufferfish(30%), Silverfish(5%), Goldfish(5%)
  
  ### Fish
    - Salmon > 11-22
    - Cod > 16-27
    - Tuna > 25-36
    - Trout > 29-37
    - Perch > 35-43
    - Silverfish > 53-99
    - Goldfish > 3-8 


### Fragments
**<span style="color:green">Advenced</span> Fragment** 
- 3% sansa de drop de la Tier I
- 5% sansa de drop la Tier II
- 7% sanse de drop la Tier III
- 9% sanse de drop la Tier MAX

**<span style="color:purple">Expert</span> Fragment** 
- 0% sansa de drop de la Tier I
- 2% sansa de drop la Tier II
- 3% sanse de drop la Tier III
- 4% sanse de drop la Tier MAX


  ### Database
| Date          | Value  | 
|---------------|--------|
| Job           | Fisher |
| Skill         | 1      | 
| Progeress     | 25.000 |
| Rod           | Basic  |
| Durability    | 80     | 
| Advenced Frag | 0      | 
| Expert Frag   | 0      | 

> ## **Farmer** (12-6-2023)

Jobul e impartit in mai multe categori:

1. Cowboy
   - Minim level 1, tier 1 Farmer
   - Trebuie sa culegi Hey Bale(6) de pe camp, apoi dupa ce vrei primi slowness, trebuie sa le duci in hamber la Vaca. Dupa ce astepti 1/2 minute, trebuie sa mergi in subsolul hambarului, de unde minezi pentru a obtine o galeata, dupa ce iei galeta, poti mulge vaca
   - Undeva la 230-350 pe tura, depinde de tier
2. Fruiter
   - Minim level 25, tier 2  Farmer
   - Ai nevoie de o galeata, pe care o faci in subsol, dupa ce ai galeata, poti merge la pomi si sa culegi fructele(25), poti vinde
   - Undeva la 50-130 pe tura, depinde de tier, daca faci 25/25 ai sansa de 2%-3% la gold(2-6)

### Tiers
    Tier I
      - Practice Job
    Tier II
      - 135.000 silver coins
      - Fruiter
      - +20 coins la rand min si max
    Tier III
      - 200.000 silver coins
      - +1% sanse gold
      - +40 coins la rand min si max

### Bucket

      Poti face rost de galeata in orice moment in care ai jobul de Farmer si Slotul pentru galeata liber. 
      Trebuie sa minezi 10-20 blocuri din subsolul hambarului pentru a obtine galeata.

> ## **Miner** (6-5-2024)

Dupa ce ai pickaxe si backpack trebuie sa mergi in mine pentru a strange crystale, cu cat mergi mai in jos, gasesti cristale mai mari.
In mine o sa gasesti:
 - 30 Small Crystal
 - 30 Medium Crystal
 - 25 Large Crystal
 - 15 Big Crystal\
Crystalele se respawneaza la 2 minute iar toti jucatori care se afla in mine o sa fie teleportati la intrarea in mina.

### Unlock the job
Ca sa poti practica job ul trebuie sa completezi niste task uri:
1. Prinde 100 de peste la Job ul Fisher
2. Mulge vaca de 30 de ori la Job ul Farmer
3. Culege 100 de fructe la Job ul Farmer -> Fruiter


  ### __**Pickaxe's**__

      Classic Pickaxe
      - craft: 500 Silver Coins
      - durability ~100
      - Small Crystal, Medium Crystal

      Advanced Pickaxe
      - craft: 2.000 Silver Coins, 5 Advanced Fragments
      - durability ~200
      - Small Crystal, Medium Crystal, Large Crystal, Big Crystal
      - Haste I

      Expert Pickaxe
      - craft: tier 2, 5.000 Silver Coins, 20 Gold Coins, 3 Expert Fragments
      - durability ~300
      - Small Crystal, Medium Crystal, Large Crystal, Big Crystal
      - Haste II

  ### __**Backpack's**__

      Classic Backpack
      - craft: 1.500 Silver Coins
      - capacity 15 kg

      Advanced Backpack
      - craft: 3.000 Silver Coins, 1 Advanced Fragments
      - capacity 30 kg
      - Speed I

      Expert Pickaxe
      - craft: tier 2, 5.000 Silver Coins, 10, Gold Coins 1 Expert Fragments
      - capacity 60 kg
      - Speed II

  ### Crystal's

      Small Crystal: 1kg, purity 9, rand(4, 8) silver coins/kg/purity, -1 pickaxe durability;
      
      Medium Crystal: 2kg, purity 8, rand(8, 13) silver coins/kg/purity, -1 pickaxe durability,
                      1%*Job Tier(+2 isRank) chance drop Advanced Fragments;
                      
      Large Crystal: 3kg, purity 5, rand(10, 16) silver coins/kg/purity, -2 pickaxe durability,
                      1%*Job Tier(+2 isRank) chance drop Advanced Fragments, 1%*Job Tier(+1 isRank) chance drop Expert Fragments;
                      
      Big Crystal: 4kg, purity 1, rand(15, 25) silver coins/kg/purity, -3 pickaxe durability,
                      3%*Job Tier(+2 isRank) chance drop Advanced Fragments, 1%*Job Tier(+1 isRank) chance drop Expert Fragments;

  ### Tiers
    Tier I
      - Basic Pickaxe, Basic Backpack, Advanced Pickaxe, Advanced Backpack
    Tier II
      - 30.000 silver coins
      - unlock: Expert Pickaxe & Expert Backpack
      - +2 coins la rand min si max
    Tier III
      - 100.000 silver coins
      - +3 coins la rand min si max

