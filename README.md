# Disclaimer
This is a modpack for friends. These are not my mods. If you own a mod in here and you have a problem with it, please contact me on filbuild.filbuild@gmail.com or write a github issue.  
All used Mods are listed below, support their creators.  
I checked all licenses that are referenced or if it is a custom license I checked github and modrinth. I did not find a license that disallows what I am doing here (I can make mistakes too).  
If you want to use this modpack, feel free to do it, just don't expect any support.  
DO NOT MONETIZE THIS IN ANY WAY!

# License (MIT)
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Info
Version: 1.20.1 Loader: Fabric  
This document will be (mostly) german from now  
(Weitere Clientside-Mods können dazu installiert werden, wenn gewollt)

# How to install
## Normaler Weg
(So kleinschrittig wie möglich)
- Installiere Fabric 1.20.1 (Installer: https://fabricmc.net/use/installer/)
- Wähle Minecraft-Version 1.20.1 aus
- (Überprüfe den Pfad von .minecraft)
- Installiere
- Starte Minecraft launcher
- Wähle das Fabric-Profil aus
- Starte Minecraft
- Nach vollständigem Starten, schließe Minecraft
- Lade dir die Zip von Github herunter (Code -> Download ZIP) (https://github.com/FilBuild/MinecraftModpackVanillaPlus)
- Gehe in den .minecraft Ordner
- Schiebe alle die Mods aus der ZIP/mods in .minecraft/mods
- Überschreibe die options.txt in .minecraft mit der ZIP/config/options.txt
- Füge den Inhalt ZIP/config/config Ordner in .minecraft/config Ordner ein (notfalls erstelle den config Ordner in .minecraft)
- Starte Minecraft
- Konfiguriere nach eigenem Verlangen
## Prism/MultiMC
- Erstelle neue 1.20.1 Instanz
- Füge Fabric hinzu
- Öffne den .minecraft Ordner von der Instanz
- Führe die Schritte wie oben ab "Starte Minecraft" aus
## Eventuelle "Updates"
Ladet die Update Zip (aus dem UpdateOrdner, welcher dann erstellt wird) runter und führt dieselben Schritte wie oben auf Basis der UpdateZips durch (natürlich ohne Minecraft neu zu installieren, sondern nur die Schritte ab Herunterladen der ZIP).

# Features
- Villager Verbesserungen / Vereinfachungen
- deutliche Performance Optimierungen (mehr FPS)
- Möglichkeit für Shader
- Mehr Informationen Ingame (zu Blöcken etc.)
- Freecam
- Minimap und Wegpunkte (Waypoints)
- Visuelle Verbesserungen
- Bessere Storage (Lager) Optionen
- Möglichkeiten Kisten (und teilweise Mobs) zu bewegen ohne diese abzubauen
- Simplere Chunkloader
- Mobile Betten, welche keinen Spawnpunkt setzen
- Hängematten mit welchen man durch den Tag schlafen kann
- Doppeltüren
- Monster, welche das Schlafen verhindern, werden markiert
- Spieler droppen Köpfe
- Creeper machen keinen Block-/Itemschaden
- Viele neue Blockvariationen (Deko)
- Neue Dekoblöcke
- Minecraftähnliche Möbel
- Armorstandeditor
- Serveradmintools

# Keybindings (Tastenbelegungen)
Gibt an wie die Keybindings von der options.txt festgelegt wurden
### Vanilla
WASD - Bewegen  
E - Inventar  
Q - Droppen  
Shift - Sneaken  
Strg - Sprinten  
Space - Springen  
T - Chat  
   
### Minimap
P - Wegpunkt setzen  
Y - Map vergrößern  
X - WegpunktOverlay verstecken  
U - Wegpunktliste  
M - Weltkarte  
  
### Rüstungsmod
J - Rüstungversteckmod an/aus  
H - Rüstungseinstellungen
  
### Lagermods
Mausrad drücken - Sortieren (In Inventaren)  
G - "Storageterminal"  

### Sonstiges
C - Chunkloader anzeigen  
V - Freecam  
R - Zoomen  
B - Backpack (Rucksack)  
O - Shader  


# Mod-list
## Villager
Vereinfachung/Verbesserung der Villager
### Our Villager Discounts
https://modrinth.com/mod/our-villager-discounts  
Jeder Spieler hat dieselben (nur positiven) Villager Discounts.
### Villager in a Bucket
https://modrinth.com/mod/villager-in-a-bucket  
Villager können wie Fische mit einem Eimer aufgehoben werden.  
Somit können diese einfacher bewegt oder gelagert werden.  
(Die Trades etc. bleiben dabei erhalten)
### Villager Converting
https://modrinth.com/mod/villager-converting  
Villager werden zu 100% zu Zombie Villager, egal welche Schwierigkeit
### Retraining
https://modrinth.com/mod/retraining  
Die Trades der Villager können mit einem Klick "gererollt" werden.  
Dies geht nur solange die Trades noch nicht gelocked sind, heißt noch keine Trades ausgeführt worden


## Performance
Mods welche die Performance von Minecraft verbessern
### Cull Less Leaves
https://modrinth.com/mod/cull-less-leaves  
Rendert Blätter durchsichtiger, welches die Performance verbessert
### Dynamic FPS
https://modrinth.com/mod/dynamic-fps  
Limitiert die FPS auf eine geringe Zahl, wenn das Spiel im Hintergrund läuft.  
Somit kann die Performance besser laufen
### Ferrite Core
https://modrinth.com/mod/ferrite-core  
RAM bzw. Memory improvements / leak fixes
### Enhanced Block Entities
https://modrinth.com/mod/ebe  
Rendert Kisten etc. besser
### Sodium
https://modrinth.com/mod/sodium  
Quasi das bessere Optifine, verbessert die FPS allgemein
### Better Sodium Video Setting
https://modrinth.com/mod/better-sodium-video-settings-button  
Bewegt die Sodiumsettings in ein extra Menu, damit das alte Menu erhalten bleibt  
HINWEIS: Version in Modrinth fehlerhaft, gefixte Version im "Modpack" (PR bereits gestellt)
### Indium
https://modrinth.com/mod/indium  
Bessere Unterstützung für Sodium (mehr Kompabilität)
### Lithium
https://modrinth.com/mod/lithium  
Verbesserungen der Gamelogic (ohne diese zu verändern)
### Iris
https://modrinth.com/mod/iris  
Möglichkeiten zu Shadern und Verbesserungen beim Rendern
### Lazy DFU
https://modrinth.com/mod/lazydfu  
Schnelleres starten (evtl. in neueren Version überflüssig)
### Immediatly Fast
https://modrinth.com/mod/immediatelyfast  
Allgemeine Verbesserungen der FPS

## Qol (Quality of Life)
Verbesserung des Spielerlebnisses, ohne dabei das Spiel groß zu verändern
### Just Enough Items
https://modrinth.com/mod/jei  
Liste an Items mit Möglichkeit die Crafting-Recipes dazu anzuzeigen
### JEI Addon Resources
https://modrinth.com/mod/just-enough-resources-jer  
Mehr Rezepte für JEI (ore, loot, etc.)
### JEI Addon Villager
https://modrinth.com/mod/just-enough-professions-jep  
Mehr Rezepte für JEI (villager)
### Capes
https://modrinth.com/mod/capes  
Lässt Labymod und optifine capes anzeigen
### Mod Menu
https://modrinth.com/mod/modmenu  
Einfache Ingame Auflistung von Mods und Konfiguration
### Controlling
https://modrinth.com/mod/controlling  
Bessere Einstellung von Tastenbelegungen
### Mouse Tweaks
https://modrinth.com/mod/mouse-tweaks  
Inventarmanagement via Maus
### Mouse Wheelie
https://modrinth.com/mod/mouse-wheelie  
Inventarmanagement via Maus + Sortieren
### Zoomify
https://modrinth.com/mod/zoomify  
Möglichkeit zu zoomen
### Lighty
https://modrinth.com/mod/lighty  
Möglichkeit anzuzeigen wo Mobs spawnen können
### Boosted Brightness
https://modrinth.com/mod/boosted-brightness  
Erlaubt die Helligkeit über 100% zu stellen (FullBright)
### Boat Item View
https://modrinth.com/mod/boat-item-view  
Erlaubt es Items in der Hand zu behalten während man Boot fährt (Treasure Maps)
### Borderless Mining
https://modrinth.com/mod/borderless-mining  
Erlaubt Borderless Fullscreen in Minecraft
### Shulker Box Tooltip
https://modrinth.com/mod/shulkerboxtooltip  
Erlaubt das gucken in Shulkerboxen (o.Ä.) bereits vom Inventar aus
### What Are They Up To
https://modrinth.com/mod/what-are-they-up-to  
Zeigt Spieler wenn sie schreiben oder in einen Inventar sind
### What the hell is that (WTHIT)
https://modrinth.com/mod/wthit  
Zeigt an welchen Block man anguckt und zusätzliche Informationen dazu  
Zeigt HP der Mobs und weitere Informationen (Damage Indicator)
### Xaero's Minimap
https://modrinth.com/mod/xaeros-minimap  
Minimap mit Waypoints
### Xaero's World Map
https://modrinth.com/mod/xaeros-world-map  
Weltkarte verbunden mit gesetzten Waypoints etc.
### AppleSkin
https://modrinth.com/mod/appleskin  
Gibt mehr Informationen zu Essen (Hungerbalken und Sättigung)
### Chat Heads
https://modrinth.com/mod/chat-heads  
Zeigt die Spielerköpfe bei Chatnachrichten
### More Chat History
https://modrinth.com/mod/morechathistory  
Längere Chat-Historie (mehr gespeicherte Nachrichten)
### Enchantment Descriptions
https://modrinth.com/mod/enchantment-descriptions  
Enchantment (Verzauberung) beschreibungen
### Advancement Info
https://modrinth.com/mod/advancementinfo  
Infos über den aktuellen Advancements (Erfolge) stand (Welche Biome fehlen etc.)
### Better Mount HUD
https://modrinth.com/mod/better-mount-hud  
Zeigt HP und Essen während man ein Pferd reitet / Boot fährt etc.
### Freecam
https://modrinth.com/mod/freecam  
Ermöglicht eine Art spectator sicht, um zum Beispiel Gebautes zu betrachten
### ClearDespawn
https://modrinth.com/mod/cleardespawn  
Lässt Items blinken kurz bevor sie despawnen
### Show Me Your Skin!
https://modrinth.com/mod/show-me-your-skin  
Erlaubt das Verstecken von Rüstung
### Tool Stats
https://modrinth.com/mod/tool-stats  
Gibt mehr Informationen zu Tools (Abbaugeschwindigkeit etc.)
### Not Enough Crashes
https://modrinth.com/mod/notenoughcrashes  
Versucht statt das Spiel komplett zu crashen einem zum Hauptmenu zurück zu leiten
### Keep Head Names
https://modrinth.com/datapack/keepheadnames  
Erlaubt das Speichern von Namen von Köpfen auch wenn sie platziert wurden sind

## Storage
### Carry On
https://modrinth.com/mod/carry-on  
Erlaubt es Kisten (und teilweise Mobs) aufzuheben und so zu bewegen ohne diese abzubauen
### Iron Chest
https://modrinth.com/mod/cyberanner-ironchest  
Kisten aus verschiedenen Materialien, welche dann mehr Platz haben
### Extended Storage Drawers
https://modrinth.com/mod/extended-drawers  
Ein Block welcher große Mengen von einem bestimmten Block speichern kann
### Toms simple storage
https://modrinth.com/mod/toms-storage  
Ein einfaches automatisches Storage system, welches einem "ME-System" ähnelt
### Inmis (Backpack)
https://modrinth.com/mod/inmis  
Simple Rucksäcke

## Vanilla+
### Chunkloader 
https://modrinth.com/mod/chunk-loaders  
Möglichkeit einen simpleren Chunkloader (als einen Block) zu bauen
### Comforts
https://modrinth.com/mod/comforts  
Möglichkeit Betten für unterwegs zu bauen, welche dann keinen neuen Spawnpoint setzen  
Erlaubt es den Tag durchzuschlafen (mit Hängematten)
### Double Doors
https://modrinth.com/mod/double-doors  
Verbindet doppelte Türen zu einer
### Monsters in the Closet
https://modrinth.com/mod/monsters-in-the-closet  
Markiert Monster wenn man wegen diesen nicht schlafen kann
### Just Player Heads
https://modrinth.com/mod/just-player-heads  
Spielerköpfe droppen
### Enviromental Creepers
https://modrinth.com/mod/environmental-creepers  
Erlaubt die Einstellung, dass Creeper keinen Block/Item schaden machen, ohne die gamerule zu ändern

## Beautify
### Chisel
https://modrinth.com/mod/chisel-reborn  
Fügt viele Variationen von Vanilla-Blöcken hinzu
### Chipped
https://modrinth.com/mod/chipped  
Fügt viel Dekoblöcke hinzu
### Continuity
https://modrinth.com/mod/continuity  
Fügt Glas zusammen
### Another Furniture
https://modrinth.com/mod/another-furniture  
Fügt Möbel hinzu
### StoneWorks
https://modrinth.com/mod/stoneworks  
Macht die Steinvarianten einheitlich (gibt generell mehr Steinvarianten)
### Handcrafted
https://modrinth.com/mod/handcrafted  
Fügt mehr Dekoblöcke hinzu
### Armor Statues
https://modrinth.com/mod/armor-statues  
Erlaubt das editieren von Armorstands

## Other
Andere Mods, meist fügen die Funktionen hinzu, die nur als Admin wichtig sind
### Chunky
https://modrinth.com/plugin/chunky  
Erlaubt das vorgenerieren von Welten zum Entlasten des Servers
### MixinTrace
https://modrinth.com/mod/mixintrace  
Bessere Fehlermeldungen bei Errors (in der Konsole)

## Dependencies
Mods brauchen ab und zu noch Dependencies (Abhängigkeiten) um zu funktionieren.  
Diese fügen keine weiteren Funktionen hinzu, daher werde ich diese nicht weiter ausführen
- Cloth Config https://modrinth.com/mod/cloth-config
- Fabric API https://modrinth.com/mod/fabric-api
- Pathouli https://modrinth.com/mod/patchouli
- Fabric Language Kotlin https://modrinth.com/mod/fabric-language-kotlin
- Searchables https://modrinth.com/mod/searchables
- Architectury API https://modrinth.com/mod/architectury-api
- Resourceful Lib https://modrinth.com/mod/resourceful-lib
- Puzzles Lib https://modrinth.com/mod/puzzles-lib
- Forge Config API Port https://modrinth.com/mod/forge-config-api-port
- Athena https://modrinth.com/mod/athena-ctm
- SuperMartijn642's Config Lib https://modrinth.com/mod/supermartijn642s-config-lib
- SuperMartijn642's Core Lib https://modrinth.com/mod/supermartijn642s-core-lib
- YetAnotherConfigLib https://modrinth.com/mod/yacl
- CoroUtil https://modrinth.com/mod/coroutil
- bad packets https://modrinth.com/mod/badpackets
- Configured https://modrinth.com/mod/configured
- Bookshelf https://modrinth.com/mod/bookshelf-lib
- CICADA https://modrinth.com/mod/cicada
- Collective https://modrinth.com/mod/collective
- Chassis https://modrinth.com/mod/chassis
- Trinkets https://modrinth.com/mod/trinkets

## Not generally
Nicht generell für jeden sinnvoll
### Distant Horizons
https://modrinth.com/mod/distanthorizons  
Zeigt größere Distanzen der Welt an (auf Entfernung in minderer Qualität)  
Hinweis: (je nach Einstellung) Deutlich schlechtere Performance; Zieht Speicher
### Bobby
https://modrinth.com/mod/bobby  
Zeigt größere Distanzen (als der Server erlaubt) der Welt an, indem Chunks zwischengespeichert werden
Hinweis: (je nach Einstellung) Deutlich schlechtere Performance; Zieht Speicher
### Nvidium
https://modrinth.com/mod/nvidium  
Verbesserung der Performance für NVIDIA-Grafikkarten (16xx, 2xxx, und höher)  
(Automatische Abschaltung) / Nicht sinnvoll bei: Shadern, NICHT Nvidia-Grafikkarten

## Considering
Überlegen ob man das hinzufügen sollte, verändern das Spiel maßgeblicher
### Elytra Slot
https://modrinth.com/mod/elytra-slot  
Fügt einen extra Elytra Slot hinzu, so dass man Elytra und Brustplatte gleichzeitig tragen kann
### Natures Compass
https://modrinth.com/mod/natures-compass  
Fügt einen Kompass hinzu mit welchem man jedes Biome finden kann
### Explorer's Compass
https://modrinth.com/mod/explorers-compass  
Fügt einen Kompass hinzu mit welchem man jede Struktur finden kann