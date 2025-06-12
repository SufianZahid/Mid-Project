cmake_minimum_required(VERSION 3.31)
project(exchange_project)

set(CMAKE_CXX_STANDARD 20)

add_executable(exchange_project main.cpp CSVReader.h
        CSVReader.cpp MerkelMain.h MerkelMain.cpp
        OrderBook.h OrderBook.cpp
        OrderBookEntry.h OrderBookEntry.cpp
        Wallet.h Wallet.cpp 20200317.csv 20200601.csv)
