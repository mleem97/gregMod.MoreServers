# Quickstart — gregMod.MoreServers

> gregMod.MoreModules** adds faster, color-coded QSFP modules to the Data Center shop. Modules use the vanilla QSFP+ form factor and persist when installed in swi

Repo: [.](.) · Version: `0.1.0` · License: Apache-2.0.

## 1. Clone

```bash
cd /home/marvin/Dokumente/Repositories/GregFramework/ModRepositories/gregMod.MoreServers
# Kein Remote konfiguriert – lokal arbeiten.
```

## 2. Build / Run

Choose **one** path depending on the tech stack:

```bash
# .NET
dotnet build -c Release
dotnet run --project src/

# Node / pnpm
pnpm install
pnpm build
pnpm start

# Python
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m <modul>
```

## 3. Test

```bash
dotnet test            # .NET
pnpm test              # Node
pytest                 # Python
```

Details are in [README.md](README.md) and [docs/INDEX.md](docs/INDEX.md).
If you run into problems: open an issue ([Issues](./issues)) or read [CONTRIBUTING.md](CONTRIBUTING.md).
