# BlueSwift Grid Rescue MT4 - ReadMe

## Introduction
This ReadMe file provides an overview of the code for the BlueSwift Grid Rescue MT4 robot. This code is developed by the Forex Robot Easy Team and is meant to be used for automated trading in the MetaTrader 4 platform.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/blueswift-grid-rescue-mt4-unbiased-software-review/). Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Code Overview
The code for the BlueSwift Grid Rescue MT4 robot is written in MQL5 language and consists of the following sections:

1. Include necessary libraries and define global variables: This section includes the required libraries and defines global variables such as the trade object and a flag to check if the robot is initialized.

2. Define grid parameters: This section defines the parameters for the grid strategy, including the grid step size and the number of grid levels.

3. Define trading function: The `TradeGrid()` function is responsible for executing the grid trading strategy. It calculates the grid levels based on the current price and places buy and sell trades at each level if there are no open trades at that level.

4. Initialize the robot: The `OnInit()` function is called when the robot is initialized. It enables automated trading and sets the expert magic number, deviation in points, and type filling.

5. Handle tick events: The `OnTick()` function is called on each tick event. It calls the `TradeGrid()` function to execute the grid trading strategy.

6. Handle deinitialization: The `OnDeinit()` function is called when the robot is deinitialized. It closes all open trades before deinitialization.

7. Script program start function: The `OnStart()` function is the entry point of the script. It runs the robot indefinitely by sleeping for 1 second in each iteration.

## Product Description
BlueSwift Grid Rescue MT4 is an automated grid trading robot developed by the Forex Robot Easy Team. It is designed to execute a grid trading strategy in the MetaTrader 4 platform.

The robot uses a predefined grid step size and number of grid levels to place buy and sell trades at specified price levels. It continuously monitors the market and checks if there are no open trades at each grid level. If there are no open trades, it places a buy trade and a sell trade at the current level.

BlueSwift Grid Rescue MT4 is a versatile and customizable robot that allows traders to adjust the grid parameters according to their trading preferences. It offers the potential for profit in both trending and ranging markets.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/blueswift-grid-rescue-mt4-unbiased-software-review/). Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.
