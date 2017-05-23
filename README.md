# LPM-natural-Algorithms-for-generative-Art
First results of the Toolkit for biological Algorithms

# Setup
Install openFrameworks: http://openframeworks.cc/download/

Open terminal then enter the following commands:
```
cd openFrameworks/addons
git clone https://github.com/patriciogonzalezvivo/ofxFX.git
cd ../apps/myapps
git clone https://github.com/PPLC/LPM-natural-Algorithms-for-generative-Art
```

Open the xcode(mac) or visual studio(win) project
Compile and run

# Advanced git workflow:
Allows to have your changes reviewed by another team member. 
Fork https://github.com/PPLC/LPM-natural-Algorithms-for-generative-Art
```
cd openFrameworks/addons
git clone https://github.com/patriciogonzalezvivo/ofxFX.git
cd ../apps/myapps
git clone https://github.com/[yourGithubProfile]/LPM-natural-Algorithms-for-generative-Art
```
Edit your code, then in your LPM-natural-Algorithms-for-generative-Art folder 
```
git status
git add file(s) and folder(s)
git commit -m "My code change description"
git push
```
Then do a Pull Request on github
A team member should review your code and accept the Pull Request if ok
