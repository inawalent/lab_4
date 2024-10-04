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

<h4></h4>

![img.png](img.png)


![img_1.png](img_1.png)

![img_2.png](img_2.png)

![img_3.png](img_3.png)

![img_4.png](img_4.png)

![img_5.png](img_5.png)

![img_6.png](img_6.png)

![img_7.png](img_7.png)

![img_8.png](img_8.png)

![img_9.png](img_9.png)

<h4></h4>
