# Vanilla Ice Cream

Serves 4

## Ingredients

Ingredients:

- Egg yolks: 4
- Granulated sugar: 180g
- Whole milk: 500ml
- Heavy cream: 250ml
- Salt: 2 pinches
- Vanilla: 1 pod (or 1-2 teaspoons vanilla extract)

## Instructions

```mermaid
gantt
    title Vanilla Ice Cream
    dateFormat m
    axisFormat %M
    tickInterval 5minute

    section Base
    Separate egg yolks : prep1, 0, 5m
    Mix yolks, sugar, milk, cream, salt and vanilla : prep2, after prep1, 10m
    Cook mixture over low heat (170°F or until steamy), stirring constantly : prep3, after prep2, 15m
    Cool in an ice bath : prep4, after prep3, 20m

    section Processing
    Beat the cooled mixture : process1, after prep4, 10m
    Place in freezer : process2, after process1, 60m
    Remove from freezer and beat again : process3, after process2, 10m
    Return to freezer and beat two more times : process4, after process3, 140m
