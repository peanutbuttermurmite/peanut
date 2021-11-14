# peanut
A new package manager.Coming soon to linux and part of Peanut OS.

All commands require root (sudo is recommended)

Commands:
```
peanut install package-name (Install packages from my repository or install a .peanut file)

peanut uninstall package-name (Uninstall all packages)

peanut update-packages (Update a package)

peanut update-peanut (Update peanut)

peanut update (Update both peanut and all packages)

peanut list (List all packages installed)

peanut uninstall

peanut info (shows help)
```


Subcommands:
```
peanut install --build package-name (Builds dependencies from source instead of using another package manager, support limited at the moment but will grow as time goes on)
peanut list -d (List packages that were downloaded upon installation of peanut)
peanut info -n (Runs neofetch if neofetch is installed)
```



