# Array-Storage-3
Array Storage.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract ArrayStorage {
    uint[] public numbers;

    function addNumber(uint _num) public {
        numbers.push(_num);
    }
}
