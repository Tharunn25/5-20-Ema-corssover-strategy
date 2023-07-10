## EMA and MACD Crossover Strategy

Strategy Overview
The strategy uses two input variables: the short EMA length and the long EMA length. These lengths determine the periods over which the EMAs are calculated. By default, the short EMA length is set to 5, and the long EMA length is set to 20. However, you can adjust these values according to your specific requirements.

The EMAs are calculated using the ta.ema() function in Pine Script, which takes the closing prices of the financial instrument as input. The short EMA represents a shorter-term moving average, while the long EMA represents a longer-term moving average.

Buy signals are generated when the short EMA crosses above the long EMA, indicating a potential upward trend. Conversely, sell signals are generated when the short EMA crosses below the long EMA, indicating a potential downward trend. The strategy uses the ta.crossover() and ta.crossunder() functions to identify these crossover points.

## Python code for the above strategy

https://github.com/Tharunn25/5-20-ema-python



## Outcome of the strategy In BankNifty with capital 1 lakh Rs

15 - Minutes

Net Profit - 98,333.25 INR (98.34%)

Total Closed Trades - 271

profit percentage % - 34.32%

Profit Factor - 1.268

MaxDrawDown - 70,034.25 INR (53.29%)

Avg Trade profit - 362.88 INR (0.06%)


<img width="872" alt="image" src="https://github.com/Tharunn25/5-20-Ema-corssover-strategy/assets/98308855/e970437d-6848-40f5-a3ae-d7e575ef0d7d">


1 - Hour

Net Profit - 317,322.75 INR (317.32%)

Total Closed Trades - 339

profit percentage % - 30.97%

Profit Factor - 1.279

MaxDrawDown - 16,353.25 INR (38.42%)

Avg Trade profit - 936.06 (0.22%)

<img width="917" alt="image" src="https://github.com/Tharunn25/5-20-Ema-corssover-strategy/assets/98308855/c1785e24-97cd-4ce4-b348-518e94581e23">

## How to add it to your Trading view 

Step 1 : copy the above text file (as it is pinescript it doesn't have any format to save).

Step 2 : Open your Trading View site.

Step 3 : on the left slide Menu You can find the pine editor.

Step 4 : copy the file in the compiler and press add to chart button.

Step 5 : now your ready to go.




## Getting Started

To use the EMA Crossover Strategy in TradingView, follow these steps:

1.Open the TradingView platform and create a new Pine Script strategy.

2.Copy and paste the provided code into the strategy editor.

3.Adjust the input variables, such as the EMA lengths, if desired.

4.Save and apply the strategy to your preferred financial instrument's chart.

The strategy will plot the EMAs on the chart, highlighting the crossover points. It will also generate buy and sell signals when the crossovers occur. You can customize the appearance of the EMAs and signals according to your preference.
## Important Considerations

1.This strategy is a basic example and should be thoroughly tested and validated before using it for live trading.

2.It's recommended to perform additional analysis, consider risk management techniques, and apply other filters to enhance the strategy's performance.

3.Adjust the EMA lengths based on the specific financial instrument and trading timeframe you are working with.

4.Use proper risk management practices and exercise caution when executing trades based on the strategy's signals.
## Disclaimer 🚫🚫

Trading and investing in financial markets carries potential risks. The EMA Crossover Strategy is provided for educational and informational purposes only. The strategy does not guarantee profitable results, and the developer and OpenAI (the creator of this language model) are not responsible for any losses incurred from using this strategy.

## screenshots

BankNifty chart with the Strategy on it

<img width="960" alt="image" src="https://github.com/Tharunn25/5-20-Ema-corssover-strategy/assets/98308855/8742606c-5a8c-45ae-924f-a6620f25678f">

Overview of the strategy

<img width="883" alt="image" src="https://github.com/Tharunn25/5-20-Ema-corssover-strategy/assets/98308855/d9e8637b-8fbf-4c7b-89ee-66d5e76596a3">

Performance Summary of the strategy

<img width="881" alt="image" src="https://github.com/Tharunn25/5-20-Ema-corssover-strategy/assets/98308855/1348a34d-ee01-4dd0-a20e-a8e6194be94d">

list of Trades Taken 

<img width="880" alt="image" src="https://github.com/Tharunn25/5-20-Ema-corssover-strategy/assets/98308855/a3f0d053-d686-47be-b861-573958e42878">


