<img width="663,5" height="623" alt="UEFN_Avisos_03V2_DEV" src="https://github.com/user-attachments/assets/aedabc0a-a836-4173-ae85-6eb04ca7dd2c" /> </br>

**1º** Baixe a UEFN Dev no servidor deles. O download é feito no canal <img width="151,5" height="29" alt="image" src="https://github.com/user-attachments/assets/5447db4a-e2bd-46f1-b068-e572fd771a81" /> do servidor. </br>

**2º** Extraia o arquivo baixado em `Fortnite/FortniteGame/Content/Binaries/Win64`. </br>

**3º** Procure o arquivo extraído e crie um atalho dele. Renomeie-o, por exemplo, para *UEFN 28.30*. </br>

**4º** Abra as propriedades do atalho com o botão direito. </br> <img width="325" height="77" alt="image" src="https://github.com/user-attachments/assets/487e3092-09ee-481d-a911-865ed6ee40ed" /> </br>
No campo **Destino**, dê um espaço após o caminho do arquivo e adicione:

```
-disableplugins="AtomVK,ValkyrieFortnite"
```

Depois, salve a alteração e abra o atalho. </br>

**5º** Se a UEFN abrir com tudo desbloqueado, procure o material que deseja portar, abra-o, clique em qualquer node, aperte `Ctrl A` e depois `Ctrl C`. </br>
**Observação:** Mantenha a UEFN Dev e a UEFN normal abertas ao mesmo tempo. </br>
Crie um material na UEFN normal com o mesmo nome do material que você está portando e cole os nodes copiados com `Ctrl V`. </br>
Conecte a saída dos nodes que estavam desconectados nas entradas correspondentes do material. </br>
Ajuste as configurações do material de acordo com o material original (ex.: se na Dev o material é translúcido, na UEFN normal ele também deve estar translúcido — feito manualmente). </br>
Extraia as texturas com o FP, configure-as e recoloque-as no material para que ele valide. </br>
Se o material tiver um MF ou MPC que não exista na UEFN normal, será necessário portar o MPC e o MF. </br>

**6º** Salve o material e execute o teste de validação. </br>

### **Erros e Problemas Comuns** </br>

**1º** Caso a UEFN não permita abrir um material, reinicie a UEFN. </br>
**2º** Niagaras não abrem? Duplique o Niagara e porte-o para a UEFN. </br>
**3º** Node não pode ser colado? Custom nodes não podem ser colados, e nem todos os nodes são desbloqueados na UEFN normal. </br>
**4º** Material não valida? Primeiro, verifique se todas as MFs foram portadas.
Segundo, confira se todas as texturas foram recolocadas no material. </br>

## **Nomenclaturas** </br>

**MF** = Função de Material (Material Function) </br>
**MPC** = Coleção de Parâmetros de Material (Material Parameters Collection) </br>
