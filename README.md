# Decentralized Stable Coin (DSC) Smart Contract

## Overview
The Decentralized Stable Coin (DSC) contract is an ERC20 token meant to be owned by the DSCEngine smart contract. It can be minted and burned by the DSCEngine smart contract.

This stablecoin is considered:
- **Collateral Type:** Exogenous
- **Minting (Stability Mechanism):** Decentralized (Algorithmic)
- **Value (Relative Stability):** Anchored (Pegged to USD)
- **Collateral Type:** Crypto

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Layout of Contract](#layout-of-contract)
  - [Version](#version)
  - [Imports](#imports)
  - [Interfaces, Libraries, Contracts](#interfaces-libraries-contracts)
  - [Errors](#errors)
  - [Type Declarations](#type-declarations)
  - [State Variables](#state-variables)
  - [Events](#events)
  - [Modifiers](#modifiers)
  - [Functions](#functions)
- [Layout of Functions](#layout-of-functions)
  - [Constructor](#constructor)
  - [Fallback Function](#fallback-function)
  - [External](#external)
  - [Public](#public)
  - [Internal](#internal)
  - [Private](#private)
  - [View & Pure Functions](#view--pure-functions)
- [SPDX-License-Identifier](#spdx-license-identifier)

## Installation
```bash
npm install
