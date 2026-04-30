INTRUÇÕES EM PORTUGUÊS DO BRASIL
<hr />
1. Faça o download do WinRAR no site oficial: https://www.win-rar.com/download.html?&L=9
   
2. Abrir o PowerShell, e executar o comando abaixo, alterando o caminho e nome do arquivo:
   => $env:__COMPAT_LAYER = "RunAsInvoker"; Start-Process "C:\Folder\winrar-x64-721br.exe"
   
3. Será aberto o processo de instalação, altere a pasta para %LocalAppData%
   <img width="751" height="682" alt="image" style="width: 50%; height: auto;" src="https://github.com/user-attachments/assets/ba1b606f-b9bf-4cce-827f-9cd2c52e9197" />

4. Faça o download do arquivo "RegisterWinRAR_Shell.reg" deste repositório, abra no Notepad e altere "USERNAME" pelo nome de usuário da sua conta do windows
   (Se tiver dúvida qual é, pressione WINDOWS+R e execute o comando %LocalAppData% e veja o nome que aparece após C:\Users\**[SEU NOME DE USUÁRIO AQUI]**\AppData\Local

5. Salve e execute para adicionar no Registro do Windows

6. Pronto
<hr />

INSTRUCTIONS IN ENGLISH
<hr />
1. Download WinRAR from the official website: https://www.win-rar.com/download.html?&L=9

2. Open PowerShell and run the command below, changing the path and filename:

=> $env:__COMPAT_LAYER = "RunAsInvoker"; Start-Process "C:\Folder\winrar-x64-721br.exe"

3. The installation process will open; change the folder to %LocalAppData%

<img width="751" height="682" alt="image" style="width: 50%; height: auto;" src="https://github.com/user-attachments/assets/ba1b606f-b9bf-4cce-827f-9cd2c52e9197" />

4. Download the "RegisterWinRAR_Shell.reg" file from this repository, open it in Notepad, and change "USERNAME" to your Windows account username.

(If you are unsure what it is, press WINDOWS+R and run the command %LocalAppData% and see the name that appears after C:\Users\**[YOUR USERNAME HERE]**\AppData\Local)

5. Save and run to add it to the Registry. Windows

6. Ready
<hr />
