# VideoSummarization
Course Project for CS771: Machine Learning

Use the following lines of code to download the SumMe dataset into the data folder. Refer to Michael Gygli's [page](https://people.ee.ethz.ch/~gyglim/vsum/).<br>
i) Linux
```
chmod +x ./run_this.sh
./run_this.sh
```

ii) Window
1. Using the wget command in the window
- Download [wget.exe](https://eternallybored.org/misc/wget/) latest version
- Setting Env: Put the downloaded wget.exe file into the C:\Windows\Systems folder
2. Install [git](https://git-scm.com/downloads).
3. Execute git bash
```
sh ./run_this.sh
```

Following is the list of dependencies: [imageio](https://imageio.github.io/), numpy, matplotlib, opencv3, scikit-learn. 
```
sudo pip install imageio
```
The same goes for numpy, matplotlib, tensorflow, scikit-learn. For opencv on Mac OSX,
```
brew tap homebrew/science && brew install --HEAD opencv3 --with-contrib --with-ffmpeg
brew install webp
```
The second command fixes an issue with importing opencv on Mac OSX.
