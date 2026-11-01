# Stock Trading Platform Simulator (Zerodha style)

## Project Overview
Stock Trading Platform Simulator is a mobile application developed in Java using Google Android Studio and Firebase Realtime Database. It simulates real-time stock order placing and order book matching logic based on price-time priority.

## Features
- **User & Stock Order Input**: Place Buy and Sell limit orders.
- **Firebase Realtime Database**: Synchronizes active orders instantly across devices.
- **Order Book Display**: Visualizes sorted Buy (highest price first) and Sell (lowest price first) orders.
- **Trade Matching Algorithm**: Automatically executes orders when Buy Price >= Sell Price.
- **Custom Exception Handling**: Validates input data and handles invalid inputs using custom exceptions.

## Java & OOP Concepts Used
- **Abstraction & Inheritance**: Base `Order` abstract class extended by `BuyOrder` and `SellOrder`.
- **Encapsulation**: Private data members with getters and setters.
- **Collections Framework**: `ArrayList` and custom `Comparators` for order book sorting.
- **Exception Handling**: `InvalidOrderException` for robust validation.

## Tech Stack
- **Language**: Java 100%
- **IDE**: Google Android Studio
- **Database**: Firebase Realtime Database
