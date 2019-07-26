# dinero-pdf
Send PDF til dinero med AppleScript workflow på Mac OS (med Microsoft Outlook)

![Eksempel](https://github.com/larsbaunwall/dinero-pdf/raw/master/img/example.png)

# Sådan kommer du i gang
1. Klon repositoriet og åbn pakken `./Send til Dinero.workflow` i en editor, fx. Visual Studio Code. Du kan også åbne og redigere pakken i Automator ved at højre-klikke og vælge "Åbn i Automator"
2. Indsæt forwarding-adressen i variablen [`mail_adr`](https://github.com/larsbaunwall/dinero-pdf/blob/3ceef1b58926152f2a7c6bebc09bd295a3491ec7/Send%20til%20Dinero.workflow/Contents/document.wflow#L60), som du finder i filen `./Contents/document.wflow` i workflow-pakken.

# Installation
For at installere udvidelsen åbner du blot `./Send til Dinero.workflow` i Automator (uden højre-klik), som installerer udvidelsen automatisk for dig.

Du kan også installere udvidelsen manuelt ved blot at kopiere filen ind i mappen `~/Library/PDF Services`

# Forslag eller kommentarer?

Bare opret et issue eller send mig en pull-request med dit forslag :)
