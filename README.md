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
- `slot model.xlsx` – main Excel file
- `slot machine.docx` – portfolio write-up with screenshots
- `README.md` – this document

## Results Snapshot
| Metric | Theoretical | Simulated (10k spins) |
|--------|-------------|------------------------|
| RTP    | 95.58%       | 93.8%                  |
| Hit Rate | 27.68%     | 27.97%                  |
| Volatility | –       | 4.166                   |

## Next Steps
- Add scatters / wilds
- Expand to 3×3 grid with multiple paylines
- Automate high-volume simulation with VBA
