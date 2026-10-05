# Hi, I'm Saiem 👋

I'm a machine learning engineer, computer vision by trade, and the creator and maintainer of the
[**SportsDataverse**](https://sportsdataverse.org/ "The home page of the SportsDataverse Organization"): R, Python
and JavaScript packages that make public sports data easy to get at. They share the same ideas about tidy data, the
same automated release pipeline and, where it matters, the same models. I have spent most of my evenings since 2020
on it, and the goal hasn't changed: take the gathering out of the way of the research.

[![saiemgilani.com](https://img.shields.io/badge/saiemgilani.com-notes%20%C2%B7%20lab%20%C2%B7%20work-c0392b?style=for-the-badge)](https://www.saiemgilani.com)
[![X](https://img.shields.io/badge/%40saiemgilani-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/saiemgilani)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-saiem--gilani-white?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B66C2)](https://www.linkedin.com/in/saiem-gilani/)
[![GitHub followers](https://img.shields.io/github/followers/saiemgilani?color=eee&logo=github&style=for-the-badge)](https://github.com/saiemgilani)
[![Stars](https://img.shields.io/github/stars/saiemgilani?affiliations=OWNER%2CCOLLABORATOR&logo=github&label=stars&style=for-the-badge)](https://github.com/saiemgilani?tab=repositories&sort=stargazers)

## What I'm working on now

- **The R packages finished a long CRAN campaign in 2026.** cfbfastR, hoopR, wehoop, fastRhockey, baseballr, oddsapiR
  and cfbseedR are all current on CRAN; the rest of the family installs from
  [sportsdataverse.r-universe.dev](https://sportsdataverse.r-universe.dev).
- **[sportsdataverse-py](https://py.sportsdataverse.org/) was rebuilt end to end on polars.** ESPN across every
  league, the NBA and WNBA stats APIs, NHL, MLB and Statcast, HockeyTech, stats.ncaa.org, plus the same loaders and
  models the R packages ship.
- **Models ship with the data.** Every `load_*()` function reads automated releases
  ([sportsdataverse-data](https://github.com/sportsdataverse/sportsdataverse-data/releases)): play-by-play, box
  scores, schedules, rosters and, increasingly, fitted models (expected points, win probability, shot quality,
  expected goals) with the training code committed beside them.
- **Public data status.** [sportsdataverse.org/status](https://sportsdataverse.org/status) shows, nightly, how fresh
  every producer's data is and whether its pipeline is passing.
- **Logos, colors and headshots for plots and tables:** [sdvplotR](https://sdvplotr.sportsdataverse.org/) for ggplot2,
  gt and reactable, and its Python sibling [sdvplot](https://sdvplot.sportsdataverse.org/) (pre-release).
- **[Blazing the Nets](https://blazingthenets.com), rebuilt.** My 2021 Brooklyn Nets shooting dashboard, now on d3 v7
  and Next.js and reading release parquet files at request time
  ([write-up](https://www.saiemgilani.com/notes/blazing-the-nets-rebuilt-on-d3-v7)).
- **[The lab](https://www.saiemgilani.com/lab)** on my site: small, runnable ideas, like querying a release file from
  the browser with DuckDB.

## Packages I build and maintain

<p align="left">
<a href="https://cfbfastR.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/cfbfastR/main/man/figures/logo.png" height="110" alt="cfbfastR"/></a>
<a href="https://hoopR.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/hoopR/main/man/figures/logo.png" height="110" alt="hoopR"/></a>
<a href="https://wehoop.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/wehoop/main/man/figures/logo.png" height="110" alt="wehoop"/></a>
<a href="https://fastRhockey.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/fastRhockey/main/man/figures/logo.png" height="110" alt="fastRhockey"/></a>
<a href="https://billpetti.github.io/baseballr/"><img src="https://raw.githubusercontent.com/BillPetti/baseballr/master/man/figures/logo.png" height="110" alt="baseballr"/></a>
<a href="https://oddsapir.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/oddsapiR/main/man/figures/logo.png" height="110" alt="oddsapiR"/></a>
<a href="https://cfbseedR.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/cfbseedR/main/man/figures/logo.png" height="110" alt="cfbseedR"/></a>
<a href="https://cfb4th.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/cfb4th/main/man/figures/logo.png" height="110" alt="cfb4th"/></a>
<a href="https://cfbplotr.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/cfbplotR/main/man/figures/logo.png" height="110" alt="cfbplotR"/></a>
<a href="https://sdvplotr.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/sdvplotR/main/man/figures/logo.png" height="110" alt="sdvplotR"/></a>
<a href="https://recruitr.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/recruitR/main/man/figures/logo.png" height="110" alt="recruitR"/></a>
<a href="https://usfootballr.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/usfootballR/main/man/figures/logo.png" height="110" alt="usfootballR"/></a>
<a href="https://r.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/sportsdataverse/sportsdataverse-R/main/man/figures/logo.png" height="110" alt="sportsdataverse (R)"/></a>
<a href="https://py.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/saiemgilani/saiemgilani/main/sdv-py-logo.png" height="110" alt="sportsdataverse-py"/></a>
<a href="https://js.sportsdataverse.org/"><img src="https://raw.githubusercontent.com/saiemgilani/saiemgilani/main/sdv-js.png" height="110" alt="sportsdataverse-js"/></a>
</p>

| Package | What it covers | Version | Downloads |
| --- | --- | --- | --- |
| [cfbfastR](https://cfbfastR.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/cfbfastR)) | College football play-by-play, EPA and win probability | [![CRAN version](https://img.shields.io/cran/v/cfbfastR?label=CRAN)](https://CRAN.R-project.org/package=cfbfastR) | [![CRAN downloads](https://cranlogs.r-pkg.org/badges/grand-total/cfbfastR)](https://CRAN.R-project.org/package=cfbfastR) |
| [hoopR](https://hoopR.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/hoopR)) | Men's basketball: ESPN, the NBA Stats API, KenPom, stats.ncaa.org | [![CRAN version](https://img.shields.io/cran/v/hoopR?label=CRAN)](https://CRAN.R-project.org/package=hoopR) | [![CRAN downloads](https://cranlogs.r-pkg.org/badges/grand-total/hoopR)](https://CRAN.R-project.org/package=hoopR) |
| [wehoop](https://wehoop.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/wehoop)) | Women's basketball: ESPN, the WNBA Stats API, stats.ncaa.org | [![CRAN version](https://img.shields.io/cran/v/wehoop?label=CRAN)](https://CRAN.R-project.org/package=wehoop) | [![CRAN downloads](https://cranlogs.r-pkg.org/badges/grand-total/wehoop)](https://CRAN.R-project.org/package=wehoop) |
| [fastRhockey](https://fastRhockey.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/fastRhockey)) | NHL, PWHL and the HockeyTech leagues | [![CRAN version](https://img.shields.io/cran/v/fastRhockey?label=CRAN)](https://CRAN.R-project.org/package=fastRhockey) | [![CRAN downloads](https://cranlogs.r-pkg.org/badges/grand-total/fastRhockey)](https://CRAN.R-project.org/package=fastRhockey) |
| [baseballr](https://billpetti.github.io/baseballr/) ([source](https://github.com/BillPetti/baseballr)) | Bill Petti's baseball package, which I maintain | [![CRAN version](https://img.shields.io/cran/v/baseballr?label=CRAN)](https://CRAN.R-project.org/package=baseballr) | [![CRAN downloads](https://cranlogs.r-pkg.org/badges/grand-total/baseballr)](https://CRAN.R-project.org/package=baseballr) |
| [oddsapiR](https://oddsapir.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/oddsapiR)) | Sports odds from The Odds API | [![CRAN version](https://img.shields.io/cran/v/oddsapiR?label=CRAN)](https://CRAN.R-project.org/package=oddsapiR) | [![CRAN downloads](https://cranlogs.r-pkg.org/badges/grand-total/oddsapiR)](https://CRAN.R-project.org/package=oddsapiR) |
| [cfbseedR](https://cfbseedR.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/cfbseedR)) | College football season simulation and playoff seeding | [![CRAN version](https://img.shields.io/cran/v/cfbseedR?label=CRAN)](https://CRAN.R-project.org/package=cfbseedR) | [![CRAN downloads](https://cranlogs.r-pkg.org/badges/grand-total/cfbseedR)](https://CRAN.R-project.org/package=cfbseedR) |
| [cfb4th](https://cfb4th.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/cfb4th)) | Fourth-down decisions | [![R-universe version](https://sportsdataverse.r-universe.dev/badges/cfb4th)](https://sportsdataverse.r-universe.dev/cfb4th) | |
| [cfbplotR](https://cfbplotr.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/cfbplotR)) | College football logos and colors for ggplot2 | [![R-universe version](https://sportsdataverse.r-universe.dev/badges/cfbplotR)](https://sportsdataverse.r-universe.dev/cfbplotR) | |
| [sdvplotR](https://sdvplotr.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/sdvplotR)) | Logos, colors, headshots and themes across leagues for ggplot2, gt and reactable | [![R-universe version](https://sportsdataverse.r-universe.dev/badges/sdvplotR)](https://sportsdataverse.r-universe.dev/sdvplotR) | |
| [recruitR](https://recruitr.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/recruitR)) | College recruiting rankings | [![R-universe version](https://sportsdataverse.r-universe.dev/badges/recruitR)](https://sportsdataverse.r-universe.dev/recruitR) | |
| [usfootballR](https://usfootballr.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/usfootballR)) | MLS and NWSL from ESPN | [![R-universe version](https://sportsdataverse.r-universe.dev/badges/usfootballR)](https://sportsdataverse.r-universe.dev/usfootballR) | |
| [sportsdataverse (R)](https://r.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/sportsdataverse-R)) | The meta-package that installs and loads the family | [![R-universe version](https://sportsdataverse.r-universe.dev/badges/sportsdataverse)](https://sportsdataverse.r-universe.dev/sportsdataverse) | |
| [sportsdataverse (Python)](https://py.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/sportsdataverse-py)) | Every league above in one polars-first package | [![PyPI version](https://img.shields.io/pypi/v/sportsdataverse?label=PyPI)](https://pypi.org/project/sportsdataverse/) | [![PyPI downloads](https://static.pepy.tech/badge/sportsdataverse)](https://pepy.tech/project/sportsdataverse) |
| [sdvplot](https://sdvplot.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/sdvplot)) | Python sibling of sdvplotR (pre-release) | not yet on PyPI | |
| [sportsdataverse (Node.js)](https://js.sportsdataverse.org/) ([source](https://github.com/sportsdataverse/sportsdataverse-js)) | ESPN, 247Sports and NCAA endpoints for Node.js | [![npm version](https://img.shields.io/npm/v/sportsdataverse?label=npm)](https://www.npmjs.com/package/sportsdataverse) | [![npm downloads](https://img.shields.io/npm/dm/sportsdataverse)](https://www.npmjs.com/package/sportsdataverse) |

Every package has a printable one-page cheat sheet at
**[sportsdataverse.org/cheatsheets](https://sportsdataverse.org/cheatsheets)**.

## Data status

Live, from the nightly [ecosystem snapshot](https://sportsdataverse.org/status). Off-season leagues read *idle*, never red.

[![CFB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2FcfbfastR-cfb-data%2Fstatus.json&label=CFB)](https://github.com/sportsdataverse/cfbfastR-cfb-data/actions)
[![NFL](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2Fnfl-data%2Fstatus.json&label=NFL)](https://github.com/sportsdataverse/nfl-data/actions)
[![NBA](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2FhoopR-nba-data%2Fstatus.json&label=NBA)](https://github.com/sportsdataverse/hoopR-nba-data/actions)
[![MBB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2FhoopR-mbb-data%2Fstatus.json&label=MBB)](https://github.com/sportsdataverse/hoopR-mbb-data/actions)
[![WNBA](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2Fwehoop-wnba-data%2Fstatus.json&label=WNBA)](https://github.com/sportsdataverse/wehoop-wnba-data/actions)
[![WBB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2Fwehoop-wbb-data%2Fstatus.json&label=WBB)](https://github.com/sportsdataverse/wehoop-wbb-data/actions)
[![NHL](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2FfastRhockey-nhl-data%2Fstatus.json&label=NHL)](https://github.com/sportsdataverse/fastRhockey-nhl-data/actions)
[![PWHL](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2FfastRhockey-pwhl-data%2Fstatus.json&label=PWHL)](https://github.com/sportsdataverse/fastRhockey-pwhl-data/actions)
[![MLB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsportsdataverse%2F.github%2Fmain%2Fstatus%2Fbadges%2Fbaseballr-data%2Fstatus.json&label=MLB)](https://github.com/sportsdataverse/baseballr-data/actions)

## Projects

### [Game on Paper](https://gameonpaper.com/cfb "Game on Paper: live analytics for the modern age")

Live college football analytics built on the same expected-points and win-probability models the packages ship
([source](https://github.com/saiemgilani/game-on-paper-app)).

<a href='https://gameonpaper.com/cfb/game/401013131'><img src='https://raw.githubusercontent.com/saiemgilani/saiemgilani/main/gameonpaper_screenshot.png' height="139" alt="Game on Paper game page"/></a>

### More

- [Blazing the Nets](https://blazingthenets.com): Brooklyn Nets shot charts, hex maps and shooting signatures
  ([source](https://github.com/saiemgilani/blazing-the-nets)).
- [saiemgilani.com](https://www.saiemgilani.com): [notes](https://www.saiemgilani.com/notes) on each package, written
  one at a time, and the [lab](https://www.saiemgilani.com/lab).
- [Sports-Research-Papers](https://github.com/saiemgilani/Sports-Research-Papers): a curated reading list of sports
  analytics research.

## Talks and writing

I presented the SportsDataverse at the
[Carnegie Mellon Sports Analytics Conference](https://www.stat.cmu.edu/cmsac/conference/2021/) in 2021. The paper won
the Data and Software contribution in the reproducible research competition's open track.
[Slides](https://saiemgilani.github.io/The_SportsDataverse_Initiative/) ·
[Repository](https://github.com/saiemgilani/The_SportsDataverse_Initiative) ·
[Paper](https://www.stat.cmu.edu/cmsac/conference/2021/assets/pdf/SaiemGilani.pdf)

The [notes on my site](https://www.saiemgilani.com/notes) pick up where that paper left off, one package at a time.

## Projects I contribute to

- [ncaascrapR](https://ehess.github.io/ncaascrapR/): Eric Hess's NCAA scraper ([source](https://github.com/ehess/ncaascrapR))
- The FSU Sports Analytics Club course packages, [fsu-sac](https://github.com/sportsdataverse/fsu-sac) and
  [fsu-sac-2025](https://github.com/sportsdataverse/fsu-sac-2025)
- Community packages in the SportsDataverse family: [sportyR / sportypy](https://sportyr.sportsdataverse.org/),
  [softballR](https://github.com/sportsdataverse/softballR), [mlbplotR](https://camdenk.github.io/mlbplotR/) and
  [more](https://github.com/sportsdataverse)

## My GitHub stats

[![Saiem Gilani's GitHub stats](https://github-readme-stats.vercel.app/api?username=saiemgilani&show_icons=true&hide_border=true&theme=monokai&layout=compact)](https://github.com/saiemgilani)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=saiemgilani&langs_count=8&hide=html&hide_border=true&theme=monokai)](https://github.com/saiemgilani)

[![GitHub streak](https://streak-stats.demolab.com?user=saiemgilani&theme=monokai)](https://git.io/streak-stats)

[![Contribution chart](https://ghchart.rshah.org/1c90ca/saiemgilani)](https://github.com/saiemgilani)

## Languages and tools

**Data and ML:** Python, R, polars, pandas, DuckDB, XGBoost, scikit-learn, PyTorch, TensorFlow, OpenCV

[![Data and ML](https://skillicons.dev/icons?i=py,r,pytorch,tensorflow,sklearn,opencv,postgres,sqlite,redis)](https://skillicons.dev)

**Web and apps:** TypeScript, React, Next.js, Node.js, d3, FastAPI

[![Web and apps](https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,d3,fastapi)](https://skillicons.dev)

**Infrastructure:** Docker, GitHub Actions, Vercel, AWS, GCP, Azure, Linux

[![Infrastructure](https://skillicons.dev/icons?i=docker,githubactions,vercel,aws,gcp,azure,linux,bash)](https://skillicons.dev)

## Support

If the packages save you time, you can help keep the data flowing:
[![Ko-fi](https://img.shields.io/badge/Ko--fi-support-FF5E5B?style=flat&logo=kofi&logoColor=white)](https://ko-fi.com/sportsdataverse)
· release notes and new datasets by email at [sportsdataverse.org/join](https://sportsdataverse.org/join).

<details><summary>Earlier work</summary>

- [cfbscrapR](https://github.com/saiemgilani/cfbscrapR) (archived): the college football scraper that became cfbfastR
- [cfbfastR-py](https://github.com/saiemgilani/cfbfastR-py), [hoopR-py](https://github.com/saiemgilani/hoopR-py) and
  [wehoop-py](https://github.com/saiemgilani/wehoop-py) (archived): folded into
  [sportsdataverse-py](https://github.com/sportsdataverse/sportsdataverse-py)
- [hoopR-data](https://github.com/sportsdataverse/hoopR-data), [wehoop-data](https://github.com/sportsdataverse/wehoop-data)
  and [kenpomR-data](https://github.com/saiemgilani/kenpomR-data): the original data repos, replaced by the automated
  [sportsdataverse-data](https://github.com/sportsdataverse/sportsdataverse-data) releases
- [sportsdataverse-nhl](https://github.com/saiemgilani/sportsdataverse-nhl): an NHL API TypeScript module
- [pbp-data](https://github.com/saiemgilani/pbp-data): raw play-by-play JSON

</details>
