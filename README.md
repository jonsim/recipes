# Jon's recipes
My [cooklang](https://cooklang.org/) recipe database.

## Conventions
- Always metric.
- tsp, tbsp, dsp - not teaspoon, tablespoon, dessert spoon.
- ml, l - not millilitres, litres.
- g, kg - not grams, kilograms.
- minutes, hours - not min, hr.
- 0.75, 0.5, 0.3, 0.25 - not ¾, ½, ⅓, ¼.
- Oven temperatures assume fan.
- Use the non-standard `yields` metadata field to express a weight or volume yield when appropriate.
- Follow [Cooklang best practices](https://cooklang.org/docs/best-practices/).
- Follow [Cooklang conventions](https://cooklang.org/docs/conventions/).

## Contributing
- Install [CookCLI](https://github.com/cooklang/CookCLI).
- Install [cook-format](https://github.com/jonsim/cook-format).
- Install [uv](https://github.com/astral-sh/uv).
- Clone the repository and run `uv sync`.
- Install pre-commit hooks: `uv run pre-commit install`.
- Start cooking.
