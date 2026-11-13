# video-ads

Een skill voor Claude die video-ads maakt in jouw vaste stijl, via je videotool.

## Wat het doet
Zonder koppeling schrijft Claude alleen tekst en doe jij de rest met de hand. Met deze skill:

1. kijkt Claude eerst of je videotool gekoppeld is (`/mcp`);
2. vraagt hij kort naar product, doelgroep, hoek en formaat;
3. houdt hij zich aan jouw stijl, die je één keer invult (lengte, opening, beeld, tekst, stem, einde);
4. maakt hij hooks, een script met tijden, een shotlijst en de opdracht voor je videotool;
5. stuurt hij de opdracht naar de tool als die gekoppeld is, en anders krijg je alles om zelf in te plakken.

## Installeren in 3 stappen
1. Download of clone deze map.
2. Zet de map `video-ads` in `.claude/skills/` van je project (of `~/.claude/skills/`) en vul in `SKILL.md` bij stap 2 jouw stijl in.
3. Koppel je videotool (typ `/mcp` in Claude Code of vraag "Installeer de koppeling voor mijn videotool") en typ daarna `/video-ads`.

## Wat erin zit
- `video-ads/SKILL.md`: de skill zelf.
  - Check van de koppeling.
  - Jouw stijl, één keer ingevuld.
  - Hooks, script, shotlijst en de opdracht voor de tool.
  - Regels: één ad per keer, geen verzonnen resultaten.

## Waar het op leunt
- Anthropic, documentatie van Claude Code: skills en MCP.
- Meta, richtlijnen voor creatives: verticaal, ondertiteling, de boodschap vooraan.
- Onze eigen regels: kort, Nederlands, alleen echte getallen.

Licentie: MIT.
