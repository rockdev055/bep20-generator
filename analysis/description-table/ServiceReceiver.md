## SÅ«rya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| dist/ServiceReceiver.dist.sol | c82d86212412d090a68f0d78b2f291b5adb29e30 |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     â      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **Context** | Implementation |  |||
| â | _msgSender | Internal ð |   | |
| â | _msgData | Internal ð |   | |
||||||
| **Ownable** | Implementation | Context |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | owner | Public âï¸ |   |NOâï¸ |
| â | renounceOwnership | Public âï¸ | ð  | onlyOwner |
| â | transferOwnership | Public âï¸ | ð  | onlyOwner |
||||||
| **ServiceReceiver** | Implementation | Ownable |||
| â | pay | Public âï¸ |  ðµ |NOâï¸ |
| â | getPrice | Public âï¸ |   |NOâï¸ |
| â | setPrice | Public âï¸ | ð  | onlyOwner |
| â | withdraw | Public âï¸ | ð  | onlyOwner |
| â | _toBytes32 | Private ð |   | |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    ð    | Function can modify state |
|    ðµ    | Function is payable |
