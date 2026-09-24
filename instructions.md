# Mac-Einrichtung – Checkliste

Stand: 24. September 2026

## 1. Grundlage und Bestandsaufnahme

- [ ] Freien Speicherplatz und macOS-/CPU-Version prüfen
- [ ] Vorhandene Programme und Kommandozeilenwerkzeuge erfassen
- [ ] Homebrew installieren und `brew doctor` prüfen
- [ ] Xcode Command Line Tools installieren

## 2. Allgemeine Programme

- [ ] Visual Studio Code installieren
- [ ] WhatsApp Desktop installieren
- [ ] Signal Desktop installieren
- [ ] Mozilla Thunderbird installieren
- [ ] Spotify installieren
- [ ] Zoom installieren
- [ ] Audacity installieren
- [ ] Arduino IDE installieren
- [ ] Bambu Studio installieren
- [ ] KiCad installieren
- [ ] EasyEDA Pro installieren
- [ ] PreForm installieren

## 3. Microsoft Office

- [ ] Microsoft Word installieren
- [ ] Microsoft Excel installieren
- [ ] Microsoft PowerPoint installieren
- [ ] Microsoft Teams installieren
- [ ] Office-Programme starten und Installationszustand prüfen
- [ ] Falls nötig: Microsoft-Anmeldung/Lizenzaktivierung durch den Benutzer

## 4. Terminal und Zsh

- [x] Zsh vorhanden (`/bin/zsh`)
- [x] Zsh ist die Login-Shell
- [ ] Oh My Zsh bzw. passende Prompt-Basis installieren
- [ ] Powerline-kompatible Nerd Font installieren
- [ ] Solarized-Dark-Farbschema für Terminal konfigurieren
- [ ] Powerline-Prompt mit breiten Pfeilsegmenten konfigurieren
- [ ] Emojis im Prompt deaktivieren
- [ ] Git-, Ordner- und Statussegmente prüfen
- [ ] Darstellung in einem neuen Terminalfenster prüfen

## 5. Nordic, J-Link und OpenEarable 2

- [ ] nRF Connect for Desktop installieren
- [ ] nRF Connect for VS Code-Erweiterungen installieren
- [ ] nRF Connect SDK 3.0.1 installieren
- [ ] nRF Toolchain 3.0.1 installieren
- [ ] SEGGER J-Link Software installieren
- [ ] `JLinkExe` und weitere J-Link-Werkzeuge auf der Kommandozeile prüfen
- [ ] OpenEarable-2-Repository herunterladen oder vorhandenes Repository finden
- [ ] OpenEarable-2-Repository in das Benutzerverzeichnis von `tobi` klonen
- [ ] Abhängigkeiten/Submodule initialisieren
- [ ] Board `openearable_v2/nrf5340/cpuapp` mit sauberem Build kompilieren
- [ ] Optionalen FOTA-Build kompilieren
- [ ] Build-Artefakte und Exit-Status dokumentieren
- [ ] Falls Hardware angeschlossen: J-Link-Geräteerkennung prüfen

## 6. Flutter, Xcode und Android

- [ ] Flutter SDK installieren
- [ ] Flutter dauerhaft in `PATH` aufnehmen
- [ ] Xcode installieren
- [ ] Xcode-Lizenz akzeptieren und Ersteinrichtung ausführen
- [ ] iOS Simulator/benötigte Plattformen installieren
- [ ] CocoaPods installieren
- [ ] Android Studio installieren
- [ ] Android SDK, Platform Tools und Command-line Tools installieren
- [ ] Android-Lizenzen akzeptieren
- [ ] `flutter doctor -v` ausführen
- [ ] Alle von `flutter doctor` gemeldeten Fehler beheben
- [ ] Abschließenden fehlerfreien `flutter doctor -v`-Lauf dokumentieren
- [ ] OpenEarable-`app`-Repository (OpenWearables) in das Benutzerverzeichnis von `tobi` klonen
- [ ] App-Abhängigkeiten installieren
- [ ] Android-App erfolgreich kompilieren
- [ ] iOS-App erfolgreich kompilieren
- [ ] Android- und iOS-Build-Artefakte dokumentieren

## 7. Trackpad

- [ ] Aktuelle Scrollrichtung ermitteln
- [ ] Scrollrichtung umkehren
- [ ] Einstellung verifizieren

## 8. Python und Jupyter

- [ ] Aktuelles Python 3 installieren
- [ ] `python3` in einer neuen Zsh-Sitzung prüfen
- [ ] `pip3` und `pip` verfügbar machen und prüfen
- [ ] JupyterLab und Jupyter Notebook isoliert installieren
- [ ] Python-Kernel registrieren
- [ ] Jupyter mit einem Test-Notebook starten und Kernel-Ausführung prüfen

## 9. Git und SSH

- [ ] Vorhandene Git- und SSH-Konfiguration prüfen
- [ ] Git-Benutzer für `TobiasRoeddiger` konfigurieren
- [ ] Dedizierten Ed25519-SSH-Schlüssel erstellen oder passenden vorhandenen Schlüssel verwenden
- [ ] GitHub-Hostschlüssel sicher hinterlegen
- [ ] Öffentlichen Schlüssel beim GitHub-Konto `TobiasRoeddiger` hinzufügen
- [ ] SSH-Agent und macOS-Schlüsselbund konfigurieren
- [ ] Zugriff mit `ssh -T git@github.com` prüfen
- [ ] Git-Zugriff über SSH abschließend testen

## 10. Abschlussprüfung

- [ ] Alle GUI-Programme unter `/Applications` prüfen
- [ ] Alle geforderten CLI-Befehle in einer neuen Zsh-Sitzung prüfen
- [ ] Offene Anmeldungen, Lizenzen oder Benutzeraktionen dokumentieren
- [ ] Abschlussbericht mit Versionen und Testergebnissen erstellen

## Reihenfolge

1. Bestandsaufnahme, Homebrew und Apple-Entwicklerwerkzeuge
2. Allgemeine Programme und Office parallel installieren
3. Terminal-Design konfigurieren
4. Nordic SDK, J-Link und OpenEarable-Build einrichten
5. Xcode, Android Studio und Flutter vollständig einrichten
6. Python, pip und Jupyter installieren und testen
7. Git-/SSH-Zugriff für `TobiasRoeddiger` konfigurieren und testen
8. Trackpad-Einstellung ändern
9. Alles einzeln prüfen und Abschlussbericht erstellen
