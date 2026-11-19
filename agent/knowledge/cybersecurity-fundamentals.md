# Fundamentos de Cibersegurança em Laboratório

A cibersegurança prática exige ética, ambiente controlado e visão dupla entre ataque e defesa. O agente precisa conhecer esses fundamentos para orientar estudos seguros, aprofundar o raciocínio defensivo e ajudar o estudante a documentar seu aprendizado.

Para cada pilar abaixo: o que é, como se aplica em estudo e como o agente pode ajudar.

## Ética e Ambiente Controlado

**O que é:** a prática de segurança da informação realizada exclusivamente em ambientes isolados e autorizados, como máquinas virtuais (VMs) ou redes internas de laboratório, com finalidade educacional e de pesquisa[cite: 1, 2].

**Como funciona:** o estudante prepara um laboratório próprio (por exemplo, com sistemas isolados ou aplicações de teste) para observar comportamentos de rede, autenticação ou software sem afetar sistemas reais ou terceiros[cite: 1, 2]. Entender a falha e como proteger o sistema vale mais do que reproduzir ataques fora de contexto[cite: 1, 2].

**Como o agente ajuda:**
- Reforçar desde o início que simulações e testes devem ocorrer apenas em ambiente controlado e autorizado[cite: 1, 2].
- Evitar entregar comandos ou scripts prontos para uso indevido, mantendo o foco no entendimento da lógica e na defesa[cite: 1, 2].
- Ajudar o estudante a delimitar o escopo do laboratório antes de começar.

## Visão Ofensiva e Defensiva (Red Team e Blue Team)

**O que é:** a análise de ameaças sob duas perspectivas complementares: entender como o risco ou vetor de ataque funciona (visão ofensiva / Red Team) e como detectar, bloquear ou mitigar o impacto (visão defensiva / Blue Team)[cite: 1, 2].

**Como funciona:** em laboratórios de cibersegurança, o estudante observa como falhas de autenticação, configurações frágeis ou scripts de captura e bloqueio de dados operam, e em seguida avalia controles como monitoramento de processos, antivírus/EDR, firewalls, políticas de backup, controle de privilégios e sandboxing[cite: 1, 2].

**Como o agente ajuda:**
- Explicar o "porquê" técnico por trás da ameaça antes de avançar para os detalhes do teste.
- Conectar cada cenário estudado a medidas concretas de prevenção, detecção e resposta (visão Blue Team)[cite: 1, 2].
- Apoiar na explicação de conceitos técnicos quando surgir dúvida (use a skill `explain-concept`).

## Fator Humano e Engenharia Social

**O que é:** a dimensão da segurança que envolve hábitos, atenção e decisões das pessoas diante de ameaças digitais, como mensagens enganosas, anexos suspeitos ou senhas fracas[cite: 1, 2].

**Como funciona:** muitas ameaças digitais exploram falhas humanas — como clicar em links maliciosos, executar arquivos sem verificação ou reutilizar credenciais — antes mesmo de explorar uma brecha puramente técnica do sistema[cite: 1, 2].

**Como o agente ajuda:**
- Ajudar o estudante a identificar onde o comportamento do usuário aumenta ou reduz o risco em cada cenário[cite: 1, 2].
- Sugerir boas práticas de prevenção, como autenticação forte, cautela com anexos/links e conscientização[cite: 1, 2].
- Contextualizar como controles técnicos e hábitos seguros trabalham juntos.

## Documentação e Portfólio no GitHub

**O que é:** o registro organizado dos estudos, testes em laboratório, análises de risco, medidas de defesa e reflexões pessoais em um repositório no GitHub[cite: 1, 2].

**Como funciona:** o estudante transforma o que aprendeu em um `README.md` claro (seja com evidências/estruturas técnicas ou como um relato reflexivo dos conceitos e aprendizados), demonstrando domínio do tema e evolução contínua[cite: 1, 2].

**Como o agente ajuda:**
- Ajudar a estruturar o `README.md` com objetivo, análise do cenário, riscos, medidas de mitigação e aprendizados[cite: 1, 2].
- Incentivar o estudante a escrever com as próprias palavras, explicando o que compreendeu de cada experimento[cite: 1, 2].
- Revisar a organização do repositório para fins de estudo ou portfólio (use a skill `portfolio-review`).

## Resumo rápido

| Pilar | Em uma frase |
|-------|--------------|
| Ética e Ambiente Controlado | Prática segura e autorizada em ambiente isolado com foco educacional[cite: 1, 2]. |
| Red Team e Blue Team | Entender como a ameaça opera para construir defesas e mitigações eficazes[cite: 1, 2]. |
| Fator Humano | Atenção a hábitos, engenharia social e decisões que influenciam a segurança[cite: 1, 2]. |
| Documentação e Portfólio | Registro claro de conceitos, defesas e aprendizados no GitHub[cite: 1, 2]. |