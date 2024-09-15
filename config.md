# Configuration

`git config --lobal user.name "bla bla"`

`git config --global user.email a@afslas.com`

`git config --global core.editor "code --wait"`

Open config file, .gitconfig  
`git config --global -e`

End of lines: Windows uses \r\n, macOS&Linux \n .

1. Windows
   `git config --global core.autocrlf true`
2. macOS & Linux
   `git config --global core.autocrlf input`
