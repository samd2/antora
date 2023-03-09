
## Antora demo  

https://antora.cppalliance.org  

https://master.antora.cpp.al (same as main site)  
https://develop.antora.cpp.al  

## Instructions  

The workflow may change in the future.

For the moment, the contents of build/site/ are being publish as-is to https://antora.cppalliance.org  

That means it's the developers responsibility to update playbooks, build files, and check in all files.  

- Modify antora-playbook.yml
- Run `npx antora --fetch antora-playbook.yml` and similar antora commands which builds the docs. The output automatically goes in build/site/
- Check into git  

The first set of docs were generated by following the instructions at https://docs.antora.org/antora/latest/install-and-run-quickstart/  

The version of node used:  

```
$ nvm install --lts
Installing latest LTS version.
Downloading and installing node v18.15.0...

$ node --version
v18.15.0
```
