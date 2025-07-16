# Fortnite Spies
Aqui você encontrará builds, AES keys e outras informações sobre os arquivos do Fortnite.
Por enquanto, só adicionarei versões que contenham eventos ou elementos relevantes para serem portados para o UEFN.
Criado por: Luiz_2213

## Como Portar

### 1º Caso – Modelos e Texturas  
Você pode usar o [Fortnite Porting](https://github.com/h4lfheart/FortnitePorting), o [FModel](https://github.com/4sval/FModel)
ou o UModel (conhecido como [UEViewer](https://www.gildor.org/en/projects/umodel)).

### 2º Caso – Materiais, Funções e Afins  
Você pode usar o [JAA](https://github.com/JsonAsAsset/JsonAsAsset/releases), que utiliza uma versão modificada do FModel</br>para transformar arquivos `.json` em `.uasset`.</br>Infelizmente, o JAA só funciona corretamente a partir da versão 24.00 (quando a UEFN foi lançada).  
Você pode usar a UEFN Dev, uma versão da UEFN com todos os arquivos do jogo desbloqueados.  
No entanto, só existe um `.exe` datado da UEFN Dev a partir da versão 28.30.

### 3º Caso – Portar coisas de eventos
No caso na UEFN Dev, se você quiser portar coisas de eventos, você tera que usar plugins de eventos, muitos</br>desse plugins estão no [servidor da UEFN Dev](https://discord.gg/UUBhVNjcsk)

### Discords:
[Fortnite Porting](https://discord.gg/UUBhVNjcsk)</br>[Fmodel](https://discord.gg/UUBhVNjcsk)</br>[JAA](https://discord.gg/TfYmWYtKG6)</br>[UEFN Dev](https://discord.gg/VpYyFS8wbm)

##  Versões com eventos
| Version | AESKeys | Mappings |  UE  | Event Codename |
|---------|---------|----------|------|----------------|
|12.61|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/12.61%20/AESKeys_12.61.md)|-|4.24|Fritter     |
|17.50|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/17.50%20/AESKeys_17.50.md)|[Usmap](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/17.50%20/++Fortnite+Release-17.50-CL-17388565-Windows_oo.usmap)|4.27|Kiwi        |
|18.40|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/18.40%20/AESKeys_18.40.md)|[Usmap](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/18.40%20/++Fortnite+Release-18.40-CL-18163738-Windows_oo.usmap)|4.28|Guava       |
|20.40|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/20.40%20/AESKeys_20.40.md)|[Usmap](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/20.40%20/%20++Fortnite+Release-20.40-CL-20244966-Windows_oo.usmap)|5.0 |Armadillo   |
|22.40|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/22.40%20/AESKeys_22.40.md)|[Usmap](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/22.40%20/++Fortnite+Release-22.40-CL-23070899-Android_oo.usmap)|5.0 |Radish      |
|27.11|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/27.11/AESKeys_27.11.md)   |[Usmap](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/27.11/%2B%2BFortnite%2BRelease-27.11-CL-29739262-Android_oo.usmap)|5.3 | Durian     |
|32.11|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/32.11%20/AESKeys_32.11.md)|[Usmap](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/32.11/%2B%2BFortnite%2BRelease-32.11-CL-38202817-Windows_oo.usmap)|5.5 | Quail      |
|35.20|[key](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/35.20%20/AesKeys_35.20.md)|[Usmap](https://github.com/luiz-2213/Versions/blob/main/Arquivos%20/35.20/%2B%2BFortnite%2BRelease-35.20-CL-42911808-Windows_oo.usmap)|5.6 |RipeHoneydew|


## Builds 
| Version | site_01 | site_02 | site_03 |  Plugins  |
|---------|---------|---------|---------|-----------|
|12.61|-------------|---------|----|-|
|17.50|-------------|---------|----|-|
|18.40|-------------|---------|----|-|
|20.40|-------------|---------|----|-|
|22.40|-------------|---------|----|-|
|27.11|-------------|---------|----|[UEFN-PIE](https://github.com/wildfurball4/UEFN-PIE/tree/27.11?tab=readme-ov-file)| 
|32.11|-------------|---------|----|[UEFN-PIE](https://github.com/wildfurball4/UEFN-PIE/tree/32.11?tab=readme-ov-file)|
|35.20|-------------|---------|----|Plugin|

Abaixo vou explicar como usar o Plugin e a UEFN-PIE
## Plugin
Vou usar a versão 35.20 de exemplo.
1º Baixe a versão 35.20
2º Baixe o Plugin **da versão 35.20**
3º Extrai-a a Arquivo do Plugin em `FortniteGame/Plugins/GameFeatures`
4º Baixe a UEFN Dev da versão 35.20 depois extrai-a o arquivo.
5º Coloque a UEFN DEV 35.20(o arquivo que você extraiu) em `FortniteGame/Content/Binaries`
6º Crie um atalho do arquivo e renomeie-o.
7º Abra as propriedades do arquivo, vá em `Destino` dê espeço e adicione: `-disableplugins="AtomVK,ValkyrieFortnite" -enablePlugins="RipeHoneydewPlaylist"`
Observação: `-enablePlugins="RipeHoneydewPlaylist"` é para desbloquear o evento da versão 35.20, ou seja, só serve para essa versão,</br>já o `-disableplugins="AtomVK,ValkyrieFortnite"` é universal para abrir a UEFN Dev em qualuqer versão

Para usar o Plugin você deve entrar dentro da pasta da versão que você baixou da seguinte forma:
`FortniteGame/Plugins/GameFeatures` e extrair o arquivo do plugin dentro da pasta GameFeatures
Baixe a versão da UEFN Dev que você precisa




