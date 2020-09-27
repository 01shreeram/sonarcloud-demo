# Steps to integrate sonarcloud with github action.

visit this link and login using your github account

https://sonarcloud.io


![](https://i.imgur.com/QhurMDr.png)

# After logging into the sonarcloud click on the create organization and choose the organization form the github

![](https://i.imgur.com/kSfGWFd.png)

# click on configure

![](https://i.imgur.com/Ekzh1VW.png)

# Then assign the permission on the repository

![](https://i.imgur.com/WPsa0N6.png)

# Click on analyze new project 

![](https://i.imgur.com/ZKOC3KO.png)

# then choose the repo you want to integrate sonarcloud with

![](https://i.imgur.com/DgwGeMq.png)

# then click on set up 

![](https://i.imgur.com/Dzh3HNR.png)

# now click on with github action

![](https://i.imgur.com/WyyqXfa.png)

# then copy the provided secret and add it to the github repo and click continue

![](https://i.imgur.com/XZnulo0.png)

![](https://i.imgur.com/xcYHQGU.png)


# choose your build type and copy the code and add it to the main branch of the github repo in .github/workflows/build.yml file and click continue
![](https://i.imgur.com/IFCWkOU.png)
![](https://i.imgur.com/RkW2Ckw.png)

# Now 
# lastly copy the given contents and save it to your root directory of main branch.

![](https://i.imgur.com/4g43bBM.png)
![](https://i.imgur.com/6zBFJ6l.png)


# For testing create a new branch in github push your code and create a pull request.
![](https://i.imgur.com/YjYybpF.png)

# PR and sonarcloud analysis output


![](https://i.imgur.com/p4ZRrkD.png)

![](https://i.imgur.com/fGF1I40.png)








