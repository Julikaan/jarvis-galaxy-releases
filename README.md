# JARVIS Galaxy

Last ned **[den lille installatøren (under 25 MB)](https://github.com/Julikaan/jarvis-galaxy-releases/releases/download/v0.5.0/JARVIS-Galaxy-Web-Setup-0.5.0-Windows.exe)** og dobbeltklikk den. Den henter hele Windows-pakken, kontrollerer størrelse, SHA-256 og produktversjon og åpner installasjonsveiviseren. Etter installasjon åpner du JARVIS fra Start-menyen.

Vil du installere uten en ekstra nedlasting, velg **[hele Windows-pakken](https://github.com/Julikaan/jarvis-galaxy-releases/releases/download/v0.5.0/JARVIS-Galaxy-Setup-0.5.0-Windows.exe)**.

**Nytt i 0.5.0: Prosjektarbeid for GPT-6.1 Sol / ultra og Claude Code.** Velg mappe, klient og oppdrag, og trykk Start oppdrag. Agentene kan lese/endre prosjektfiler, bruke kommandoer og installerte skills, plugins, hooks og konfigurerte MCP-forbindelser. Følg tekst og verktøyhendelser, godkjenn/avvis konkrete ekstra forespørsler eller stopp oppdraget. Ett oppdrag om gangen; de siste 20 loggene lagres lokalt. Start gir tillatelse til vanlige prosjektendringer. Native Claude på Windows har ingen OS-sandbox; godkjente kommandoer/utvidelser kan påvirke filer og tjenester utenfor prosjektet, og oppstartshooks/MCP kan starte prosesser ved klientinitialisering.

JARVIS Galaxy har en original 3D-galakse med solen som leder, jorden og Jupiter: første klikk zoomer, andre klikk åpner funksjonene. Chat, oppgavetavle, prosjektbokmerker, Vault, fokusklokke og offentlig GitHub-/HTTPS-lesing følger med. Vanlig chat bruker fortsatt avgrensede samtale-/planleggingsbroer; faktisk coding startes fra Prosjektarbeid eller funksjonsknappene på solen og Jupiter.

For Windows 10/11 x64. Den lille installatøren bruker .NET Framework 4.8 og trenger internett. Fullpakken inneholder programmets runtime; Node.js og separat nettleser er ikke nødvendig. Coding-klienter må installeres og logges inn separat på hver PC. Sol trenger en komplett Codex-klient som støtter GPT-6.1 Sol og ultra. Lokalmodus trenger ingen modellkonto. Oppdrag bruker kontoens kapasitet; JARVIS kan ikke utløse en bruksreset. Tale er fortsatt planlagt.

155 automatiske tester, produksjonsbygg, native oppstart og ekte isolerte fil-/kommandoprøver for begge coding-agentene er kontrollert. Hver tredjepartsutvidelse/MCP-tjeneste er ikke særskilt testet. Dette er en usignert utviklingsutgave; førstegangsinstallasjon på en ny PC og avinstallasjon er ikke testet.

Ingen API-nøkler, kontoinnlogging, private prosjektfiler eller brukerdata følger med. Dette distribusjonsrepoet inneholder bare veiledning og installasjonsfiler. SHA256.txt gir kontrollsummene for begge EXE-filene.
