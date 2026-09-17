# Signals  
  
Adds an Call Signal action and a On Signal Call condition to the General section in GDevelop.  
Adds a Call Signal with Strength action and a Compare Signal Strength condition to the General section in GDevelop.  
This allows for re-use of actions from different conditions without the need for extensions or re-writing the same actions repeatedly.
  
Use Call Signal as an action, and then use On Signal Call as a condition, using a Signal Name as the linking parameter.  
This call can be re-used as many times as you want, will go through the list of actions on the sheet once when called.  
Works with sub-events, Call Signal can be put before On Signal Call and vice versa.  
  
Each Signal can be called with or without a strength value.  
This strength value can then be compared to another value in the Action Sheet.  
Checking for a signal call has no affect on strength, these are separate comparisons.  
If a signal is called without a strength, this comparison will always evaluate to false.  

<br>

## Example Usage
  
*Test_Signals*  
![](/Test_Signals/assets/2.jpg)  