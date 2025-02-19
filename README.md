# NEXUS
更好  
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract Counter {
    uint256 private count;
    
    event CountIncremented(uint256 newCount);
    
    function increment() public {
        count += 1;
        emit CountIncremented(count);
    }
    
    function getCount() public view returns (uint256) {
        return count;
    }
}
nexus-counter/
├── contracts/
│   └── contracts/
│       └── Counter.sol
├── frontend/
│   ├── pages/
│   │   └── index.tsx
│   └── package.json
└── package.json
