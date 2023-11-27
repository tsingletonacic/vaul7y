# Vaul7y / Vaulty

Vaulty is a TUI for Hashicorp Vault. The goal is to support as many functionalities as possible in order to make the tool as usefu as possible.   

## Why use Vaul7y 
   
I started the tool purely for personal use as I love tools like [K9s](https://github.com/derailed/k9s) or [Wander](https://github.com/robinovitch61/wander). I generally prefer the use of CLI tools but when it came to vault and looking up at stuff, sometimes having a UI just speeds things up. I couldn't find something finished, so decided to write my own.

## Video
![gif](./images/vaulty-min.gif)

## Usage

To see detailed guide on how to use the tool see the [docs](./docs/usage.md)

## Features and Bugs

The tool is in active development and is bug heavy. There are multiple things that are on my short and long term TODO list.

If anyone decides to use this and wants to request a specific feature or even fix a bug - please open an issue :smile:

## Short term TODO list:
1. Change the logger (current one is a mess)
1. Finish adding tests (wip in another branch)
2. Finish implementing Update to existing secrets
    * Bonus: Create net new ones.
3. Support for namespace changes. 