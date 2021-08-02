# CutStudio **Print & Cut**


## Criação de imagem

  Para a criação da imagem podemos utilizar qualquer programa, tanto vetorial(***Inkscape***) quanto editor de imagem normal(***GIMP***). Na criação da imagem é recomendado que se deixei uma sobra de cor antes da linha de corte, chamada de bleed mark, para que no momento do corte não fiquem falhas no fundo quando for colorido.
  Utilizando o Inkscape é necessário inserir um retângulo preenchido com a cor branca, pois na exportação, caso esteja sem fundo, é exportado um fundo preto.

![](imgs/4/GerarImagem1.png){: .center}
 
## Criação de linha de corte

  Para a criação da linha de corte somente gerei uma imagem preenchida de preto por cima da imagem que será impressa.
  
![](imgs/4/GerarCorte.png){: .center}
  
## Exportando Imagem
  
 O CutStudio importa imagens em **.bmp** e **.jpg**. Apesar de informar que importa **.eps**, essa função só funciona utilizando o plugin proprietário da Roland para Illustrator e CorelDraw ou utilizando o plugin do Inkscape chamada **Roland CutStudio** (não consegui fazer funcionar). 
 A partir do Inkscape só é possível exportar arquivos em **.png** e **.jpg**, então vamos seguir pela última opção. Para exportar podemos usar o atalho ++shift+ctrl+e++ ou ir ao menu **File:arrow_right:Export PNG Image**

![](imgs/4/ExportarImagem.png){: .center}

![](imgs/4/ExportarCorte.png){: .center}
 
## Importação no CutStudio
  
 Primeiro passo para utilizar as marcações é ativar a opção ***Print & Cut***
  
![](imgs/4/ActiveCutPrint.jpg){: .center}

 Logo após a ativação devem aparecer os marcadores na área de trabalho do CutStudio.

 Após ativação podemos ir em ***File:arrow_right:Import*** para importar os arquivos (recomendo começar pelo perfil de corte) e realizar a extração dos contornos em seguida clicando com o botão direito sobre a imagem e seleciona o ***Image Outline***
 
![](imgs/4/Outline.jpg){: .center}

 Ajuste o *Alignment Image Density* até obter o resultado desejado e clique em *Extract Contour Lines* para obter os vetores de corte.
 
![](imgs/4/Outline2.jpg){: .center}

 Agora delete a imagem inicialmente importada e importe a imagem que será impressa. Por serem feitas no mesmo arquivo devem se manter alinhadas e é possível ajustar a escala caso necessário selecionando o contorno  e a imagem e clicando com o botão direito e mudando o tamanho nas Propriedades da imagem.

 Ajuste a imagem e seu contorno dentro dos marcadores.
![](imgs/4/PosicioneDentroCropMark.jpg){: .center}

## Impressão

 Selecione a opção em ***File:arrow_right:Print***
 
![](imgs/4/MandeImprimir.jpg){: .center}
![](imgs/4/FolhaImpressa.jpg){: .center}

## Instalação do vinil/etiqueta

Após a impressão é necessário instalar a folha na vinil, tomando o cuidado de mante-la alinhada e com os marcadores posicionados iguais a imagem no CutStudio.

![](imgs/4/FolhaPosicionada.jpg){: .right} 
![](imgs/4/FolhaReconhecer.jpg){: .left}

## Corte

Pluge o computador na máquina caso não o tenha feito e digite ++ctrl+p++ ou ***File:arrow_right:Cutting*** para que a máquina começe o reconhecimento dos marcadores antes de realizar o corte.

![](imgs/4/FolhaMark1.jpg){: .left}
![](imgs/4/Mark1Vinil.jpg){: .right}
![](imgs/4/FolhaMark2.jpg){: .left}
![](imgs/4/Cortado.jpg){: .right}
