# kabug-rb
Repositorio do projeto Kabug com Cucumber, Capybara e Ruby

#*Como executar o projeto

*Importante ter o Ruby instalado (versão 2.5 ou superior)

###Instalar o Bundler
`
gem install bundler
`

### Instalar as dependências do Ruby (projeto)
`
bundle install
`
### Executar localmente (minha maquina)
`
bundle exec cucumber
`

### Executar no servidor do CI (gerando reports JSON)
`

bundle exec cucumber -p ci
`
