1.  Run the status command. Notice how it tells you what branch you are in.
![Screenshot 2024-03-13 104344](https://github.com/Jatin048/Mst/assets/114685074/e8e9209b-65f5-43a7-9cc0-f7c2c2096a96)

2.  Create branch using **git branch** command  

![Screenshot 2024-03-13 104401](https://github.com/Jatin048/Mst/assets/114685074/c8a52ed4-5bd3-47ce-a4e0-4da415f3cb10)

3.  Now checkout to the branch using **git checkout <branch_name>**
![Screenshot 2024-03-13 104408](https://github.com/Jatin048/Mst/assets/114685074/aaa423e1-e9de-4107-be70-35f6587a7fd1)

4.  Edit the files in it and add make a couple of commits using **git commit**
![Screenshot 2024-03-13 104421](https://github.com/Jatin048/Mst/assets/114685074/e55989b7-fb0f-4aeb-8333-a4fb8fbf0f46)

5.  Now using **git log** check the commit history of the branch created
![Screenshot 2024-03-13 104458](https://github.com/Jatin048/Mst/assets/114685074/a095f82b-7477-44bb-80d9-9df6ff38dc1e)

  ![Screenshot 2024-03-13 104733](https://github.com/Jatin048/Mst/assets/114685074/ffa793ae-9d13-4057-8a77-980cb4569edd)
6.  Now switch back to the main branch and check the status using **git status**

![image](https://github.com/Jatin048/Mst/assets/114685074/0d57273c-6db8-420c-b118-36e667f815ad)

7.  Also check the commit history of main branch using git log and see there is no commits made in main branch
![image](https://github.com/Jatin048/Mst/assets/114685074/62bb0372-96e9-4703-805d-d632a73abe1f)

8.  Now switch back to the branch using checkout and make chenges in the files previously created but do not make the changes in the main branch.

9.  Now checkout to main branch and using **git merge <branch_name>** name merge the changes of feature branch into main
![image](https://github.com/Jatin048/Mst/assets/114685074/d47142b4-4664-451e-bb02-2be04fe0dfca)

10.  Now check DAG using **gitk** command
 ![image](https://github.com/Jatin048/Mst/assets/114685074/4cfd5005-7c96-4e11-8517-e62dc56b94cc)

![image](https://github.com/Jatin048/Mst/assets/114685074/5d768a0b-eb58-4870-8d6f-be87bdce3862)

  
11.  Switch back to your branch. Make a couple more commits.
![image](https://github.com/Jatin048/Mst/assets/114685074/20e52247-d3b6-4242-a17c-83f0dadda083)

12. Switch back to master. Make a commit there, which should edit a different file from the ones you touched in your branch – to be sure there is no conflict.
![image](https://github.com/Jatin048/Mst/assets/114685074/af178f3e-232c-451f-801b-4f11050dda8e)

13. Now merge the branch again.
![image](https://github.com/Jatin048/Mst/assets/114685074/cde44f1b-10d7-4fa2-abd7-ed0a17c63697)

14. Look at git log again to see the commit history.
![image](https://github.com/Jatin048/Mst/assets/114685074/151c4522-2125-4d92-b704-8ea8b62f39ae)
![image](https://github.com/Jatin048/Mst/assets/114685074/ab7c5073-c14a-4752-89a1-8a5c4572abe2)

  
