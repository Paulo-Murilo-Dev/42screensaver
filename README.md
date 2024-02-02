## 🔒 42screensaver
Uma simples modificação estética do Xscreensaver.

## Modificações
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">
Foram mudadas pouquissimas coisas, se você quiser fazer suas proprias modificações nos arquivos saiba que você tem q modificar em `/utils/images` para ter acesso as logos (sendo as logos que eu modifiquei as logos de exibição do lock da tela) e também no `/drive/XScreenSaver.ad` para modificar os textos, fora isso acredito que seja bem menos estético e mais funcionalidades.

## Sobre a arte
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">
Um detalhe que não foi expecificado mas para modificar a imagem .xpm do xcreensaver você com suas modificações não pode deixar a imagem muito grande, ela deve pesar por volta de 30kbs, é fortemente recomendado também q você mude o esquema de cores para indexado e reduza o número de cores, vai ajudar na compressão da imagem, eu usei o GIMP para fazer as modificações.

## Compilação
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">
A compilação é chatinha, eu não costumo mexer com software para compilação, há várias dependências que eu precisei baixar para compilar o arquivo, mas para uma compilaçao mais limpa não recomendo clonar esse repositório e modificar, recomendo pegar o arquivo da versão mais atualizada da build e modificar, já que assim você vai ter menhos problemas com dependências.

## Modo fácil
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">
Se você não tá com muito saco para fazer esse processo eu recomendo fortemente que você vá até o repositório do AUR https://aur.archlinux.org/packages/xscreensaver-arch-logo e baixe a build e modifique apenas as imagens do arquivo, depois rode o famoso `makepkg --skipinteg` ignorando assim as verificações de hash dos arquivos de imagem, e depois só aproveitar seu xscreensaver modificado a o seu gosto. 
