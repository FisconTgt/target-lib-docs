@target-lib/tgt-components / [Exports](modules.md)

# Target-Lib
Projeto iniciado com [Angular CLI](https://github.com/angular/angular-cli) versão 14.2.0.

## Novos componentes
  >[Geração de novos componentes](./src/README_ADD_NEW_COMPONENT.md): Documento com passo a passo detalhado para realizar adição de novos itens na biblioteca.

## Build
Executar `ng build --project=@target-lib/tgt-components` para buildar o projeto. O build artifacts é gerado no caminho `dist/`.

## Gerar pacote e instalar localmente
Depois de buildar com `ng build --project=@target-lib/tgt-components`, execute `npm pack` no diretório dist `cd dist/target-lib/tgt-components`, que irá gerar o .tgz do seu pacote que será utilizado na instalação.
Após a geração acessar `dist/target-lib/tgt-components` e extrai o pacote existente no `.tgz` e executar o comando `npm install (caminho até o package extraído)`

## Publicar
Depois de buildar com `ng build --project=@target-lib/tgt-components`, na pasta dist  `cd dist/target-lib/tgt-components` e executar `npm publish`.
> O processo de "publish" do pacote npm é realizado automaticamento pelo pipeline do Azure DevOps.

## Executar os testes unitários
Executar `ng test --project=@target-lib/tgt-components ` para rodar os testes unitários via [Karma](https://karma-runner.github.io).
