# Event Engine AWS Account Environment

If you are running this workshop in an AWS-sponsored or AWS-staffed event. It is likely you will be given a temporary AWS account environment for the purpose of this lab. This allows you to run the workshop without incurring any usage fees and also provides a clean environment with some prerequisite resources already pre-provisioned to save time.

Let's get started!

## Login to the AWS Console

At the beginning of the workshop you have been provided with a **12-character access code**. This access code grants you permission to use a dedicated AWS account for the purpose of this workshop. Your workshop instructor or lead presenter will also share with you the AWS Region in which the workshop will be used.

Go to <a href="https://dashboard.eventengine.run/" target="_blank">**https://dashboard.eventengine.run/**</a>, enter the access code and click **Proceed**.

<span class="image">![EventEngine Login](ee-login.png?raw=true)</span>

On the **Team Dashboard**, please click **AWS Console** to log into the AWS Management Console.

<span class="image">![EventEngine Dashboard](ee-dashboard.png?raw=true)</span>

Click **Open Console**. For the purposes of this workshop, you will not need to use command line and API access credentials.

<span class="image">![EventEngine Open Console](ee-open-console.png?raw=true)</span>

## Download the EC2 keypair

On your browser, return to <a href="https://dashboard.eventengine.run/" target="_blank">**https://dashboard.eventengine.run/**</a>, you should be back on the **Team Dashboard**, click on **SSH Key**.

<span class="image">![EventEngine Dashboard](ee-ssh1.png?raw=true)</span>

Click on the **Download Key** button. This will download the .pem file.

<span class="image">![EventEngine Dashboard](ee-ssh2.png?raw=true)</span>

Remember the location that you saved the pem keypair file on your computer. You will use this file later to decrypt the Windows login password in order to log on to the remote desktop.

## Get the environment parameters

Once you have opened the AWS Management Console for the first time, go ahead and open the <a href="https://console.aws.amazon.com/cloudformation/" target="_blank">AWS CloudFormation</a> console and click on the `mod-XXXXXXXXXXXXXXXX` stack. Make sure you are remaining in the designated AWS Region.

<span class="image">![Stack List](cfn-stack-list.png?raw=true)</span>

If the status of the stack is `CREATE_COMPLETE`, click on the **Outputs** tab. The values here will be critical to the completion of the remainder of the lab.  Please take a moment to save these keys and values somewhere that you will have easy access to them during the remainder of the lab, such as a notepad.

<span class="image">![Stack Outputs](.png?raw=true)</span> (output sample photo)

## Select a module

(Follow the normal module selection)