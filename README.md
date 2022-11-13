# 07
• Dokončete switch u metody adaptive_streaming (3x case, podle PathVariable)
• Rozcestník na stránce index pro výběr zdrojů (např: jako tlačítka nebo výběr
přes radio button) => volání přes dashPlayer metodu. Bude obsahovat:
• Lokální MP4 video (například lze získat přes adresu /file)
• Video z URL
• Dash stream z URL
• Lokální Dash stream (cesta /dash/manifest.mpd)
• Lokální HLS stream (cesta /hls/playlist.m3u8) = ve výsledku stream nepůjde spustit
• Metodu a šablonu dashPlayer upravte dle potřeby pro získání cesty k souboru.
Nejlépe přes model a String url jako RequestParam
• Vytvořte stránku (/gallery) a metodu pro získání šablony. Na stránce bude jen
nadpis, že se jedná o galerii a vaše jméno a id (navážeme příště)
• Objekt Movie v balíčku model. Bude obsahovat proměnné File file, String
image_name, String file_name. Konstruktor bude ve
stejném pořadí. Přidejte i patřičné gettery (alt+insert)
• Odkaz na /gallery přidejte jako tlačítko na index
