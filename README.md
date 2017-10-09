# ImageServe-Heroku

Instructions:  
-

1. Fork this repo
2. Create a heroku app
3. Select the forked repo as the deploy source
4. Click deploy from the master branch
5. Go to settings > config vars > Add Var "PASSKEY" with a value of any password
6. After the deploy complete, go to overview > configure dynos > disable web and enable worker (This just increases the max file size)
7. Follow the imageserve setup instructions with sharex
