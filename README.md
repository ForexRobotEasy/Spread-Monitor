# Spread Monitor ReadMe File

This ReadMe file provides an overview of the code for the Spread Monitor indicator in MQL5. It includes a description of how the code works and a product description based on this code.

## Code Description

The Spread Monitor indicator is designed to monitor the spread of multiple currency pairs in real-time. It displays an oscillator chart that represents the spread value for each currency pair.

The code includes the following features:

1. Spread Monitor settings:
   - `spreadLevel`: A parameter that defines the spread level.
   
2. Spread Monitor oscillator colors:
   - `spreadColor`: The color of the oscillator.
   - `spreadBelowLevelColor`: The color when the spread is below the spread level.
   - `spreadAboveLevelColor`: The color when the spread is above the spread level.

3. Spread Monitor oscillator buffer:
   - `spreadBuffer`: An array that stores the spread values for each currency pair.

4. Spread Monitor initialization function:
   - `OnInit()`: Initializes the oscillator buffer.

5. Spread Monitor deinitialization function:
   - `OnDeinit()`: Clears the oscillator buffer.

6. Spread Monitor tick event function:
   - `OnTick()`: Retrieves the spread for each currency pair, stores it in the oscillator buffer, and sets the oscillator color and value.

7. Spread Monitor chart event function:
   - `OnChartEvent()`: Handles chart resize events and creates the spread oscillator objects.

## Product Description

Spread Monitor is an instant forex pair spread indicator that allows traders to monitor the spread of multiple currency pairs in real-time. It provides valuable information about the liquidity and volatility of the forex market.

Key Features:
- Real-time spread monitoring: The indicator displays an oscillator chart that represents the spread value for each currency pair.
- Customizable spread level: Traders can set a specific spread level parameter to be notified when the spread goes above or below a certain threshold.
- Visual color coding: The indicator uses different colors to indicate when the spread is below or above the spread level, making it easy for traders to spot potential trading opportunities.
- User-friendly interface: The indicator is easy to install and use, with clear and intuitive visual representations of the spread values.

Please note that ForexRobotEasy is not the official developer of this product. We only provide this code as a sample that can work similarly to the described product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/spread-monitor-review-instant-forex-pair-spread-indicator/).
