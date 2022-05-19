## Instruções
- Clonar este repositório
- Compilar o código usando eclipse
- Modificar o arquivo `robocode.bat` para adicionar ao classpath (do argumento `-cp`) o caminho até a pasta bin do projeto. No meu caso, foi `C:/Users/bpmsi/eclipse-workspace/BayesJayes/bin;`. Um exemplo do arquivo robocode está no diretório raiz deste repositório. Você só precisa modificar esse caminho no arquivo `robocode.bat` pelo o caminho da pasta `bin` no seu computador
- Pronto!

## Passo a passo utilizado:
- Criar um projeto Java utilizando o eclipse usando [este tutorial](https://robowiki.net/wiki/Robocode/Eclipse/Create_a_Project) - ATENÇÃO: adicionar o robocode.jar no classpath!
- Criar a classe principal do seu robô usando [este tutorial](https://robowiki.net/wiki/Robocode/Eclipse/Create_a_Robot) - P.S.: o nome do pacote escolhido foi `ia`;
- Copiar os arquivos da pasta `plugins/plugins/org.eclipse.recommenders.jayes/src/` [deste repositório](https://github.com/kutschkem/Jayes) para o diretório `src`;
- Copiar as linhas de código do exemplo do slide;

## Observações
- O procedimento descrito foi feito para o sistema operacional Windows 11 usando a versão 18.0.1 do Java