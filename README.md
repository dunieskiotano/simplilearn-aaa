# AWS Solutions Architect Associate - Simplilearn

<h1>INFORMATION ON AWS</h1>

EC2 => Elastic Compute Cloud => server in the cloud => virtual machine in AWS

<h2>What is scaling?</h2>
Scale out => Increasing the number of servers<br/>
Scale in => Decreasing the number of servers<br/>
Scale up => Increasing the capacity/power of the server (+ CPU, + RAM, Storage, etc)<br/>
Scale down  => Decreasing the capacity/power of the server ( - CPU,  -RAM, Storage, etc)

<h2>Reserve Instances (RI)</h2>
1-yr term, 3-yr term, up to 75 % discounts

<h2>Three choices for RI:</h2>
<strong>AURI</strong> -> All Upfront Reserved Instances => biggest discounts<br/>
<strong>PURI</strong> -> Partial Upfront Reserved Instances => smaller discounts<br/>
<strong>NURI</strong> -> No Upfront Reserved Instances => much smaller discounts<br/>

<h2>AWS Pricing Model:</h2>
1.	Pay for what you use<br/>
2.	Pay less when you reserve<br/>
3.	Pay less when you use more<br/>
4.	Pay less as AWS grows => Since 2006, AWS has decreased the prices 75 times<br/>

<h2>Three fundamental drivers of cost with AWS:</h2>
1.	<span style="color: red;">Compute</span> (charged by hour/second, instance type – t3.micro, x4.large)<br/>
2.	<span style="color: red;">Storage</span> (typically per GB)<br/>
3.	<span style="color: red;">Data transfer</span> (Outbound is aggregated and charged, inbound has no charge, charged typically per GB)<br/>


<h2>Four types of instances:</h2>
1.	On-demand Instances (spiky, short-term, unpredictable workloads)<br/>
2.	Reserved Instances (long-term, predictable workloads)<br/>
3.	Spot Instances (up to 90% discount compared to On-demand instances. Spare capacity has and put it on auction, the highest bidder will keep the instance temporarily)<br/>

*If someone bids higher than you, you may lose the instance. If that happens, you guys have 2 minutes to react. 
4.	Dedicated Instances (government, military organization, some companies<br/>
5.	Dedicated Host <br/>
Dedicated instance is the room, and dedicated host is the hotel<br/>
CloudTrail => tracking service => enable traceability 

Region => Contains at least 1 Availability Zone(AZ) => 50 to 60 miles distance between them
Availability Zone => Contains at least 1 data center (one or more discrete data centers)
Data Center => Has between 50,000 and 80,000 servers

<h2>Helpful Links</h2>
<a href="https://aws.amazon.com/free" target="_blank">Click Here to Know about the AWS Free Tier</a>

