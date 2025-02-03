Step 1 : Create Control Server and Managed server 

Set up of cs ms1 ms2 ms3 ms4 ms5

Then connect all servers to cmd

Step 2 : Add mujahed.pem in .ssh and change the permissions 

Step3 : install ansible on control machine and then check the version

Step 4 : Edit the config file for control server (CS) can access Managed Server

Check access from cs to ms4 ms1

Step5 :  write hosts file inside CS .

sudo vi /etc/hosts 

Step6 :Ping To verify the connectivity of all or selected nodes. To confirm that the basic Ansible setup is working correctly.

Step 7: Write playbook for installing open java version 8 in WS1 and version 17 in Ws2

Run Playbook :  $ ansible-playbook  jdk8_install.yml(filename)

