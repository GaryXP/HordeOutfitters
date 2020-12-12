# About Horde Outfitters
Horde Outfitters (H-O) is a sophisticated spreadsheet system set up to sell gear in World of Warcraft (Classic). 

The spreadsheet which is used by H-O customers is here: https://docs.google.com/spreadsheets/d/1heI5KchyTKUHXWSYy3xTPe48SlRGTY1veh-gPg2cG1I/edit?usp=sharing

Horde Outfitters had it's grand opening in November of 2019. At the time, the interface was similar, but since it opened, the work required to operate the store has been minimized. The spreadsheet system is designed to easily host a store on every server, but because each store requires a manager to keep and price inventory, only one store is currently in operation as of December 2020, managed by the creator of the spreadsheet system, GaryXP, AKA "Jer Z. Kau".

Famous on a tiny Role-Playing server in Blizzard's World of Warcraft, Jer Z. Kau has put thousands of pieces of magical gear into the hands of deserving players. The built-in in-game platform for hosting auctions has steep fees. Furthermore, auctions can only be hosted for a maximum of 48 hours. By circumventing the Auction House, a player can easily host hundreds of auctions without the constant upkeep of re-posting each auction every 2 days, and all without losing any gold to the Auction House fees! 

The Discord Channel:
To more easily access the store, players have joined the store's Discord channel. On the "bsb-store" tab at this link is the link to the customer spreadsheet.
https://discord.gg/2N56V5z


Behind-The-Scenes:
There are two other spreadsheets which work with each other to populate the spreadsheet used by customers...

The Manager Spreadsheet:
This is where the manager of the store enters all of their inventory. There is one Manager spreadsheet for each H-O Store. If a third-party decides to manage a store, they'll be given access to the Google Spreadsheet with two pre-programmed macros: one for entering a new item into the store, and one to remove sold items from the store. Prices are set automatically to be a certain fraction of the average market price (according to the user's Auctioneer data). A manual pricing option is also available for each item. The Item Name, Market Price, and Manual Price (if applicable) are then passed to the Database Spreadsheet. 

The Database Spreadsheet:
Neither the store managers nor the customers should ever see this spreadsheet. This spreadsheet contains information about hundreds of pieces of gear, and is used to populate the store spreadsheet with the appropriate information. For example, if the manager stocks the "Serpentine Sash" the Database Spreadsheet finds the relevant information about the sash, including the level required to use it (53, if you care), what type of armor it is (Leather), what 'slot' it belongs to ("waist" in this case), and who it's good for (Rogues and Druids). This information is passed from the Database to the to the Store Spreadsheet, where it is visible to potential customers.
