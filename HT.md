# HYPERTHREADING / SMT

This feature allows the operating system to see a physical core as two virtual cores. Although good for highly-threaded loads such as rendering or compiling, this feature massively increases the system’s latency. This is because cores only have one execution unit, which is exacerbated by the operating system attempting to spread the load across both virtual processors of the same core, which creates a stall while the core’s execution unit is busy with the second logical processor.

---

ON = MORE FRAMES IN GAMES, POOR LATENCY. 

OFF = LOWEST LATENCY, FPS MAY VARY; MOUSE WILL FEEL AMAZING.
> CAREFUL WITH 8k POLLING RATES (they use a lot of cpu without HT/SMT).

---

6 CORES CPUs

In my personal experience, i tested two 6-cores CPU (i5-12400f & R5 5600) and now i can't game with HyperThreading enabled, mouse feels terrible in any polling rate.

In competitive shooters, where every ms matter, probably you prefer to disable it.

In CPU games like Valorant/CS2/Overwatch/Fortnite; i got more frames and lower latency with HT disabled.

In heavy games like Warzone/Battlefield2042/SinglePlayers or multi-tasking lot of things while gaming, i prefer to enable HT because i got more frames (120-144avg vs 165avg).

So yeah, unless you have a 6-core CPU, disable it by default.
In 6-cores; test it or depending on your game toggle it.

---

LATENCY
![Screenshot 2024-06-20 at 14-04-18 (3) Calypto on X Latency of Hyper-threading on vs  off https __t co_x6sFmslVrb _ X](https://github.com/gzmatte/trash/assets/117684932/d5f34e37-01d9-491d-824d-762f962f437f)

ON
![smt-on-lattencymon-2](https://github.com/gzmatte/trash/assets/117684932/0f02a35f-e849-4665-aace-4a672775f98a)

OFF
![smt-off-lattencymon-3](https://github.com/gzmatte/trash/assets/117684932/9aca6281-d572-4683-8aec-74f75e0fd43a)

ON
![Screenshot 2024-06-20 at 14-18-22 Disabling SMT_Hyper-Threading for Better Latency XBitLabs](https://github.com/gzmatte/trash/assets/117684932/284b5d74-3643-4847-b3fb-f78a5f1f3383)

OFF
![Screenshot 2024-06-20 at 14-20-35 Disabling SMT_Hyper-Threading for Better Latency XBitLabs](https://github.com/gzmatte/trash/assets/117684932/076e0f02-2b75-49fc-a560-98fcc64685db)


VALORANT 6cores


SOURCE; [Calypto Latency Guide](calypto.us), [XBITLABS](https://www.xbitlabs.com/disabling-smt-hyper-threading-for-better-latency/)
