# Department-VLAN-Build

Place the departments
Start with one access switch and four employee PCs.

Cable the access layer
Give every workstation its own physical switch port.

Address the hosts
Keep all four PCs in one IPv4 subnet so the VLAN boundary is the only intentional separator.

Create the VLAN boundary
Name the two broadcast domains and place each access port in the correct one.

Prove the result
Test inside each VLAN, then test across the boundary.
