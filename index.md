Wszystkie grupy

 - git config --global user.name ""
     - ustawia globalną nazwę użytkownika 
 - git reset HEAD
     - kasuje zmiany zarejestrowane (za pomocą git add) ale nie zakomitowane (git commit) lecz nie zmienia plików (wersja z --hard również usuwa zmiany z plików)
 - gitk -all
 - git branch --merged
 - git branch "branch" "commit hash" 
 - git pull "remote" "branch"
 - git config --global user.email ""
    - ustawia globalną wartość email
 - git diff --staged
    - porównuje zmiany  
 - git checkout -b "branch"
    - to samo co git checkout ale do tego przechodzi na nowo utworzony branch (zamiast przechodzenia do stanu detached)
 - git log --graph --all
 - git branch -d "branch"
 - git fetch "remote" "branch"
     - ściąga zmiany wprowadzone na serwerze remote na gałęzi branch lecz jeszcze nich nie wprowadza (do tego należy wywołać git merge lub git rebase)
 - git config --global color.ui true
 - git commit "filename"
 - git branch -v
   - pozwala obejrzeć ostatni zatwierdzony zestaw zmian na każdej z gałęzi
 - git push "remote" "branch"
 - git log "branch" --not "branch"
 - git bisect (start, bad, good, reset)
 - git commit -a -m ""
 - git add .
     -  rejestruje wszystkie ostatnio wprowadzone zmiany w danym folderze i podfolderach
 - git checkout "branch"
     - przechodzi na podany branch 
 - git remote add "remote_name" "git url"
     - rejestruje nowy server z git'em którego można potem używać 
 - git blame -C "filename"
 - git branch "name"
