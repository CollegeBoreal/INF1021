# INF-1023

RIPv2 Route

Pour pratiquer cet example:
```
- utiliser PacketTracer
- Configurer le réseau en utilisant la topologie ci-dessous 
     (par notre convention, le PC est à .1 et la passerelle à .254 sur Ethernet)
- Ajouter un serveur et le connecter avec R3 sur le reseau 192.168.103.0/24 
- Executer les commandes du fichier .txt
```
![alt tag](https://github.com/CollegeBoreal/INF1021-16H/blob/master/5.RIPv2Route/RIPv2Route.png)

## Le but de l'exercice:

Tester le routage a travers le reseau, a partir du 1er PC [192.168.100.1] en executant la commande

> ping 192.168.103.1 

## Les commandes a retenir:

```
SHOW IP ROUTE                "Chercher des R"

SHOW IP RIP DATABASE
```

Note: Utiliser Cisco Packet Tracer 6.2.0
