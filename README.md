# auxillary-projects
We need to onboard 20 new Linux users onto a server. Create a shell script that reads a csv file that contains the first name of the users to be onboarded.


     a. First lets copy our private key and public key into our ssh folder
          Go to /home/Iyanu/.ssh/ and ls
          
          
          
      b.Change the private key  and publickey in the folder /home/Iyanu/.ssh/id_rsa and the public key /home/Iyanu/.ssh/id_rsa.pub
      
      
      
      c. Lets run the script using ./onboardingusers on the test.csv
      d.To test if the user can login with private key :
      e.Go to the ssh_config directory and make sure the passwordAuthentication is set to no and PubkeyAuthentication yes
      f. Let the test the user Bami we created can login use "ssh -i /home/Iyanu/.ssh/id_rsa Bami@remote ip"
      



    
