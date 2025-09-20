  

# Redes de Computadores e Segurança Cibernética

  

## Conceitos de Redes de Computadores

  

Uma rede de computadores é o conjunto de dispositivos conectados que compartilham dados e recursos. Esses dispositivos incluem servidores, roteadores, impressoras, laptops, sensores e equipamentos domésticos como TVs e geladeiras. As redes podem ser organizadas em topologias como estrela, barramento, malha e híbridas. A comunicação pode ocorrer via meios físicos (cabos) ou sem fio (Wi-Fi, infravermelho, rádio). A transmissão de dados ocorre em bits, e cada dispositivo converte essas informações em formatos compreensíveis ao usuário.

  

## Largura de Banda, Transferência e Latência

  

A largura de banda é a capacidade máxima de transmissão de dados, medida em Kbps, Mbps ou Gbps. A taxa de transferência é o valor real que está sendo transmitido. Já a latência é o tempo que os dados levam para trafegar entre origem e destino. Esses parâmetros impactam diretamente o desempenho da rede.

  

## MAC Address

  

O endereço MAC é o identificador físico e único de uma interface de rede, atribuído pelo fabricante. Ele é usado para identificar dispositivos em uma rede local. MAC é divido em duas partes.

  

## Protocolos e Modelos

  

Os protocolos são regras que regem a comunicação entre dispositivos. O modelo OSI serve como referência teórica, enquanto o modelo TCP/IP é amplamente utilizado na prática. O encapsulamento é o processo de empacotar dados em diferentes camadas para envio pela rede.

  

### Protocolo IP (IPv4 e IPv6)

  

O IP é responsável pelo endereçamento lógico dos dispositivos. O IPv6 surge como solução para a limitação de endereços do IPv4. Ambos possuem cabeçalhos com informações como TTL (Tempo de vida) e destino.

  

### TCP e UDP

  

O TCP garante a entrega confiável dos pacotes e é orientado à conexão. O UDP é mais rápido, mas não garante entrega, sendo ideal para streaming.

  

### Portas de Rede

  

Portas conhecidas incluem: 80 (HTTP), 443 (HTTPS), 53 (DNS), 21 (FTP), 22 (SSH) e 3389 (RDP). Elas identificam serviços específicos nos dispositivos.

  

### DNS

  

O DNS traduz nomes de domínios para endereços IP. É essencial para a navegação na internet, permitindo o acesso a sites por nomes amigáveis.

  

### HTTP/HTTPS

  

O HTTP é o protocolo base da web, e o HTTPS é a versão segura que utiliza criptografia. Métodos comuns incluem GET, POST, PUT e DELETE.

  

### ICMP

  

Usado para diagnósticos e controle, como o comando ping, que envia pacotes do tipo Echo Request e recebe Echo Reply.

  

## Segurança em Redes

  

A segurança envolve a restrição de protocolos, monitoramento de tráfego e logs, segmentação de redes, uso de firewalls, IDS/IPS, NTP, VPN e políticas como Zero Trust. O objetivo é limitar o impacto de acessos maliciosos e evitar movimentação lateral dentro da rede.

  

## Criptografia

  

Criptografia é o processo de tornar informações ilegíveis para terceiros. Utiliza algoritmos (cifras) para garantir a confidencialidade.

  

### Criptografia Simétrica

  

Mesma chave para criptografar e descriptografar. Usada em compactação de arquivos.

  

### Criptografia Assimétrica

  

Utiliza par de chaves (pública e privada). Aplicada em assinaturas digitais e certificados.

  

### Hash

  

Transforma dados em uma sequência fixa e irreversível. Garante a integridade das informações, muito usado para senhas e verificação de arquivos.

  

## Segurança de Perímetro

  

### Firewall

  

Controla o tráfego entre redes com base em regras. Pode ser do tipo packet filtering (stateless), stateful ou de aplicação, cada um atua de maneiras e em camadas diferentes.

  

### IDS (Intrusion Detection System)

  

Detecta e alerta sobre atividades suspeitas na rede. Pode ser baseado em host (HIDS) ou rede (NIDS).

  

### IPS (Intrusion Prevention System)

  

Além de detectar, bloqueia os ataques em tempo real. Pode ser implementado em host (HIPS) ou rede (NIPS).

  

## Monitoramento de Redes

  

O monitoramento contínuo permite a detecção precoce de incidentes. Ferramentas como IDS, IPS, SIEM e análise de logs são essenciais. Métricas como latência, largura de banda e disponibilidade também são acompanhadas.

  

## Proteção de Estações de Trabalho

  

### Hardening

  

Processo de reforço da segurança das máquinas com base em boas práticas e frameworks como ISO 27001, NIST e CIS Controls.

  

### Anti-malware

  

Ferramentas que detectam e bloqueiam softwares maliciosos. Podem ser baseadas em assinaturas, comportamento ou proteção contra scripts (fileless). Incluem antivírus, antispyware, antispam e firewalls locais.

  

---