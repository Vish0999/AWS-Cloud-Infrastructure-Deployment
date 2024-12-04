<h1 style="color:blue;"><b>AWS Cloud Infrastructure Deployment</b></h1>
<h2>Key Skills:</h2>
<h4>  AWS, Terraform, Docker, Kubernetes, AWS S3, AWS IAM, AWS Auto Scaling, Route 53, etc.</h4>
<h2 style="color🟥;"><b>Description : </b></h2>
<h4>This project aims to design, deploy, and manage a scalable, secure and highly   available cloud infrastructure an Amazon Web Services (AWS). The infrastructure will support  web  Applications, Databases, analytical tools, and Storage also with the flexibility to scale resources up or down based on demands. I was implements Infrastructure as a Code (IaaC) using tools Terraform to automate the deployment process, ensuring consistency and repeatability. In this project I was established a secure environment by implementing best practices and access management (IAM), network Security (VPC, Subnets, Security Groups), and data protection. In this project I was use AWS services like Elastic Load balancing (ELB), Auto Scaling, and Amazon RDS to make infrastructure more scalable and highly available. Also, I was used AWS Service Network Firewall to provide network  security by filtering incoming and outcoming requests. In this project I was used various AWS Services (VPC, Subnet, Routing, EC2, IAM User, Load balancer, Network Peering, RDS, Auto Scaling, IGW, AWS EFS, Route 53, Network Firewall, etc.) which Useful to deploy AWS Infrastructure.</h4>
<h2><b>Key Features in the Code:</b></h2>
<h3>1) Highly Available Subnets: Separate public and private subnets across two Availability Zones.</h3>
<h3>2) Route 53: Manages DNS records for your application.</h3>
<h3>3) Auto Scaling & Elastic Load Balancing: Automatically scales EC2 instances based on demand and distributes traffic.</h3>
<h3>4) Secure RDS Database: Deployed in private subnets with restricted access.</h3>
<h3>5) Security Best Practices: Security groups to control inbound and outbound traffic.</h3>
<h2>How to Deploy:</h2>

<h3>1. Initialize the Terraform configuration :</h3>
<h3>terraform init</h3>
<h3>2. Preview the infrastructure changes :</h3>
<h3>terraform plan</h3>
<h3>3. Apply the changes to create resources :</h3>
<h3>terraform apply</h3>
<h3>4. Destroy the infrastructure if needed :</h3>
<h3>terraform destroy</h3>
<h2>Important Note :</h2>
<h4>Before deploying this infrastructure first edit .env file. Instert Access and Security key in file. After that first run .env file, then run infrastructure file.</h4>


