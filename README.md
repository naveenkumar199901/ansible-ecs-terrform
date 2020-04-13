##### How to deploy
1. Insert your AWS credentials with the command ```aws configure```. Also configure your ```Default region name``` with the same region that is set in the file ```ansible/group_vars/all.yml``` in var ``` aws_region```, the default is us-west-2.
2. Insert your AWS keypair in the file ```ansible/group_vars/all.yml```, in var ```aws_keypair``` wich is the name of the keypair that EC2 will use
3. To run the deploy, access the folder ```ansible``` and run the command ```ansible-playbook ansible-ecs-deploy-playbook.yml```.
