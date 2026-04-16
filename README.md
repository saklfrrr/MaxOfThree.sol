# MaxOfThree.sol
MaxOfThree.sol
pragma solidity ^0.8.20;
contract MaxOfThree {
    function max(uint a,uint b,uint c) public pure returns(uint){
        uint m = a > b ? a : b;
        return m > c ? m : c;
    }
}
