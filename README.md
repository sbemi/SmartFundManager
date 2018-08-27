# SmartFundManager
-- Requirement : 
  SmartFundManager is a concept where Innovators come up with Project for their ideas(amount of funds required to implement their idea). 
  Then there are also group of Investors who would invest in those Projects (ideas).
  The investors are responsible for funding ether to wallet(allows multi signature) and innovators can propose a value to get funds for their projects.
  The innovative Projects can be proposed only when the investor contribution period has ended.
  Only 10% of the total amount can be proposed for a given project.
  Atleast 2 approvals must be met to get the innovation project funded.
  If there are more than or equal to 2 rejections then the Project can be rejected.
  The Innovator (proposer) can withdraw partial amounts till his withdrawl value is equal to proposed value
  
-- For Installation run the following steps :
   1)Unzip the SmartFundManager.tar.gz using Winzip or anyother compatable tool
   2)ganache-cli
   3)npm install
   4)truffle compile
   5)truffle migrate --reset --network=development
   6)truffle test
   7)npm start
