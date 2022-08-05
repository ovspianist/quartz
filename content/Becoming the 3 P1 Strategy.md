---
title: "Becoming the 3% – Part 1 – Strategy"
tags: 
- "trading"
---


## **The game of probability**

Deep down at its core, trading is just like running a casino, it’s nothing but a game of probability. The difference is when you gamble, the casino has an absolute edge of winning over yours, while designed to be deceptively random. 

You might win once or twice, but over a large number of plays, the casino always wins. In order to win, you need to be the casino, not the gambler.

Profitability = ( Wins% * Reward ) - ( Losses% * Risk )

When you have a 1:2 risk-reward ratio, you really have to keep your winning probability above 33% to be profitable in the long run. Some people are more comfortable with higher risk-reward ratio such as 1:1, but with this ratio, you’ll have to keep winning probability above 50% to make a profit.

Generally, the winning probability of a system is inverse proportional to the risk-reward ratio. You cannot change the risk-reward ratio without affecting winning rate. So far, I haven’t seen any system or strategy that doesn’t follow this rule.

Having a strategy that has a genuine mathematical edge is crucial for trading success, luckily this is the easiest part to learn and develop within all the areas.

The outcome of any single trade is completely random, and it’s futile to try to predict it. What can be measured, predicted and acted on is the probability of one thing happening over the other in a series of trades.

## **Back testing**

In case you don’t know already, back testing means testing your trading strategy with real historical price data to see how it performs. No matter what kind of strategy you decide to use, either you learned from others or developed on your own, bring it to test with real life historical data. 

There are some ways of running back tests automatically via commercial apps, with a scripting language of your choice, or completely manually. As long as you have accurate historical data, you could test out how your strategy performs over a series of 50 trades, at least. 

Probability won’t work when you have a small set of samples.

If the result is not profitable over 50 trades, either make some changes to it, or just find another strategy, 50 trades are not a lot, but any solid strategy should at least give you a small profit at the end of that period.

## **Risk of ruin**

There’s also an idea called "Risk of Ruin".

Any chance of winning that’s less than exactly 100%, will give you losing trades, a probability of 50% of winning, statistically will have an 100% chance of generating 4 consecutive losing trades over 100 trades, and a 9% chance of generating 10 consecutive losing trades.

Let this sink in, imagine yourself tossing a coin, and one after another you get a tail, for 10 times. How would you feel if every time it’s a tail you lose 3% of your whole account?

You need to accept it, because it will happen eventually.

With a 50% winning rate, you should expect to see a 10 trades long losing streak at some point, and it’s definitely not an indication that you’re trading badly.

Encountering those losing streaks in the back testing stage before you start trading live, will help you learn how to deal with the negative feeling. Especially if the losing streak happens right at the beginning of live trading, it could be extremely hard to maintain your composure and keep trading the strategy exactly it should be traded, since you have no idea if there’s something wrong with the strategy or just the statistical inevitability.

It’s very important to keep this in mind, if you risk 5% of your remaining equity every time, in the event of this unfortunate 10 trades losing streak, you’ll have a 40% drawdown( 0.95 to the power of 10 ), if you risk 10%, that’ll be a 66% drawdown.

After you have a 50% drawdown, you will need to make a 100% profit to break even.

The lower your winning rate is, the less you need to risk per trade so that these unforeseeable losing streaks don’t destroy your account.

## **Try to break your strategy**

If your results in back testing proves that strategy could be profitable, try to break it by changing some parameters that define your strategy, in an ideal situation, the changes you make are going to affect the performance gradually, let’s say if you now tweak the distance between your entry point and stop loss point, together with the distance to take profit point so that they maintain the same ratio. 

Just by scaling up and down the distances, you’ll have different performance, you might find out with the distances shorter, it’s more likely to hit your stop loss and then reverse, or it might be too wide that a large number of trades couldn’t reach your take profit point before reversing. Your job is to find the optimal distances that maximise winning rate.

If you change the parameter gradually, but the results end up jumping up and down as if there’s no connection to the parameter you tweaked, then there might be a systematic flaw with your strategy. Ideally performance changes gradually and there is often an area that gives you the best performance.

## **Paper trading**

After thorough back testing and fine tuning the strategy, now you’re ready to trade, but I strongly advise you to do a forward testing.

What is forward testing now?

Similar to back testing, but instead of using historical data, you’ll be using live data, testing your strategy as it happens. This is pretty much like live trading, but in a safe environment.

If you have access to a trading platform that provides paper trading accounts or trading simulators, it’ll be the best tool to forward test. They allow you to trade like a live account, but with fake money, and it’s great for testing your strategy.

If you don’t have a platform to paper trade, there’s always the option to just do it on a charting software, TradingView for instance, allows you to place simulated trades on the chart. 

**_Forward testing provides a few benefits over back testing, such as:_**

-   Back testing can’t simulate waiting time. In forward testing, you have to wait for the trades to resolve in their own time, you might have some doubts before a trade ends, and some people don’t have the patience to let it play out. 

-   Depending what instruments are designed to be used with the strategy, if you only have 1 concurrent trade allowed at any given moment, and you happen to see 2 or more trading opportunities, you can only choose one, this might affect the real performance. It’s hard to spot this when back testing.

-   For part time traders, missing opportunities is normal, when you’re back testing you won’t find out that all those trades that happen around dinner time are actually not possible to execute, in forward testing you can.

**_However even forward testing cannot give you the full experience as you would have in live trading:_**

-   Simulators can’t simulate emotions which you will have when trading live, losing fake money probably feels like nothing other than a dent in your confidence, while losing real money might shake your whole belief in trading in general.

-   For some fast trading styles such as scalping, slippage is frequent in live trading but simulators don’t include the impact of slippage.

-   Size does matter in paper trading, one common mistake new traders make is to trade way bigger sizes and more aggressive than what they can afford in future live trading, not treating paper trading exactly like live trading is likely to encourage bad habits.

## **Focus on one strategy**

At least at the beginning, juggling between several different strategies will only diverge your attention. 

Learning is a process of turning knowledge from consciousness into subconscious so you can utilise it naturally without thinking hard.

I see trading as sports, there’s training and there’s competition. When you’re in the actual game competing with others, you’d better be sure you have all the techniques fully developed before jumping in. 

That’s the worst time where you should be thinking about how to do certain things.

There are traders who constantly switch between different markets and trading styles, I would advise against trading like that when you’re starting out. If you want to add another strategy or trading style, do it after you’ve proven consistently profitable with one strategy.

## **Pick strategies that fit your personality**

This is more about optimisation than validity, there are many strategies with proven profitability, but you might find most of them hard to adopt because how they are executed.

Say you have a 9-5 job and only trade part time, a strategy that requires a lot of screen time during daytime is probably not for you.

Maybe you are not comfortable to trade in a very fast fashion, then active day trading might not be a good fit.

Or like myself, you seek quick action and more aggressive approach, swing trading is simply too slow to consider.

## **Conclusion**

The topics I listed above are just some of the important aspects in developing and adapting strategies that apply to most active traders, based on your own trading style you might have more or different components to check against. 

Make sure you understand all of these key points and find out which strategy you’ll be focusing on, is the first step forward. 

How far are you now after you have figured all those things out? 

If you agree with the consensus about how much importance strategies hold, then you are 10% there.

> Trading is 10% strategy, 30% risk management and 60% psychology.

**I agree.**

Especially after blowing up my account twice.

In the next article let’s have a look at risk management, the art of keeping the money you made and not giving back everything when things go bad.
