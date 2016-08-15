# Get-ARMAvailableIPs

This is a PowerShell script that allows you to quickly get a view and summary of your VNets in your ARM Portal. 

What it does:

Get's list of IPs taken, broken down by VNet and Subnet.
List's if the IP is taken and if so by what Azure Resource (VM NICs, ILB IP, Orphan NIC, VPN Gateway)

This allows you to specify a VNet and subnet, or all VNets and Subnets in your subscription. 

It will also output all the information to a CSV file located in C:\Temp\AvailableIPs location.


