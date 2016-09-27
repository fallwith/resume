# James A. Bunch
#### Senior Ruby Developer, DevOps / Cloud Engineer

> San Diego, CA 92130  
> [fallwith@gmail.com](fallwith@gmail.com)  
> [github.com/fallwith/resume](https://github.com/fallwith/resume)  

------

### Objective

To fulfill a senior developer or ops role on a passionate team that makes extensive use of open source tools and dynamic languages (especially Ruby, Python, and Perl) and that will benefit from my technical experience and penchants for creativity, efficiency, and quality design.

------

### Skills {#skills}

#### Development
* Consistent senior level Ruby development since 2004 (in both pure Ruby and Ruby on Rails)
* Senior level development in Python, Perl, Java, and PHP
* Intermediate level development in C/C++
* SQL proficiency (MySQL, PostgreSQL, Oracle, MS SQL) and NoSQL proficiency (Redis and MongoDB)
* Shell scripting expertise (Bourne, Bash, Korn, and Z shells)
* Web development proficiency (HTML, CSS, JavaScript, XML, REST, etc.)
* High level of familiarity with unix (Linux, BSD, Solaris, OS X) and Windows
* Preference for the CLI for development and testing (Vim, Emacs, tmux, SSH, etc.)  

#### DevOps / Cloud
* Amazon Web Services (AWS) based cloud design and architecture since 2008
* Experience with VPCs and the majority of AWS services
* Ruby based aws-sdk gem and AWS CLI tool development
* OpenStack, VirtualBox/Vagrant, Docker, etc. familiarity
* Familiarity with large scale production cloud environments with high customer traffic concurrency
* Experience with full end-to-end build and deployment pipelining  

#### Leadership and Teamwork
* Highly effective communication, documentation, and comprehension skills
* Patient leadership, training, and mentoring as team lead and supervisor
* Experienced in coordinating with interdepartmental teams and remote and international workers
* End-result driven teammate with a lack of concern for personal credit and great desire to elevate others  

------

### Experience

#### SAP / MeLLmo / Roambi  
**DevOps team lead**  
April 2013 - Present  
*Encinitas, CA*  
  
* Lead the DevOps team of 10 developers split between offices in San Diego and Bangalore. Serve in a hybrid capacity switching between Ruby server application development and devops responsibilities for a small start-up acquired by and left largely autonomous away from SAP.
* Plan, prioritize, and assign all tasks for the team. Produce trail maps style training documentation and runbook style how-to guides (chiefly in Markdown). Leverage a variety of communication channels to interface with our Bangalore office and SAP's Europe based offices. Handle all team member interviewing and new hire onboarding procedures. Take care of all training and mentoring for Ruby, AWS, unix, and SAP specific business logic.
* Refactored the primary Rails application to allow for the decoupling of the heavy client app (JavaScript based) and server pieces; freeing the separate client and server dev teams from their lockstep dev cycles. Each team can now iterate idependently without blocking each other and the client team can release more frequent updates without requiring downtime.
* Introduced a new build pipeline that leveraegs Amazon Machine Images (AMIs) to "prebake" servers with all necessary packages and application code to facilitate the rapid hot / rolling deployment of code releases to cloud environmenets.
* Worked with the other server team Rubyists to produce and maintain a series of gems that are leveraged by a slew of microservices.
* Work closely with the Java, iOS, Android, Windows, Chrome, and JavaScript dev teams for all internal and cloud based product rollout and resource provisioning needs. Set up automated build and deployment pipelines using Bamboo and a custom developed Ruby based AWS cloud interface.
* Led an initiative to migrate from using Chef server with untested, forked community cookbooks to using Chef solo with Berkshelf, ChefSpec, Vagrant, Foodcritic, and Test Kitchen. Each cookbook now has its own test suite based build plan that has taken us from a "fingers cross" style of deployment to one based on reliable consistency and confidence.
* Produced a flexible cron driven job system for scheduling tasks to be ran using REST endpoints and a plain English language syntax based YAML file (supports "every hour" for example). Tasks can be assigned to one or more server type clusters and then executed on either a single node or all nodes within each cluster.
* Introduced a "provisioner" cloud server type that is controlled via Capistrano over SSH and orchestrates database migrations, rake tasks, and other chores within each VPC environment, allowing for the full advantages of VPC security without sacrificing convenience.
* Leveraged the AWS Ruby SDK (both v1 and v2) for exhaustive automation of the company's various cloud services based on EC2 instances, AMIs, ELBs, ASGs, S3, ElastiCache, CloudFront, RDS instances, VPC environments, Route 53, CloudWatch, CloudFormation, IAM, SNS, SQS, etc.  

<br />

#### Sony Computer Entertainment America (SCEA) (PlayStation)   
**Senior Online Engineer**  
June 2008 - March 2013  
*Sorrento Valley, CA*  
  
* Worked within a team dedicated to providing first and third party PlayStation video games with server-side online functionality such as leaderboards, profiles, chat, game servers, metrics, trophies, and data syncing.
* Made significant contributions to all aspects of our various Ruby based applications using Rails, Sinatra, Resque, Rake, and EventMachine.
* Shared responsibility for cloud based architecting, provisioning, and deployments (against public and private cloud environments using AWS and OpenStack) and lead development of Vagrant/VirtualBox based virtualization imaging.
* Utilized most all technological components offered by AWS to handle significant production traffic to the tune of 10,000 concurrent users per game title.
* Provisioned software with Chef, Vlad/rake-remote_task, and a series of custom Rake based deployment tools.
* Led efforts to introduce, improve, and standardize unit testing, client and server environment configurations, and coding guidelines and best practices.
* Worked with local and remote / international game development teams to integrate client support for our offerings, based on utilizing a C++ SDK piece that makes REST based XML service calls. Adapted to each game team’s different sprint planning procedures and project management tools.
* Interfaced directly with project producers, managers, game devs, QA staff, and NOC staff to transition titles from development to QA and out into production.  

<br />

#### Qualcomm  
**Senior Programmer Analyst**  
June 2006 - May 2008  
*Sorrento Valley, CA*  
  
* Worked within a small team to develop and maintain internal and external facing custom web applications using Ruby, Perl, Python, and an enterprise Java based technology stack (Struts, JSF, MyFaces, Tomahawk, OC4J, and Oracle).
* Assumed lead development responsibilities for QSRP, anin-house code validation system that compares project contributions at check-in time against a database of known exploits, bugs, and viruses. QSRP consisted of roughly 50,000 lines of Python code, a PHP web interface, Berkeley DB, and MySQL.
* Assumed lead development responsibilities for a highly customized Qualcomm instance of Best Practical’s “Request Tracker” ticketing system. Pioneered and introduced several significant new functionality enhancements and performance improvements. Implemented a built-from-scratch custom packaging and deployment system for distributing the application across multiple load balanced instances. Technologies included object oriented Perl, Mason, mod_perl2, Apache2, Oracle, and Solaris.  

<br />

#### First American CREDCO  
**Lead Developer / Systems Engineer / Technical Analyst**  
September 1997 - June 2006  
*Poway, CA*  
  
**Lead Developer**  
December 2005 - June 2006  

* Developed and introduced a Rails based web application framework for internal intranet use in order to consolidate various existing console and web based Perl, Java, mod_perl, and PHP tools. These tools had previously been deployed to several teams in several different formats and locations, each with their own deployment complications. With the move to consolidate these tools on a single server with the view layer accessible via only a browser, the deployment, maintenance, and authentication pieces saw great improvements in simplicity and effectiveness. The new apps were built in Ruby on Rails, and served up by Lighttpd running on Linux.
* Assumed lead development for the company’s premier web portal solution, “CREDCOConnect”. CREDCOConnect has a servlet based infrastructure that provides clientele with HTTPS based access to CREDCO's products and services. Re-architected the platform to replace its proprietary I/O system with a flexible solution that allows modular support for all current and future data formats. Worked closely with project managers, business managers, database admins, sysadmins, architects, QA personnel, and other developers to additionally introduce several major new improvements to the platform.  
  
**Systems Engineer**  
June 2004 - November 2005  

* Served as a member of an elite four employee Systems Engineering team comprised of senior developers to produce enterprise development guidelines with regards to application dependencies, security, logging, performance, support requirements, etc.
* Joined several projects as chief Systems Engineer to offer suggestions for new development efforts on how to best implement guidelines, and to retroactively enforce the guidelines for existing platforms.
* Produced multiple Java desktop apps featuring SSL communications, database interaction, GUI multi-threading, IBM MQ interaction, encryption, XML parsing and generation, etc. Revision controlled these apps with ClearCase, packaged them with Ant, and released them with customized NSIS installers.
* Produced hundreds of extensible, custom parsers in Perl and Ruby to aggregate and quantify data from various sources including web logs, database tables, XML, source code, unix process output, proprietary text and binary formats, etc.
* Architected, scripted, and tested the autonomous alteration of over a half million lines of C++ source code across several packages fora large scale corporate COTS component upgrade.
* Worked closely with several external .NET, J2EE, Perl, Ruby, PHP, C++, and Curl developers to facilitate third party platform integration with the company's web based portals. Developed and maintained sample source code, reviewed and contributed to developer guides, produced DTD validators with extra custom non-DTD based validation (based on business logic), and facilitated client side digital certificate deployment and configuration.
* Created custom tools for the IT Security department for use in tracking malicious and fraudulent activity involving private consumer data in order to regularly convert large numbers of proprietary logs into meaningful leads for the FBI.
* Automated several QA, DBA, and Network Operations Center (NOC) based regression tests (involving FTP, HTTP, SSL, SQL, and/or custom I/O tasks), eliminating the need for manual, after hours on-call support for a variety of internal and customer facing platforms.  
  
**Senior Technical Analyst**  
February 1999 - May 2004  

* Developed and maintained a full suite of mod_perl based Informix front-end tools to simplify various complex dynamic SQL based research tasks.
* Developed and administered multiple Linux and BSD hosted, database driven intranet sites built in PHP with interactive user content updating functionality.
* Designed and deployed multiple automated statistics gathering applications to produce tripwire style near instantaneous activity tracking, as well as qualitative post activity analysis work on a per hour, day, week, or month basis.  
  
**Technical Analyst**  
September 1997 - February 1999  

* Worked with external developers, administrators, and end users via phone and e-mail to resolve both new platform deployment issues and routine troubleshooting issues related to existing deployments of web and desktop based Loan Origination Software packages.  

------

### Footer {#footer}

James A. Bunch -- [fallwith@gmail.com](fallwith@gmail.com) -- San Diego, CA 92130

------
