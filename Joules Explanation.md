
  ---Trimo 8/28/18
 
     So I've been getting asked this question a lot recently, "What is joules?",
Joules is a self sustainable smart contract. Joules works by paying dividends
   out to it's stake holders. When you Deposit Atheios to the contract you are
  issued joules(stake). Overtime you will be issued dividends you can either 
  claim or reinvest your earnings. If you claim your dividends the ATH 
  will be sent to your address. But if you reinvest your dividends you will 
  will recieve more joules(stake) which will yield to a higher dividends payout.
  The fees allow for dividends payouts to be sustainable**
  
  There's a safe math library imported into the contract to keep it secure from
  exploits.
 - Calculations:
 - Deposit fee: Amount/(100/7) = deposit fee
 - Withdrawal fee: Amount/(100/4) = withdrawal fee
 - Stake Calculation: stakeValue + ((100/7)/totalstake)
 - TotalStake is calculated by: totalstake issued + Stake increment 
   
   So you ask yourself why would participate in Joules? Joules gives you the 
   opportunity to grow your investment by reinvesting your dividends that recieve
   (which increases your overall stake)= higher dividend payouts
   or you could look at it as passive income where you'd just claim your dividends
   and do what you wish with them. 
   Overall I look Joules as a way for people to have fun, if you're like me and
   don't have a lot ATH you can start small and let it grow. The possiblities are 
   end less.
 
	Functions:
	Deposit:Use this to send ATH to the Joules contract.
	-Claim: lets you have your dividends sent your address.
	-Reinvest: Sends your dividends directly back to the
	contract.
	-preauthorize:Disabled
	-Start game:Disabled as game is already running.
	-Withdraw: lets you take out your ATH.(scroll down!)
Call Functions <–– these functions require no gas.

	Call Functions:
	-dividendsForUser:displays your current earnings in 
	wei
	-investment: Displays your overall holdings in the 
	in the contract
	-stake:displays your current stake in the contract.
	-TotalStake: Displays total stake of all Joule holders.

 -- wei to ether calculator: https://etherconverter.online/ <--- Use to convert to ATH
 - Investment Output is also displayed in wei
 - DividendsForUser Output is displayed in wei

 –Withdrawal Instructions –please use the webwallet for this.

 **Balances are displayed in wei use the calculator above if you're not sure what the amount is.
 
	For any reason if you choose to withdraw you need
	to do the following:
	1)– Select Investment on the contract interface, 
	and enter your address and hit read. this
	is your current ATH holdings +/- (dividends 
	depending if you reinvested or claimed them.)
	2)– Next copy and paste that amount 
	"20690041609344690193" wei <– a number will appear 
	similar to the one I gave amount.
	3)– After you've copied the amount in wei, enter it
	 into the _amount box. Then you need to access your
	  wallet. Once you've done that hit write and 
	  execute the transaction.
If you have any Questions feel free to reach out to me on discord @Trimo#5265