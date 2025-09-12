# WTT_Syzygy Quickstart Guide

## Overview
WTT_Syzygy is a comprehensive trading indicator that combines volume spike detection with support/resistance zone analysis to provide enhanced market insights and trading signals. The indicator's signal generation and optimization algorithms are derived using advanced AI technology to ensure maximum accuracy and reliability.

## Key Features
- **AI-Powered Signal Generation**: Advanced algorithms derived using artificial intelligence for optimal signal accuracy
- **Volume Spike Detection**: Identifies unusual volume spikes with configurable thresholds
- **Support/Resistance Zones**: Dynamic liquidity zone identification with penetration alerts
- **Daily High/Low Tracking**: Optional daily level monitoring
- **Unified Alert System**: Comprehensive alerts for all signal types

## Quick Setup

### Recommended Settings
```
Volume Spike Settings:
- Volume Lookback Period: 20 (default)
- Volume Spike Threshold: 1.2 (default)
- Price Change Threshold: 0.5% (default)
- Use ATR for Price Filter: ✓ (enabled)

Support/Resistance Settings:
- Number of Liquidity Zones: 5 (default)
- Show Low Liquidity Zones: ✓ (enabled)
- Support Zone Color: Gray
- Resistance Zone Color: Teal

Alert Settings:
- Enable All Alerts: ✓ (enabled)
- Show Alert Indicators: ✓ (enabled)
- Zone Penetration Threshold: 50% (default)
```

## Signal Interpretation

### Volume Spike Signals
- **Green Upward Label (Below Bar)**: Long signal - Volume spike with bullish price movement
- **Red Downward Label (Above Bar)**: Short signal - Volume spike with bearish price movement

### Zone Penetration Signals
- **Red Downward Triangle (Above Bar)**: Resistance zone penetration - Price moved >50% into resistance
- **Green Upward Triangle (Below Bar)**: Support zone penetration - Price moved >50% into support

### Liquidity Zones
- **Weak**: Low volume strength zones (gray/teal with high transparency)
- **Moderate**: Medium volume strength zones (medium transparency)
- **Strong**: High volume strength zones (low transparency, bold text)

## Trading Applications

### Entry Signals
1. **Volume Spike + Zone Interaction**: Look for volume spikes near support/resistance zones
2. **Zone Penetration**: Monitor for significant penetration into key zones
3. **Daily Levels**: Use daily high/low as additional reference points

### Risk Management
- Volume spikes provide momentum confirmation
- Support/resistance zones offer key levels for stop losses
- Zone penetration alerts help identify potential reversals

## Alert Types
- **Volume Spike Long/Short**: Immediate momentum signals
- **Zone Penetration**: Significant price movement into key levels
- All alerts include ticker symbol and current price

## Best Practices
1. **Combine Signals**: Use volume spikes with zone analysis for higher probability setups
2. **Timeframe Selection**: Works best on 5m, 15m, and 1h timeframes
3. **Market Conditions**: Most effective in trending markets with clear support/resistance levels
4. **Volume Confirmation**: Always confirm signals with volume analysis

## Troubleshooting
- **No Signals**: Check if volume threshold is too high or price change threshold too restrictive
- **Too Many Signals**: Increase volume threshold or price change threshold
- **Zones Not Showing**: Ensure "Show Low Liquidity Zones" is enabled
- **Alerts Not Working**: Verify "Enable All Alerts" is checked in settings

## Customization Tips
- **Sensitive Detection**: Lower volume threshold (1.0-1.2) for more signals
- **Conservative Detection**: Higher volume threshold (1.5-2.0) for fewer, higher-quality signals
- **Zone Visibility**: Adjust zone colors and transparency for your chart theme
- **Alert Frequency**: Use TradingView's alert frequency settings to control notification frequency

---
**Copyright © 2025 William Skrzypczak. All rights reserved.**

**Disclaimer**: This indicator is for educational purposes only. Trading involves risk and past performance does not guarantee future results. Always use proper risk management and consider your trading experience before using any trading signals.

**Version**: Rev1.1 - Enhanced visual indicators with small labels for volume spikes and tiny triangles for zone penetration

**AI-Powered**: Signal generation and optimization algorithms derived using advanced AI technology for enhanced accuracy and reliability.
