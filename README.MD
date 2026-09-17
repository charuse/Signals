# Signals  
  
#### Adds Call Signal and Call Signal With Strength actions and On Signal Call condition to GDevelop.  
This allows for re-use of actions from different conditions.  
Reduces the need for re-writing the same actions repeatedly.  

Use Call Signal as an action, and then use On Signal Call as a condition, using a Signal Name as the linking parameter.  
This call can be re-used as many times as you want, will go through the list of actions on the sheet once when called.  
Works with sub-events, Call Signal can be put before On Signal Call and vice versa.  

Each Signal can be called with or without a strength value.  
This strength value can then be compared to another value in the Action Sheet.  
Checking for a signal call has no affect on strength, these are separate comparisons.  
Calling without a strength will set its `GetStrength` return value to `-1`  
Strength value can be checked using `Signals::GetStrength("Signal Name")`<br>

## Example Usage

*Test_Signals*  
![](/Test_Signals/assets/pic.jpg)  