# peanut
A new package manager.Coming soon to linux and part of Peanut OS.
How it works:
1.A git repository or file hosting service is added to your sources
2.The .peanut files are downloaded
3.Once a .peanut file is verified, a key is assigned to it.
4.Verified packages can be added to your .peanut database.
5.Packages in your database can be installed or uninstalled at any time.
6.Peanut Package Manager keeps a record of all packages installed so you know what they are.

All commands require root (sudo is recommended)

Commands:
```
peanut install package-name (Install packages from my repository or install a .peanut file)

peanut uninstall package-name (Uninstall all packages)

peanut update --package (Update a package)

peanut update --peanut (Update peanut)

peanut update --all (Update both peanut and all packages)

peanut list (List all packages installed)

peanut uninstall

peanut info (shows help)

```


Subcommands:
```
peanut install --build package-name (Builds dependencies from source instead of using another package manager, support limited at the moment but will grow as time goes on)

peanut list -d (List packages that were downloaded upon installation of peanut)

peanut install --no-verify(Install unverified .peanut files)
```



