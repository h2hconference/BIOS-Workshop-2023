![H2HC 2023 BIOS Hacking Workshop][header]

O **H2HC 2023 | BIOS Hacking Workshop** é uma introdução à análise e
modificação de firmwares BIOS legados, usados desde o surgimento da computação
pessoal na década de 1980 até a popularização da UEFI no início de 2010.

O workshop acontecerá **nos dias 9 e 10 de dezembro das 13h às 17h**, dentro da
programação da H2HC 2023.

## Participação

Basta [inscrever-se na conferência]; não é preciso registrar-se separadamente
para o workshop, e não há nenhum custo adicional para participar.

Certifique-se de chegar cedo ao workshop, pois temos uma quantidade limitada de
equipamento disponível para as atividades práticas. Para participar, é
essencial que você traga seu próprio notebook, como especificado na seção
"[Requerimentos]".

Se você não puder ou preferir não participar das atividades práticas, você
ainda poderá assistir às sessões teóricas com demonstrações em vídeo que
acontecerão às 13h e às 15h30 em ambos os dias do evento.

## Escopo

Este evento será focado exclusivamente em firmware BIOS legado e não tratará
sobre sistemas modernos baseados em UEFI.

Esperamos que o conteúdo seja particularmente relevante para os seguintes
grupos:

- Entusiastas de retrocomputação que desejam aprofundar-se nos aspectos
  técnicos relacionados à inicialização de PCs fabricados nas décadas de 1990 e
  2000;

- Pesquisadores de segurança interessados em uma introdução ao conteúdo sobre
  análise e modificação de firmware de PCs;

- Pessoas envolvidas em atividades de manutenção e pesquisa de segurança em
  sistemas que utilizam firmware BIOS legado.

## Atividades

As seguintes atividades serão realizadas:

1. Introdução teórica de conceitos e ferramentas úteis, bem como exemplos de
   modificação de hardware preparados pelos organizadores do workshop;

2. Seção prática em que cada participante terá a oportunidade de interagir
   com uma placa-mãe real para adquirir o firmware, realizar análises, efetuar
   modificações, bem como testar as alterações realizadas, contando com as
   dicas e orientações fornecidas pela equipe de organização do workshop.

## Requerimentos

A maioria dos equipamentos necessários para realizar as atividades estará
disponível no local. No entanto, cada participante deverá trazer o seu próprio
notebook com o software listado na seção "[Preparação]" (abaixo) previamente
instalado. Os requisitos de hardware recomendados são os seguintes:

- Processador moderno da AMD ou Intel com suporte à arquitetura x86 de 64 bits;
- Pelo menos 8 GB de memória RAM;
- No mínimo 50 GB de espaço livre em disco.

Para garantir o máximo aproveitamento das atividades planejadas, é aconselhável
ter conhecimento prévio nos seguintes tópicos:

- Engenharia reversa de software para a arquitetura x86;
- Compreensão de inglês para leitura de conteúdo técnico;
- Habilidade em programação de baixo nível, incluindo as linguagens C e
  assembly para a arquitetura x86;
- Familiaridade com o uso de sistemas operacionais baseados em Linux.

## Preparação

Existem duas maneiras de preparar o seu notebook pessoal para o evento. A opção
mais simples é usar a máquina virtual fornecida, que já inclui todas as
ferramentas e configurações necessárias para realizar as atividades. No
entanto, também fornecemos orientações de configuração para os participantes
que preferem não usar uma máquina virtual.

### Máquina virtual (recomendada)

A maneira mais simples e recomendada de preparar o seu notebook para o evento é
utilizando a máquina virtual disponibilizada. Para executar a máquina virtual,
recomenda-se o [VirtualBox] na versão 7.0 ou superior.

Todos os recursos e arquivos necessários já estão incluídos na máquina virtual,
o que significa que não é necessário realizar nenhuma outra instalação. Além
disso, o uso das ferramentas no ambiente virtualizado proporciona uma camada
adicional de segurança contra a possibilidade de malware.

> ⚠️ **Atenção:** a máquina virtual contém programas provenientes de fontes
> cuja confiabilidade não pode ser completamente verificada. Há a possibilidade
> de que tais programas incluam malware.
>
> Os organizadores do evento não assumem responsabilidade por danos derivados
> do uso desta máquina virtual.
>
> É recomendado que ela seja mantida em isolamento, ou seja, sem conexão à
> rede, sem utilização de ferramentas de convidado e sem o acesso a outros
> recursos que possam facilitar a interação com o sistema hospedeiro e/ou com a
> rede.
>
> A senha para o usuário `bios` da máquina virtual é `life`.

