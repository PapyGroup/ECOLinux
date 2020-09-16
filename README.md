Liste des commandes linux pour un serveur ECO. 

apt-get update  / MAJ de l'OS

apt-get install unzip / Unzip du prgm

apt install apt-transport-https dirmngr gnupg ca-certificates

apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF

apt install mono-devel

Y

mkdir ECO / Création dossier eco

cd ECO /ouvrir le dossier créer

Accédez à la page Inscrivez-vous et téléchargez le serveur là-bas  -> https://accounts.play.eco/account

wget https://s3-us-west-2.amazonaws.com/eco-releases/EcoServerLinux_v0.9.0.1-beta.zip

unzip EcoServerLinux_v0.9.0.1-beta.zip

chmod u+x EcoServer / Régler pb de droit

./EcoServer / Starter le serveur. 


PapyBrossard/ Alexis Brossard détenteur de ce tutoriel. 
