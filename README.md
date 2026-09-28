# flix1323.github.io

Statische Seite für geteilte PersOS-Inhalte. Kein Backend.

- `.well-known/apple-app-site-association` ordnet Links unter `/s/` der App zu (Universal Links).
- `s/index.html` ist die Hinweisseite für alle ohne App. Der geteilte Inhalt steht im `#`-Teil des Links; Browser senden ihn nie an den Server, und die Seite liest ihn nicht.
- `.nojekyll` sorgt dafür, dass GitHub Pages den Ordner `.well-known` ausliefert.

Quelle: `docs/share-site/` im PersOS-Repo. **Repo und Kontoname nie umbenennen:** jeder geteilte Link enthält `flix1323.github.io`.
