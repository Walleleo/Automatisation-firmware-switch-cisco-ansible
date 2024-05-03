# td_ansible_infra

Ce playbook à était crée pour un switch 2960
crée votre fichier inventaire sur votre machine ubuntu (ansible.ini)
    - changer les informations : IP, Login ssh, password ssh

créee un fichier yml
insére le playbbok dans ce fichier
  - changé la version que vous voulez modifier

le fichier yml comprends plusieur petit playbook:
   - PLAYBOOK: confirmer la version du firmware.
   - PLAYBOOK: sauvegarder la configuration.
   - PLAYBOOK: Copier l’image dans le flash du switch
   - PLAYBOOK: Mettre à jour le firmware
   - PLAYBOOK: Attente de la reconnexion du switch.
   - PLAYBOOK: Check du firmware.
   - PLAYBOOK: Sauvegarde de la config.
