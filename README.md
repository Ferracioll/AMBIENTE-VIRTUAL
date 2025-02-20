# Ambiente Virtual Educacional💻

## Introdução
Este projeto tem como objetivo criar um ambiente virtual para fins educacionais, que possibilite a execução de softwares como MySQL, Node.js e Python. A atividade integra conceitos de Sistemas Operacionais, Redes de Computadores, Levantamento de Requisitos e Lógica de Programação. Nele, você pesquisará componentes para a montagem de um computador com custo máximo de R$ 3.000,00, configurará uma máquina virtual e instalará uma distribuição Linux gratuita, escolhida com base na compatibilidade e facilidade de uso.

## Levantamento de Requisitos

### Requisitos para o Computador Físico
- **Processador (CPU):** Bom desempenho para multitarefa.
- **Memória RAM:** Idealmente 8GB (conforme o orçamento).
- **Armazenamento:** SSD para melhor desempenho.
- **Outros:** Placa-mãe, fonte de alimentação, etc.
- **Orçamento Máximo:** R$ 5.000,00

### Requisitos para a Máquina Virtual🖱️
- **Memória:*2x 8GB* 
- **CPU:*Ryzen 3 3200G* - escolhido
- **Armazenamento:*SSD 480GB* - escolhido 
- **Rede:** Configuração via NAT ou Bridge para acesso à internet

