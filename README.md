# Forex Strength Analyzer Pro

Real-time currency strength analysis across H4, D1, and W1 timeframes using EMA 5/12 crossovers.

## Features

- **Live Data**: Fetches real-time technical indicators from TradingView
- **Multi-Timeframe Analysis**: Analyzes H4, D1, and W1 timeframes
- **Currency Strength Meters**: Visual representation of each currency's strength (-5 to +5 scale)
- **Pair Analysis**: Detailed breakdown of all 28 major forex pairs
- **Weighted Scoring**: H4 (1x), D1 (2x), W1 (3x) for professional analysis

## How to Use

1. Open the tool at: `https://YOUR_USERNAME.github.io/forex-strength-analyzer/`
2. Click **"Update Live Data"** to fetch current market analysis
3. Review the currency strength meters on the left
4. Check the pair strength table on the right for detailed timeframe analysis

## Scoring Scale

- **+5 to +4**: Very Strong Uptrend (Red )
- **+3 to +2**: Moderate Uptrend (Orange)
- **+1**: Weak Uptrend (Light Green)
- **0**: Neutral/Consolidating (Gray)
- **-1**: Weak Downtrend (Light Green)
- **-2 to -3**: Moderate Downtrend (Green)
- **-4 to -5**: Very Strong Downtrend (Dark Green)

## Technical Details

- **EMA 5 vs EMA 12**: Trend detection based on exponential moving average crossovers
- **Currency Strength**: Calculated by averaging all 7 pairs where each currency appears
- **Base vs Quote Logic**: For base currencies, uptrends indicate strength; for quote currencies, downtrends indicate strength

## Data Source

Live data is fetched from TradingView's public scanner API using the FX_IDC data feed.

## Browser Compatibility

Works on all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

## License

Free to use and modify.
