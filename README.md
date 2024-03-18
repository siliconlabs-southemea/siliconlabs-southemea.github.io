<img src="assets/images/homepage_logo.png" alt="Silicon Labs Logo" width="200">

# South Europe FAE Team Documentation

To contribute to this documentation repo :

```bash
git clone https://github.com/siliconlabs-southemea/siliconlabs-southemea.github.io.git
cd siliconlabs-southemea.github.io
git submodule update --init
git submodule foreach git checkout main
```

Contribution Flow for Collaborators :

1. Always Pull-Rebase repos prior to any push
   If git reports an error, uncommit the last one an pull
   Re-commit
2. Stage only the files that you have been working on
3. Push

On VSCode Source Conrtol this results in :

Initial Pull on all Submodules

![1709649527290](image/README/1709649527290.png)

Stage individual changes you have been working on

![1709649838601](image/README/1709649838601.png)

Commit your staged changes and **add a message** :

![1709650004184](image/README/1709650004184.png)

Push or Sync your changes :

![1709650076314](image/README/1709650076314.png)
