# Warning
Like most systems created with Mineflow, EconMF can be unstable if its usual behavior is modified. It is not recommended to modify if you do not have an exact idea of what you are doing.

# 1. Configs
You can get the data from the configuration files using the "Create config file" action and putting the name of the configuration file from which you want to obtain the data, the name of the variable can be anything. Remember that there are two configuration files:
- money
- econfig

# 2. Get the data
The amount of money is kept in a key with the player's name. In case you wanted to get the player's money, you would have to carry out the previous step and then place the file variable with the corresponding key. Example:
- {money.{target.name}}
