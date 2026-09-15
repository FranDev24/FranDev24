<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FranDev24/FranDev24/main/dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FranDev24/FranDev24/main/light.svg">
  <img alt="Franchesco Benavides" src="https://raw.githubusercontent.com/FranDev24/FranDev24/main/light.svg" width="100%">
</picture>

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <strong>Subject</strong><br>Franchesco Benavides
      </td>
      <td align="center" width="50%">
        <strong>Role</strong><br>Full-Stack Developer
      </td>
    </tr>
    <tr>
      <td align="center">
        <strong>Origin</strong><br>México
      </td>
      <td align="center">
        <strong>Education</strong><br>Universidad Iberoamericana
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <strong>Status</strong><br>Building · Learning · Shipping
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <strong>ToolChain</strong><br>VS Code · Git · Node.js · Python · Docker
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <strong>Core.Lang</strong> · JavaScript · TypeScript · Python · C++
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <strong>Core.Frontend</strong> · React · Vue · HTML5 · CSS3 · Tailwind
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <strong>Core.Backend</strong> · Node.js · Express · FastAPI · GraphQL
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <strong>Core.Database</strong> · PostgreSQL · MongoDB · Redis · SQLite
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <strong>Core.Infra</strong> · Vercel · GitHub Actions · Docker · Linux
      </td>
    </tr>
  </table>
</div>

<div align="center">
<img width="100%" src="https://streak-stats.demolab.com/?user=FranDev24&hide_border=true&background=000000&stroke=1c1c1e&ring=38e4f2&fire=7cf4ff&currStreakLabel=f2f4f6&sideLabels=8e8e93&currStreakNum=f2f4f6&sideNums=8e8e93&dates=6e6e73&titleColor=f2f4f6&card_width=1180" alt="streak" />
<br/><br/>
<img width="49%" src="https://github-readme-stats-hazel-chi.vercel.app/api?username=FranDev24&show_icons=true&count_private=true&include_all_commits=true&hide_rank=true&hide_border=true&title_color=38e4f2&icon_color=7cf4ff&text_color=f2f4f6&bg_color=000000&card_width=500" alt="stats" />
<img width="49%" src="https://github-readme-stats-hazel-chi.vercel.app/api/top-langs/?username=FranDev24&layout=compact&langs_count=8&hide_border=true&title_color=38e4f2&text_color=f2f4f6&bg_color=000000&card_width=500" alt="top langs" />
</div>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FranDev24/FranDev24/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FranDev24/FranDev24/output/github-contribution-grid-snake.svg" />
  <img alt="Snake eating my contributions" src="https://raw.githubusercontent.com/FranDev24/FranDev24/output/github-contribution-grid-snake.svg" />
</picture>
</div>

<div align="center">
<a href="https://www.linkedin.com/in/franchesco-benavides-mu%C3%B1oz-71990219b/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;&nbsp;
<a href="https://www.instagram.com/frxnchxscx_x/">
  <img src="https://img.shields.io/badge/Instagram-38e4f2?style=for-the-badge&logo=instagram&logoColor=000000&labelColor=38e4f2" alt="Instagram" />
</a>
&nbsp;&nbsp;
<a href="mailto:dalug.1996@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-38e4f2?style=for-the-badge&logo=gmail&logoColor=000000&labelColor=38e4f2" alt="Gmail" />
</a>
&nbsp;&nbsp;
<a href="mailto:dalug.1996@outlook.com">
  <img src="https://img.shields.io/badge/Outlook-38e4f2?style=for-the-badge&logo=microsoftoutlook&logoColor=000000&labelColor=38e4f2" alt="Outlook" />
</a>
</div>

---

<details>
<summary><strong>🛠 Checklist manual (haz esto una vez)</strong></summary>

1. **SVGs del banner** → ya subidos (`dark.svg` / `light.svg`) ✓
2. **Token GitHub clásico** → Settings → Developer settings → Tokens (classic) → Generate new (classic) → scope `repo` → Sin expiración → **Cópialo ya, no lo publiques**
3. **Fork & Vercel** → Fork `anuraghazra/github-readme-stats` → Vercel (Hobby free) → Import fork → Env `PAT_1` = tu token → Deploy → Usa **tu URL** en los badges de stats
4. **Snake Action** → Crea `.github/workflows/snake.yml` (ver abajo) → Settings → Actions → General → Workflow permissions → **Read and write** (repo settings, no account) → Push a main → espera verde → output branch existe
5. **Snake SVGs** → Se generan en rama `output` → el `<picture>` ya apunta ahí

**Colores iPhone 18 Pro (ya aplicados arriba):**
- Dark: `#000000` / `#f2f4f6` / `#38e4f2` / `#7cf4f2` / `#1c6bd8`
- Light: `#E8E8ED` / `#1b1d21` / `#1fa7c9` / `#2f6fed` / `#0b3fa0`

**⚠ LinkedIn:** su logo solo existe en `#0A66C2`; si cambias color, el glifo desaparece. Lo dejé en brand blue.
</details>

---

<details>
<summary><strong>⚙️ snake.yml (copia a .github/workflows/snake.yml)</strong></summary>

```yaml
name: Contribution Snake

on:
  schedule:
    - cron: '0 */12 * * *'   # cada 12 horas
  workflow_dispatch:
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      - name: Generate snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: FranDev24
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg
          color_snake: "#38e4f2,#7cf4ff,#1c6bd8"
          color_dots: "#000000,#1c1c1e,#2d3343,#3a3a3c,#48484a"
          color_dots_dark: "#2d3343,#3a3a3c,#48484a,#5c5c5e,#6e6e73"

      - name: Deploy to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
</details>