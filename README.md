# auxillary-projects
 a. First lets copy our private key and public key into our ssh folder
          Go to /home/Iyanu/.ssh/ and ls
<img width="581" alt="ssh list" src="https://user-images.githubusercontent.com/57386428/107860022-0cd91a80-6df2-11eb-9a65-d2f546460648.PNG">

b.Change the private key  and publickey in the folder /home/Iyanu/.ssh/id_rsa and the public key /home/Iyanu/

<img width="441" alt="id_rsa" src="https://user-images.githubusercontent.com/57386428/107860132-75c09280-6df2-11eb-9647-bbd0cfc80668.PNG">
<img width="441" alt="private key" src="https://user-images.githubusercontent.com/57386428/107860149-87a23580-6df2-11eb-83df-c12c77d7f776.PNG">

c. Lets run the script using ./onboardingusers on the test.csv

<img width="553" alt="user creation" src="https://user-images.githubusercontent.com/57386428/107860170-adc7d580-6df2-11eb-9812-a68369151341.PNG">

d.To test if the user can login with private key :
e.Go to the ssh_config directory and make sure the passwordAuthentication is set to no and PubkeyAuthentication yes
<img width="960" alt="ssh config" src="https://user-images.githubusercontent.com/57386428/107860191-d18b1b80-6df2-11eb-947e-92a0e7656e5d.PNG">
f. Let the test the user Bami we created can login use "ssh -i /home/Iyanu/.ssh/id_rsa Bami@remote ip"
<img width="601" alt="user login" src="https://user-images.githubusercontent.com/57386428/107860218-f97a7f00-6df2-11eb-93f8-18fb4b0323a3.PNG">



    
