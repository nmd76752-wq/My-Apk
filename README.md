# Quotex Chart Analyzer v2

This is a more complete Android starter for a floating chart analyzer.

### Flow
1. Install/build the app.
2. Allow "display over other apps".
3. Tap "Start screen analysis" and approve Android's screen-capture prompt.
4. Open the trading app.
5. Press the floating ANALYZE button.
6. The app captures one frame, crops the chart area, detects red/green candle-like pixels and shows UP/DOWN/WAIT + confidence.

### Important limitations
- The crop is tuned for the portrait layout shown in the supplied screenshot; different screen layouts need calibration.
- Pixel-based candle detection is a prototype, not a reliable trading strategy.
- Confidence is an internal score, NOT a probability of winning.
- The app deliberately does not click Quotex's Up/Down controls or submit orders automatically.
- Do not use a signal as a guarantee of profit.
