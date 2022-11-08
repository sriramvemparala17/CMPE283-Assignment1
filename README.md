# CMPE283-Assignment1 

## Question 1: Members
I did this assignment by myself.

## Question 2: Describe in detail the steps you used to complete the assignment

1. Create a Virtual Machine under a project named 283-assignment1 in Google Cloud.

![1](https://user-images.githubusercontent.com/68690234/200460155-b1bb0199-c81e-4b44-8dff-2a66470036a6.png)

2.Fill the required information while creating VM and open the Cloud Shell when done.

![image](https://user-images.githubusercontent.com/68690234/200460914-593e2699-3cc8-4ac0-bd9d-916d790d4e76.png)

## Enabling nested virtualization directly on an existing Virtual Machine

3.Export the properties of the VM by using the following gcloud compute instances export command:

![image](https://user-images.githubusercontent.com/68690234/200461321-9a1b4af2-4700-4fff-a826-db0dce35870d.png)

4.In the VM configuration file that was saved in FILE_PATH, update the value for enableNestedVirtualization. If the value is not in the file, add the following:

![image](https://user-images.githubusercontent.com/68690234/200461795-23bc73a1-699f-4681-9598-853714b05ef5.png)

5.Update the VM with the value for enableNestedVirtualization by using the following gcloud compute instances update-from-file command:

![image](https://user-images.githubusercontent.com/68690234/200461875-8c18f6be-403b-44bb-ad15-7ce9b50be183.png)

6.Now we can the VM using cloud shell.

![image](https://user-images.githubusercontent.com/68690234/200464606-60634012-2f1a-45ea-aab0-c5c1b4389679.png)

7.Check for the updates, necessary installations and upgrade if needed.

![image](https://user-images.githubusercontent.com/68690234/200464960-7d6d0e75-e6bf-4769-8eab-c137702188bf.png)

![image](https://user-images.githubusercontent.com/68690234/200465040-6f17a032-89c5-4639-9bca-22ddfa017050.png)

8.Create a new directory named "cmpe283_assignment1"

![image](https://user-images.githubusercontent.com/68690234/200465482-cae72488-2088-4537-82c3-384b088a11a2.png)

9.Copy the template "cmpe283-1.c" file and the template "Makefile" to the cmpe283_assignment1 directory.

10.Modify "cmpe283-1.c" file, add all others 5 MSRs. Now, build the module using the following command inside the cmpe283_assignment1 directory.
>> make

![image](https://user-images.githubusercontent.com/68690234/200466048-1924bcd1-3c29-4a3b-8d7f-afc84477d578.png)

11.Inserting the modules in the kernel.

![image](https://user-images.githubusercontent.com/68690234/200466927-eb68b8d4-b2f7-48e9-b325-45e04ae9a7c6.png)

12.Get the result which displays VMX capabilities.

![image](https://user-images.githubusercontent.com/68690234/200467463-3d7cb27a-1081-4961-834d-8eeea2f66cf2.png)

13. Result

![image](https://user-images.githubusercontent.com/68690234/200467609-b651157c-0966-4651-8119-967eee5450c9.png)

![image](https://user-images.githubusercontent.com/68690234/200467707-ba38729a-e24c-4098-ae10-ae026eb31efc.png)

14. Removing module using the following command.
>>sudo rmmod cmpe283_1

15. Now, clone the github repository and push the content to the github.

![image](https://user-images.githubusercontent.com/68690234/200469088-47ed7482-e0dc-49ae-aa69-c70f3058235f.png)

![image](https://user-images.githubusercontent.com/68690234/200469211-85b34470-63b9-4fc3-8fb4-6f4404dce93c.png)





