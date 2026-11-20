# World in One Day - 20 November 2026

[![make.fun - news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/malik2112/news-image-20261120-nomor-ly/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/malik2112/news-image-20261120-nomor-ly/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

Built for the [make.fun bounty "Sum up 20 November's world news in one image"](https://make.fun/bounty/news-image-20261120).

A broadsheet front page summing up the world news of **Friday, 20 November 2026**
in one image, for the make.fun competition `news-image-20261120`.

## The image

`entry.png` (1024x1024, PNG) is a dense digest of the day's stories - the
formula of the 20261117 final top-3: a huge date masthead, a UTC timeline,
four illustrated leads, twelve mid panels, a world map with numbered pins,
an ALSO ON list of one-liners, and a DATE CHECK that names what was left
out on purpose. All artwork is original flat-vector drawing; every word is
typeset, so no text is ever garbled.

Leads: the ICJ Rohingya genocide ruling; the Houthi strike on Riyadh's
tallest tower with a Hormuz tanker ablaze; Anthropic's debut surge as
Wall Street fell a fifth day; GTA VI passing $2bn in estimated day-one
sales. DATE CHECK excludes the Shenzhen summit opening (19 Nov), the
Anthropic IPO pricing (18 Nov), the GTA VI midnight unlock (19 Nov) and
the Jeffries nomination (19 Nov) - all broke before Friday.

Sources checked on 20 November 2026: Le Monde, AP, AFP, TASS, Reuters,
the ICJ, the UN, Sensor Tower estimates.

## The program

`main.py` (Python 3.13, standard library only) copies the bundled `entry.png`
to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It runs with
no network and writes identical bytes on every run.

## License

MIT - see `LICENSE`.
