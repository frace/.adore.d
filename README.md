# Personal notes
~~Not sure yet if I want to use [stow][source-stow], make or something else for deployment.
Ideally I'd like to involve as little dependenies as possible in order to deploy the dotfiles. 
Also I did not decide yet if I will use git submodules for each application's dotfiles.
I want the deployment process to be modular, so git submodules are not a bad idea at all.~~

I will use a simple *bash* script to deloy the dotfiles. Everything else would be
an additional dependency. IMHO using solutions like vcsh etc. are overkill for a simple
task like that.

[source-stow]: https://www.gnu.org/software/stow/

## Dependencies so far
- Git
- Bash

* * *
- [Using GNU Stow to manage your dotfiles][demo-stow-1]

[demo-stow-1]: http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html
