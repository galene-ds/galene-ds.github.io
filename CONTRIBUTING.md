# Instalação

1. Instale git e um editor de texto da sua preferência
```sudo apt-get install git```
certififique-se de que a instalação for bem sucedida com
```
git --version
```
deve ter como
```
git version x.x.x
```

2. Clone o repositório

```
git clone https://github.com/galene-ds/galene-ds.github.io.git
cd galene-ds.github.io
git config user.name "Seu Nome"
git config user.email "seu@email.com"
```

3. Faça uma nova branch
```
git checkout -b feature/nome-da-sua-feature
```

4. Faça suas modificações

5. Coloque suas modificações no servidor do Github
```
git add -A
git commit -m "mensagem de commit bem bonitinha e completa"
git push origin feature/nome-da-sua-feature
```

6. Coloque suas modificações em produção: entre no [repo](https://github.com/galene-ds/galene-ds.github.io), abra um pull-request, faça o merge, aguarde alguns minutos e veja suas modificações no [site](https://galene-ds.github.io)
