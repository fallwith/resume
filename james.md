## James Bunch
##### Senior Developer / Engineer (Ruby, DevOps, Cloud)

> ##### San Diego, CA 92037  
> ##### [fallwith@gmail.com](fallwith@gmail.com)  
> ##### [github.com/fallwith/resume](https://github.com/fallwith/resume)  

------

#### Objective

Seeking a senior position within a passionate team that leverages open source and will benefit from my intuition, creativity, and experience in taking software from concept to design to development to testing to deployment to scaling, hardening, and automating.

------

#### Skills {#skills}

* Ruby development since 2004
* DevOps related engineering since 2008 (especially with Amazon Web Services)
* Team leadership, supervision, and mentoring
* Independent and team based design, creativity, and problem solving
* Highly effective communication, documentation, comprehension, and critical thinking

------

#### Experience

##### SAP / MeLLmo (aquired by SAP in 2016)
**DevOps team lead**  
April 2013 - Present  
*Cardiff-By-The-Sea, CA*  
  
* Team lead for DevOps for the Roambi product, with the team size ranging at different times from 1 to 10 people split between San Diego and Bangalore.
* Collaborate with product owners, managers, client and server developers, QA testers, and ops personnel to cooperatively facilitate the implementation of DevOps methodologies throughout all stages of every product's lifecycle.
* Plan, prioritize, and assign all tasks for the team. Produce training documentation and runbook / flowchart style how-to guides. Leverage a variety of communication channels to interface with our Bangalore and European offices. Handle interviews and new hire onboarding procedures. Take care of all training and mentoring for Ruby, AWS, unix, and SAP specific products and business logic.
* Pioneered and provide lead development for a container based build and deployment system using Packer, Docker, and Ansible in order to ensure consistent and reliable behavior across all stages of application deployment.
* Leverage Amazon's Elastic Container Service (ECS) to facilitate the migration off of local physical LAN hardware to private cloud VPC based offerings.
* Refactored the San Diego team's primary Rails based application to allow for the decoupling of the heavy JavaScript client and Ruby server pieces; freeing the separate client and server dev teams from their lockstep development cycles. Each team can now iterate idependently without blocking each other in order to produce more frequent updates with less error prone deployments.
* Introduced a new build pipeline that leverages Amazon Machine Images (AMIs) to "prebake" server images with all necessary packages and application code to facilitate rapid rolling deployments of code releases to cloud environments with zero downtime. This took our team from a two hour late night deployment process used once every couple of weeks to being able to deploy at will at any time whenever new functionality was ready.
* Work on the Ruby team to produce, document, and maintain a series of gems that are leveraged by a slew of microservices.
* Work closely with the Java, iOS, Android, Windows, and JavaScript dev teams for all internal and cloud based product rollouts and resource provisioning needs. Set up automated build and deployment pipelines using Bamboo and a custom developed Ruby based AWS cloud interface.
* Produced a flexible cron driven job system for scheduling tasks to be ran using REST endpoints and a plain English language syntax based YAML file (supports phrases such as "every hour" for example). Tasks can be assigned to one or more server type clusters and then executed on either a single node or all nodes within each cluster.
* Introduced a "provisioner" cloud server type that is controlled via Capistrano over SSH and orchestrates database migrations, rake tasks, and other chores within each VPC environment, allowing for the full advantages of VPC security without sacrificing convenience.
* Leveraged the AWS Ruby SDK (versions 1, 2, and 3) for comprehensive automation of the company's various cloud services based on EC2 instances, ECS clusters, AMIs, ALBs and ELBs, Lambda functions, ASGs, S3 buckets, ElastiCache, CloudFront, RDS instances, VPC environments and all associated networking and security, Route 53 DNS entries, CloudWatch monitoring, CloudFormation templates, IAM roles, SNS and SQS for messaging, etc.  

<br />

##### Sony Computer Entertainment America (SCEA) (PlayStation)   
**Senior Online Engineer**  
June 2008 - March 2013  
*Sorrento Valley, CA*  
  
