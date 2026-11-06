# Markdown: rychlý tahák pro BUM

V [Markdownvieweru](https://markdownviewer.org/) vlevo píšete, vpravo vidíte výsledek. Mezi značkou a textem nadpisu či seznamu patří mezera. Prázdný řádek odděluje odstavce.

| Název | Doslovný zápis | Poznámka |
| :--- | :--- | :--- |
| Hlavní nadpis | `# Název materiálu` | Další úrovně: `##` a `###` |
| Tučné | `**Důležité**` |  |
| Kurzíva | `*volitelně*` |  |
| Odrážka | `- první položka` | Každý bod na novém řádku |
| Číslovaný seznam | `1. první krok` | Každý bod na novém řádku |
| Odkaz | `[Název stránky](https://example.org)` |  |
| Obrázek | `![Popis obrázku](https://example.org/obrazek.jpg)` | Obrázek musí být jako odkaz |
| Vzorec v řádku | `$E = mc^2$` | |
| Blok vzorců | `$$E = mc^2$$` |  |
| Citace | `> Cizí myšlenka` |  |
| Seznam úkolů | `- [ ] Hotovo?` |`- [x] Hotovo` |
| Přeškrtnutí | `~~původní~~` |  |
| Program / kód | `` `<h1>Nadpis</h1>` `` | Zpětný apostrof: `AltGr + 7`|
| Čára | `---` |  |



**Mezera po značce + prázdný řádek mezi odstavci = čitelný Markdown.**

## Tabulka a zarovnání

```markdown
| Pomůcka | Počet | Stav |
| :--- | ---: | :---: |
| Pravítko | 1 | připraveno |
| Papír | 2 | doplnit |
```

`:---` vlevo · `:---:` na střed · `---:` vpravo

Zarovnání platí pro celý sloupec, ne pro jednotlivou buňku. Běžný odstavec nemá v základním Markdownu značku pro zarovnání na střed.

## Obrázky a vzorce v praxi

```markdown
![BUM](https://i.imgur.com/v5wOGi1.png)

Rychlost: $v = \frac{s}{t}$.

$$
E_k = \frac{1}{2}mv^2
$$
```

Poznámka: místní obrázek se při přenosu mezi aplikacemi nemusí přenést; zkontrolujte náhled. Vzorce nejsou univerzální součástí Markdownu, služby je podporují různě.

**`.md` = upravitelný zdroj; PDF = hotový výstup.**

Dokumenty Google umějí `.md` otevřít či vložit jako formátovaný text, ale výsledek tabulek a vzorců kontrolujte.

- [Nápověda ke Markdownu](https://www.markdownguide.org/cheat-sheet/)
- [Pište v Markdownvieweru](https://markdownviewer.org/)
- [Převod do stylovaného PDF](https://markdownviewer.org/md-to-pdf)

---

*Tento tahák vytvořila AI! Jindřich Zdráhal u toho jenom zavazel, zkontroloval to a pak se pod to podepsal 😉*  
[www.sskola.cz](https://www.sskola.cz)
