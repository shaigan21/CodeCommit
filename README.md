# AWS CodeCommit

<h2>Description</h2>

- <B> Create a code repository using AWS CodeCommit via the Amazon Management Console</B>
- <B> Create a local code repository on the Linux instance using git</B>
- <B> Synchronize a local repository with an AWS CodeCommit repository</B>


<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 

<h2>Environments Used </h2>

- <b>AWS CodeCommit</b> 
- <b>EC2</b>
<h2>CodeCommit walk-through:</h2>

<p align="center">
Create an AWS CodeCommit repository <br/>
<img src="https://i.imgur.com/a6R29UW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connect to the Amazon EC2 instance <br/>
<img src="https://i.imgur.com/gyWgFhQ.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a local repository using Git  <br/>
<img src="https://i.imgur.com/eswG3To.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/CUR7Fy2.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
Making a code change and first commit to the repo <br/>
<img src="https://i.imgur.com/oXybco6.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
Push your first commit  <br/>
<img src="https://i.imgur.com/prqYWH9.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
View the contents using the AWS CodeCommit console <br/>

<img src="https://i.imgur.com/ie21qys.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/PVzi5mv.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/CRrxeHC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<h3> How to bring AWS CodeCommit’s features and capabilities to your development workflow, including: </h3>

- <b>Collaboration: AWS CodeCommit is designed for collaborative software development. CodeCommit allows you to commit, diff, and merge your code allowing you to easily maintain control of your team’s projects. You can create a repository from the AWS Management Console, AWS CLI, or AWS SDKs and start working with the repository using Git.

- <b>Encryption: You can transfer your files to and from AWS CodeCommit via HTTPS and SSH. Your repositories are also automatically encrypted at rest through AWS Key Management Service using customer-specific keys.

- <b>Access Control: AWS CodeCommit uses AWS Identity and Access Management to control and monitor who can access your data as well as how, when, and where they can access it.

- <b>High Availability and Durability: AWS CodeCommit stores your repositories in Amazon S3 and Amazon DynamoDB. Your data is redundantly stored across multiple facilities. This architecture increases the availability and durability of your repository data.

- <b>Unlimited Repositories: AWS CodeCommit allows you to create as many repositories as you need, with no size limits. You can store and version any kind of file, including application assets such as images and libraries alongside your code.

- <b>Easy Access and Integration: You can use the AWS Management Console, AWS CLI, and AWS SDKs to manage your repositories. You can also use Git commands or Git graphical tools to interact with your repository source files. AWS CodeCommit supports all Git commands and works with your existing Git tools. You can integrate with your development environment plugins or continuous integration/continuous delivery systems.
