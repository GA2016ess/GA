# GA
Gestão de Atletas

Grails Version: 2.4.3

JDK 1.7.0_65 SDK 7 (1.8 Não funciona)

Faça o download do chromedriver compatível com sua máquina e coloque ele na pasta chromedrivers.

Em GebConfig.groovy setar caminho do chromeDriver no File

Mark as Test Source todas as subpastas imediatas de test (não as subpastas das subpastas)

Run configurations:

Grails:GA

run-app

Cucumber:GA

(IntelliJ) Para rodar os testes, crie uma configuração do grails com a seguinte linha de comando:

test-app functional:cucumber
