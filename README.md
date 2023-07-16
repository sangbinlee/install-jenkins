# install-jenkins
install-jenkins

  
  1.  Install OpenJDK 17 on Ubuntu 22.04
      - sudo apt update
      - sudo apt install -y openjdk-17-jdk
      - sudo apt install -y openjdk-17-jre
  2. Verify Java JDK Installation
      - java -version   

        ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/ac96172f-6ecb-4c1d-ad16-2eee6b5b8897)


# after installing jenkins and jdk17 and jre17 on Ubuntu 22.04
     
    0.  install jenkins on Debian/Ubuntu 
      https://www.jenkins.io/doc/book/installing/linux/
      
      curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
        /usr/share/keyrings/jenkins-keyring.asc > /dev/null
      echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
        https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
        /etc/apt/sources.list.d/jenkins.list > /dev/null
      sudo apt-get update
      sudo apt-get install jenkins

    - Start Jenkins
      sudo systemctl enable jenkins
      sudo systemctl start jenkins
      sudo systemctl status jenkins
      
        


 ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/3358c0b5-39a4-4114-8aae-8f2cdbc6c6e8)
       



  1.  sudo vi /var/lib/jenkins/secrets/initialAdminPassword
    ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/5278c3a0-2b49-4081-a322-a6b01b2c4b9d)

  1.  Customize Jenkins
     ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/30ea703b-1787-46e2-ac3f-ec40ce4558cc)

  2. install click
     ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/519f16ae-6478-4c19-84dd-69d5df607681)


  3. Create First Admin User
     ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/eaeedbe4-88fe-4d3a-b2e5-46e22ae7dc87)

     
  4. set jenkins url : http://jy6.shop:8080/
     ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/16479966-c083-4b46-a3d9-8b244db1ea88)

  5. Jenkins is ready!
      ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/6d448e6e-f28f-4249-91c2-74d33cf906a6)

  6. welcome page : Jenkins에 오신 것을 환영합니다.
     ![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/fb8b430e-f065-43fd-8763-618477eba50b)








![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/417450e1-a89a-48c9-965e-ccac0867a038)


![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/0b266b56-a9d9-4f3b-beb9-4fbd6aa05c9c)



![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/b766388b-539c-4a51-bc6c-8923eb9b7fac)



![image](https://github.com/sangbinlee/install-jenkins/assets/4024414/0792c060-ba48-49dd-b212-5f49de4b0360)







