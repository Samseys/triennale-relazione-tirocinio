# Sentinel: Sviluppo di un Modulo di Gestione Conti con Architettura Event-Driven e Frontend Angular

Questa repository contiene la relazione di tirocinio svolto presso Resi Informatica tra il 1 febbraio 2024 e il 31 maggio 2024.

Il tirocinio è stato completato come parte del percorso di Laurea Triennale in Informatica e e ha fornito un'opportunità per applicare le competenze tecniche acquisite durante gli studi in un ambiente aziendale.

## Setup dell'ambiente per VSCode:

- Crea una cartella dove inserire tutti gli eseguibili, per esempio:

  ```
  C:\tectonic
  ```

- Scarica l'eseguibile di tectonic utilizzando questi comandi
  da PowerShell:

  ```
  [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072

  iex ((New-Object System.Net.WebClient).DownloadString('https://drop-ps1.fullyjustified.net'))
  ```

- Scarica l'ultima versione di tex-fmt:

  ```
  https://github.com/WGUNDERWOOD/tex-fmt/releases/
  ```

- Infine, scarica la versione di biber corrispondente alla versione di biblatex utilizzata (in questo momento, tectonic installa la versione 2.17):

  ```
  https://sourceforge.net/projects/biblatex-biber/files/biblatex-biber/2.17/binaries/Windows/biber-MSWIN64.zip/download
  ```

- Aggiungi la cartella creata inizialmente al PATH.
