<h1>Лабараторная  работа  #4</h1>

<h3>1). Установка Docker</h3>

```
sudo apt update
```

<h4>Установка необходимых пакетов для использования репозитория по HTTPS</h4>

```
sudo apt install -y apt-transport-https ca-certificates curl gnupg lsb-release
```

<h4>Добавление официального ключа Docker</h4>

```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
```

<h4>Добавление репозитория Docker в список источников</h4>

```
echo \
"deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
$(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```

<h4>Шаг 5: Обновление списка пакетов снова после добавления нового репозитория</h4>

```
sudo apt update
```

<h4>Установка Docker Engine</h4>

```
sudo apt install -y docker-ce docker-ce-cli containerd.io
```

<h4>Проверка успешной установки Docker</h4>

```
sudo docker run hello-world
```

<h3>Проверка примера из лабараторной работы</h3>

![photo_1_2024-10-04_23-27-09](https://github.com/user-attachments/assets/097022d0-2759-4547-bc64-24ad7af7f937)
![photo_2_2024-10-04_23-27-09](https://github.com/user-attachments/assets/3ae43d97-7b8b-4698-9015-071ac1e64e2d)
![photo_3_2024-10-04_23-27-09](https://github.com/user-attachments/assets/757c47c7-bbdb-4d5a-88ed-5ec0755d780b)
![photo_4_2024-10-04_23-27-09](https://github.com/user-attachments/assets/e67faf1b-3a71-49c7-bf89-439905533333)
![photo_5_2024-10-04_23-27-09](https://github.com/user-attachments/assets/de81fd0b-336e-484c-9e69-19c5091fcaf4)
![photo_6_2024-10-04_23-27-09](https://github.com/user-attachments/assets/cb194738-6d0c-4237-9081-fce47766c66e)
![photo_7_2024-10-04_23-27-09](https://github.com/user-attachments/assets/81b059b5-143b-4f80-8acd-13c0d914e89a
![photo_8_2024-10-04_23-27-09](https://github.com/user-attachments/assets/0aab2ec1-7153-4139-b707-7db5f5fabd51)
![photo_9_2024-10-04_23-27-09](https://github.com/user-attachments/assets/28e0c53d-5ae4-4dfe-b090-ec8e51ea139b)
![photo_10_2024-10-04_23-27-09](https://github.com/user-attachments/assets/f1849960-c4f5-4da3-891a-049441cb5dad)








