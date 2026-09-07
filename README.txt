Hana Trasy – instalovatelná PWA

Obsah:
- index.html – aplikace
- manifest.webmanifest – nastavení instalace
- sw.js – offline cache

Důležité:
- Data klientů a plány se ukládají lokálně v zařízení přes localStorage.
- Fotografie se po OCR neukládají do aplikace.
- OCR používá Tesseract.js z internetu, takže první načtení OCR vyžaduje připojení.
- Skutečná optimalizace trasy podle silnic a času jízdy zatím není napojena na mapové API.
- Pro instalaci jako PWA musí být soubory nasazené na HTTPS webu.
