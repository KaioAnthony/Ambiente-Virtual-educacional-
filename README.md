# __Ambiente Virtual Educacional__

__Este projeto tem como objetivo criar um ambiente virtual para fins educacionais, que possibilite a execução de softwares como MySQL, Node.js e Python. Utilizando um orçamento de até 5.000 reais, ele inclui a montagem de um computador, configuração de uma máquina virtual e instalação de uma distribuição Linux gratuita, aplicando conceitos de Sistemas Operacionais, Redes de Computadores e Lógica de Programação.__

### __Levantamento de requisito:__

### Requisitos para a Máquina Virtual

__Requisitos mínimos:__

__Memória:__ 2 GB

__CPU:__ Dual-core de 2 GHz ou superior

__Armazenamento:__ 25 GB de espaço livre no disco

__Rede:__ NAT(Network Address Translation), pois as vantagens são a simplicidade na configuração, segurança aumentada devido ao isolamento da VM e acesso fácil à internet utilizando o IP do host.



### Pesquisa e Orçamento de Componentes

Requisitos para computador fisíco:

__Processador__ (CPU): AMD Ryzen 5 5600GT 3.6 GHz 6-Core

- Bom desempenho (6 núcleos, 12 threads, até 4.6 GHz)

- Gráficos integrados Radeon (dispensa GPU para tarefas leves)

- Eficiente e econômico (65W TDP + cooler Wraith Stealth incluso)

- Ótimo custo-benefício

__Memória RAM:__ Memória XPG GAMMIX D35 8 GB (1x8 GB) DDR4-3200 x2

-  Velocidade de 3200MHz → Melhor desempenho em games e multitarefas.

 - Baixa latência (CL16) → Respostas mais rápidas do sistema.

 - Dissipador compacto → Mantém a temperatura controlada.

 - Compatível com Intel e AMD → Suporte amplo, incluindo overclock (XMP 2.0).

 - Boa relação custo-benefício → Ótima opção para upgrades acessíveis.


__Armazenamento:__ Kingston SSD NV2 M.2-2280

- Alta velocidade com interface NVMe PCIe 4.0 → superior aos SSDs SATA.

- Formato compacto (M.2 2280) → ideal para notebooks e desktops compatíveis.

- Eficiência energética → consumindo menos energia e gerando menos calor.

- Disponível em várias capacidades (250GB, 500GB, 1TB, 2TB).

- Ótimo custo-benefício para quem busca um SSD NVMe rápido e acessível.



__Placa de vídeo:__ Asus Radeon RX 550 4 GB

- Custo-benefício → para jogos leves e multimídia

- Baixo consumo → (não precisa conector extra)

- Compacta e silenciosa → ideal para PCs pequenos

- Suporte a DirectX 12 e 4K → para melhor experiência gráfica 



__Placa mãe:__ Asus Prime A520M-K Micro ATX AM4

- Compatibilidade com Ryzen → Suporta processadores AMD Ryzen 3000, 4000G e 5000.

- Chipset A520 → Oferece estabilidade e suporte a recursos essenciais.

- Slot M.2 PCIe 3.0 → Suporte para SSDs NVMe de alta velocidade.

- Memória DDR4 até 4600MHz (OC) → Expansível até 64GB em dual-channel.

- Conectividade → Possui USB 3.2 Gen 1, HDMI, VGA e LAN Gigabit.

- Durabilidade → Proteções contra surtos elétricos e componentes de alta qualidade.

- Formato Micro ATX → Compacta, ideal para gabinetes menores.




__Fonte:__ Corsair CV550 550 W Certificado 80+ Bronze ATX

- Eficiência 80+ Bronze → Consome menos energia e gera menos calor.

- Potência de 550W → Suporta PCs de médio desempenho, incluindo GPUs dedicadas.

- PFC Ativo → Estabiliza a corrente elétrica, protegendo os componentes.

