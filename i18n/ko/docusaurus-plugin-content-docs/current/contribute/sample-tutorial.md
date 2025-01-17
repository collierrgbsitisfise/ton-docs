# Sample Tutorial Structure 

## Introduction

The Introduction heading **must** be H2: `## Introduction`

This section is for you to explain the context for this tutorial and why it matters, what we're going to build and learn in this tutorial.

- Explain this section like you're explaining it to 5-year-old (**[ELI5](https://www.dictionary.com/e/slang/eli5/)**)
- Explain everything in 5-6 lines maximum.

*For example:*

>A smart contract is simply a computer program running on TON blockchain - or more exactly its [TVM](/learn/tvm-instructions/tvm_overview) (_TON Virtual Machine_). The contract is made of code (_compiled TVM instructions_) and data (_persistent state_) that are stored in some address on TON.

## Prerequisites

The Prerequisites heading **must** be H2: `## Prerequisites`

This section is for you to explain any prior knowledge needed or any existing tutorials that need to be completed first, any tokens that are needed, mention them here.

*For example:*

>In this tutorial, we're going to mint a jetton on testnet, so before we proceed further make sure to prepare your [testnet](/develop/smart-contracts/environment/testnet) wallet first with enough balance.

## Requirements

The Requirements heading **must** be H2: `## Requirements`

**OPTIONAL :** Embed any video content in this section, if your tutorial has any.

Any technology that needs to be installed **prior** to starting the tutorial and that the tutorial will not cover (`TON Wallet Extension`, `node`, etc). Do not list packages that will be installed during the tutorial.

*For example:*

- We'll need TON Wallet Extension in this tutorial, install it from [HERE](https://chrome.google.com/webstore/detail/ton-wallet/nphplpgoakhhjchkkhmiggakijnkhfnd).
- Make sure to have NodeJS 12.0.1+ version installed.

## Body of the Tutorial

- Please do not use "Body of the Tutorial" as a heading, use your own heading that is relevant to the material.
  - "Getting started" is acceptable if you can't think of anything else 😉
- Add any text content necessary to guide readers through your tutorial, and ***remember to proofread your content*** for spelling and grammar before you submit your tutorial.
  - [Grammarly](http://grammarly.com) is a good free program that help you to avoid grammar problems.

### Key points

- Do not use "Body of the Tutorial" as a heading!
- **Keep all sub-headings at H3,** don't go into H4 or lower**:**
    - In Markdown syntax, two hashmarks are used for H2 headings: ##
    - Three hashmarks are used for H3 headings: ###
- Add only necessary comments in code blocks. ***Do not*** add # style comments to terminal input code blocks.
- Add all relevant code blocks:
    - Markdown syntax for code blocks is three backticks at the beginning and the end of the code block. Also make sure that all code blocks have a newline before and after the backticks. *For example*:
        - 
        \```js  
        const testVariable = 'some string';  
        someFunctionCall();  
        \```  
        
    - ALL code blocks ***must*** have a syntax highlighting type, use ```text if you are not sure.
    - \```text must be used for terminal output, terminal commands and plaintext.
    - \```javascript *or* ```js can be used for any JavaScript code.
    - \```typescript or ```ts can be used for any TypeScript code.
    - \```jsx is for ReactJS code.
    - \```cpp is for Func code.
    - Use \```graphql when highlighting GraphQL syntax.
    - Use \```json when highlighting valid JSON (for invalid JSON examples, use \```text instead).
    - \```bash should *only* be used for code blocks where you need to have # style comments. This must be done carefully because in many situations the # character will render as a markdown heading. If this happens it will usually impact the Table of Contents.
- Do not use `pre-formatted text` for emphasis - only use **bold** or *italic* text for emphasis.
- Add Images or code blocks to reflect expected terminal output.

- Take an error-driven approach when writing your tutorial: Add common errors and steps to troubleshoot the errors, *for example:*

> **Not able to connect to the Testnet, getting an error on executing  
> `node deploy:testnet` command.** 
>
> Let's check for some common causes:
>  
* Make sure you have enough balance on your generated testnet wallet in `.env`. If not, please add some testnet coins from the faucet giver. 
* If you're still experiencing the same issue, reach out devs on the [Dev Chat](https://t.me/TonDev_eng/) for help.
>

## Conclusion

The Conclusion heading **must** be H2: `## Conclusion`

This section should summarize what was learned in the tutorial, reinforce key points and also congratulate the learner for completing the tutorial. Use a maximum of 5-6 lines.
*For example*:

> We created a simple new FunC contract with the counter functionality. We then built and deployed it on-chain and finally interacted with it by calling a getter and sending a message.


Please remember that this code is not intended for production: there are still a few other things to consider if you wanted to deploy this to mainnet, such as disabling the transfer method if the token is listed on the market and so on.
>

## Next Steps *(Optional)*

The Next Steps heading **must** be H2: `## Next Steps`

Use this section to explain what can be done next after this tutorial for continued learning.
Feel free to add recommended projects and articles here which are related to this tutorial.
If you're working on any other advanced tutorials, you can briefly mention them here.

## About the Author

The About the Author heading **must** be H2: `## About the Author`

Keep it short. One or two lines at most. You can include a link to your GitHub profile + Telegram profile, however please refrain from adding your LinkedIn or Twitter here.

## References

The References heading **must** be H2: `## References`

This section ***must*** be present if you have taken any help in writing this tutorial from other documents, GitHub repos and existing tutorials.

Credit sources by adding their name and a link to the document when possible.

If it is not a digital document, include an ISBN or other form of reference.