# KanMind Frontend Project

![KanMind Logo](assets/icons/logo_icon.svg)

Dieses Projekt ist ein einfaches Frontend, das mit **Vanilla JavaScript** (reines JavaScript ohne Frameworks) erstellt wurde. Es wurde speziell entwickelt, um Schülern der **Developer Akademie** mit Backend-Erfahrung den Einstieg in kleinere Frontend-Anpassungen zu erleichtern.

---

## Voraussetzungen

Lege beide Repositories als Geschwisterordner in einem gemeinsamen
übergeordneten Ordner ab:

    mkdir KanMind
    cd KanMind
    git clone https://github.com/VitaliBanmann/Kan-Mind-Backend.git
    git clone https://github.com/VitaliBanmann/Kan-Mind-Frontend.git

- Visual Studio Code mit der **Live Server**-Erweiterung oder eine ähnliche Möglichkeit, die `index.html` auf oberster Ebene lokal im Browser zu starten.

---

## Nutzung

1. Richte das Backend im Ordner `Kan-Mind-Backend` nach dessen README ein.
2. Starte dort das Backend mit `python manage.py runserver`.
3. Öffne den Ordner `Kan-Mind-Frontend` in **Visual Studio Code**.
4. Rechtsklicke auf `index.html` und wähle **Open with Live Server**.

Das Frontend verwendet standardmäßig `http://127.0.0.1:8000/api/`. Passe
`shared/js/config.js` an, wenn dein Backend unter einer anderen Adresse läuft.

---

## Ziel des Projekts

Dieses Frontend wurde bewusst mit **Vanilla JavaScript** erstellt, um die folgenden Ziele zu erreichen:

- **Einfacher Einstieg**: Durch den Verzicht auf Frameworks wie React oder Angular bleibt der Code leicht verständlich und nachvollziehbar auch bei wenig Frontend-Erfahrung.
- **Lernen durch Anpassung**: Schüler können den Code anpassen, um kleine Änderungen vorzunehmen und Frontend-Konzepte besser zu verstehen.
- **Backend-Erweiterung**: Das Projekt lässt sich einfach an das bestehende Django-Backend `KanMind` anbinden.

---

## Hinweis

Dieses Projekt ist **ausschließlich für Schüler der Developer Akademie** gedacht und nicht zur freien Nutzung oder Weitergabe freigegeben.

---
