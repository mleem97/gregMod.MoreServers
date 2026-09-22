# Quickstart — gregMod.MoreServers

> gregMod.MoreModules** adds faster, color-coded QSFP modules to the Data Center shop. Modules use the vanilla QSFP+ form factor and persist when installed in swi

Repo: [.](.) · Version: `0.1.0` · Lizenz: Apache-2.0.

## 1. Klonen

```bash
cd /home/marvin/Dokumente/Repositories/GregFramework/ModRepositories/gregMod.MoreServers
# Kein Remote konfiguriert – lokal arbeiten.
```

## 2. Bauen / Starten

Je nach Tech-Stack **einen** Weg wählen:

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

## 3. Testen

```bash
dotnet test            # .NET
pnpm test              # Node
pytest                 # Python
```

Details stehen in [README.md](README.md) und [docs/INDEX.md](docs/INDEX.md).
Bei Problemen: Issue anlegen ([Issues](./issues)) oder [CONTRIBUTING.md](CONTRIBUTING.md) lesen.
