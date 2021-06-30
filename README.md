# Magyar billentyűzet JSON elrendezés

Ez a gyűjtemény a Magyar billentyűzet JSON formátumú elrendezésének tárolására lett létrehozva.

Az ág azért lett létrehozva, mert a HAK5 csapata magyar nyelvű billentyűzetre nem tervezett külön elrendezést, ami fontos a Ducky Scriptünk kódolásánál.

Ha esetleg egy másik billentyűzet elrendezését használjuk a kódolásnál, akkor ha leakarjuk futtatni egy eszközön a USB Rubber Ducky Micro SD kártyáján található scriptünket, akkor nem ugyanazt az eredményt kapjuk sok esetben.

Pl.: Ha az Egyesült Államokban használt billentyűzet elrendezésével (us.json a HAK5 Gitjén található) kódoljuk a scriptünket, akkor ha például egy / jelet akarunk beírni, akkor mivel a / jel az Egyesült Államokbeli billentyűzeteken a Magyar billentyűzeten a - jel helyén található (lásd: https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/KB_United_States-NoAltGr.svg/400px-KB_United_States-NoAltGr.svg.png), így egy - jelet fog írni a Rubber Ducky.

Ez a JSON fájl a HAK5 eredeti Ducky Encoder-hez használható, ami a https://docs.hak5.org/hc/en-us/articles/360010471234-Writing-your-first-USB-Rubber-Ducky-Payload címen belül, a tölthető le a JS Ducky Encoder bekezdésben. Más kódoló alkalmazások esetében más lehet az elrendezés típusa!

A JSON fájl tartalmazza a bal Shift mellett található í betűre használt gombot is, ha nincs ilyen a billentyűzeteden, vagy a céleszköz billentyűzetén, akkor sincsen gond, mert a kis í betűt a Shift + j-vel, illetve a nagyot a Shift + i kulcs kombinációval szintúgy el lehet érni.

Ha átszeretnéd alakítani a billentyűzet elrendezést, akkor ahhoz megtalálod a megfelelő dokumentumok linkjét a JSON fájlban.
