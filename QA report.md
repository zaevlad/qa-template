# Overall Analysis

</br>

* ## About the Protocol
  [Protocol name ](linkToProtocol) Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

</br>

* ## Low Severity Issues
  * **[[L-01] Description of the issue #1](#Short-description-of-L-issue-1)**
  * **[[L-02] Description of the issue #2](#Short-description-of-L-issue-2)**

</br>

* ## Non-Critical Severity Issues
  * **[[N-01] Description of the issue #1](#Short-description-of-N-issue-1)**
  * **[[N-02] Description of the issue #1](#Short-description-of-N-issue-2)**

</br>

## **[L-01] Short description of L issue**<a name="L-01"></a>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### **Links to affected code**

- [contractName#71-73](https://github.com/)
- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua: 

### **Recommended Mitigation Steps**

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

</br>

## **[L-02] Short description of L issue 2**<a name="L-02"></a>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor `incididunt` ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis `nostrud` exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat..

### **Links to affected code**

- Could be added, for instances, [here](https://github.com/)

### **Recommended Mitigation Steps**

- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

</br>

## **[N-01] Short description of N issue 1**<a name="N-01"></a>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
  

### **Links to affected code**

-  Lorem ipsum dolor sit amet, consectetur adipiscing elit:
   -   [here](https://github.com/)
   -   [here](https://github.com/)
   -   [here](https://github.com/)


</br>

## **[N-02] Short description of N issue 2**<a name="N-02"></a>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
  

### **Links to affected code**

-  Lorem ipsum dolor sit amet, [here](https://github.com/)

</br>


# Hints to make your report looks awesome

</br>

## Another way to write a table of contents

| *Issue* | *Description*                                                                  |
|---------|--------------------------------------------------------------------------------|
| [L-01]  | Lorem ipsum dolor sit amet, consectetur adipiscing elit                        |
| [L-02]  | Lorem ipsum dolor sit amet, consectetur adipiscing elit                        |
| [N-01]  | Lorem ipsum dolor sit amet, consectetur adipiscing elit                        |
| [N-02]  | Lorem ipsum dolor sit amet, consectetur adipiscing elit                        |

</br>

## And one more

| ID | Description | Severity |
| :-: | - | :-: |
| [L-01](#l-01-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elit | Low |
| [L-02](#l-02-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elit | Low |
| [L-03](#l-03-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elit | Low |
| [L-04](#l-04-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elit | Low |
| [L-05](#l-05-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elit | Low |
| [N-01](#n-01-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elit | Non-Critical |
| [N-02](#n-02-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elit | Non-Critical |
| [N-03](#n-03-link) | Lorem ipsum dolor sit amet, consectetur adipiscing elitr | Non-Critical |

</br>

## If you want to show some differences in the code, use:

```diff
  function cancelAllBids(uint256 _tokenid) public {
+       uint256 totalAmount;
        for (i=0;) {
            if (i = 2) {
-               (bool success, ) = payable(...).call{}("");
+               totalAmount = totalAmount + ...;
            } else {}
        }
+       (bool success, ) = payable(msg.sender).call{value: totalAmount}("");
  }
```

</br>

## If you want to paste a Solidity code, use:

```solidity 
  function participateToAuction(uint256 i) public payable {
        require(msg.value > 2);
        auction[_tokenid].push(newId);
    }
```

</br>

## If you want to paste a link use:

[textToShow](https://yourLink)

</br>

## If you want to quote some text from the protocol docs use:

> Lorem ipsum dolor sit amet, consectetur adipiscing elit

</br>

## If you want to past an image use:

![imageDesc](https://linkToImage)

</br>

