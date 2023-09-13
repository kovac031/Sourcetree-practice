# Sourcetree-practice
- Sourcetree
  
> Practicing handling branches, rebase, and merge conflicts

## Steps
- stage & commit local branch changes once done

![1](https://github.com/kovac031/Sourcetree-practice/blob/main/1.png)

- from branch > finish feature > uncheck rebase (merging into develop)
  
![2](https://github.com/kovac031/Sourcetree-practice/blob/main/2.png)
> our local develop is now up to date

- using pull request on GitHub to simulate someone else finishing their branch and pushing changes onto develop

![3](https://github.com/kovac031/Sourcetree-practice/blob/main/3.jpg)

![4](https://github.com/kovac031/Sourcetree-practice/blob/main/4.jpg)

- fetch & pull develop > check rebase instead of merge

![5](https://github.com/kovac031/Sourcetree-practice/blob/main/5.png)

- merge conflicts popup

![6](https://github.com/kovac031/Sourcetree-practice/blob/main/6.png)

- File Status > open in VS Code

![7](https://github.com/kovac031/Sourcetree-practice/blob/main/7.jpg)

- resolve conflicts & save

![8](https://github.com/kovac031/Sourcetree-practice/blob/main/8.jpg)

- right click > mark as resolved

![9](https://github.com/kovac031/Sourcetree-practice/blob/main/9.jpg)

- Actions tab > Continue rebase

![10](https://github.com/kovac031/Sourcetree-practice/blob/main/10.jpg)

- rebased once all conflicts are resolved, can proceed as normal

![11](https://github.com/kovac031/Sourcetree-practice/blob/main/11.png)

## Develop to Main
> Once done with develop, switch to Main branch > rebase changes onto develop
>  - main and develop now the same
>    - can delete develop
