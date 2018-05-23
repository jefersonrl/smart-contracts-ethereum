<h3>Exemplo de Smart Contract - Ethereum</h3>

<b>Conceito de contrato inteligente:</b>

<p>Desenvolver um contrato inteligênte permite a criação de um vinculo entre o fornecedor e a empresa contratante (Cliente) de uma forma inteligênte permitindo envio e recebimento de valores (ETH) de forma automática utilizando o próprio contrato, tirando toda a burocracia de realização de depósitos e transferências bancárias e o pagamento de taxa por utilização desses serviços.</p>

<p align="center"><img src="imgs/Azure_.png" width="300"/><img src="imgs/ethereum.png" width="200"/><img src="imgs/Windows.png" width="200"/></p>

<b>Criando o ambiente:</b>

<p>Para esse processo estou utilizando a plataforma do Microsoft Azure Student com o ambiente M. Windows, se você não tem acesso aos serviços do Microsoft Azure você pode utilizar uma máquina virtual (VM) com a distribuição do M. Windows de sua esolha e seguir os passos abaixo.</p>

<b>Configurando um Nó no Ethereum (ETH)</b>

<p>Um nó é qualquer dispositivo (Smartphone, Computador, Notebook e etc) que faça parte da rede blockchain da rede Ethereum, esses nós podem ser programado em diversas tecnologias, nesse tutorial estarei utilizando a tecnologia GO, antes de começarmos a programação vamos realizar o download da plataforma Geth (https://geth.ethereum.org/downloads/) </p>

<p align="center"><img src="imgs/geth.png"/></p>

<p>Após esse processo você deve realizar a instalação do Geth em sua respectiva máquina</p>

<p align="center"><img src="imgs/geth2.png"/>&nbsp;&nbsp;<img src="imgs/geth3.png"/></p>

<p>Após esse processo você deve acessar o diretório C:\Program Files\Geth e rodar o comando <b>geth</b> após esse processo você esta rodando um ethereum node, apenas para informativo nesse momento você esta realizando o download intereiro da rede do blockchain do Ethereum, tenha paciência e espere o término do processo.</p>

<p><img src="imgs/blockchain_eth.png"/></p>

<p>Esse processo demorou certa de 1,5hs em um máquina com M. Windows 10 no Azure, então tenha muita paciência.</p>

<p><img src="imgs/geth4.png"/></p>

<p>Crie um diderório blockchain_privada, acesse o mesmo e rode o comando <b>mkdir chaindata</b> em seguida abra um editor de texto (notepad ++) e copie e cole o código abaixo:</p>

<p><img src="imgs/genesis.png"/></p>

<p><img src="imgs/geth5.png"/></p>
