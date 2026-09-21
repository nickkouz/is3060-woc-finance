# Lab 3: WOC Mobile App Prototype (Track E: Finance)

**Thunkable share link:** https://x.thunkable.com/copy/1463a5644a3ef72e5f690655d4410fda

## What it does

A capital investment ROI calculator for WOC store managers. The user enters an asset name, an initial cost, and an estimated annual revenue. The app then displays the return on that asset on a Results screen, calculated as:

```
ROI = (Revenue - Cost) / Cost x 100
```

## Why it matters

WOC executives have no standardized way to measure ROI on capital purchases and decide on intuition rather than data. This prototype gives every store manager the same calculation, so a purchase request from Park City can be compared against one from Sandy on identical terms.

## Screenshots

| File | Screen |
|---|---|
| `01_Home_Empty.png` | Home screen on launch, with empty input fields and placeholder prompts for asset name, initial cost, and estimated annual revenue. |
| `02_Home_Filled.png` | Home screen with a sample asset entered — E-Bikes at a $10,000 initial cost against $15,000 in estimated annual revenue. |
| `03_Results.png` | Results screen showing the calculated return for that asset, with a button to run another calculation. |

All three screens are also collected in `WOC_App_Screenshots.pdf`, one screen per page, in the order above.

## Limitations

This prototype uses a simplified formula. A production version would incorporate maintenance costs and location-specific data, so that the same asset priced identically at two stores can still return different projected ROI based on the traffic and cost structure of each location.
