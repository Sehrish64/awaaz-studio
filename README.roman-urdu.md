# Awaaz Studio (Roman Urdu guide)

Free aur open source text-to-speech studio, Gemini API ke liye. Sirf ek HTML file hai: na build, na server. Ye Google ka product nahi hai.

## Kya kar sakti hai
- Ek awaaz ya do awaazon (dialogue) ka mode, 30 Gemini voices
- Style ka box, jaise "slow, dramatic storyteller"
- Lambi script khud chhote hisson mein bant kar jud jati hai
- "Roman Urdu → Urdu script" ka button, taake talaffuz behtar aaye
- Browser mein sun sakte hain aur WAV download kar sakte hain
- Pehle se "Magarmach" wali demo script bhari hui hai, bas Generate dabayein

## Istemal kaise karein
1. https://aistudio.google.com/apikey se free API key banayein.
2. `index.html` kholein (double-click karein ya host karein).
3. Key paste karein, script likhein, **Generate audio** dabayein.

Key sirf aap ke browser mein rehti hai aur sirf Google ko jati hai. Free quota Google tay karta hai aur badal sakta hai.

## Do awaazon ka mode
Do speakers ke naam likhein, phir script yun likhein:
```
Maa: Mera bacha wapas kar do.
Magarmach: Pehle andaza lagao.
```

## GitHub Pages par free host karna
1. Is folder ko GitHub repo mein push karein.
2. Settings → Pages → Source: **GitHub Actions** chunein.
3. `main` branch par push karte hi site live ho jayegi (workflow pehle se shamil hai).

## Dhyan rakhein
- Models abhi preview mein hain, naam badal sakte hain. `index.html` mein model wali list badal dein.
- API key kabhi code ya GitHub mein seedha na likhein.
- Google ka naam ya logo istemal na karein.

MIT License.
