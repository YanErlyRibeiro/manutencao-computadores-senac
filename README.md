# Manual Pessoal de Segurança e Boas Práticas do Técnico em Informática

Este documento reúne diretrizes fundamentais de ergonomia, prevenção contra descarga eletrostática (ESD), gestão responsável de resíduos eletrônicos e orientações oficiais de fabricantes de hardware, visando garantir a segurança operacional, a integridade dos componentes e a sustentabilidade no trabalho técnico de manutenção e montagem de computadores.

---

## 📋 Sumário
1. [Introdução à Profissão e Ergonomia (NR-17)](#1-introdução-à-profissão-e-ergonomia-nr-17)
2. [Guia Completo de Prevenção à ESD (Descarga Eletrostática)](#2-guia-completo-de-prevenção-à-esd-descarga-eletrostática)
3. [Mapeamento de E-lixo Regional](#3-mapeamento-de-e-lixo-regional)
4. [Insights dos Manuais de Fabricantes](#4-insights-dos-manuais-de-fabricantes)

---

## 1. Introdução à Profissão e Ergonomia (NR-17)

A atuação do técnico em informática exige longos períodos de postura sentada ou curvada sobre bancadas de testes e montagem, além de esforço visual e repetitividade nos braços e mãos. A obediência às diretrizes da **Norma Regulamentadora nº 17 (NR-17)** previne lesões corporais, fadiga mental e doenças ocupacionais (como LER/DORT).

### Diretrizes de Ergonomia para a Bancada de Trabalho:
* **Mobiliário e Postura:**
  * Assentos com regulagem de altura, suporte lombar adequado e borda frontal arredondada para evitar a compressão vascular das pernas.
  * Disponibilização de apoio para os pés sempre que o técnico não conseguir manter as plantas totalmente apoiadas no piso.
  * Garantia de espaço suficiente abaixo do plano de trabalho para movimentação livre das pernas e aproximação ao ponto de operação.
  * Bancadas projetadas para permitir a alternância entre a posição sentada e em pé durante a jornada.
* **Organização do Trabalho e Pausas:**
  * Adoção de pausas de descanso remuneradas fora do posto de trabalho e alternância de tarefas/posturas para prevenir sobrecarga muscular estática no pescoço, tronco e membros superiores.
  * Acesso irrestrito às instalações sanitárias para necessidades fisiológicas independentemente das pausas programadas.
  * Limitação do manuseio e transporte manual de cargas pesadas (como gabinetes de grande porte e servidores), respeitando alcances horizontais máximos de 60 cm do corpo.
* **Conforto Ambiental:**
  * **Iluminação:** Projeto e instalação em conformidade com a NHO 11 da Fundacentro, de modo a evitar reflexos na tela, ofuscamento, sombras ou contrastes excessivos.
  * **Conforto Térmico:** Temperatura do ar entre **18 °C e 25 °C** em ambientes climatizados.
  * **Conforto Acústico:** Nível aceitável de ruído de fundo de até **65 dB(A)** para locais que exijam constante atenção e solicitação intelectual.

---

## 2. Guia Completo de Prevenção à ESD (Descarga Eletrostática)

A Descarga Eletrostática (*Electrostatic Discharge – ESD*) é a transferência repentina de carga elétrica entre dois corpos com potenciais elétricos diferentes. Na manutenção de hardware, representa uma ameaça crítica devido à sua natureza imperceptível ao ser humano.

### Por que a ESD é uma Ameaça Invisível?
* **Sensibilidade Humana vs. Eletrônica:** O corpo humano armazena energia via efeito triboelétrico (atrito com roupas sintéticas, cadeiras ou carpetes) e só consegue sentir o choque de uma descarga acima de **2.000 a 3.000 Volts** (e ver uma faísca a partir dos 5.000 V).
* **Vulnerabilidade dos Microchips:** Processadores (CPUs), memórias RAM e placas-mãe possuem transistores microscópicos com camadas isolantes de óxido de silício que podem sofrer perfurações físicas irreversíveis com tensões tão baixas quanto **10 a 100 Volts**.

### Tipos de Danos Causados por ESD:
1. **Dano Imediato (Falha Catastrófica):** Ocorre a fusão instantânea das trilhas ou microtransistores do circuito integrado. O componente para de funcionar no mesmo momento da descarga e o equipamento não liga.
2. **Dano Latente (Falha Degradativa):** O microchip sofre uma fissura ou enfraquecimento em sua estrutura interna, mas continua operando parcialmente. O componente apresentará comportamento instável ao longo do tempo (telas azuis, erros aleatórios de memória, travamentos em carga e degradação prematura da vida útil), tornando o diagnóstico extremamente complexo.

### Procedimentos Preventivos Obrigatórios do Técnico:
* **Equalização de Potencial:** Utilizar **pulseira antiestática** com cabo espiral conectado ao aterramento da rede elétrica ou à carcaça metálica desbotada de um gabinete que esteja conectado à tomada aterrada (com a chave da fonte desligada).
* **Superfície Antiestática:** Realizar qualquer procedimento de montagem e teste sobre **mantas/tapetes antiestáticos** condutivos devidamente aterrados.
* **Armazenamento e Transporte:** Guardar todas as placas de circuito, memórias e processadores exclusivamente em **sacos antiestáticos (bolsas ESD)** de proteção.
* **Ponto de Pegada Correto:** Segurar placas e módulos rigorosamente pelas **bordas de fibra de vidro/fenolite**, sem nunca tocar com os dedos nos pinos dourados, barramentos de contato ou chips expostos.
* **Tática de Emergência (Sem pulseira):** Na ausência temporária de acessórios ESD, tocar repetidamente em uma superfície metálica não pintada da carcaça do gabinete para equalizar momentaneamente as cargas elétricas do corpo antes de manusear os circuitos.

---

## 3. Mapeamento de E-lixo Regional

O descarte incorreto de resíduos eletrônicos (*e-lixo*) libera metais pesados tóxicos (chumbo, mercúrio, cádmio) no solo e nos lençóis freáticos, além de oferecer riscos térmicos decorrentes de baterias de lítio. O técnico deve gerenciar o ciclo de vida dos insumos e encaminhar componentes obsoletos aos Pontos de Coleta Seletiva / Ecopontos mapeados abaixo na cidade de Manaus-AM:

### Pontos de Coleta e Ecopontos Identificados

#### 1. Ecopontos e Sedes Municipais (Parceria Semulsp / Circular Brain)
Totens e estrutura de logística reversa destinados a equipamentos de pequeno e médio porte.
* **Sede da Semulsp:** Avenida Brasil, s/nº, Compensa II.
* **Sede da Prefeitura de Manaus:** Avenida Brasil, 2971, Compensa II.
* **Ecoponto Zona Sul:** Bairro Educandos.
* **Itens Aceitos:** Smartphones, tablets, computadores, notebooks, periféricos (teclados, mouses, pen drives, roteadores), cabos, carregadores, pequenas TVs e eletroportáteis.
* ⚠️ *Restrição:* Não aceitam pilhas ou baterias avulsas fora dos equipamentos, tampouco lâmpadas comerciais.

#### 2. Lojas Bemol – Pontos de Entrega Voluntária (Parceria Green Eletron)
Pontos de Entrega Voluntária (PEVs) posicionados em polos de fácil acesso comercial.
* **Bemol Matriz:** Rua Miranda Leão, 41, Centro.
* **Bemol Cidade Nova:** Avenida Noel Nutels, 1762, Cidade Nova.
* **Bemol Manauara Shopping:** Avenida Mário Ypiranga, 1300, Adrianópolis.
* **Bemol Shopping Grande Circular:** Avenida Autaz Mirim, 6100, São José Operário.
* **Itens Aceitos:** Eletroeletrônicos de pequeno porte (mouses, teclados, fones, carregadores) e baterias/pilhas avulsas (em coletores específicos da Green Eletron).
* ❌ *Restrição:* Não aceitam monitores de tubo, TVs grandes ou eletrodomésticos de linha branca.

---

## 4. Insights dos Manuais de Fabricantes

Mapeamento de segurança e boas práticas extraído do manual técnico oficial da placa-mãe **ROG STRIX X870E-E GAMING WIFI7 NEO** (ASUSTeK Computer Inc.):

### Localização das Seções Iniciais no Manual:
* **Safety Information (Informações de Segurança):** Página 4
* **Button/Coin Batteries Safety Information:** Página 5
* **Specifications Summary (Alimentação e Energia):** Páginas 8 a 13
* **Section 1.1 - Before You Proceed (Manuseio e Alertas de ESD):** Página 16

### Principais Cuidados Exigidos pelo Fabricante:
1. **Prevenção de Descarga Eletrostática (ESD):**
   * Usar obrigatoriamente pulseira antiestática ou tocar em objetos devidamente aterrados antes do manuseio (*pág. 16*).
   * Segurar a placa-mãe e componentes pelas bordas, sem encostar nas superfícies dos circuitos integrados (*pág. 16*).
   * Dispor as peças desinstaladas em sacos ou superfícies antiestáticas (*pág. 16*).
2. **Desconexão Total da Energia:**
   * Desconectar o cabo de alimentação da tomada antes de tocar, instalar ou remover qualquer placa, memória ou conector interno (*pág. 4, 16*).
   * Verificar se todos os conectores obrigatórios da CPU (8 pinos +12V) estão devidamente inseridos (*pág. 25*).
   * Utilizar fontes de alimentação de 900W a 1200W (ou superior) quando o sistema contar com múltiplas placas de vídeo de alta demanda energética (*pág. 25*).
3. **Proteção Física do Soquete do Processador (AM5):**
   * O encaixe do CPU AM5 é assimétrico e único; **não exercer força excessiva** ao posicionar o processador para evitar a deformação dos pinos de contato (*pág. 19, 37*).
   * A tampa de proteção plástica do soquete (*PnP Cap*) deve ser preservada; a garantia do fabricante (RMA) exige que a placa-mãe seja enviada com a tampa protetora instalada no soquete (*pág. 19, 37*).
4. **Condições Ambientais e Segurança Física:**
   * A placa-mãe deve ser operada apenas em ambientes com temperatura controlada entre **10 °C e 35 °C** (*pág. 4*).
   * Afastar objetos condutores (parafusos soltos, grampos e clipes de papel) das trilhas e soquetes para evitar curtos-circuitos (*pág. 4*).
   * Recomenda-se o uso de luvas ou equipamentos de proteção ao manusear a placa no chassi para evitar acidentes pessoais (*pág. 4*).
5. **Cuidados com a Bateria do CMOS (CR2032):**
   * A placa contém uma bateria moeda de Lítio 3V (CR2032). Perigo de ingestão química com risco de morte ou queimaduras graves internas em menos de 2 horas (*pág. 5*).
   * Jamais incinerar ou descartar em lixo comum; encaminhar aos postos de coleta seletiva para e-lixo (*pág. 5*).
```

eof