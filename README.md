**Título do projeto:** OncoCare4u — Dispositivo Lab-on-a-Chip para Deteção do Biomarcador CEA no Cancro Colorretal 
https://padlet.com/aliciaraujoramos/oncocare4u-7ba0zhttz8r7ufeh


O objetivo deste projeto foi desenvolver um protótipo baseado no conceito de um dispositivo lab-on-a-chip para apoio à deteção e monitorização do biomarcador tumoral **CEA — antigénio carcinoembrionário**, associado ao cancro colorretal. O trabalho partiu de uma problemática atual: o aumento da incidência de cancro em pessoas com menos de 50 anos e a necessidade de soluções que possam contribuir para rastreio, monitorização e acompanhamento clínico de forma mais acessível e menos invasiva.

Inicialmente, o grupo identificou como problema central o crescimento dos casos de cancro em populações jovens, bem como a influência de fatores de risco associados ao estilo de vida e à predisposição hereditária. A partir dessa análise, foi selecionado o **cancro colorretal** como caso de estudo, devido à sua elevada incidência, mortalidade significativa e relevância clínica da deteção precoce.

A solução proposta consistiu no desenvolvimento conceptual de um dispositivo lab-on-a-chip destinado à deteção de biomarcadores tumorais em amostras biológicas. O dispositivo foi pensado para ser utilizado em pessoas com maior risco hereditário, em fases de monitorização após diagnóstico e durante o acompanhamento pós-tratamento, nomeadamente em períodos críticos de possível reincidência da doença. O projeto deixou claro que **o dispositivo não substituiria o diagnóstico médico**, funcionando antes como ferramenta complementar de alerta e monitorização.

O biomarcador selecionado foi o **CEA**, uma glicoproteína cuja **concentração no sangue pode estar elevada em casos de cancro colorretal**. O projeto considerou valores de referência para adultos saudáveis não fumadores e fumadores, bem como intervalos associados a doença localizada, prognóstico desfavorável, maior probabilidade de reincidência e possibilidade de metástases. A monitorização do CEA foi apresentada como relevante antes, durante e após o tratamento, permitindo acompanhar a resposta terapêutica e possíveis sinais de progressão ou recorrência.

A tecnologia escolhida foi baseada em **microfluídica** e **imunofluorescência**. O dispositivo conceptual previa a entrada de uma pequena **amostra de sangue**, entre **20 e 50 µL**, num **chip descartável**, seguida de etapas de **separação dos componentes sanguíneos**, **condução do plasma por microcanais**, **mistura com anticorpos específicos anti-CEA** e **deteção da fluorescência** gerada na **câmara de reação**.

O chip de microfluídica foi pensado como um consumível descartável, evitando problemas de lavagem, contaminação cruzada e interferência em leituras futuras. O material considerado para o chip foi o **PDMS**, devido à sua utilização comum em prototipagem microfluídica, transparência, baixo custo e facilidade de fabrico. Foram ainda considerados tratamentos de superfície por plasma de oxigénio para melhorar a **molhabilidade** e favorecer o **movimento capilar do sangue nos canais**.

A arquitetura do dispositivo incluía um sistema de inserção do chip numa gaveta, uma câmara de reação, um **LED** azul com comprimento de onda de **495 nm** para excitação do fluoróforo e um fotodíodo posicionado para captar a emissão luminosa. A intensidade de fluorescência seria comparada com uma **curva standard intensidade-concentração**, permitindo estimar a **concentração de CEA na amostra**.

A componente eletrónica foi também desenvolvida de forma conceptual e prático. Foi proposto um circuito alimentado por uma **pilha alcalina de 9 V**, com **Arduino Uno R3**, **interruptor de fim de curso**, **LED** azul, **fotodíodo**, **conversor corrente-tensão**, **filtro passa-baixo digital** e **LCD** para apresentação dos resultados. O interruptor permitiria verificar se a gaveta do dispositivo estava corretamente fechada antes do início do teste, aumentando a segurança e a consistência da medição.

O processamento do sinal previa a conversão da corrente gerada pelo fotodíodo em tensão, seguida de filtragem e análise pelo microcontrolador. Quanto maior a fluorescência detetada, maior seria a tensão associada e, consequentemente, maior a concentração estimada de CEA. A interpretação final dependeria da comparação com a curva standard, permitindo apresentar ao **utilizador mensagens simples**, como **''Normal''** ou **''Consulte o seu médico''**.

Durante o desenvolvimento do projeto, foram consideradas melhorias relacionadas com a conservação dos reagentes. Uma das soluções estudadas foi a **liofilização dos anticorpos**, permitindo o seu armazenamento em cartuchos substituíveis e hermeticamente vedados. Esta abordagem foi pensada para **aumentar a durabilidade** dos reagentes à **temperatura ambiente** e facilitar o uso do dispositivo **sem necessidade de profissionais especializados**.

O projeto evoluiu ao longo de várias etapas, incluindo pitch inicial, apresentação intermédia, reuniões de orientação, definição do nome e apresentação final. O nome inicial LAB4CANCER acabou por evoluir para OncoCare4u, reforçando uma identidade mais orientada para cuidado, acompanhamento e aplicação biomédica.

A equipa concluiu que o OncoCare4u representa uma solução promissora para aplicação em rastreio complementar, monitorização terapêutica e seguimento pós-tratamento no contexto do cancro colorretal. O projeto permitiu integrar conhecimentos de biomarcadores tumorais, microfluídica, imunofluorescência, eletrónica básica, processamento de sinal e desenvolvimento de produto biomédico.

Como limitações, importa deixar claro que o projeto foi **conceptual** e **não corresponde a um dispositivo clinicamente validado**. Para uma **continuação realista**, seriam necessários **ensaios experimentais com amostras controladas**, estudo da sensibilidade e especificidade do sistema, avaliação da estabilidade dos reagentes, otimização dos canais microfluídicos e **validação segundo requisitos regulamentares aplicáveis a dispositivos médicos de diagnóstico in vitro**.

Conteúdos deste repositório:

- PDF exportado do Padlet — registo da evolução do projeto OncoCare4u.
- Secção de equipa — identificação dos elementos do grupo.
- Pitch inicial — apresentação da problemática, fatores de risco e proposta de solução.
- Pesquisa sobre o aumento da incidência de cancro em pessoas jovens.
- Seleção do cancro colorretal como caso de estudo.
- Fundamentação sobre biomarcadores tumorais e escolha do CEA.
- Estudo de tecnologias lab-on-a-chip aplicadas à deteção de biomarcadores.
- Pesquisa sobre microfluídica, PDMS, imunofluorescência e deteção ótica.
- Definição conceptual do chip descartável de microfluídica.
- Proposta do circuito eletrónico com LED, fotodíodo, Arduino, filtro digital e LCD.
- Descrição do funcionamento do dispositivo e interpretação dos resultados.
- Apresentação intermédia e apresentação final do projeto.
- Comentários, sugestões e decisões tomadas ao longo do desenvolvimento.

Este trabalho foi importante para consolidar conhecimentos em **microfluídica**, **biossensores**, **biomarcadores tumorais**, **imunofluorescência**, **eletrónica** aplicada à saúde e **desenvolvimento conceptual de dispositivos médicos**. Também permitiu trabalhar a ligação entre investigação biomédica, viabilidade técnica, comunicação de produto e necessidade clínica.

Projeto realizado por **Afonso Lopes**, **Alícia Ramos**, **Matilde Serra** e **Sílvia Gonçalves**, no âmbito da Licenciatura em Engenharia Biomédica da Universidade do Minho. **Classificação final: 17,5 valores em 20**.
