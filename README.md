# ✨ Making Your GitHub Profile Attractive (Fresher's Guide)

*By Alekha Kumar Swain — [@alekhakumarswain](https://github.com/alekhakumarswain)*

Once your README has the basics (see `01-how-to-build-a-github-profile-readme.md`),
these are the polish tricks that turn a plain profile into one people actually
remember.

---

## 1. Use a visitor counter

A small psychological trick — showing traffic makes your profile feel active:

```md
[![](https://visitcount.itsvg.in/api?id=YOUR_USERNAME&icon=5&color=12)](https://visitcount.itsvg.in)
```

---

## 2. Pick one consistent theme across all widgets

Mixing five different color themes across stats/streak/trophy widgets looks messy.
Pick one theme name (`algolia`, `merko`, `blueberry`, `radical`, `discord`, etc.)
and reuse it everywhere so the page feels designed, not assembled:

```md
![](https://github-readme-stats.vercel.app/api?username=YOU&theme=merko)
![](https://github-readme-streak-stats.herokuapp.com/?user=YOU&theme=merko)
![](https://github-readme-activity-graph.vercel.app/graph?username=YOU&theme=merko)
```

---

## 3. Use tables to place widgets side by side

Two summary cards stacked vertically waste space. Put them in an HTML table so
they sit side by side:

```md
<table>
  <tr>
    <td><img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=YOU&theme=vue"></td>
    <td><img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=YOU&theme=vue"></td>
  </tr>
</table>
```

---

## 4. Show top languages, not just commit counts

A "top languages" card tells recruiters what you actually build with, at a glance:

```md
![](https://github-readme-stats.vercel.app/api/top-langs/?username=YOU&layout=compact&theme=merko)
```

---

## 5. Add a rotating dev quote for personality

Small, low-effort, but makes the page feel alive rather than static:

```md
![](https://quotes-github-readme.vercel.app/api?type=vetical&theme=merko)
```

---

## 6. Use `<hr>` and section headers to create rhythm

Long profiles get overwhelming fast. Break them into clear zones — About,
Achievements, Tech Stack, Stats, Socials — each with its own heading and a
horizontal rule between them, exactly like a landing page has sections.

---

## 7. Keep icons consistent — devicon or shields, not both randomly

Pick one icon source for skill icons (I use [devicon](https://devicon.dev) for
the "Languages and Tools" row and [Shields.io](https://shields.io) badges for the
detailed tech-stack breakdown). Mixing styles within the *same* row looks
inconsistent.

```md
<a href="https://reactjs.org/" target="_blank" rel="noreferrer">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
</a>
```

---

## 8. Bookend the page with a banner top and bottom

A `capsule-render` wave banner at the very top (behind your name/title) and
bottom (as a footer) gives the whole README a "designed" frame instead of
looking like a plain text file:

```md
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=header"/>
</p>
```

---

## 9. Don't overdo it

Common fresher mistake: stacking 10+ widgets, 3 stat cards, 2 trophy rows, and 5
banners. It becomes noise. Pick **one** stats card, **one** streak card, **one**
trophy row, **one** activity graph. Quality of curation matters more than
quantity of widgets.

---

## Quick before/after checklist

| Plain profile | Attractive profile |
|---|---|
| Wall of bullet text | Emoji-led, sectioned content |
| Text list of skills | Badge/icon rows grouped by category |
| No stats | One consistent-themed stats + streak card |
| No proof of activity | Activity graph + trophies |
| Dead-end page | Footer banner + working social links |

---

*Back to: `01-how-to-build-a-github-profile-readme.md` for the full build steps.*
