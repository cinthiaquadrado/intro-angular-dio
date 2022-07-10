- Módulo é um limitador de contexto cujos componentes correspondem àquele contexto.
- Exemplo da casa e dos seus cômodos que possuem itens/móveis.

#app.components.ts
- templateurl traz o html que será usado no componente.
- selector vai gerar uma tag que pode ser usada onde a gente quiser.
- title vai refletir no nosso app.component.html. Ele vai aparecer entre {{ title }}.

#app.modules.ts
- Importo o FormsModule e adiciono em imports no trecho que vem logo abaixo.
- one way data binding: é uma ligação de uma única via, que só lê e não atualiza. <input [ngModel]="name" name="name">
- two way data binding: exibe e altera o valor da propriedade. <input [(ngModel)]="name" name="name">

