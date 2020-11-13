# Arquitetura de componentes e a gestão da complexidade no front-end 

Projeto desenvolvido para exemplificar os tipos de data binding do Angular.

Para consultar os slides da apresentação, acessar o link: https://drive.google.com/file/d/1Wv4BDj7YXd9mBsvTc-tBACAw0Hb-FN8U/view?usp=sharing

Obrigada pela participação e bons estudos!

Qualquer coisa só dar um salve!

## Redes sociais:

- **Instagram**: https://www.instagram.com/ravenita_/
- **Linkedin**: https://www.linkedin.com/in/geovanasribeiro/
- **Spotify** (pra quem quiser ouvir umas playlists maneiras): https://open.spotify.com/user/22tk6jgofco56wm3rk3ctx6lq?si=7oQp1VrcRRiVQ8nDaPGBWg 

- componentes reutilização 
- carrousell , cards 
- escalabilidade , manutenção e performance 
![](../1.PNG)
- serviços : lógica de negocios , programação 
- chama api , trata dados 
- como usar um serviço ? 
- Injeção de dependencia (todo serviço é uma dependencia)
- pegamos a instancia que já existe e utilizamos 
![](../2.PNG)
- lifecicles ngoninit , ondestroy,  onchanges, docheck 
![](../3.PNG)
- construtor : deve ser usado apenas para inicialisar serviços injetados via DI 
- ngoninit deve ser usado para todo tipo de lógica que o componente precisa executar apos ter sido criado 
- @componentes são chamados de metadados 
- Input e output 
- Pai para filho 
![](../4.PNG)
- Filho para pai 
![](../5.PNG)
- errata : deveria ter um .emit depois do this.remaninigMoney.emit(change); 
- Dumb Components (components puros)
![](../6.PNG)
- Smart Components
![](../7.PNG)
![](../8.PNG)
- Design modular 
![](../9.PNG)
- https://materializecss.com/about.html
- angular elements 

## Arquiteturas para CSS 
### SMACSS 
Arquitetura modular e escalável para CSS dividida em 5 camadas : 
- base : estilização de sleetores e pseudo-classes além de resets 
- Layout : Principais componentes como cabeçalho, rodapé entre outros 
- Module : Componentes reutilizáveis como botões e ícones 
- State : : todo elemento que será modificado ou terá alguma alteração no seu estado inical 
- Theme : Temas específicos para uma mesma aplicação 

![](../10.PNG)

### BEM CSS 
Uma nomenclarura interessante Block , element , modifier sendo uma metodologia que segue esses conceitos para definir uma nomenclatura de nomes de classes para css 
![](../11.PNG)

bloco : card 
tudo que está dentro : elemento nomenclatura : bloco__elemento
- para modificar um elemento vamos usar um modificador -- 

### OOCSS 

![](../12.PNG)









