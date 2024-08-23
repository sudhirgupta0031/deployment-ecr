# Script demo
In this Script demo we are doing 2 set of task 
1) For monitoring the various system resource which we need to provide output in dashboard format and it should take user input and refresh
2) We have to make script for auditing security and hardening the linux server

Pre-requisite: We need to install some network related utility like netstat ,net-tool,nginx,iptables,apache2 etc so that the command run without giving any exception 

Command:I had use familiar command in this script which used quite in monitoring the resource like
top: show the process running and memory ,cpu usage
sort: for sorting in order
sudo : to get root privilege
awk : To get particular column 
cut : This is also used to get particular coloum 
case: This is used for switch case 
| : Pipe is used to combine 2 or more command 
if : Use to decision making
for/while : for looping a task
chmod: to give permission to a file

1) Let see the 1st set of task what we have done to archieve this
When we execute the script we see this output where it taking input from the user
![image](https://github.com/user-attachments/assets/420ec042-cc87-4d8e-aa4b-6339c54ef55f)

Once you enter the choice you will get the output and again it will prompt you to enter the input 
![image](https://github.com/user-attachments/assets/a10ee7e5-b58b-4b44-9f04-85d6b2446e58)

So this scritp basically check all the resource like which application using high cpu and memory, service status like ssh/nginx etc below i am pasting the snapshot of output
![image](https://github.com/user-attachments/assets/0582ab59-58cf-426a-a69a-cb572e3b101b)

![image](https://github.com/user-attachments/assets/eb6020d1-e8be-49ec-8f96-dc78a74e9f16)

![image](https://github.com/user-attachments/assets/f1416897-256a-49d7-abfd-90d72404a83c)

![image](https://github.com/user-attachments/assets/286c6d0d-4af2-4edd-887d-b45bdb08473b)

![image](https://github.com/user-attachments/assets/a3240f24-8a56-484e-8047-ea6d38fa52a5)

![image](https://github.com/user-attachments/assets/572af08a-24d8-432f-84b5-b6a6d98375f7)

It will end the execution once you select the choice for exit


2) Now it we will see the secuirty audit , this script is used to do audit of files permission, firewall status etc .So the you see this prompt when you execute the script
![image](https://github.com/user-attachments/assets/152b2689-3e39-4d83-9484-6cf04e37c52c)

After selecting the task you will see the output ,i just take the upper most element to get complete in snapshot
![image](https://github.com/user-attachments/assets/8ceac8f0-3a1f-4d2a-8611-8335e0858e14)


![image](https://github.com/user-attachments/assets/6cd918ad-e185-45b9-8e8b-f95b08d08ae4)


![image](https://github.com/user-attachments/assets/2893caa1-5bf8-43db-819d-ab98d96247ba)

![image](https://github.com/user-attachments/assets/3b492138-81b8-4952-87c3-03c3db251130)

![image](https://github.com/user-attachments/assets/de19b8c9-bdfe-4ba0-85ac-96391d255393)

![image](https://github.com/user-attachments/assets/cc23c78e-9cf5-4893-bc42-e5bea0cc6c2e)

![image](https://github.com/user-attachments/assets/02f7e5d8-b4f4-46cd-9d9d-ed485233f5e5)





