# spark-basic-structure
Java on Piku Micro PaaS on Ubuntu 18 and Linux Mint 19
This is an example of one possible way of structuring a Spring application.

This is a simple Java app that demonstrates deploying your apps on Piku.

To publish this app to `piku`, make a copy of this folder and run the following commands:

```bash
cd Spring
git init .
git remote add piku piku@your_server:spring
git add .
git commit -a -m "initial commit"
git push piku master
```


## Critique welcome
If you find anything you disagree with, please feel free to create an issue.
