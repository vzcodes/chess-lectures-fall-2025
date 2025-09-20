# Welcome to the slide deck for my Fall 2025 chess lessons

## Running one slide deck
To start the deck, visit:

- `npm install`
- `npx slidev slides/week1/week1.md`
- visit <http://localhost:3030>

## To build full system
1. Build individual slide decks: 
- `npx slidev build slides/week1/week1.md --out dist/week1 --base /chess-lectures/week1/`
- `npx slidev build slides/week2/week2.md --out dist/week2 --base /chess-lectures/week2/`

2. Copy slide decks into build folder such as .local/site/chess-lectures

3. Copy `index.html` to the root repository

4. Run HTTP server such as `npx vite preview`

5. Open `http://localhost:4173/chess-lectures/`

## Public website

The website deployed at https://vzcodes.github.io/chess-lectures-fall-2025/ runs a slightly complex build which goes through each of the folders under `/slides` before adding all assets to the correct folder. Feel free to see the build yaml file [here](/.github/workflows/build-slidev.yml).
