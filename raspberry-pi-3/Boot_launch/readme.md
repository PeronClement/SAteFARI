# Tutoriel d'installation des services

### 1. Placer les fichiers .service dans le dossier /etc/systemd/system/ :
  ex :
  
   ```
   sudo cp /chemin/vers/le/fichier/android.service /etc/systemd/system/
   ```

### 2. Installer les services et les activer : 
  ex :
  
   ```
   sudo chmod 664 /etc/systemd/system/android.service
   sudo systemctl daemon-reload
   sudo systemctl enable android.service
   ```
   
### 3. Placer les fichiers .sh dans le dossier /usr/local/bin/ :
  ex :
  
   ```  
   sudo cp /chemin/vers/le/fichier/android.sh /usr/local/bin/
   ```
   
### 4. Rendre le script exécutable :
  ex :
  
   ```
   sudo chmod 744 /usr/local/bin/android.sh
   ```

### 5. Redémarrer la Raspberry et les commandes écrites dans les fichiers .sh s'exécuteront


## Source
[linuxconfig](https://linuxconfig.org/how-to-automatically-execute-shell-script-at-startup-boot-on-systemd-linux)



