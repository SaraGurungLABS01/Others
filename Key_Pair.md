# Creating a New Key Pair in AWS

**Step 1: Sign in to AWS**

- Open a web browser and go to the [AWS Management Console](https://aws.amazon.com/).
- Sign in using your AWS account credentials.

**Step 2: Access the EC2 Dashboard**

- In the AWS Management Console, navigate to the "EC2 Dashboard" by clicking on "Services" > "Compute" > "EC2."

**Step 3: Access the Key Pairs Section**

- In the EC2 Dashboard, on the left sidebar, locate and click on "Key Pairs" under the "Network & Security" section.

**Step 4: Create a New Key Pair**

- In the "Key Pairs" section, click the "Create Key Pair" button.

**Step 5: Provide a Name for the Key Pair**

- You will be prompted to enter a name for your key pair. Choose a descriptive name for your key pair, e.g., "MyEC2KeyPair."

**Step 6: Choose the Key Pair File Format**

- Select the key pair file format:
    - If using SSH clients like OpenSSH, choose "PEM."
    - If using PuTTY on Windows, choose "PPK."

**Step 7: Create Key Pair**

- Click the "Create Key Pair" button to generate your new key pair.

**Step 8: Download the Key Pair**

- After creation, AWS will generate the key pair and provide a private key file for download.
- Download and save the private key file to your local computer. Ensure you store it securely.

**Step 9: Keep the Key Pair Secure**

- Safeguard the private key file to prevent unauthorized access.
- Do not share the private key file with others.
- Losing the private key file may lead to loss of access to your AWS instances.

With the key pair created and the private key file saved, you are ready to use it for SSH access to your AWS EC2 instances. When launching an EC2 instance, you can associate this key pair with the instance to enable secure SSH access using the private key file.

Remember to follow AWS best practices for key pair management and security to maintain the confidentiality and integrity of your AWS resources.
