# Fix for Fix for AlmaLinux 9 from Centos 7 Upgrade 23-2024 on Ragnarokkr nodes

fixing glibc installation package when upgrading from Centos 7 image

Issue fail to open setup files from the upgrade node.

## Application du patch sur Ragnarokkr
>How to apply the patch


Dans votre [dashboard](https://app.rag-control.hosteur.com/): 
>From your [dashboard](https://app.rag-control.hosteur.com/)

1 - Ouvrir l'import de JPS (open JPS Import menu)

2 - Copier l'url ci-contre (copy this url ) : 

https://raw.githubusercontent.com/hosteur-sa-ch/rag-hosteur-alma9up-fix/main/manifest.jps

3 - Importer le package (Import the package)

4 - Choisir l'environement et le noeud a patcher (Choose the env and node to patch)

5 - Appliquer le patch (Apply the patch)
