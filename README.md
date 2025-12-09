# Slot Machine Math Model 

This project demonstrates a 3-reel slot machine built in Excel, with both theoretical and simulated analysis of RTP, hit rate, and volatility.  

## Features
- Reel strips configurable per reel
- Paytable with two-of-a-kind and three-of-a-kind multipliers
- Random spin generation (Excel formulas)
- Theoretical RTP and hit rate calculation from symbol counts
- Simulation of thousands of spins to validate theory
- Results reporting: RTP, hit rate, volatility

## Files
- `slot_model.xlsx` – main Excel file
- `WillMorris_SlotModelPortfolio.pdf` – portfolio write-up with screenshots
- `README.md` – this document

## Results Snapshot
| Metric | Theoretical | Simulated (10k spins) |
|--------|-------------|------------------------|
| RTP    | 96.0%       | 95.8%                  |
| Hit Rate | 28.5%     | 28.1%                  |
| Volatility | –       | 1.92                   |

## Next Steps
- Add scatters / wilds
- Expand to 3×3 grid with multiple paylines
- Automate high-volume simulation with VBA
