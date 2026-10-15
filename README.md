# Hi, I'm Aleksandr Esipov 👋

**Unity / C# game developer · 6+ years in game dev**

I build games in Unity. I've worked on a mobile 5v5 PvP arena, a live mobile RTS, F2P visual novels, hyper-casual and web games, from first prototype to release and live ops. Gameplay and networked features (Photon Fusion / PUN 2), bot AI on NodeCanvas behaviour trees, UI architecture (MVP), Addressables and performance work. I've also led a team and mentored developers along the way.

I like making the team's tools better too: below are a couple of open-source utilities for working with NodeCanvas graphs.

## 🎮 Games

| Game | About |
|---|---|
| [**War Legends**](https://play.google.com/store/apps/details?id=com.geargames.warlegends.rts.strategy.game) · Gear Games | Live mobile RTS. Built a UI pipeline on MVP, premium subscription, moved the in-game shop to Addressables and added background bundle loading. Acted as team lead and mentored a junior to mid level. |
| [**Grow a Garden**](https://yandex.ru/games/app/458922) · Yandex Games | Multiplayer farming sim I built and shipped solo. Planting, harvesting, shop, inventory, saves with migrations. Unity 6, URP, Photon PUN 2, VContainer, R3, UniTask, LitMotion. |
| [**Novels: Choose your story**](https://play.google.com/store/apps/details?id=com.interactive.novella) · Ayist Games | F2P visual novels. Lead technical designer: bundle and memory optimisation, content automation tools, a team of 4. |
| [**Disco Planets**](https://github.com/Primeer/Disco-Planets) | Hyper-casual 2D planet-merging game, shipped as a web game. UI Toolkit, VContainer, UniTask, DOTween. |

## 🛠 Open-source tools

| Project | What it does |
|---|---|
| [**NodeCanvas Usages for Rider**](https://github.com/Primeer/NodeCanvasForRider) · [Marketplace](https://plugins.jetbrains.com/plugin/35036-nodecanvas-usages) | NodeCanvas calls C# members by string name, so Rider marks them unused and a rename silently breaks graphs. This plugin brings graph references into **Code Vision, Find Usages and Rename**, plus inspections for broken references. Indexes a ~4000-asset project in ~0.3 s. C# (ReSharper SDK) + Kotlin. |
| [**nodecanvas-cli**](https://github.com/Primeer/nodecanvas-cli) | Read, search, lint and edit NodeCanvas graphs (behaviour trees, FSMs, dialogue trees) without opening Unity: find broken references, see where a method or variable is used, apply edits as atomic batches with byte-identical round-trips. Python, no dependencies. |

## 🧰 Stack

**Engine & gameplay:** Unity · C# · Photon Fusion / PUN 2 · FishNet · NodeCanvas · A* Pathfinding · Cinemachine · Addressables · ECS · URP  
**UI:** UI Toolkit · uGUI · MVP · Odin Inspector  
**Architecture:** VContainer · Zenject · UniTask · UniRx / R3 · unit testing  
**Performance:** Profiler · Frame Debugger · memory & bundle optimisation  
**Other:** Git · Rider / ReSharper SDK · Python · GitHub Actions

## 📫 Contact

[Telegram @p_imeer](https://t.me/p_imeer) · [esipovaa.985@gmail.com](mailto:esipovaa.985@gmail.com)
