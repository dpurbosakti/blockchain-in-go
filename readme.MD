# Blockchain CLI Readme

This CLI (Command Line Interface) allows you to interact with a blockchain. You can print all the blocks of the blockchain or add a new block to it.

## How to Run

Make sure you have Go installed on your system. You can download it from [here](https://golang.org/dl/).

1. Clone this repository:

    ```bash
    git clone https://github.com/dpurbosakti/blockchain-in-go.git
    ```

2. Navigate to the project directory:

    ```bash
    cd blockchain-in-go
    ```

3. Run the following commands in your terminal:

    To print all the blocks of the blockchain:
    
    ```bash
    go run . printchain
    ```
    
    To add a block to the blockchain:
    
    ```bash
    go run . addblock -data "block_data"
    ```

    Replace `"block_data"` with the actual data you want to include in the new block.

## Example

To add a block with data "Hello, World!" to the blockchain, run:

```bash
go run . addblock -data "Hello, World!"
