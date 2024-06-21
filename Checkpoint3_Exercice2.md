# Partie 1

### Q.2.1.1 Sur le serveur, créer un compte pour ton usage personnel.

![Q 2 1 1png](https://github.com/Kamalors/Checkpoint3/assets/162970946/3cb08741-fcfd-45a6-b9ba-44f5cf8def3a)

### Q.2.1.2 Quelles préconisations proposes-tu concernant ce compte ?
Q.2.1.2 : Je préconise de mettre un mot de pas assez complexe et d’ajouter mon compte au groupe sudo


# Partie 2

### Q.2.2.1  Désactiver complètement l'accès à distance de l'utilisateur root.

![Q 2 2 1](https://github.com/Kamalors/Checkpoint3/assets/162970946/554d8f5b-8bbb-41c8-93b6-12c32e649266)


### Q.2.2.2 Autoriser l'accès à distance à ton compte personnel uniquement.

![Q 2 2 2](https://github.com/Kamalors/Checkpoint3/assets/162970946/cd860f04-353c-460f-85d1-05fd79d6bc96)


### Q.2.2.3 Mettre en place une authentification par clé valide et désactiver l'authentification par mot de passe

![Q 2 2 3](https://github.com/Kamalors/Checkpoint3/assets/162970946/d3accc78-0d26-47fc-8cf0-4f602bfeae11)

![Q 2 2 3 1](https://github.com/Kamalors/Checkpoint3/assets/162970946/989f5ec9-e0d3-41ea-9666-93bb460c3a45)

# Partie 3

### Q.2.3.1 Quels sont les systèmes de fichiers actuellement montés ?

![Q 2 3 1](https://github.com/Kamalors/Checkpoint3/assets/162970946/678d6cde-4caa-44eb-911a-f35e2af62141)

### Q.2.3.2 Quel type de système de stockage ils utilisent ?
Q.2.3.2 ils utilisent du LVM et du RAID1

### Q.2.3.3 Ajouter un nouveau disque de 8,00 Gio au serveur et réparer le volume RAID

![Q 2 3 3](https://github.com/Kamalors/Checkpoint3/assets/162970946/6db02fba-67a4-429f-b6c0-33037c8ecf9e)

![Q 2 2 3 1](https://github.com/Kamalors/Checkpoint3/assets/162970946/8715c927-4558-4e4d-9ae4-3010b1f0dc33)

### Q.2.3.4 Ajouter un nouveau volume logique LVM de 2 Gio qui servira à héberger des sauvegardes. Ce volume doit être monté automatiquement à chaque démarrage dans l'emplacement par défaut : /var/lib/bareos/storage.

![Q 2 3 4](https://github.com/Kamalors/Checkpoint3/assets/162970946/c90961d1-68a9-4d7a-8e33-b9ffe21eb2b4)

### Q.2.3.5 Combien d'espace disponible reste-t-il dans le groupe de volume ?
Q.2.3.5 : 3.79 GIB 
![Q 2 3 5](https://github.com/Kamalors/Checkpoint3/assets/162970946/decd5f8c-a6b1-4896-8068-b5bcc0e302e7)


# Partie 4

### Q.2.4.1 Expliquer succinctement les rôles respectifs des 3 composants bareos installés sur la VM.
Q.2.4.1 bareos-dir :Orchestrateur des opérations de sauvegard, bareos-sd:Gestionnaire des supports de stockage et bareos-f :Agent de sauvegarde installé sur les clients,

# Partie 5


### Q.2.5.1 Quelles sont actuellement les règles appliquées sur Netfilter ?

![Q 2 5 1](https://github.com/Kamalors/Checkpoint3/assets/162970946/e7c5308f-7a4e-4660-bdc5-a81e54f5957b)


### Q.2.5.2 Quels types de communications sont autorisées ?
Port 22 (SSH) : Le port 22 SSH. Protocole ICMP : pour les pings. Protocole ICMPv6 :pour les pings IPv6. lo :loopback est accepté.

### Q.2.5.3 Quels types sont interdit ?
Q.2.5.3 tout ce qui n'est pas ACCEPT







