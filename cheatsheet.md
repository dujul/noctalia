test debug before release

#### update
```git fetch upstream```
```git checkout main && git merge upstream/main```

solve merge conflict

after updating and adding local changes
```git add .```
```git status```
```git log```
```git commit -m "commit message here"```
```git push origin main```

#### release
```just build release```
```just build install```

```which noctalia``` or ```noctalia```
/home/juna/.local/bin/noctalia

reboot

#### debug build commands
(run pkill noctalia once)
```pkill noctalia ```

```just build```
```just run```
