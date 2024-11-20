
# GoQuant Order Execution and Management System (OEMS)

## Overview

**GoQuant OEMS** is a high-performance C++17 application designed for interacting with the Deribit cryptocurrency trading platform. This application supports various trading functionalities, including placing, modifying, and canceling orders, as well as managing open orders, positions, and retrieving order books. It includes a WebSocket server to subscribe clients to specific symbols and continuously stream order book updates.

## Features

- **Place Orders:** Place market and limit orders on Deribit.
- **Modify Orders:** Update existing orders with new quantities or prices.
- **Cancel Orders:** Cancel open orders by order ID.
- **Retrieve Order Book:** Fetch and display the order book for specific trading pairs.
- **View Current Positions:** Display current open positions.
- **WebSocket Server:** Allows clients to subscribe to symbols and receive real-time order book updates.
- **Supported Markets:** Spot, futures, and options for all supported symbols.

## Scope

- Supports **Spot, Futures, and Options** markets.
- Provides low-latency access to **all supported symbols** on Deribit.
- **Websocket server** that clients can connect to and subscribe to a symbol by sending a message.

## Prerequisites

- **C++ Compiler:** C++17 or later.
- **CMake:** Version 3.10 or later.
- **Visual Studio 2022:** or another compatible C++ IDE.
- **vcpkg:** A package manager for C++ libraries.

## Dependencies

- **Drogon:** For HTTP and WebSocket client/server functionality.
- **cURL:** For HTTP requests.
- **OpenSSL:** For handling secure connections.
- **JsonCpp:** For JSON parsing.

