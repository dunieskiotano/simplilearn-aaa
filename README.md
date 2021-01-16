# AWS Solutions Architect Associate - Simplilearn

<h1>INFORMATION ON AWS</h1>

EC2 => Elastic Compute Cloud => server in the cloud => virtual machine in AWS

<h2>What is scaling?</h2>
Scale out => Increasing the number of servers
Scale in => Decreasing the number of servers

Scale up => Increasing the capacity/power of the server (+ CPU, + RAM, Storage, etc)
Scale down  => Decreasing the capacity/power of the server ( - CPU,  -RAM, Storage, etc)


<h2>Reserve Instances (RI)</h2>
1-yr term, 3-yr term, up to 75 % discounts

<h2>Three choices for RI:</h2>
AURI -> All Upfront Reserved Instances => biggest discounts
PURI -> Partial Upfront Reserved Instances => smaller discounts
NURI -> No Upfront Reserved Instances => much smaller discounts

<h2>AWS Pricing Model:</h2>
1.	Pay for what you use
2.	Pay less when you reserve
3.	Pay less when you use more
4.	Pay less as AWS grows => Since 2006, AWS has decreased the prices 75 times

<h2>Three fundamental drivers of cost with AWS:<h2>
1.	Compute (charged by hour/second, instance type – t3.micro, x4.large)
2.	Storage (typically per GB)
3.	Data transfer (Outbound is aggregated and charged, inbound has no charge, charged typically per GB)


<h2>Four types of instances:</h2>
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

<h2>AWS Free Tier:</h2>
<a href="https://aws.amazon.com/free" target="_blank">Click Here to Know about the AWS Free Tier</a>

