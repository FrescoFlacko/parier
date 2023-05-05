# Parier - Equity Betting Application

## What is Parier?
Parier is a web application where you can bet on the price that equities will open at in the next market session. You can bet in terms of percentage over/under what the previous closing price is.

This application is built on the **Solana blockchain**, and you are able to use the **Solana** cryptocurrency in the application for betting.

This web application was created as a part of the [Solana Riptide hackathon](https://solana.com/news/solana-riptide-announcement).

## Features
- Connect your Phantom wallet and deposit money into the application for use.
- Bet on the percentage differentiation of equities
- Current supported stocks: **$SPY**, **$AAPL**, and **$TSLA**
- Cancel outstanding bets
- Ability to view past bets
- Ability to collect rewards 

## Technologies used
- **[React](https://react.dev/)**: Library used to build out the user interface in Typescript.
- **[Tailwind CSS](https://tailwindcss.com/)**: CSS framework used for creating user interface.
- **[Solana JavaScript SDK](https://solana-labs.github.io/solana-web3.js/)**: JavaScript SDK used to make RPC commands to the Solana blockchain.
- **[Anchor](https://www.anchor-lang.com/)**: Framework used to provide development tools for developing smart contracts in Rust.
- **[Pyth Network](https://pyth.network/)**: Price oracles used to retrieve latest prices for stocks.

## Demo
Below is a demo presentation that we used for the Solana riptide hackathon:
[![Parier - Solana Riptide Hackathon Demo](https://img.youtube.com/vi/Ll0Zd5Q6gNo/0.jpg)](https://www.youtube.com/watch?v=Ll0Zd5Q6gNo)

## Website
You can visit a live version of this application at https://parier.netlify.app/

**NOTE**: This application is connected to the **Solana devnet**. Please switch your wallet to use devnet.

## Contributors
[@ajistrying](https://github.com/ajistrying): Smart contracts
[Me](https://github.com/FrescoFlacko): Web application, smart contracts
