# 4cu3nt1x
4cu3nt1x Patch Install (Full path)



Cracked trial acunetix for linux

Install Ubuntu or Kali Linux

apt install unzip curl ; rm -rf /tmp/acun*
apt install libxdamage1 libgtk-3-0 libasound2 libnss3 libxss1 libx11-xcb1 -y
cd /tmp; rm master.zip -f
curl -L -o master.zip http://github.com/neolead/acunetix-linux/zipball/master/
unzip master.zip
cd `ls|grep neolead` && cat acupatch* > acupatch.tgz
tar -zxvf acupatch.tgz
chmod +x ./acunetix_trial.sh
./acunetix_trial.sh
service acunetix_trial stop
chmod 0755 patch_awvs
cp patch_awvs /home/acunetix/.acunetix_trial/v_190515149/scanner/
su - acunetix -c "/home/acunetix/.acunetix_trial/v_190515149/scanner/patch_awvs"
cd /tmp;rm -rf /tmp/acu*
service acunetix_trial stop
chattr +i /home/acunetix/.acunetix_trial/data/license/license_info.json
service acunetix_trial start
curl -k https://127.0.0.1:13443

Change credentials:

su - acunetix -c "/home/acunetix/.acunetix_trial/ && bash change_credentials.sh"

