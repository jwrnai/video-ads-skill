---
name: video-ads
description: Maakt video-ads in jouw vaste stijl via een gekoppelde videotool (MCP of API). Geef een product, een doelgroep en een hoek; je krijgt een script, een shotlijst en de opdracht voor je videotool, en Claude maakt de video als de koppeling er is. Gebruik bij "video-ads", "maak een video-ad", "video voor mijn ads" of "maak content met mijn videotool".
---

# Video-ads

Jij beschrijft één keer hoe jouw video's eruitzien. Daarna maakt Claude elke nieuwe ad in die stijl, en stuurt hij hem naar je videotool als die gekoppeld is. Zonder koppeling krijg je alles klaar om zelf in te plakken.

## Stap 0: check de koppeling
Kijk of er een koppeling met een videotool is (in Claude Code: `/mcp`). Is er geen, zeg dat in één zin en lever aan het eind alles als tekst om in te plakken. Verzin nooit dat een video gemaakt is.

## Stap 1: vraag wat je nodig hebt
In één bericht, als het nog niet gegeven is: het product, voor wie, de ene belofte of hoek, en het formaat (9:16 voor reels en stories, 4:5 voor de feed).

## Stap 2: jouw stijl (vul dit één keer in)
Pas dit blok aan voordat je de skill gebruikt. Claude houdt zich er altijd aan.
- **Lengte:** bijvoorbeeld 15 tot 30 seconden.
- **Opening:** de eerste 2 seconden laten het probleem zien, geen logo.
- **Beeld:** echt product in beeld, rustige camera, daglicht.
- **Tekst in beeld:** maximaal 6 woorden per kaart, groot, ondertiteling altijd aan.
- **Stem:** spreektaal, je-vorm, geen reclamezinnen.
- **Einde:** één duidelijke actie, bijvoorbeeld "Bekijk de site".
- **Nooit:** prijzen in beeld, beloftes die je niet kunt waarmaken.

## Stap 3: maak de ad
1. **Hook:** 3 opties voor de eerste 2 seconden, kies de sterkste en zeg waarom.
2. **Script:** de gesproken tekst, per regel met de tijd erbij.
3. **Shotlijst:** per shot wat je ziet, hoe lang, en welke tekst in beeld staat.
4. **Opdracht voor de videotool:** precies wat de tool nodig heeft (prompt, formaat, lengte, beelden).
5. **Maken:** is de koppeling er, stuur de opdracht naar de tool en geef de link of het bestand terug. Anders lever je stap 1 tot en met 4 als tekst.

## Regels
- Eén ad per keer, tenzij de gebruiker om varianten vraagt. Varianten verschillen alleen in de hook.
- Nederlands, kort, geen em-dashes.
- Geen verzonnen resultaten of cijfers in de ad.

## Waar dit op leunt
- Anthropic, documentatie van Claude Code: skills (`SKILL.md` met name en description) en MCP-koppelingen.
- Meta, richtlijnen voor creatives: verticaal formaat, ondertiteling, de boodschap in de eerste seconden.
- Onze eigen regels: kort, Nederlands, alleen echte getallen.
