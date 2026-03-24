# Lab-3-Traffic-HTTP-avec-Burp

# verification de config de burp
Apres avoir creer un projet temporaire sur burp, on s'assure que les parametres proxy sont correctes.
<img width="581" height="670" alt="image" src="https://github.com/user-attachments/assets/67222492-5676-438c-9ab8-d7cb97b3c5f5" />

# Proxy Listener
sur l'image on peut bien voir que le listener est actif 
le port est 8080 comme indiquer dans la rebrique interface : 127.0.0.1:8080
l'adresse d'ecoute est 127.0.0.1 (loopback only)
<img width="1879" height="1189" alt="image" src="https://github.com/user-attachments/assets/3dbbea49-756c-41bc-a5a6-779bec3e3ca8" />
le mode de l'interface qu'on modifie pour la rendre all interfaces selon les besoins du lab
<img width="991" height="664" alt="image" src="https://github.com/user-attachments/assets/799a70e5-461c-4fc8-8f0b-bfb6aef2c7c2" />

<img width="1879" height="1189" alt="image" src="https://github.com/user-attachments/assets/bda52cc6-e960-4055-ac92-25d679379cb9" />
# L'adresse reseau de la machine Hote

j'utilise mon adresse locale que j'ai obtenu avec la commande : ipconfig  
192.168.11.182.168
Etant donner que je n'utilise pas de VM est que j'execute sur ma machine locale
<img width="235" height="51" alt="image" src="https://github.com/user-attachments/assets/4b11df38-4f0b-4bfd-9949-47542b3e9799" />
<img width="565" height="127" alt="image" src="https://github.com/user-attachments/assets/998d8af7-4098-4522-8033-49eb7fe61aed" />

#  Config le proxy cote Android emulator 
<img width="622" height="56" alt="image" src="https://github.com/user-attachments/assets/9d1eeae7-2314-4884-aca4-3a70378a2c1a" />

# Capture du HTTP sur Burp
<img width="1163" height="1339" alt="image" src="https://github.com/user-attachments/assets/2325c1a7-d85c-45cc-87c5-caf1a8d67f59" />

