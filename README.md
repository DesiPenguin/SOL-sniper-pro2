<h1 align="center"> SOL-sniper2 </h1> <br>
<p align="center">
  <a href=""> 
    
  </a>
</p>

<p align="center">
  A pocket-sized bot designed for taking profits or executing buy/sell transactions on Raydium.
</p>


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#Installation)
- [Usage](#Usage)
- [Setting](#Setting-)
- [Disclaimer ](#Disclaimer)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

The SOL-sniper2 is an innovative tool within the thriving Solana ecosystem, specifically crafted to address a prevalent challenge that traders encounter: the risk of losing profit opportunities after acquiring tokens on the Solana network, which can result in token rug-pulls or dumps. This software not only incorporates sniping capabilities, enabling users to swiftly purchase tokens at launch, but also includes trading tools to enhance their trading positions.


## Features

A few of the things you can do with SOL-sniper2:

- Sniping: Execute buy transactions instantly when liquidity is added to an SPL token, ensuring you're among the first to buy in promising new tokens.
- Take Profit: Automatically sell tokens at a predefined profit percentage, securing gains.
- Buy/Sell x Times: Execute repeated buy orders to average down or scale into positions.
- Sell Limit Order: Set your tokens to sell automatically at a predetermined price, locking in profits.
- User friendly interface - hands-on interface
- **Making the first to trade in new tokens.**

## Installation

- Downloads Python ( Recommend the latest version )  [Python 3.13.0](https://www.python.org/downloads/)
-  ***VERY IMPORTANT***: When installing Python also install **"Add python.exe to path"** and ***"Use admin privileges when installing py.exe:*** => Tick

-  Linux:
```python
sudo apt update
sudo apt upgrade
sudo apt install python3
python3 --version
```

- Update `pip` Run the following command to update pip to the latest version

```python
python -m pip install --upgrade pip
```
- Clone or download the project

```git 
git clone https://github.com/DesiPenguin/SOL-sniper2.git
```

Option 2: Download the project directly

Go to the project's GitHub page, click the "Code" button and select "Download ZIP". Unzip the downloaded ZIP file to get the project folder.

- Navigate to the project folder

Open a terminal and navigate to the project folder

```python
cd SOL-sniper2
```

- Install libraries

Run the following command to install the required libraries for the project:

```python
pip install -r requirements.txt
```

## Usage

- Run the project

Run the following command to start the project:



```python
python main.py
```



## Setting
- **BALANCE** : Show Balance & Profit
- **BUY DELAY** : In seconds after launch. Set to 0, Token will buy immediately after token launch
- **TAKE PROFIT** : Take-Profit Order (TP) . Token places a sell order and confirms immediately after reaching the target
- **SELL DELAY** : to the number of seconds you want to wait before selling the token. Set to 0, token will be sold immediately after it is bought.
- **CHECK RUG** : Set to true to check the risk score and protect against rug pulls.


## Disclaimer

- This extension is not affiliated with Solana Foundation or Solana Labs. It is a non-profit community project.
- Sol sniper2 is in active development, so all the snippets are subject to change.
- The snippets are unaudited. Use at your own risk.

