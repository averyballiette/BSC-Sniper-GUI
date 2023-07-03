# BSC Token Sniper with PyQT GUI

## Desktop Application

This project is a desktop application designed to assist in facilitating a quick transaction between ERC-20 contracts on the BSC 
network and an individuals wallet. The tech-stack is comprised of Python, SQLite3, MongoDB, and the web3.py library. Although the targeted 
chain of this application is BSC, it could be converted to the Ethereum chain by swapping out the node information along with a few other
minor changes.
The primary focus of the application was to explore the following:

* GUI creation and design
* Parallel processing management
* Blockchain technologies

## How to run

To run this program the following are recommended and/or required:

1. Node access .. To ensure a more secure transaction (and to alter the preferred chain), the user should provide their own node
or obtain one through a provider.

2. Graphics : graphics are needed to complete the design of the application. The recommended list includes the following :

    * An "exit" icon for exiting the application
    * A "broom" icon for indicating an input reset
    * A "gas pump" icon for indicating on-chain gas prices
    * A "gear" icon for the settings button
    * A "three horizontal lines" icon for the menu button
    * A "floppy disk" icon for the save button
    * "Opposite facing arrows" icon for swapping buy/sell modes
    * A well made logo for the loading splash

3. Crypto wallet with private key : this is required to send transactions on your behalf. It can be saved in the SQLite3 database IF DESIRED.
                            *** IMPORTANT ***
        The Private key is NOT SECURE OR ENCRYPTED. Use / save at YOUR OWN RISK

4. MongoDB for confirming access to the application. (This can be easily bypassed if used personally)
