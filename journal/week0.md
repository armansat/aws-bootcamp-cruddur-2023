### Week 0 — Billing and Architecture

• I made an AWS account for Bootcamp. 

• I made a Github repository (which you are currently reading from).

• I set up a Gitpod account that is allowed to access Github. 

I watched Gifted Lane's video to set it up, and Andrew Brown's video to add the Gitpod button
I participated in the Week 0 Live Stream and also attended the Discord Q&A Session that followed. Additionally, I watched a video on Week 0 follow-up topics such as generating credentials, AWS CLI, budget, and billing alarms via CLI.

I watched a video by Chirag on the considerations to keep in mind when spending money during the bootcamp.
I also watched a video by Ashish on security considerations during the bootcamp. Furthermore, I had previously set up an AWS Organization and made the Bootcamp account as a subaccount. I wrote an article about it. Additionally, I enabled MFA for the root user and reviewed my IAM policies for any changes. I confirmed that none of my policies were affected and needed to be updated.

I created an IAM Admin user with a unique login alias and also generated an Access Key/Secret pair for this user. Additionally, I tried using the AWS CloudShell. I installed the AWS CLI for Gitpod by following a video tutorial. I manually installed it and also edited the ".gitpod.yml" file to ensure that it automatically installs if the environment restarts.

I launched a new Gitpod environment to verify that the AWS CLI was installed correctly and that the AWS credentials were correctly pulled from Gitpod variables to environment variables. I ran the command "aws sts get-caller-identity" and it returned the expected values, indicating that everything was working as intended.

:bulb: Homework Solution links:

[Logical Architectual Diagram](https://lucid.app/lucidchart/8c0de0ca-39bd-48f1-ae4c-a1d544594505/edit?viewport_loc=-504%2C-901%2C3275%2C1742%2C0_0&invitationId=inv_4a6763c3-e501-4a69-8834-5e7a9c78ce90)

[Conceptional Diagram](https://lucid.app/lucidchart/13223fc5-be39-48c1-bf61-bd0548eccb1e/edit?viewport_loc=-153%2C1%2C2412%2C1283%2C0_0&invitationId=inv_8d69da79-f7f8-4644-b61d-9c6bba0e82d2)

[Week 0 assets](https://github.com/armansat/aws-bootcamp-cruddur-2023/tree/main/journal/week0-assets)
