# Backpack + Blessed Example Repo

This repo demonstrates an issue where Backpack echoes input to the terminal, which covers up content rendered by Blessed.


### Instructions

First, run `yarn` or `npm install` to install the dependencies.

Run `npm run blessed` to see the expected behaviour of the blessed script.
Then, type any keys in your terminal.
You should not see them echoed back, unless you click in the blue input bar.

Then, run `npm run backpack` and begin typing anything in your terminal.
You should see the keys you type echoed back into your terminal, which blocks the content rendered by blessed.
This is the behaviour we are trying to prevent.

