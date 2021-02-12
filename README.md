# auxillary-projects
We need to onboard 20 new Linux users onto a server. Create a shell script that reads a csv file that contains the first name of the users to be onboarded.


     a. First lets copy our private key and public key into our ssh folder
          Go to /home/Iyanu/.ssh/ and ls
          
          <img width="581" alt="ssh list" src="https://user-images.githubusercontent.com/57386428/107829751-41d86500-6d3f-11eb-98a8-074ae0fa3912.PNG">
          
      b.Change the private key  and publickey in the folder /home/Iyanu/.ssh/id_rsa and the public key /home/Iyanu/.ssh/id_rsa.pub
      
      <img width="441" alt="id_rsa" src="https://user-images.githubusercontent.com/57386428/107829786-5288db00-6d3f-11eb-8d40-e6bfbaf71173.PNG">
     <img width="441" alt="private key" src="https://user-images.githubusercontent.com/57386428/107829822-60d6f700-6d3f-11eb-9bca-7affefb80cc1.PNG">
      
      c. Lets run the script using ./onboardingusers on the test.csv
      
      <img width="553" alt="user creation" src="https://user-images.githubusercontent.com/57386428/107829880-7a783e80-6d3f-11eb-8eb0-26cdc6bb8282.PNG">
      
      
      d.To test if the user can login with private key :
      e.Go to the ssh_config directory and make sure the passwordAuthentication is set to no and PubkeyAuthentication yes
      
     <img width="960" alt="ssh config" src="https://user-images.githubusercontent.com/57386428/107829912-8bc14b00-6d3f-11eb-8410-a5a1b7381119.PNG">
     
     
      f. Let the test the user Bami we created can login use "ssh -i /home/Iyanu/.ssh/id_rsa Bami@remote ip"
      
      
      <img width="601" alt="user login" src="https://user-images.githubusercontent.com/57386428/107829945-a1cf0b80-6d3f-11eb-9f9d-fd2da05ae457.PNG">






      



    
