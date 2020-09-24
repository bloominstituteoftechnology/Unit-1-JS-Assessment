I did the whole thing on codepen here: 
https://codepen.io/matt22881/pen/KKzJbwO?editors=0012

 i've also put it in index,js

not sure if i'm doing something wrong so i'll inclede error logs im my repo in a moment.

thank you for your attention



## Get Started

Local Setup Instructions: From Command Line</summary>

1. Fork & clone to your local computer
1. `cd` into your newly cloned repository
1. Install dependencies using `npm i`
1. Run test command using `npm test`

```sh
git clone <insert your git clone url here>
cd <repo folder name>
npm install
npm run test:watch

```

## Data

Example data your code will be tested against. This can be found in the data folder.
if you want to console.log() to check your outputs when a function is invoked the objects are named:
lukeSkywalker,
leiaOrgana,
and obiWanKenobi

```js
// Complete Test Data Object (credit: https://SWAPI.co)
// Side note: Yes Star Wars 🤓 purists. It's a bit out of date. Talk to SWAPI about it.
// Focus & follow instructions above. 🤖
{
  "name": "Luke Skywalker",
  "height": "172",
  "mass": "77",
  "hair_color": "blond",
  "skin_color": "fair",
  "eye_color": "blue",
  "birth_year": "19BBY",
  "homeworld": "Tatooine",
  "films": [
    "A New Hope",
    "The Empire Strikes Back",
    "Return of the Jedi",
    "Revenge of the Sith",
    "The Force Awakens"
  ],
  "species": [
    "Human"
  ],
  "vehicles": [
    {
      "name": "Snowspeeder",
      "model": "t-47 airspeeder",
      "manufacturer": "Incom corporation",
      "cost_in_credits": null,
      "length": "4.5",
      "max_atmosphering_speed": "650",
      "crew": 2,
      "passengers": 0,
      "cargo_capacity": "10"
    },
    {
      "name": "Imperial Speeder Bike",
      "model": "74-Z speeder bike",
      "manufacturer": "Aratech Repulsor Company",
      "cost_in_credits": "8000",
      "length": "3",
      "max_atmosphering_speed": "360",
      "crew": 1,
      "passengers": 1,
      "cargo_capacity": "4"
    }
  ],
  "starships": [
    {
      "name": "X-wing",
      "model": "T-65 X-wing",
      "manufacturer": "Incom Corporation",
      "cost_in_credits": 149999,
      "length": "12.5",
      "max_atmosphering_speed": "1050",
      "crew": 1,
      "passengers": 0,
      "cargo_capacity": "110",
      "consumables": "1 week",
      "hyperdrive_rating": "1.0",
      "MGLT": "100",
      "starship_class": "Starfighter"
    },
    {
      "name": "Imperial shuttle",
      "model": "Lambda-class T-4a shuttle",
      "manufacturer": "Sienar Fleet Systems",
      "cost_in_credits": 240000,
      "length": "20",
      "max_atmosphering_speed": "850",
      "crew": 6,
      "passengers": 20,
      "cargo_capacity": "80000",
      "consumables": "2 months",
      "hyperdrive_rating": "1.0",
      "MGLT": "50",
      "starship_class": "Armed government transport"
    }
  ],
  "created": "2014-12-09T13:50:51.644000Z",
  "edited": "2014-12-20T21:17:56.891000Z",
  "url": "https://swapi.co/api/people/1/"
}
```

## Hints

#### Helpful tips & reminders 🔎

-   **Critical:** Don't make assumptions about input data types. (Convert/handle `Numbers` & `null`)
    -   Convert **number strings** into **actual numbers** with built-in functions `parseInt`, `parseFloat`, `Number`, etc.
-   Ensure your functions **`return somethingUseful`.**
-   Make sure you understand the requirements. All the words used? Try list the steps in comments first.
-   Don't forget the source data uses `snake_case` naming.
-   Pay close attention to array vs. object syntax (`vehicles[0].name` vs. `character.vehicles`.)
-   Some of the functions include detailed instructions.
-   You might have to infer the desired fields. Carefully read the description and function name (description included above the function.)
