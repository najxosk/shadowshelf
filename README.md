# 📚 ShadowShelf

Terénny skener knižných chrbtov – odfotiš policu a aplikácia rozozná knihy, označí ich podľa zberateľského potenciálu a ponúkne 1-klik overenie ceny na TrhKnih.cz / Bazoš.sk / antikvariátoch.

## ▶️ Otvoriť aplikáciu

**→ https://najxosk.github.io/shadowshelf/**

Funguje na počítači aj na mobile (Chrome). Na prvom použití vlož svoj Gemini API kľúč cez ikonu 🔑 vpravo hore – kľúč sa ukladá len lokálne v tvojom prehliadači a v tejto stránke nie je žiadny.

## Ako to funguje

1. Odfoť policu kníh (alebo klikni **Ukážka** pre test bez fotografovania).
2. Gemini Vision rozozná jednotlivé chrbty kníh a farebne ich zvýrazní:
   - 🟢 zberateľský potenciál
   - 🟡 dobrá likvidita
   - ⚪ bežný titul
3. Klikni na knihu → detail + 1-klik overenie reálnej ceny na trhu.
4. Ulož úlovok do zoznamu a exportuj si ho do CSV.

## Technické

Single-file HTML app (žiadne servery, žiadne inštalácie). Obrázok sa komprimuje v prehliadači na max 1600 px a posiela priamo na Google Gemini API.
