<img width="663,5" height="623" alt="UEFN_Avisos_03V2_DEV" src="https://github.com/user-attachments/assets/aedabc0a-a836-4173-ae85-6eb04ca7dd2c" /> </br>
**1º** Baixe a UEFN Dev no servidor deles, o download é feito no canal <img width="151,5" height="29" alt="image" src="https://github.com/user-attachments/assets/5447db4a-e2bd-46f1-b068-e572fd771a81" /> do servidor
UEFN DEV Tutorial</br>
**2º** Extrai-a o arquivo baixado em Fortnite/FortniteGame/Content/Binaries/Win64</br>
**3º** Procure o arquivo extraido e crie um atalho dele, renomei-o de, por exemplo UEFN 28.30</br>
**4º** Abra as propriedades do atalho com o boltaõ direito </br>
<img width="325" height="77" alt="image" src="https://github.com/user-attachments/assets/487e3092-09ee-481d-a911-865ed6ee40ed" /> </br>
Adicione `-disableplugins="AtomVK,ValkyrieFortnite"` ao caminho do arquivo, salve essa alteração a abra o atalho </br>
**5º** Se sua uefn abriu com tudo desbloqueado, procure o material que deseja portar, abra-o, clique em qualquer node aperte `Ctrl A` depois `Ctrl C` </br>
OBS: Fique com a uefn dev e a uefn normal abertas ao msm tempo </br>
Crie um material, na UEFN normal, com o mesmo nome do material que você esta portando e cole com `Ctrl C`. </br>
Conecte a saída dos nodes que foram desconectados nas entradas correspondentes no Material. </br>
Mude as configurações do material para as configurações do material original(ex: se na dev está que o material é translúcido na uefn normal o material também deve estar translúcido). </br>
Extrai-a as texturas com o FP, configure as texturas, e coloque-as no material para ele validar. </br>
Caso o material tenha um MF, ou MPC que não tenha na UEFN normal, vcprecisa portar o MPC e o MF. </br>
**6º** Salve o material, execute o teste de validação no material  </br>
### **ERROS COMUNS** </br>
**1º**  Caso a UEFN não deixe você abrir um material, renicie a UEFN </br>
**2º** Niagaras não abrem? Duplique o niagara e porte-o para UEFN</br>
