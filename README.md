# FirewallCreationScript
A script that creates a firewall to block any connections between a source and destination IP address

The script takes two shell arguments, the first being the source IP address, and the second being the destination IP address. A rule is created the blocks any connections between the two addresses and prints that the rule was added if it doesn't already exist. If the rule already exists it asks the user if they would like to delete the rule and does so if they type "y".
