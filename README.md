# Lab 01 — Установка Nginx с помощью Ansible

## Описание

В рамках данного лабораторного задания необходимо написать Ansible-плейбук, который выполняет следующие действия на целевых хостах:

- Устанавливает веб-сервер **nginx**
- Загружает индексный файл с содержимым:  


## Технологии

- **Ansible**
- **Vagrant**
- **VirtualBox**
- **Ubuntu 24.04**

## Развёртывание виртуальных машин

### 1. Клонирование репозитория

```bash
git clone https://github.com/your-user/lab_01-weather.git
cd lab_01-weather
```
### 2. Генерация SSH-ключа (если ещё не создан)

```bash
ssh-keygen -t ed25519 -f ~/.ssh/runner_vagrant_key
```
### 3. Запуск виртуальной машины

```bash
vagrant up
```
### 4. Запуск Ansible-плейбука
```
```bash
ansible-playbook ./playbook.yml
```
> **Примечание:**  
> При использовании сети NAT, **Vagrant** автоматически пробрасывает SSH-порты для каждой виртуальной машины, начиная с `2222`, затем `2200`, `2201` и т.д


![Снимок экрана от 2025-06-06 10-44-07](https://github.com/user-attachments/assets/39b4dc8c-38de-4fb3-8722-d6468c0342e2)
![Снимок экрана от 2025-06-06 10-46-08](https://github.com/user-attachments/assets/b9293a5e-e3df-4263-8b15-913f98e0cca5)
