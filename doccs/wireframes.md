# Wireframes

Every screen shares one header, a tab bar and a notice banner. Every stock row has a star.

## Markets (home)
    [Header]  [Markets|Stocks|Popular|Dashboard|Live data|Design]
    [Notice: sample or live data]
    [Index] [Index] [Index] [Index]
    [Top mover card] [Top mover card] ...

## Stocks
    [Header + tabs]
    [Search box] [Region filter]
    [ ☆ | Symbol | Name | Region | Price | Change | Volume | Cap ]   (sortable)

## Popular trades
    [Header + tabs]
    [Symbol  name ............ volume  change  ☆]
    [========== volume bar ==========]  x 8

## My dashboard
    [Header + tabs]
    [Saved count, average move]
    [Card: symbol, sparkline, price, change, volume, cap] x N
    [Refresh quotes] [Clear dashboard]
    (empty state: "Nothing saved yet. Tap ☆ to add a stock.")

## Live data
    [1. Link to get a free Alpha Vantage key]
    [2. Key field] [Save and test] [Remove key]
    [3. Status message and rate-limit note]
