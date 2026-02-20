# contract4.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract Contract4 {
    uint public total;

    function add(uint x) public {
        total += x;
    }
}
