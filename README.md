# GITLOAD - Simple GitHub Upload Tool

Et simpelt værktøj der automatisk uploader dine projekter til GitHub.

## Installation

```bash
# Kopier gitload til din PATH
sudo cp gitload /usr/local/bin/
```

## Brug

```bash
# Opret et repository med navn og beskrivelse
gitload -n "mit-tool" -d "Mit awesome CLI tool"

# Opret privat repository
gitload -n "hemmeligt-projekt" -p -d "Privat projekt"

# Tilføj README og License automatisk
gitload -n "komplet-projekt" -r -l -d "Projekt med dokumentation"
```

## Funktioner

- ✅ Automatisk git init hvis nødvendigt
- ✅ Upload alle filer til GitHub
- ✅ Opret public/private repositories
- ✅ Tilføj README.md automatisk
- ✅ Tilføj MIT License automatisk
- ✅ Farvet output for bedre UX
- ✅ Fejlhåndtering og validering

## Eksempler

```bash
# Simpel upload
gitload -n "min-script"

# Komplet projekt med dokumentation
gitload -n "awesome-cli" -d "Et awesome CLI værktøj" -r -l

# Privat repository
gitload -n "secret-tool" -p -d "Hemmeligt værktøj"
```

## Krav

- GitHub CLI (`gh`) installeret
- Autentificeret med GitHub (`gh auth login`)
- Git installeret
