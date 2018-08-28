# SmartFundManager
-- Description of Requirement : 
SmartFundManager is a collborative tool where Startups(Innvoators) and Investors collaborate to get the funding for the projects.
Innovators come up with Project for their ideas(amount of funds required to implement their idea). 
Then there are also group of Investors who would invest in those Projects (ideas). 
The First step is investors are responsible for funding ether to wallet(allows multi signature) and innovators can propose a value to get funds for their projects. 
The innovative Projects can be proposed only when the investor contribution period has ended. 
Only 10% of the total amount can be proposed for a given project. 
Atleast 2 approvals must be met to get the innovation project funded. 
If there are more than or equal to 2 rejections then the Project can be rejected. 
The Innovator (proposer) can withdraw partial amounts till their withdrawl value is equal to Project proposed value
  
-- Run the following steps for installation :
   1)Extract the SmartFundManager.tar.gz in ubuntu any other compatable tool (this is the video just in case you want to know how to extract tar.gz file in ubuntu https://youtu.be/KKbGGbczheI)
   2)ganache-cli
   3)npm install
   4)truffle compile
   5)truffle migrate --reset --network=development
   6)truffle test
   7)npm start
   8)For getting understanding of flow of SmartFundManager functionality while testing I have prepared a document with screens (Steps for testing functionality.docx) you may go through this document before you start testing.
