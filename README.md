# Repro for yarn node issue on Windows

1. Clone/checkout this repo on Windows
1. Execute `yarn test`. You should see the file `node.js` get opened 👎🏻
1. Rename `node.js` to `_node.js`.
1. Execute `yarn test`. You should see the following on the command line 👍🏻
    ```
    $ yarn test
    OK
    ```