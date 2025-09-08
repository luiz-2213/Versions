## UEFN-PIE Tutorial
Vou usar a versão 35.20 de exemplo.</br>

**1º** Baixe a versão 35.20</br>
**2º** Baixe o Plugin **da versão 35.20**</br>
**3º** Extrai-a a Arquivo do Plugin em `FortniteGame/Plugins/GameFeatures`</br>
OBS: EM OUTROS PLUGINS VC DEVE EXTRAIR EM `FortniteGame` </br>
**4º** Baixe a UEFN Dev da versão 35.20 depois extrai-a o arquivo.</br>
**5º** Coloque a UEFN DEV 35.20(o arquivo que você extraiu) em `FortniteGame/Content/Binaries`</br>
**6º** Crie um atalho do arquivo e renomeie-o.</br>
**7º** Abra as propriedades do arquivo, vá em `Destino` dê espeço e adicione:</br> `-disableplugins="AtomVK,ValkyrieFortnite" -enablePlugins="RipeHoneydewPlaylist"`</br>
**Observação:** `-enablePlugins="RipeHoneydewPlaylist"` é para desbloquear o evento da versão 35.20, ou seja, só serve para essa versão,</br>já o `-disableplugins="AtomVK,ValkyrieFortnite"` é universal para abrir a UEFN Dev em qualquer versão.</br>
**8º** Depois **SALVE** o passo anterior e abra o **ATALHO Q VC CRIOU**</br>
**Observação:** a versão 35.20 costuma dar alguns erros na hora de inicializar, é só clicar em **OK** e a UEFN vai abrir normalmente</br>

### Como abrir os arquivos do evento?</br>
Os arquivos dos eventos ficam escontidos nos arquivos você tem que forçar o carregamento dos arquivos</br>
**1º** Baixe o [Fiddler](https://www.telerik.com/download/fiddler)</br><img width="683" height="342" alt="fiddler" src="https://github.com/user-attachments/assets/f0c8b182-7621-4204-93ae-e5405abcd82f" /></br>
**2º** Baixe o [Neonite](https://github.com/HybridFNBR/Neonite)</br><img width="482,5" height="300,5" alt="neonite" src="https://github.com/user-attachments/assets/50df8868-5bdd-4c88-af75-be4c8daa3a3e" /></br>
**Baixe o [Node.js](https://nodejs.org/en/download/current/) para o Neonite funcionar**</br>
**3º** Após extrair o arquivo do neonite abra o `neonite.bat`, ele demora um pouco para compliar os arquivos mesmo,</br>quando aparecer a mensagem `port 5595!`significa que deu tudo certo, **NÃO FECHE O NEONITE APÓS ISSO**</br>
**4º** Depois abra o flidder, cole o texto `FiddlerScript`, abra Tools\Options\HHPTS </br>
<img width="1600" height="848" alt="fliider_01" src="https://github.com/user-attachments/assets/f62d7f3f-d247-420d-b600-b469b773bbba" /> </br>
**5º** Deixe suas opções como na imagem a baixo, depois concorde com todos os termos </br>
<img width="565" height="370" alt="image" src="https://github.com/user-attachments/assets/f532f501-a7f9-4e3a-a94c-dab26cb7b0cb" /> </br>
<img width="253" height="53" alt="image" src="https://github.com/user-attachments/assets/2795c7ff-a733-4ed2-b376-2ab1e60e5a65" /> </br>
**6º** Abra a uefn modificada, vá em  `Game/Maps` e abra Frontend, **jamais clique em salvar nada na uefn dev porque se não ela crasha** </br>

vá até a pasta do evento, que geralmente fica em `Plugins/Events`

