# MT5 iBotTrader

This code is for the MT5 iBotTrader Expert Advisor, developed by the Forex Robot Easy Team. It is designed for price action trading and includes an AI algorithm for making trading decisions.

## How it Works

The Expert Advisor class, `iBotTrader`, is the main component of this code. It includes event handlers for `OnTick`, `OnInit`, `OnDeinit`, and `OnStart`. 

In the `OnTick` event handler, the AI algorithm for price action trading is implemented. This is where the trading logic is executed.

In the `OnInit` event handler, the trading symbol parameters are set using the `SetSymbolParameters` function of the `CTrade` class instance. The AI engine parameters can also be set here.

The `OnDeinit` event handler is used for performing necessary cleanup actions when the program is stopped.

The `IsFridayHour` function is used to check if it is a Friday hour. The logic for this check can be implemented here.

The `CalculateLotSize` function is used to calculate the lot size for trading XAUJPY based on the given risk percentage. The lot size calculation logic can be implemented here.

The `OnStart` event handler is the main entry point of the Expert Advisor. It increments the sales count, sets the promotional price for the EA, and displays it. It also checks and resolves any minor bugs from previous versions. Finally, it starts the trading based on the AI algorithm by calling the `OnTick` function.

The `OnStart` function is the entry point of the program. It initializes the Expert Advisor by calling the `OnInit` function and starts it by calling the `OnStart` function.

The `OnDeinit` event handler is used for performing necessary cleanup actions when the program is stopped.

## Product Description

The MT5 iBotTrader is an Expert Advisor developed by the Forex Robot Easy Team. It utilizes an AI algorithm for price action trading. With its advanced trading logic, it aims to provide reliable trading signals and profitable trading opportunities.

Key Features:
- Price action trading strategy
- AI algorithm for making trading decisions
- Customizable trading symbol parameters
- Risk management with lot size calculation based on risk percentage
- Bug fixes and improvements in each version

The iBotTrader is suitable for traders who prefer automated trading and want to take advantage of price action trading strategies. It can be used on various trading symbols, including XAUUSD, XAUAUD, XAUJPY, and XAUEUR.

Please note that ForexRobotEasy is not the official developer of this product. We only provide this sample code as a demonstration of how the iBotTrader Expert Advisor can work. For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-mt5-ibottrader-new-version-v-1-12-fixes-minor-bugs-and-trade-opening-issues/). To find the official developer of this product, please use the MQL5 platform.
