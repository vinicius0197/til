# Avoid tons of commits when deploying

Got this idea from this [SO post](https://stackoverflow.com/questions/8480153/how-to-avoid-tons-of-commits-when-debugging-heroku-app?lq=1).

The quote is:

Create a new branch when you start debugging (git checkout -b debugging or similar), and then make all your commits on there, 
pushing them to Heroku instead of your master via git push heroku debugging:master.

Then when you've fixed the problem, you can squash your debugging changes into a single commit and merge them back into master:

```
git checkout master
git merge debugging --squash
git branch -D debugging
```