- **H2HC2023_BIOS_Hacking_VM_v2.ova (6,2 GB)**  
  SHA-256 `f04b9fd10b636f443ffa59e6e039b6e71c378476dd53a8ce5d1acc5a46bfb455`  
  [Download via teske.net.br][H2HC2023_BIOS_Hacking_VM_v2.ova@teske.net.br] (recomendado)  
  [Download via drive.google.com][H2HC2023_BIOS_Hacking_VM_v2.ova@drive.google.com]  
  [Download via archive.org][H2HC2023_BIOS_Hacking_VM_v2.ova@archive.org] (lento)

### Instalação manual

Os participantes que preferirem não usar a máquina virtual fornecida podem
preparar a sua própria máquina. Basta, em um sistema operacional Linux, fazer o
download do pacote abaixo e instalar as ferramentas listadas.

#### Pacote

> ⚠️ **Atenção:** tal como na máquina virtual, há a possibilidade de que os
> programas contidos no pacote contenham malware. Os organizadores do evento
> não assumem responsabilidade por danos derivados da instalação desses
> programas e recomendam que eles sejam usados apenas em ambientes isolados. A
> senha para o arquivo .zip é `biosislife`.

- **H2HC2023_BIOS_Hacking_Pack_v2.zip (33 MB)**  
  SHA-256 `b229aa3c341df794b3b65f11a7c4d0f2ba33015c278a79df6d5af5dc60a44af2`  
  [Download][H2HC2023_BIOS_Hacking_Pack_v2.zip]


#### Ferramentas

> ⚠️ **Atenção:** é possível utilizar ferramentas alternativas às listadas a
> seguir. Entretanto, ao fazê-lo, você aceita o risco de problemas de
> compatibilidade que podem dificultar ou inviabilizar a sua participação nas
> atividades do workshop. Fluxos de trabalho envolvendo programas diferentes
> dos recomendados não foram testados pelos instrutores.

- **Compatibilidade**  
  [Wine]

- **Compressão de arquivos**  
  [7-Zip]

- **Editor de código**  
  [Visual Studio Code]

- **Engenharia reversa**  
  [Ghidra], [ImHex]

- **Ferramentas de build**  
  [binutils], [gcc], [make], [nasm]

- **Leitura e escrita de memória flash**  
  [flashrom]

## Contato

Em caso de dúvidas, sugestões ou qualquer outro assunto relacionado a este
workshop, sinta-se à vontade para abrir uma discussão na aba "[Issues]" ou
entrar em contato diretamente com os organizadores, a seguir.

- **Rodrigo Laneth**  
  Website: [rlaneth.com]  
  Telegram: [@rlaneth][t-rlaneth]

- **Davidson Francis**  
  GitHub: [@Theldus][gh-theldus]  
  Telegram: [@Theldus][t-theldus]

<!-- Assets -->
[header]: assets/header.webp

<!-- Downloads -->
[H2HC2023_BIOS_Hacking_Pack_v2.zip]: https://github.com/h2hconference/BIOS-Workshop-2023/raw/main/assets/H2HC2023_BIOS_Hacking_Pack_v2.zip
[H2HC2023_BIOS_Hacking_VM_v2.ova@archive.org]: https://archive.org/download/h-2-hc-2023-bios-hacking-vm/H2HC2023_BIOS_Hacking_VM_v2.ova
[H2HC2023_BIOS_Hacking_VM_v2.ova@drive.google.com]: https://drive.google.com/file/d/1E4CaHPpMazDdXiYJnpeAbwKHnhVsd1I2/view
[H2HC2023_BIOS_Hacking_VM_v2.ova@teske.net.br]: https://www.teske.net.br/h2hc2023/H2HC2023_BIOS_Hacking_VM_v2.ova

<!-- External links -->
[7-Zip]: https://7-zip.org
[binutils]: https://www.gnu.org/software/binutils/
[Cutter]: https://cutter.re
[flashrom]: https://flashrom.org
[gcc]: https://www.gnu.org/software/gcc/
[gh-theldus]: https://github.com/Theldus
[Ghidra]: https://ghidra-sre.org
[ImHex]: https://github.com/WerWolv/ImHex
[inscrever-se na conferência]: https://www.h2hc.com.br
[make]: https://www.gnu.org/software/make/
[nasm]: https://www.nasm.us
[rlaneth.com]: https://rlaneth.com
[t-rlaneth]: https://t.me/rlaneth
[t-theldus]: https://t.me/Theldus
[VirtualBox]: https://www.virtualbox.org
[Visual Studio Code]: https://code.visualstudio.com
[Wine]: https://www.winehq.org/

<!-- Internal links -->
[Issues]: ../../issues
[Preparação]: #preparação
[Requerimentos]: #requerimentos