This repo is just to be cd'ed/used by the next repos of this series, so there's no need to try out this one.

In this "Connect to wallet series" we are following the video:
https://www.youtube.com/watch?v=pdsYCkUWrgQ, from Patrick Collins.

In the next repos we'll be aplying the following ways to connect to a wallet:

1. HTML / Ethers
2. NextJS / React and "raw" ethers
   Then we're gonna get more advanced, and use some more advanced tooling for the web3 space (NextJS and a package):
3. NextJS & "web3-react"
4. NextJS & "react-moralis"
5. NextJS & "web3Modal"
6. NextJS & "useDapp"

A quick summary:

- The "1. HTML / Ethers" one is the raw version and in "2. NextJS / React and "raw" ethers" we add the nextjs and react features.
- In "3. NextJS & "web3-react" is used by protocols like uniswap/aave. Here we add functionality that allows us to make our aplication remember the state of whether or not we are connected to a wallet, across the different pages. Plus it adds some functionality to make it easier to connect, connect to the provider and know if we're connected to the provider or not.
- "4. NextJS & "react-moralis" has pretty much the same functionalities as "web3-react" but can be even simpler, given that its easier to set up the connect() and to perform calls to functions.
- "5. NextJS & "web3Modal" adds an easy integration with multiple wallets by having that frontend ui to choose the wallets automatically. The rest of the implementation is close to the simple nextjs/react/ethers implementation in 2."
- "6. NextJS & "useDapp" is similar to all of those with some syntax differences, but really similar features. we can check the code at "https://github.com/PatrickAlphaC/nextjs-usedapp-metamask-connect/tree/f8858d687125f0d8c41a6ad0116901d94b9feb47"

Patrick's advice -> Patrick gave us two really good repos that by his words are insane to study and to reverse engineer in order to learn react things and to apply them into our projects, which can be good for me in the future.

- https://github.com/ethereum-boilerplate/ethereum-boilerplate applies Moralis and react.
- https://github.com/scaffold-eth/scaffold-eth/tree/master/packages/react-app/src/components, created by Austin Griffith, applies web3modal and react.

This repo is just to be cd'ed/used by the next repos of this series, so there's no need to try out this one. Skip directly to "connect-to-wallets-part1--html-ethers".
