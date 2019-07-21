# Premise

This system is meant to be a relatively simple way of logging weekly spending and doing basic analytics on it.

For the moment at least, concepts like net worth and tracking investments are not in scope.

The core pieces of raw data the user will provide are:
- Income sources (pre-income tax)
- Recurrent spending (i.e. predictable spends that happen at regular intervals, like rent)
- Spending (i.e. any other spend, be it a bill, a meal, a service or a consumer item)
- Weekly (monthly? yearly?) budget configuration

Either kind of spending can be _tagged_ with arbitrary tags. The weekly budget specifies a budget for some specific tags.

The primary analytics I want are to be able to answer the questions:
- Have I overspent in a particular tag/category this week?
- How much have I (theoretically*) earned this week, after expenses?

\* Income and recurrent spending that are defined e.g. as a yearly salary or monthly bill will be 'amortized' over the period.