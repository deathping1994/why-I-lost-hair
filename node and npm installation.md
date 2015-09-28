#Node JS and NPM installation on ubuntu

## Always get the latest tar.gz package from nodejs website
1.Extract the downloaded package into ~/programs (I like to keep all my tar packages in programs)
2. Create a symlink to node executable using `sudo ~/programs/<node>/bin/node /usr/bin/node`
  (replace <node> with your folder nodejs name)
3. Add path to node binary in  ~/.bashrc
    i. `nano ~/.bashrc`
    ii. add `export PATH=~/programs/<node>/bin/:$PATH` at the end of bashrc and save it
    iii. run `source ~/.bashrc` in terminal

## Installing Yoeman angular generator
1. Yoeman website does not list build-essential as a dependency but you need to install it.
2. follow all instructions as it is

#note: Never do sudo npm install <package name> it is almost always deadly
      If styling is not shown in yoeman then edit your bower,json to list bootstrap 3.3.4 as a dependency
