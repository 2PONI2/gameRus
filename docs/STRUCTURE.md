# Структура репозитория

```
vsem-mirom/
├── README.md
├── CLAUDE.md                  правила для Claude Code
├── .gitignore  .gitattributes (Unity + Git LFS)
├── docs/
│   ├── ROADMAP.md             этапы и критерии готовности
│   ├── STRUCTURE.md           этот файл
│   ├── prompts/               промты 00-06 для ИИ
│   ├── design/                дизайн-документ (результат этапа 1)
│   └── art-credits/           лицензии сторонних ассетов
├── Assets/
│   ├── Scripts/
│   │   ├── Core/              игровой цикл, менеджеры, общие утилиты
│   │   ├── Player/            движение, взаимодействие, ввод
│   │   ├── Items/             предметы, переноска, бросок
│   │   ├── Stations/          станции и прогресс-бары
│   │   ├── Orders/            заказы, очередь, очки, звёзды
│   │   ├── Levels/            LevelData, менеджер уровней, препятствия
│   │   ├── Network/           Netcode, Relay, Lobby, LAN
│   │   ├── UI/                меню, лобби, HUD, итоги
│   │   ├── Audio/             звук и музыка
│   │   └── Editor/            Tools/Build Game (сборка сцен и префабов)
│   ├── Data/                  ScriptableObject: предметы, рецепты, уровни
│   ├── Prefabs/
│   ├── Scenes/
│   ├── Art/
│   ├── Audio/
│   ├── Input/                 Input Actions
│   └── Resources/
├── Packages/                  (создаст Unity)
├── ProjectSettings/           (создаст Unity)
└── Tests/
    ├── EditMode/
    └── PlayMode/
```

Папки с `.gitkeep` пустые, Unity их игнорирует. Папки Library, Temp, Logs в Git не попадают.
