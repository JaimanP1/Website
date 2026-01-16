+++
date = '2026-01-15T19:49:05-05:00'
draft = false
title = 'Trading Bot'
+++

Can we beat the market? The first step to systematically losing all my money on the market is to first have a workflow that is easily scalable. 

To that end, I've first developed a backtesting suite. Using this backtesting suite, strategies, APIs, and performance statistics can be easily switched and tested. 

The main idea of this code is that a portfolio object is instantiated, then operated on in a loop every time step to reflect changes in positions and equity. 

By separating each operation on the portfolio into methods of abstract base classes, modularity of components can be acheived. Each strategy, for example, can be a class that implements the abstract base class of strategies called in the main loop acting on the portfolio object. 

While the code is a private repository, you can find the documentation here: [backtesting suite](https://backtesting-suite.netlify.app/).
