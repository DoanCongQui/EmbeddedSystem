- Setup môi trường biên dịch cho arm
```
sudo apt install lib32z1
```
- Chế độ GUI
```
// On
sudo systemctl isolate graphical.target
// OFF
sudo systemctl isolate multi-user.target
```
Nếu muốn đặt làm mặc định thì `set-default`
