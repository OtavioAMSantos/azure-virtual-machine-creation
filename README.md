Documentação da Experiência: Criação de Máquinas Virtuais no Azure

Objetivo:

O objetivo deste desafio foi aplicar os conceitos aprendidos sobre a criação de máquinas virtuais no Azure, documentando o processo em um repositório no GitHub. A criação de uma máquina virtual é um dos primeiros passos para se familiarizar com o gerenciamento de infraestrutura na nuvem, permitindo o uso de recursos de computação escaláveis e sob demanda.

1. Preparação do Ambiente no Azure

A primeira etapa do processo consistiu em configurar o ambiente no portal do Azure para criação da máquina virtual. Utilizando o Portal do Azure, segui o tutorial para criar uma máquina virtual com o sistema operacional Windows Server. Os principais parâmetros que configurei foram:

Imagem do sistema operacional: Escolhi a versão do Windows Server 2019, pois é amplamente utilizado em ambientes corporativos e possui compatibilidade com diversas aplicações.
Tamanho da máquina virtual: Para o exercício, selecionei a opção Standard B1s, que é uma configuração básica e mais econômica, adequada para ambientes de teste.
Configuração de rede: Criei uma rede virtual (VNet) para garantir que a máquina virtual fosse provisionada de maneira segura e conectada corretamente à internet e a outros recursos.

2. Criação e Configuração da Máquina Virtual
   
Ao seguir os passos do tutorial, configurei os parâmetros necessários para a criação da máquina virtual. Esses passos incluíram:

Configuração de disco: Escolhi um disco padrão SSD para garantir um bom desempenho de leitura e gravação na máquina virtual.
Ajuste de segurança: Apliquei regras de firewall para permitir acesso remoto via RDP (Remote Desktop Protocol), garantindo que eu pudesse acessar a máquina virtual de forma segura e remota.
Criação do usuário administrador: Defini um nome de usuário e senha para gerenciar a máquina virtual, garantindo a segurança do ambiente.

3. Acesso e Teste da Máquina Virtual

Após a criação da máquina virtual, consegui acessá-la via RDP. O sistema operacional foi iniciado corretamente e configurei algumas ferramentas básicas, como o PowerShell e o Windows Update, para garantir que a máquina estivesse pronta para uso. Durante esse processo, pude perceber como o Azure facilita a configuração e o gerenciamento de máquinas virtuais, oferecendo uma interface intuitiva.

Conclusão

Com a conclusão deste desafio, pude aplicar de maneira prática os conceitos discutidos nas vídeo-aulas. O Azure oferece uma plataforma robusta e intuitiva para criação e gerenciamento de máquinas virtuais, e a documentação que fiz sobre o processo serviu para consolidar o aprendizado, além de fornecer uma referência para futuras implementações. A experiência também me permitiu entender melhor a importância da infraestrutura na nuvem e os benefícios que ela oferece, como escalabilidade, segurança e flexibilidade.
