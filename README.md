# SimplePing.sol
Base - Smart Contract Deployed by Remix SimplePing.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimplePing {
    function ping() public pure returns (string memory) {
        return "pong";
    }
}
