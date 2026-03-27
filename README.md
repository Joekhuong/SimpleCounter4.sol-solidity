# SimpleCounter4.sol-solidity
Remix - Deploy Contract On Base Network SimpleCounter4.sol solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleCounter4 {
    uint public count;

    function addOne() public {
        count++;
    }

    function addTwo() public {
        count += 2;
    }
}
