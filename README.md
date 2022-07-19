
# C-Coin

[![Contributors](https://img.shields.io/github/contributors/dsckgec/C-Coin.svg)](https://github.com/dsckgec/C-Coin/graphs/contributors) [![Forks](https://img.shields.io/github/forks/dsckgec/C-Coin.svg)](https://github.com/dsckgec/C-Coin/network/members) [![Issues](https://img.shields.io/github/issues/dsckgec/C-Coin.svg)](https://github.com/dsckgec/C-Coin/issues) [![Pull Request](https://img.shields.io/github/issues-pr-closed-raw/dsckgec/C-Coin)](https://github.com/dsckgec/C-Coin/pulls)


![Blockchain](https://blogs.iadb.org/caribbean-dev-trends/wp-content/uploads/sites/34/2017/12/Blockchain1.jpg)


## Contents

1. [Description](#description)
1. [Project structure](#project-structure)
1. [Getting started](#getting-started)
1. [Contributing](#contributing)
1. [Authors](#authors)
1. [License](#license)


## Description

A blockchain is a growing list of records, called blocks, that are securely linked together using cryptography. Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data. Blockchains are typically managed by a peer-to-peer network for use as a publicly distributed ledger, where nodes collectively adhere to a protocol to communicate and validate new blocks. Although blockchain records are not unalterable as forks are possible, blockchains may be considered secure by design and exemplify a distributed computing system with high Byzantine fault tolerance.

Outline of Project

- Define the characteristics of underlying blockchain.
- Use a Flask implementation to imitate transaction, mining and all other cryptocurrency behaviors.
- Play around with the implementation by creating multiple instances (nodes) using the same blockchain Definition.

## Project structure

```
  ├── Transaction/                            Empty directory to play around and understand transaction of C-coins
  ├── Defining Blockchain and C-coin.py       Code and Definition of Blockchain with which you can trade C-Coins
```
## Getting started


### Prerequisites

#### Software Needed
 
  1. Postman
  2. Any Web Browser

#### Knowledge Needed

- Strong Idea of how a blockchain functions and its behaviors
- Python OOPs Knowledge
- Very basic understanding of git and github:

    1.  What are repositories (local - remote - upstream), issues, pull requests
    2.   How to clone a repository, how to fork a repository, how to set upstreams
    3.   Adding, committing, pulling, pushing changes to remote repositories.


### Installing

Clone the project

```bash
  git clone https://github.com/DSCKGEC/C-Coin.git
```

Go to the project directory

```bash
  cd C-Coin
```

To run this:
```bash
  pip install DateTime
  pip install hashlib
  pip install Flask
  pip install requests
  pip install uuid
  pip install urllib3
```


## Contributing

Please read [contributing.md](contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

- [@sbk2k1](https://github.com/sbk2k1)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.