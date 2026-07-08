# Rotary Healthcare Professionals — website

Službeni statični sajt organizacije (čisti HTML/CSS, bez build koraka).

- **Live:** https://rotaryhealthprofessionals.org
- **Hosting:** Vercel (statični deploy)
- **Struktura:** `index.html` je naslovnica u korijenu, podstranice su zasebne `.html` datoteke, slike u `images/`.
- **Porijeklo:** sadržaj presložen iz izvorne WordPress stranice u ručno pisan statični HTML.

## Razvoj

Uređuj HTML/CSS izravno. Radni tijek:

```bash
git checkout -b naziv-izmjene
# ... izmjene ...
git commit -am "opis"
git push -u origin naziv-izmjene
gh pr create --fill
# merge PR-a → Vercel deploya produkciju
```

`_template.html` je predložak za nove podstranice i namjerno se ne objavljuje (u `.gitignore`).

---
*Zadnja izmjena: 2026-07-08 | Autor: Claude*
