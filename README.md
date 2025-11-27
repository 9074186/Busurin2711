    1  ls -al ~/.ssh
    2  ssh-keygen -t ed25519 -c "9074186@gmail.com"
    3  ssh-keygen -t ed25519 -C "9074186@gmail.com"
    4  ls -al ~/.ssh
    5  cd id.ed25519.pub
    6  cat ~/.ssh/id_25519.pub
    7  cd .ssh
    8  ls -al
    9  eval "$(ssh-agent -s)"
   10  ssh-add ~/.shh/id_ed25519
   11  cat ~/.ssh/id_ed25519.pub
   12  git config --global user.name "9074186"
   13  git config --global user.email "9074186@gmail.com"
   14  git config --list
   15  cd
   16  git config --global user.name "9074186"
   17  git config --global user.email "9074186@gmail.com"
   18  git config --list
   19  cd "/d/git"
   20  mkdir Busurin2011
   21  cd Busurin2011
   22  echo "content 1" > file1.txt
   23  git add file1.txt
   24  git commit -m "1st commit: add file1"
   25  [200~echo "content 2" > file2.txt
   26  git add file2.txt
   27  git commit -m "2nd commit: add file2"
   28  cd/d/git
   29  cd\d\git
   30  cd ~
   31  mkdir Busurin2011
   32  cd Busurin2011
   33  git init
   34  echo "file2 > file2.txt
   35  git add file1.txt
   36  git commit -m "Initial commit: add file1"
   37  echo "file2" > file2.txt
   38  git add file2.txt
   39  git commit -m "Add second file"
   40  [200~git commit -m "Initial commit: add file1"
   41  [200~echo "Information 3" > file3.txt
   42  git add file3.txt
   43  echo "file3" > file3.txt
   44  git add file3.txt
   45  git commit -m "Add third file"
   46  echo "file4" > file4.txt
   47  git add file4.txt
   48  git commit -m "Finalize base structure"
   49  git remote add origin https://github.com/9074186/Busurin2011.git
   50  git push -u origin main
   51  git remote add origin git@github.com:9074186/Busurin2011.git
   52  git push -u origin main
   53  cd d
   54  cd ~
   55  mkdir Busurin2711
   56  cd Busurin2711
   57  git init
   58  git branch -M main
   59  echo "1" > file1.txt
   60  git add file1.txt
   61  git commit -m "Add file1"
   62  echo "2" > file2.txt
   63  git add file2.txt
   64  git commit -m "Add file2"
   65  echo "3" > file3.txt
   66  git add file3.txt
   67  git commit -m "Add file3"
   68  echo "4" > file4.txt
   69  git add file4.txt
   70  git commit -m "Add file4"
   71  [200~git remote add origin https://github.com/9074186/Busurin2711.git
   72  git push -u origin main
   73  git remote add origin https://github.com/9074186/Busurin2711.git
   74  git push -u origin main
   75  git log --oneline
   76  git branch dev 136d169
   77  git branch test 136d169
   78  git push -u origin dev
   79  git push -u origin test
   80  git checkout dev
   81  echo "<svg color='brown'>Capybara</svg>" > capybara.svg
   82  git add capybara.svg
   83  git commit -m "Add capybara.svg"
   84  echo "<svg color='red'>Capybara</svg>" > capybara.svg
   85  git add capybara.svg
   86  git commit -m "Change capybara color"
   87  echo "<svg color='red' background='blue'>Capybara</svg>" > capybara.svg
   88  git add capybara.svg
   89  git commit -m "Change background color"
   90  git push
   91  git checkout test
   92  git cherry-pick 136d169
   93  git cherry-pick 2af82c3
   94  git cherry-pick ffec238
   95  git cherry-pick 3c2c4af
   96  git push
   97  git checkout main
   98  git merge test
   99  git push
  100  git checkout dev
  101  git rebase main
  102  git push --force-with-lease
  103  git checkout main
  104  history > README.md
