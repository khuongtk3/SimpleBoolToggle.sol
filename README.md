# SimpleBoolToggle.sol
Contract deployed via Web3 SimpleBoolToggle.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleBoolToggle {
    bool public active;

    function toggle() public {
        active = !active;
    }
}
