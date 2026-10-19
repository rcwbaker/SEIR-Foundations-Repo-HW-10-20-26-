**Deployment 	Public IPv4 address** 	Connection method 	**Screenshot** 	Instance terminated?

1 	**172.31.19.237** 	EC2 Connect / SSH 	**screenshots/deployment-1.png** 	**[Yes]** / No

2 	**172.31.26.235** 	EC2 Connect / SSH 	**screenshots/deployment-2.png** 	**[Yes]** / No

3 	**172.31.23.217** 	EC2 Connect / SSH 	**screenshots/deployment-3.png** 	**[Yes]** / No

**What I did, how I connected, and what the dashboard showed & Description of the launch, SSH connection, and dashboard**

First, I created a security group. I named the security group(which has the same name as my instance), gave it a description, then added two inbound rules (both SSH and HTTP with AnywhereIPv4 and descriptions).  
After creating the security group, I created the instance. I named the instance, made sure I was using a t3.micro instance in the free-tier. Created a key pair, named the key pair after my instance and clicked create and then selected that key pair. 
Selected the security group I created earlier, then, I scrolled down the “Advanced configurations” box, and pasted the EC2 script from the SEIR Foundations GitHub repo, I then selected create instance. 
I selected the instance ID found in the green notification bar and selected “connect” from the EC2 summary page it led me to. 
I was led to the SSH page, where I accepted the default selected option to connect via “instance connect” and clicked create. I was led to the dashboard where it showed me the EC2 script posted inside the terminal, revealing that I had successfully SSH’d into the EC2 server. 
I copy and pasted “seir-dashboard” and the same script was reposted in the terminal.

**Description of what the CPU, memory, disk, and uptime tell you about the instance.**

The description of the CPU, memory, disk, and uptime tell you that the EC2 instance is not running anything that it computationally costly, which is why the CPU was at “0% busy”, the memory was 177mi of 913mi, 1.7G of 8G(21% full), and the uptime(up 13 minutes) - all according to the run script output in the terminal of the SSH’d EC2 instance.

**One thing that became easier after repeating the process:**

The entire process became faster and easier to remember. The more I practiced it, the more confident and capable I became at completing the process.

**Any errors I encountered and how you resolved them:**

I wasn’t able to connect to one of my instances, but then I realized that I forgot to add the inbound rules of SSH and HTTP to my security group. After adding the inbound rules, I then tried to connect to the instance again and my connection was successful. 

***Confirmation that I retained the launch template and cleaned up practice instances is listed in the directory screenshots.**
