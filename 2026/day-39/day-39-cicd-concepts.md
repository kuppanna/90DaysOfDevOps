# what is CI/CD?
. CI - continous integration 
. CD - continous Delivery / contnuous Deployment

It is a Devops practices taht auomates building, testing  and deployning the application so developers can release softeare faster  and more reliably

# CI/CD stages:
Typical pipeline stages:
1. Code
2. Build
3. test
4. package
5. Deploy
6. Monitor


# CI/CD pipline Diagram
 
      Devloper --> GitPush --->|Source Control(GitHub)|---> | CI pipeline/Build Application / Run Test |-->|Artifact storage(jfrog)|-->| CD pipeline/Deploy to /Stage/Dev/prod|--> Users
                            