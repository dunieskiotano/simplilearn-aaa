# AWS Solutions Architect Associate - Simplilearn

<h1>INFORMATION ON AWS</h1>

EC2 => Elastic Compute Cloud => server in the cloud => virtual machine in AWS

What is scaling?
Scale out => Increasing the number of servers
Scale in => Decreasing the number of servers

Scale up => Increasing the capacity/power of the server (+ CPU, + RAM, Storage, etc)
Scale down  => Decreasing the capacity/power of the server ( - CPU,  -RAM, Storage, etc)


Reserve Instances (RI)
1-yr term, 3-yr term, up to 75 % discounts

Three choices for RI:
AURI -> All Upfront Reserved Instances => biggest discounts
PURI -> Partial Upfront Reserved Instances => smaller discounts
NURI -> No Upfront Reserved Instances => much smaller discounts

AWS Pricing Model:
1.	Pay for what you use
2.	Pay less when you reserve
3.	Pay less when you use more
4.	Pay less as AWS grows => Since 2006, AWS has decreased the prices 75 times

Three fundamental drivers of cost with AWS:
1.	Compute (charged by hour/second, instance type – t3.micro, x4.large)
2.	Storage (typically per GB)
3.	Data transfer (Outbound is aggregated and charged, inbound has no charge, charged typically per GB)




Four types of instances:
1.	On-demand Instances (spiky, short-term, unpredictable workloads)
2.	Reserved Instances (long-term, predictable workloads)
3.	Spot Instances (up to 90% discount compared to On-demand instances. Spare capacity has and put it on auction, the highest bidder will keep the instance temporarily)

*If someone bids higher than you, you may lose the instance. If that happens, you guys have 2 minutes to react. 
4.	Dedicated Instances (government, military organization, some companies
5.	Dedicated Host 
Dedicated instance is the room, and dedicated host is the hotel
CloudTrail => tracking service => enable traceability 

Region => Contains at least 1 Availability Zone(AZ) => 50 to 60 miles distance between them
Availability Zone => Contains at least 1 data center (one or more discrete data centers)
Data Center => Has between 50,000 and 80,000 servers

AWS Free Tier:
https://aws.amazon.com/free

