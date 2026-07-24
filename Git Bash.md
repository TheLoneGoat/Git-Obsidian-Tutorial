Go here and install git bash https://git-scm.com/install/windows

after doing so open git bash in where your vault folders will be located!
![[Pasted image 20260724010326.png]]

then run 
```
git config --global user.email "you@example.com" 
git config --global user.name "Your Name"
```
ex: 
`git config --global user.email ragibmlg@gmail.com`
`git config --global user.name TheLoneGoat`

then verify
`git config --global --list`

note, --global means these settings applies to every git repository on this computer.