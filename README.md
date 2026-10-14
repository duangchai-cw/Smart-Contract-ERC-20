## Contract Deployment

This project contains the `kig.sol` Solidity contract, an ERC-20 token implementing standard functions for transfers, approvals, and balance management.

### Contract Details

**Name**: onlyworknosleep (KIG)  
**Description**: ERC-20 token with 8 decimals and 21,000,000 total supply  
**Compiler**: Solidity ^0.8.34  
**Deployment Address**: [0x4151CCB3F36253504b3254B11A494953E8759213](https://explorer.labchain.la/address/0x4151CCB3F36253504b3254B11A494953E8759213?tab=contract)

### Contract Features

- `transfer()`: Transfer tokens between accounts
- `transferFrom()`: Transfer tokens with approval
- `approve()`: Approve spending on behalf of another account
- `balanceOf()`: Get account balance
- `allowance()`: Check approved spending amount
- Custom errors for common failure scenarios

### Deployment Details

The contract was deployed to the LAB Chain network. All functionality is standard ERC-20 with custom error handling for robust transaction safety.

### Verification

You can verify the contract source code on the LAB Chain explorer:

[https://explorer.labchain.la/address/0x4151CCB3F36253504b3254B11A494953E8759213?tab=contract](https://explorer.labchain.la/address/0x4151CCB3F36253504b3254B11A494953E8759213?tab=contract)

## Usage

### Prerequisites

- Solidity compiler ^0.8.34 or higher
- Target network: LAB Chain

### Compiling

```bash
forge build
```

### Deploying

Deploy using a deployment script:

```bash
forge script script/Deploy.s.sol --rpc-url <rpc-url> --private-key <private-key>
```

## License

This contract is deployed and maintained under the terms specified in the LICENSE file.