- Ventoinha de 120mm silenciosa → Resfriamento eficiente com baixo ruído.

- Cabos revestidos → Melhor organização e fluxo de ar no gabinete.

- Confiabilidade Corsair → Construção durável e proteção contra sobrecarga, subtensão e curto-circuito.


__Monitor:__ Samsung LF24T350FHLMZD 24.0″ 1920 x 1080 75 Hz

- Design moderno → Estética clean com lateral de acrílico para exibir os componentes.

- Compatibilidade ATX/Micro-ATX/Mini-ITX → Suporta diferentes tamanhos de placa-mãe. 

- Boa ventilação → Suporte para múltiplas ventoinhas e resfriamento eficiente.

- Espaço interno amplo → Acomoda placas de vídeo grandes e coolers de CPU altos.

- Gerenciamento de cabos → Passagem de fios organizada para melhor fluxo de ar.

- Frontal com acabamento clean → Visual minimalista e elegante.





__Gabinete:__ Pichau APUS ATX Mid Tower (Branco)

- custo-benefício

- Resolução Full HD (1920x1080) → Imagem nítida e detalhada.

- Taxa de atualização de 75Hz → Movimentos mais fluidos que monitores de 60Hz.

- Painel IPS → Cores mais vivas e ângulos de visão amplos.

- AMD FreeSync → Reduz cortes e travamentos em jogos compatíveis.

- Design sem bordas em 3 lados → Visual moderno e mais imersão.

- Conectividade → Entradas HDMI e VGA para compatibilidade com vários dispositivos.

- Modo Eye Saver e Flicker Free → Reduzem cansaço visual em longas sessões.



__Mouse:__ MO270 Com fio

- custo-benefício 

__Teclado:__ Rise Mode G1 Full

 - custo-benefício 

#### __Orçamento Máximo:__ R$ 5.000,00

### __Valor total:__ R$ 4.340,65

          https://meupc.net/build/o47cXo

### __Escolha do Sistema Operacional__

Fizemos a escolha do Linux, devido ser muito popular para programação porque é um sistema de código aberto que permite personalização, oferece muitas ferramentas de desenvolvimento e é estável e seguro. Ele é eficiente, funcionando bem até em hardware menos potente, e é amplamente utilizado em servidores de produção, garantindo consistência entre os ambientes de desenvolvimento e produção. Além disso, a comunidade ativa de usuários e desenvolvedores oferece vasto suporte e recursos. Esses fatores tornam o Linux uma escolha confiável para muitos programadores.


__Manual de Instalação do Linux no VirtualBox
Pré-requisitos
VirtualBox: Baixe e instale a versão mais recente do VirtualBox.
Imagem ISO do Linux: Faça o download da imagem ISO do Ubuntu em Ubuntu Download.__

### Passo a Passo
### 1. __Instalação do VirtualBox__
Acesse o site do VirtualBox e baixe a versão para seu sistema operacional.
Siga as instruções de instalação fornecidas.
Após a instalação, abra o VirtualBox.

### 2. __Criação da Máquina Virtual__
clique em novo:

