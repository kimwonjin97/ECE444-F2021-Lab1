Won Jin Kim

## Process of Rebasing

1. Added two commits to both rebase and develop branch independently using following command.
    ```
        git add helloworld.py
        git commit -m <commit number>
    ```
2. On the rebase branch, typed following command for rebasing.
   `git rebase develop`

![image](https://user-images.githubusercontent.com/25218108/133471490-36969afd-0fc9-458e-94d6-23ab0307e666.png)

3. During the process of rebasing merge conflicts has been resolved.
