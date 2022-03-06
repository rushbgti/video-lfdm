# video-lfdm bot trading CryptoRobotFr
https://github.com/CryptoRobotFr/video-lfdm

Commande

# télécharger le répertoire
git clone https://github.com/rushbgti/video-lfdm.git

# aller dans le répertoire
cd video-lfdm

# vérifier les fichier
ls

# installer le bot
bash install-HiveOs.sh


# changer apikey - secret - ftx-subaccount
nano cross_ema_live.py

# Activer le bot
source /env/bin/activate

python3 cross_ema_live.py


exit

cd /video-lfdm/log/ && touch log.log

chmod 777 log.log
# une fois activer Je n'ai rien envie de faire. Il suffit d'attendre

# CRONTAB ne fonctionneras pas. Pour vérifier que le bot s'est bien exécuté après le reboot taper
crontab -e

# vérifier que la ligne est tout en bas
#echo "00 */1 * * * /env/bin/python3 /video-lfdm/cross_ema_live.py >> /video-lfdm/log/log.log" >> /hive/etc/crontab.root

reboot

# vérifier qu il fonctionne 
cat /video-lfdm/log/log.log

# fermer le ficier
# c est ok :)


cat /video-lfdm/log/log.log