## Pesquisa e Orçamento de Componentes
- **Exemplo de Link para Processador:** [Processador](https://www.kabum.com.br/produto/102248/processador-amd-ryzen-3-3200g-3-6ghz-4ghz-max-turbo-cache-4mb-quad-core-4-threads-am4-yd3200c5fhbox
)
- **Exemplo de Link para Memória RAM:** [Memória]( https://www.kabum.com.br/produto/548589/memoria-ram-lexar-16gb-3200mhz-ddr4-cl22-preto-ld4au016g-b3200gsst)
- **Exemplo de Link para Placa mãe:** [Placa mãe]( https://www.kabum.com.br/produto/111107/placa-mae-asrock-b450m-hdv-r4-0-amd-am4-micro-atx-ddr4-preto-90-mxb9n0-a0uayz)
- **Exemplo de Link para Gabinete:** [Gabinete]( https://www.kabum.com.br/produto/204669/gabinete-gamer-rise-mode-z3-glass-lateral-em-vidro-fume-preto-rm-z03-03-fb)
- **Exemplo de Link para Fonte:** [Fonte]( https://www.kabum.com.br/produto/369658/fonte-msi-mag-a650bn-650w-80-plus-bronze-pfc-ativo-com-cabo-preto-306-7zp2b22-ce0)
- **Exemplo de Link para Periféricos:** [mouse e teclado](https://www.dell.com/pt-br/shop/teclado-e-mouse-sem-fio-dell-km3322w/apd/580-bbbb/acess%C3%B3rios-para-computador)
- **Exemplo de Link para Mousepad:** [Mousepad]( https://www.kabum.com.br/produto/111142/mousepad-gamer-rise-mode-black-mode-speed-estendido-900x300mm-rg-mp-06-fbk)
- **Exemplo de Link para Monitor:** [Monitor]( https://www.kabum.com.br/produto/119721/monitor-lg-19-5-hd-60hz-2ms-vga-hdmi-ajuste-de-inclinacao-reader-mode-screen-split-preto-20mk400h-b)
- **Exemplo de Link para Pasta térmica:** [Pasta térmica](https://www.kabum.com.br/produto/506055/pasta-termica-rise-mode-silver-cold-10w-5g-cinza-rm-tg-10-cld?utm_id=21585251035&gad_source=1&gclid=Cj0KCQiAwtu9BhC8ARIsAI9JHangVjx2e1eSPPzkcimck1ciFRJEKLrlhUm4MOMaTW0k3ma5Vlt-I9MaAgPSEALw_wcB)

### VALOR TOTAL:R$ 2.895,99 💸

<br>

---

![](https://rocketz.com.br/rails/active_storage/blobs/proxy/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBalVCIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--a127337310f1d02bf5dfe101345ad521f2504037/pc-gamer-atlas-2.jpg)



  



## Escolha do Sistema Operacional
Após analisar e comparar as versões e sistemas, decidimos instalar o sistema **UNBUTU**

## Manual de Instalação do Linux no VirtualBox

### Pré-requisitos
- **VirtualBox:** Baixe e instale a versão mais recente do [VirtualBox](https://www.virtualbox.org/).
- **Imagem ISO do Linux:** Faça o download da imagem ISO do Ubuntu em [Ubuntu Download](https://ubuntu.com/download).

### Passo a Passo

#### 1. Instalação do VirtualBox
- Acesse o site do VirtualBox e baixe a versão para seu sistema operacional.
- Siga as instruções de instalação fornecidas.
- Após a instalação, abra o VirtualBox.

#### 2. Criação da Máquina Virtual
1. **Clique em "Novo":**
   - **Nome:*VM-UNBUTU* 
   - **Tipo:*UNBUTU - LINUX*
   - **Versão:*24.04.2* 

2. **Configuração de Memória:**
   - Na memória, definimos **4GB**(4096MB).
   - No processador, escolhemos **4 NÚCLEOS**
  
     ![image](https://github.com/user-attachments/assets/4c49a286-eb47-4ed1-813a-6dffb1297ac1)


3. **Criação do Disco Rígido Virtual:**
   - No disco rígido, definimos **25GB** (o necessário para rodar o Unbutu).

#### 3. Configuração de Rede

- Selecione a máquina virtual criada e clique em "Configurações".
- Vá em **Redes**
- Defina a configuração para **NAT**

![image](https://github.com/user-attachments/assets/e85e0cf4-d9c9-4c5b-970a-b6e8cd307fcc)



#### 4. Configuração do Disco de Instalação
- Utilizamos um Disco Rígido existente
- Definimos 25GB para o Sistema.
- utilizamos o controlador listado **PIIX 4** (compativel com o UNBUTU).

![image](https://github.com/user-attachments/assets/af91e977-b65c-4494-9efe-95d8ba8e10e7)


#### 5. Iniciando a Instalação do Ubuntu

1. **Inicie a Máquina Virtual:**
   
   - Após iniciar, o sistema vai perguntar se você deseja instalar o programa ou **Experimentar** (sem instalar)
   - Se escolher "Experimentar", o sistema vai estar pronto para uso, mas sem algumas funcionabilidades disponiveis
  

  ![image](https://github.com/user-attachments/assets/788bd42c-2da8-4fa4-bc78-4097f147e26a)

     
3. **Instalação Passo a Passo:**
   
   - Se escolher iniciar, o sistema ira te mandar configurar o software (idioma, idioma do teclado, tipo de instalação).
   - Após definir esses termos, o sistema te levara para configurar sua conta (nome, nome da maquina, senha).
   - Feito isso, o Unbutu vai começar a instalar
   - Com o download pronto, a maquina vai reiniciar e estar pronta para uso.
   - Se solicitado, conecte à internet para atualizações (opcional).
  
   ![image](https://github.com/user-attachments/assets/4230308e-3589-4d98-a1d4-13ace4c7aab5)


#### 6. Pós-Instalação e Testes
- Após a instalação, a máquina virtual reiniciará.
- Faça login com as credenciais criadas.
- Abra o terminal e verifique a instalação dos softwares executando os seguintes comandos:
  ```bash
  mysql --version
  node -v
  python3 --version


### CONSIDERAÇÕES FINAIS🏆

Com o término da atividade, conseguimos aprender muito, principalmente com os sistemas de rede, instalar maquinas virtuais e escolher os componentes certos para o PC. Sortear as equipes foi muito bom, porque conseguimos socializar e formar novas amizades, otimizando o termino da atividade atraves do trabalho em equipe!😄
