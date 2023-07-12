# Help in Android Studio Flamingo 2022.2.1 - ADB

### No momento de executar o aplicativo através do emulador, aparece a seguinte mensagem:

<p align="center">
  <img src= https://github.com/andresima0/Help-AndroidStudio/assets/111400782/61c451fd-105e-4b25-9b02-8fb8e86e57a0)" alt="Detected ADB")>
</p>

Esse aviso significa que o Android Studio não conseguiu encontrar automaticamente o arquivo binário do ADB (Android Debug Bridge) em seu sistema. O ADB é uma ferramenta essencial para se comunicar com emuladores e dispositivos Android durante o desenvolvimento.

Quando o Android Studio não encontra o ADB automaticamente, ele pode levar a algumas limitações, como problemas na execução de emuladores ou na depuração de aplicativos em dispositivos reais. É importante resolver esse problema para garantir o funcionamento adequado das funcionalidades relacionadas ao emulador e à depuração no Android Studio.

Para verificar o caminho do ADB nas variáveis de ambiente do sistema no Windows, siga as etapas abaixo:

1. Abra o Painel de Controle do Windows.

2. Navegue até Sistema e Segurança > Sistema.

3. Clique em "Configurações avançadas do sistema" no painel esquerdo.

4. Na janela "Propriedades do Sistema", clique no botão "Variáveis de Ambiente".

5. Na seção "Variáveis do Sistema", localize a variável chamada "Path" (ou "PATH") e clique em "Editar".

6. Uma nova janela será aberta, mostrando os valores da variável "Path". Verifique se existe um caminho para o diretório que contém o arquivo `adb`. Por padrão, o caminho costuma ser semelhante a `C:\Users\SeuUsuario\AppData\Local\Android\Sdk\platform-tools`, onde "SeuUsuario" é o nome do seu usuário no Windows.

7. Se o caminho para o diretório `platform-tools` não estiver presente, você pode adicioná-lo clicando em "Novo" e inserindo o caminho completo para o diretório. Certifique-se de separar os caminhos existentes com ponto-e-vírgula (;).

8. Após adicionar o caminho correto, clique em "OK" para fechar todas as janelas.

Lembre-se de reiniciar o Android Studio após fazer essas alterações para garantir que as novas configurações sejam aplicadas corretamente.

É importante lembrar que o caminho do ADB pode variar dependendo de onde o Android SDK foi instalado no seu computador. Certifique-se de verificar o local correto do diretório `platform-tools` no seu sistema.

E para verificar a localização do Android SDK no Android Studio, você pode seguir estas etapas:

1. No menu superior, clique em "File" (Arquivo) e selecione "Project Structure" (Estrutura do Projeto). Uma janela será aberta.
  
2. No painel esquerdo da janela "Project Structure", clique em "SDK Location".

3. Na seção "Android SDK location" (Localização do Android SDK), você encontrará o caminho atual do SDK exibido no campo "Android SDK location". Por exemplo, o caminho pode ser algo como "C:\Users\SeuUsuario\AppData\Local\Android\Sdk" no Windows.

<p align="center">
  <img src= https://github.com/andresima0/Help-AndroidStudio/assets/111400782/fcbcd865-d244-45ec-af9e-9a283cd72399)" alt="Android SDK location" width="600">
</p>
