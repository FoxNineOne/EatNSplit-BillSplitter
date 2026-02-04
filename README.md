# EatNSplit – Bill Splitter (React)

A small React app to track balances with friends and split bills.

Based on EatNSplit app from the React Course by Jonas Schmedtmann
Updated with personal changes to:
- Allow only numerical inputs on the bill fields
- Allow saving and reloading of friends and financials from local storage

## Live Demo
[View the app here] https://eatnsplit-billsplitter.netlify.app/

## Features
- Add friends with an avatar URL
- Select a friend and split a bill
- Tracks running balances (who owes who)
- Basic validation (e.g. your expense can’t exceed the bill)

## Tech
- React (hooks: useState)
- Component composition, state lifting, derived state
- Immutable updates (map over array to update a single friend)


