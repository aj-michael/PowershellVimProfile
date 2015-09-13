I've started using PowerShell recently now that Windows 10 is out.

It took me all of 5 minutes to get my old workflow with vim/screen/python/git running. Tip of the hat to you, Microsoft.

If anyone sees this and wants to run Vim in PowerShell, follow these instructions:

1. Install gVim from [www.vim.org](www.vim.org)
2. Allow PowerShell to run scripts by running `Set-ExecutionPolicy RemoteSigned` in an Admin PowerShell
3. Create a powershell profile with `new-item -path $profile -itemtype file -force`
4. Open the newly created profile with `notepad $profile` and add the contents of the `ps1` file in this repo
5. Add Vim to your system environment variables
