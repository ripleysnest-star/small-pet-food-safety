# Can my small pet eat this? An open table of 1,274 food answers

A plain table of which foods are fine, fine now and then, or not for nine small pets: rats, rabbits, guinea pigs, hamsters, mice, gerbils, chinchillas, degus and ferrets.

Each row gives the animal, the food, a short answer (`yes`, `sometimes` or `no`), how often (`daily`, `weekly`, `occasional` or `never`), the sources it comes from with their links, and a link to read more. 346 foods have a full page on bruxlings.com with the reasons and how to serve them: those rows have a one-line `short_answer` and link to their page. The other 928 rows give `how` (how much, or what to give instead) and `why`, and link to the food checker.

| Animal | Foods answered | With a full page |
|---|---|---|
| Chinchillas | 89 | 15 |
| Degus | 60 | 13 |
| Ferrets | 62 | 16 |
| Gerbils | 86 | 21 |
| Guinea pigs | 187 | 60 |
| Hamsters | 221 | 56 |
| Mice | 116 | 23 |
| Rabbits | 232 | 75 |
| Rats | 221 | 67 |

Answers: 133 yes, 573 sometimes, 568 no. 4,167 search names in all (the food's name plus other names people use for it), from 415 source pages.

## Files

- `small-pet-foods.csv`: one row per animal and food. `sources` and `search_names` hold several values split by `; `.
- `small-pet-foods.json`: the same rows as JSON, with `sources` as a list of `{name, url}` and `search_names` as a list.

Columns: `animal`, `food`, `answer`, `how_often`, `short_answer`, `how`, `why`, `sources`, `full_answer_url`, `has_page`, `search_names`.

## Ready-made charts and a tool for your site

- **Printable charts**, one A4 page per animal with the everyday foods sorted into yes, sometimes and no, and cage sizes: [rats](https://tools.bruxlings.com/charts/rats/), [rabbits](https://tools.bruxlings.com/charts/rabbits/), [guinea pigs](https://tools.bruxlings.com/charts/guinea-pigs/), [hamsters](https://tools.bruxlings.com/charts/hamsters/), [mice](https://tools.bruxlings.com/charts/mice/), [gerbils](https://tools.bruxlings.com/charts/gerbils/), [chinchillas](https://tools.bruxlings.com/charts/chinchillas/), [degus](https://tools.bruxlings.com/charts/degus/), [ferrets](https://tools.bruxlings.com/charts/ferrets/). Same licence.
- **A food checker you can put on your own page**, with search as you type and the sources under every answer: [tools.bruxlings.com/food](https://tools.bruxlings.com/food/). The copy-paste code is at [bruxlings.com/pages/food-checker#embed](https://bruxlings.com/pages/food-checker#embed). There is a [cage size checker](https://bruxlings.com/pages/cage-checker#embed) too.

## Use it

Free to use, share and adapt, including in articles, apps, charts and printed sheets, under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit it with a link:

> Food answers from [Bruxlings](https://bruxlings.com/pages/food-checker), small-pet care guides.

Each answer is general guidance for a healthy adult animal, not advice for a particular pet. If your animal is unwell, young, old or on a special diet, ask a vet who sees small pets.

## Where it comes from

Written by Bruxlings from welfare and care sources and experienced keepers; every row names its sources. The answers are kept up to date at [bruxlings.com/pages/food-checker](https://bruxlings.com/pages/food-checker); this table is a copy taken on 15 November 2026.

Spotted something wrong? Open an issue.