* Worked within a small skunkworks team exploring cloud solutions (Amazon and OpenStack based) long before they were adopted on a large scale throughout the company.
* Provided first and third party PlayStation video game development teams with server-side online functionality such as leaderboards, profiles, chat, game servers, metrics, trophies, and data syncing.
* Made significant contributions to all aspects of our various Ruby based applications using Rails, Sinatra, Resque, Rake, and EventMachine.
* Shared responsibility for all cloud based architecting, provisioning, and deployments against public (AWS) and private (OpenStack) cloud environments and lead the development of Vagrant/VirtualBox based virtualization.
* Utilized most all of the services offered by AWS to handle significant production traffic (gamers) to the tune of 10,000 concurrent users per game title.
* Provisioned software with Chef, Vlad/rake-remote_task, and a series of custom Rake based deployment tools.
* Led efforts to introduce, improve, and standardize unit testing, client and server environment configurations, and coding guidelines and best practices.
* Worked with local, remote US based, and international game development teams to integrate client support for our server side offerings, based on utilizing a C++ SDK that made REST based XML service calls. Adapted to each game team’s unique development styles and procedures (sprint planning, project management, etc.)
* Interfaced directly with project producers, managers, game devs, QA staff, and NOC staff to transition titles from development to QA and out into production.  

<br />

##### Qualcomm  
**Senior Programmer Analyst**  
June 2006 - May 2008  
*Sorrento Valley, CA*  
  
* Worked on a small, agile team within a large organization to develop and maintain internal and external facing custom web applications using Ruby, Perl, Python, and an enterprise Java based technology stack (based on Struts, JSF, MyFaces, Tomahawk, OC4J, and Oracle).
* Assumed lead development responsibilities for QSRP, an in-house code validation system that compares project contributions at check-in time against a database of known exploits, bugs, and viruses. QSRP consisted of roughly 50,000 lines of Python code, a PHP web interface, Berkeley DB, and MySQL.
* Assumed lead development responsibilities for a highly customized Qualcomm instance of Best Practical’s "Request Tracker" ticketing system. Pioneered and introduced several significant new functionality enhancements and performance improvements. Implemented a built-from-scratch custom packaging and deployment system for distributing the application across multiple load balanced instances. Technologies included object oriented Perl, Mason, mod_perl2, Apache2, Oracle, and Solaris.  

<br />

##### First American CREDCO  
**Lead Developer / Systems Engineer**  
September 1997 - June 2006  
*Poway, CA*  
  
* Developed and introduced a Rails based web application framework for internal intranet use in order to improve upon and consolidate various existing console and web based Perl, Java, Informix, and PHP tools. These tools had previously been deployed in several different formats, each with their own deployment complications. With the move to consolidate these tools with a consistent view layer accessible via a web browser, the deployment, maintenance, and authentication pieces saw great improvements in their simplicity and effectiveness.
* Assumed lead development for the company’s premier web portal solution, “CREDCOConnect”. CREDCOConnect had a Java servlet based infrastructure that provided clientele with HTTPS based access to CREDCO's products and services. Re-architected the platform to replace its proprietary I/O system with a flexible solution that allowed modular support for all current and future data formats. Worked closely with project managers, business managers, database admins, sysadmins, architects, QA personnel, and other developers to introduce several major new improvements to the platform.  
* Served as a member of an elite four employee Systems Engineering team comprised of senior developers to produce enterprise development guidelines with regards to application dependencies, security, logging, performance, support requirements, etc.
* Joined several company projects as chief Systems Engineer to offer suggestions for new development efforts on how to best implement guidelines, and to retroactively enforce the guidelines for existing platforms.
* Produced multiple Java desktop apps featuring SSL communications, database interaction, GUI multi-threading, IBM MQ interaction, encryption, XML parsing and generation, etc. Revision controlled these apps with ClearCase, packaged them with Ant, and released them with customized NSIS installers.
* Produced hundreds of extensible, custom parsers in Perl and Ruby to aggregate and quantify data from various sources including web logs, database tables, XML, source code, unix process output, proprietary industry text and binary formats, etc.
* Architected, scripted, and tested the autonomous alteration of over a half million lines of C++ source code across several packages for a large scale corporate COTS component upgrade.
* Worked closely with several external .NET, J2EE, Perl, Ruby, PHP, C++, and cURL developers to facilitate third party platform integration with the company's web based portals. Developed and maintained sample source code, reviewed and contributed to developer guides, produced DTD validators with extra custom non-DTD based validation (based on business logic), and facilitated client side digital certificate deployments and configuration.
* Created custom tools for the IT Security department for use in tracking malicious and fraudulent activity involving private consumer data in order to regularly convert large amounts of proprietary log data into meaningful leads for the FBI.
* Automated several QA, DBA, and Network Operations Center (NOC) based tools (involving FTP, HTTP, SSL, SQL, and/or custom I/O tasks), eliminating the need for manual, after hours on-call support for a variety of internal and customer facing platforms.  

------

### Footer {#footer}

James Bunch -- [fallwith@gmail.com](fallwith@gmail.com) -- San Diego, CA 92037

------