![imagem](https://scontent-gru1-2.xx.fbcdn.net/v/t1.15752-9/479743487_630790559715751_2915314868008043686_n.png?stp=dst-png_s640x640&_nc_cat=100&ccb=1-7&_nc_sid=0024fc&_nc_ohc=VCnnmFrz2WsQ7kNvgGTNvtJ&_nc_oc=Adhsr0b2nx4cxEt7KYGKxPumGM866gRgRQTRXLlrV3y23uelRlGm8uxZjjVJ7AqUJwQ&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru1-2.xx&oh=03_Q7cD1gFlGtb0AA4VW1WfjOTZVeKTg2aWrTXBa1ERMDMwVUmeJA&oe=67DEB251)

 __Configuração de Memória:__
![imagem](https://scontent-gru2-2.xx.fbcdn.net/v/t1.15752-9/474962451_541315888969687_9001083963964649223_n.png?stp=dst-png_s640x640&_nc_cat=102&ccb=1-7&_nc_sid=0024fc&_nc_ohc=aiozOzCZK1UQ7kNvgHDF91K&_nc_oc=AdgPPBUG1Qi7f7G7IhnVHswRa13dKMfCfCevTn3ntd0vc9aro5EQh5kAzJI9MqpZFQc&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru2-2.xx&oh=03_Q7cD1gGIf4RCJDrcKFCAjfNbqKcIBxlRbs1CwOxuOYkMiUTLfQ&oe=67DED635)

 __Criação do Disco Rígido Virtual:__
![imagem](https://scontent-gru1-2.xx.fbcdn.net/v/t1.15752-9/479531627_1294865961599319_2363528473826662522_n.png?stp=dst-png_s640x640&_nc_cat=110&ccb=1-7&_nc_sid=0024fc&_nc_ohc=gTlSOZBXRp4Q7kNvgE8L1PN&_nc_oc=Adj4ltgMq291qOq3aEPH01eyOcUXMthPCl96aXqJELfiRgAmqwssY633aiLxfmsioqE&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru1-2.xx&oh=03_Q7cD1gEnl2sJLdUVAFhHRVwU6v6jcXDr277jyf3gqPHPBMnOjQ&oe=67DECC32)

### 3. __Configuração de Rede__
__Selecione a máquina virtual criada e clique em "Configurações".__

![imagem](https://scontent-gru2-2.xx.fbcdn.net/v/t1.15752-9/477847287_457473344000686_8234988697495108404_n.png?stp=dst-png_s640x640&_nc_cat=106&ccb=1-7&_nc_sid=0024fc&_nc_aid=0&_nc_ohc=ngjp_IJZiY8Q7kNvgG9EsLk&_nc_oc=AdirYlFEcgl6fK-PwYP_YIpFlUcwjIzadOPieU4VXigP_QIDlH_ZTesSakiNEauUm3s&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru2-2.xx&oh=03_Q7cD1gE1az2ZVJDZuL3g7y0qoyU-gJo9aTf8O0aAQqN73mZUIw&oe=67DEE145)



### 5. __Iniciando a Instalação do Ubuntu__

__Instalação Passo a Passo:__

![imagem](https://scontent-gru1-2.xx.fbcdn.net/v/t1.15752-9/479977494_1160587212341001_3457104147467774115_n.png?stp=dst-png_s600x600&_nc_cat=110&ccb=1-7&_nc_sid=0024fc&_nc_ohc=t9u48vtbNcsQ7kNvgH5viiB&_nc_oc=AdgAd08M3X695XgDnRRgdF42p8D946Btj9zssi0CmezI4GI0rN1nMhXShTja1owdMMY&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru1-2.xx&oh=03_Q7cD1gGmNk17VmvDBmwBmzhCrcb-4s8sKDHGTiHmbw3FPCzO7w&oe=67DECF69)

![](https://scontent-gru1-2.xx.fbcdn.net/v/t1.15752-9/479247534_645678564494955_4604186582979827678_n.png?stp=dst-png_s600x600&_nc_cat=100&ccb=1-7&_nc_sid=0024fc&_nc_ohc=nyAOL3fOfqoQ7kNvgGfQOFQ&_nc_oc=AdgUKaTdpGsgT_E3meuSI8pELCkrNfwA1hI3aSegHNWyNHEXq55k4b23OR7nN9JGgt4&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru1-2.xx&oh=03_Q7cD1gEU4nMA7O50PH4tK9e_xe7fgWJfdPJSWBeYYeCTr2SCjA&oe=67DEC71E)

![](https://scontent-gru2-2.xx.fbcdn.net/v/t1.15752-9/479743084_658898976705844_5101673767520013407_n.png?stp=dst-png_s600x600&_nc_cat=105&ccb=1-7&_nc_sid=0024fc&_nc_ohc=zvUu8eeqnDQQ7kNvgGqLNxG&_nc_oc=AdjnuxNpAlM3Db2DI2DZt5ZoLbhK4SmwIdQbMTnCg7FBi32wQ-VUZ2Y4gPmhNyaIhpE&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru2-2.xx&oh=03_Q7cD1gE0SOgVdv8twhgCfR32XLUAitxYdsBUpnh9FCPxqtHs0g&oe=67DEEFD9)

![](https://scontent-gru2-1.xx.fbcdn.net/v/t1.15752-9/478206336_642838591547206_9157701308841604877_n.png?stp=dst-png_s600x600&_nc_cat=111&ccb=1-7&_nc_sid=0024fc&_nc_ohc=Rc4E89P2BeMQ7kNvgGC8r7w&_nc_oc=AdhkKzWarzN_1pQD6ewbg94cy2drAsYLF7F3GhExYMsHxKV5EpQklGQt4eBJ9jJQSl8&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru2-1.xx&oh=03_Q7cD1gGJXGz59pzV8MFiQwfVcsEkbUzphYtTohS2a5uETlkFvg&oe=67DEC72A)

![](https://scontent.fcpq1-1.fna.fbcdn.net/v/t1.15752-9/479550966_1155293512803641_1297334503824398664_n.png?stp=dst-png_s600x600&_nc_cat=100&ccb=1-7&_nc_sid=0024fc&_nc_ohc=df-DmH6LgNoQ7kNvgG8Nxbr&_nc_oc=AdiT6QiZPPbEyA1tAwYjMRzrUwKXOy-PwkrH1ezTRffjSg9BbMlIm9U1MJ8oXFMEeZo&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.fcpq1-1.fna&oh=03_Q7cD1gHqcO7ZUsQp3hC9ZE0_Dr723QSNYPTHoWeD3hCMFOU9AQ&oe=67DEF1D1)

![](https://scontent-gru2-1.xx.fbcdn.net/v/t1.15752-9/479449860_1311156736761057_6738318932543213077_n.png?stp=dst-png_s600x600&_nc_cat=111&ccb=1-7&_nc_sid=0024fc&_nc_ohc=rRfOkRTZE9sQ7kNvgG0zjh_&_nc_oc=AdjzQM09BPNHvAaLkRBFqzrfnS10undfna5WGSsmpeP0vvneZxQkvx7uZWLIocx7NoE&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru2-1.xx&oh=03_Q7cD1gF1yEYKKAGOUURb_JbA2TbuFXtXhMwkyaH2Er9a4WnSRw&oe=67DEDD8B) 

![](https://scontent-gru2-2.xx.fbcdn.net/v/t1.15752-9/477633681_580789495008386_4720262496620129101_n.png?stp=dst-png_s600x600&_nc_cat=106&ccb=1-7&_nc_sid=0024fc&_nc_ohc=E0PGy5jz6PMQ7kNvgHejtb2&_nc_oc=AdjzfpcPjEPLDB8Pk3YReJua2LcITJjQAdK5iiMlSjDlNNnNltZtKhdDT3agzmjPLyw&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-gru2-2.xx&oh=03_Q7cD1gFw0jFM86TlHkd6kiYLaDCEab9AViPFMFzeUttAxubmuw&oe=67DED587) 
 ### 6. __Pós-Instalação e Testes__

Após a instalação, a máquina virtual reiniciará.

Faça login com as credenciais criadas.

Abra o __terminal__ (CMD) e verifique a instalação dos softwares executando os seguintes comandos:

### - __mysql --version__
Se não estiver instalado, coloque os seguinte comando para instalar: 

__sudo apt install mysql-client-core-8.0__

### - __node -v__
Se não estiver instalado, coloque os seguinte comando para instalar: 

__sudo apt install nodejs__


### - __python3 --version__




