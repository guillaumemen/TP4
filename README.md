# TP4 Spéléologie réseau : descente dans les couches

## I. Mise en place du lab
### 1. Création des réseaux

Je créer 2 réseaux host-only.

### 2. Création des VMs

Je créer les 3 clones du patron en ajoutant les cartes réseaux créees précedement.

J'effectue ensuite la Checklist.
J'ai modifié les noms des domaines.
Mon client et mon serveur peuvent ping mon routeur 

### 3.Mise en place du routage statique

Je vais maintenant permettre au serveur et au client de se ping entre eux en transformant la machine en routeur ( sudo systemctl -w net.ipv4.conf.all.forwarding=1 ) et désactiver le firewall ( sudo sysemctl disable firewalld ).

Je crée les routes entre net1 et net2 pour qu'ils puissent se ping. 
Mission accomplie!!

## II. Spéléologie réseau


