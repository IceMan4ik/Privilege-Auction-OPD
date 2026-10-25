# Privilege-Auction-OPD

🇬🇧 [English](README.md) | 🇷🇺 [Русский](README.ru.md)

---

## Build

**Windows (cmd):**
```cmd
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

**Linux (bash):**
```bash
mkdir build && cd build
cmake .. -DCMAKE_BUILD_TYPE=Release
cmake --build . -j$(nproc)
```

---

## 📚 Documentation

- 📖 [Contributing Guidelines](CONTRIBUTING.md) — How to set up the project, work with branches, and create Pull Requests.
- 📝 [Changelog](CHANGELOG.md) — Project history and version updates.
- 🛠️ [Development Docs](docs/) — Internal guides and technical documentation.
