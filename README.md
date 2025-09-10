# Welcome to the slide deck for my Fall 2025 chess lessons

## Running one slide deck
To start the deck, visit:

- `pnpm install`
- `pnpm slidev slides/week1/week1.md`
- visit <http://localhost:3030>

## To build full system
1. Build individual slide decks: 
- `npx slidev build slides/week1/week1.md --out dist/week1 --base /chess-lectures/week1/`
- `npx slidev build slides/week2/week2.md --out dist/week2 --base /chess-lectures/week2/`

2. Copy slide decks into build folder such as .local/site/chess-lectures

3. Copy `index.html` to the root repository

4. Run HTTP server such as `npx vite preview`

5. Open `http://localhost:4173/chess-lectures/`