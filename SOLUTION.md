# Lösning

## Nyckelkommandon

```bash
git status
git show --stat HEAD
git rm <filnamn>
git commit --amend --no-edit
git restore <filnamn>
git log --oneline
git reset --hard <commit-id>
git status
```

## Därför händer det

Filen följde med när den senaste commiten skapades och blev därför en del av commiten.

Eftersom felet finns i den senaste commiten kan du ta bort filen och sedan ändra samma commit i stället för att skapa en helt ny commit.

## Tips

- Använd `git show --stat HEAD` för att kontrollera vad den senaste commiten innehåller.
- Kontrollera noggrant vilken fil som ska tas bort.
- `git commit --amend --no-edit` uppdaterar den senaste commiten utan att ändra commit-meddelandet.
- Kontrollera med `git status` när du är klar.
Ändringarna finns bara i arbetskatalogen och har ännu inte blivit committade.

Git kan därför återställa filen till den senaste committade versionen och ta bort de lokala ändringarna.

## Tips

- Använd `git status` för att se vilka filer som har ändrats.
- Använd `git restore <filnamn>` för att ångra ändringar i en specifik fil.
- Om flera filer ska återställas kan du ange flera filnamn.
- Kontrollera med `git status` att ändringarna är borta.
Git sparar projektets historik i commits.

Genom att välja en tidigare commit kan du återställa projektet till exakt det läge som fanns när den commiten skapades.

## Tips

- Använd `git log --oneline` för att hitta rätt commit.
- Kontrollera commit-id noggrant innan du återställer.
- `git reset --hard <commit-id>` återställer både historiken och filerna till den valda commiten.
- Kontrollera med `git status` när du är klar.
