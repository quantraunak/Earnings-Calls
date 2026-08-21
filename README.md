# Earnings Calls and Stock Returns

Raunak Sood · June 2023

Text analysis of earnings call transcripts for ten semiconductor and large-cap technology
companies, joined to daily price data to test whether call language relates to subsequent
returns.

## Universe

`MU · CSCO · NVDA · AMZN · AAPL · MSFT · GOOGL · AMD · ASML · INTC`

## Method

Transcripts are parsed per company and tokenised with `tidytext`, then merged with daily stock
data on company and date so that language measured on the call date can be related to the
returns that follow it. Regression results are reported with `stargazer`.

## Files

- `Project43.Rmd` — parsing, tokenisation, merge, regressions
- `Project43.html` — knitted output

`R · tidytext · tidyverse · ggplot2 · lubridate · stargazer`
