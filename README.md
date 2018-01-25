# **Instalação do VSCode**

## Code CLI -> Comandos do VSCode pelo Terminal

### **Windows**
Basta selecionar a opção Add to PATH durante instalação para habilitar as linhas de comando (Necessária a reinicialização do PC).

---

### **Mac**
Abra Command Palette (Cmd+Shift+P) e execute o comando `Shell Command: Install 'code' command in PATH` .

---

Exemplo:
```
code .
```
Quando executado, abre o VSCode na pasta do caminho.

> **Pode ser executado no terminal para abrir uma nova janela com outro projeto.**


### [Mais comandos da CLI](https://code.visualstudio.com/docs/editor/command-line)

---

## Configurações
### **PHP Snippets**
1. Verifique se a opção `php.suggest.basic` em `File > Preferences > Settings` está em **false**.
2. Abra `File > Preferences > User Snipets`.
3. Selecione a linguagem (**HTML** para os snippets fora da tag php e **PHP** para os snippets dentro da tag php).
4. As configurações podem ser encontradas em `./Visual Studio Code/html.json` e `./Visual Studio Code/php.json` neste repositório.

### **settings.json / keybindings.json**
1. Ir em `File > Preferences > Settings` para settings.json e `File > Preferences > Keyboard Shortcuts` e procurar embaixo da search bar pelo link keybindings.json.
2. As configurações podem ser encontradas em `./Visual Studio Code/settings.json` e `./Visual Studio Code/keybindings.json` neste repositório.

### **extensões**
1. Executar o comando `code --install-extension {nome-da-extensão}` no terminal.
2. Sugestões podem ser encontradas em `./Visual Studio Code/extensions.txt` neste repositório.

### [Mais sobre comandos e extensões](https://code.visualstudio.com/docs/editor/extension-gallery#_command-line-extension-management)