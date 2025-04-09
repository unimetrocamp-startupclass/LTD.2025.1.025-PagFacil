﻿
```markdown
**Documentação do Sistema**

SUMÁRIO

[[Dados do Cliente 2]{.underline}](#dados-do-cliente)

[[Equipe de Desenvolvimento 3]{.underline}](#equipe-de-desenvolvimento)

[[1. Introdução 4]{.underline}](#introdução)

[[2. Objetivo 5]{.underline}](#objetivo)

[[3. Escopo 6]{.underline}](#escopo)

[[4. Backlogs do Produto 7]{.underline}](#backlogs-do-produto)

[[5. Cronograma 8]{.underline}](#cronograma)

[[6. Materiais e Métodos 9]{.underline}](#materiais-e-métodos)

[[7. Resultados 10]{.underline}](#resultados)

[[8. Conclusão 11]{.underline}](#conclusão)

[[9. Homologação do MVP junto ao cliente
12]{.underline}](#homologação-do-mvp-junto-ao-cliente)

[[10. Divulgação 13]{.underline}](#divulgação)

[[11. Carta de Apresentação 15]{.underline}](#carta-de-apresentação)

[[12. Carta de Autorização 16]{.underline}](#carta-de-autorização)

[[13. Relato individual do processo
18]{.underline}](#relato-individual-do-processo)

+-----------------------------------------------------------------------+
| # Dados do Cliente                                                    |
+-----------------------------------------------------------------------+

Título do Projeto: PagFacil: um aplicativo de reconhecimento de contas

Cliente: Elaine Cristina Ferreira Iamarino

CNPJ/CPF: 263.396.038-31

Contato: Willian Luiz Iamarino Gandolphi

Email do contato: 202308428454@alunos.unimetrocamp.edu.br

+-----------------------------------------------------------------------+
| # Equipe de Desenvolvimento                                           |
+-----------------------------------------------------------------------+

  --------------------------- --------------------- ---------------------
       **Nome completo**            **Curso**          **Disciplina**

  Wallace da Silva Francisco           ADS          Programação Orientada
                                                      a Objetos em Java

     Willian Luiz Iamarino             ADS          Programação Orientada
           Gandolphi                                  a Objetos em Java

        Augusto Ramlow             Sistemas de      Programa Orientada a
                                   Informação          Objetos em Java

                                                    
  --------------------------- --------------------- ---------------------

  -----------------------------------------------------------------------
                         **Professor Orientador**

                          Kesede Rodrigues Julio
  -----------------------------------------------------------------------

+-----------------------------------------------------------------------+
| # Introdução                                                          |
+-----------------------------------------------------------------------+

> O cliente enfrenta dificuldades para lembrar as datas de vencimento de
> suas contas, o que frequentemente resulta em atrasos e no pagamento de
> juros. Esse problema impacta diretamente sua organização financeira e
> pode gerar despesas desnecessárias ao longo do tempo.
>
> Para resolver essa questão, será desenvolvido um sistema automatizado
> de gerenciamento de contas, que utilizará inteligência artificial (IA)
> para reconhecimento de texto. O usuário poderá apontar a câmera do
> celular para uma conta física ou digital, e o sistema extrairá
> automaticamente informações essenciais, como data de vencimento, valor
> e beneficiário. Esses dados serão armazenados em um calendário
> inteligente, que enviará notificações antes da data de vencimento.
>
> A solução será implementada com tecnologias modernas, incluindo
> machine learning para extração de texto, bancos de dados para
> armazenamento das contas, uma interface mobile amigável para facilitar
> o uso e integração com APIs de notificações para envio de lembretes.
>
> Com essa abordagem, o sistema permitirá que o usuário evite atrasos no
> pagamento de contas e melhore sua organização financeira, reduzindo
> prejuízos com juros e aumentando sua tranquilidade no controle de
> despesas.

+-----------------------------------------------------------------------+
| # Objetivo                                                            |
+-----------------------------------------------------------------------+

Atualmente, o cliente enfrenta dificuldades para lembrar as datas de
vencimento de suas contas, o que frequentemente resulta em atrasos e
cobranças de juros. Esse problema é ainda mais comum para pessoas que
possuem múltiplas faturas mensais, como água, energia, internet e cartão
de crédito, tornando a gestão financeira uma tarefa desafiadora.

Para solucionar essa questão, o sistema proposto utilizará um calendário
automatizado integrado a um sistema de reconhecimento de texto baseado
em inteligência artificial (IA). O funcionamento será simples e
intuitivo: o usuário poderá apontar a câmera do celular para a conta
física ou digital, e a IA identificará automaticamente informações como
data de vencimento, valor e beneficiário. Essas informações serão
registradas no calendário do sistema, que enviará lembretes automáticos
antes do vencimento, ajudando o usuário a evitar atrasos e juros
desnecessários.

Com essa abordagem, o sistema proporcionará uma solução prática e
eficiente para o gerenciamento de contas, reduzindo o risco de
esquecimento e melhorando o controle financeiro do usuário.

+-----------------------------------------------------------------------+
| # Escopo                                                              |
+-----------------------------------------------------------------------+

Este projeto tem como objetivo criar um aplicativo que ajude as pessoas
a organizarem melhor suas contas. A ideia é que o usuário possa escanear
boletos e faturas com a câmera do celular, e o app, usando inteligência
artificial, identifique automaticamente informações importantes como
data de vencimento, valor e beneficiário.

Esses dados serão salvos em um calendário digital dentro do próprio app,
que também enviará lembretes próximos aos vencimentos, evitando
esquecimentos. Tudo será acessível por uma interface simples, onde o
usuário poderá ver e editar suas contas, além de configurar alertas
conforme sua necessidade.

Importante: nesta primeira versão, o app não fará pagamentos, não estará
conectado a bancos e pode ter limitações ao reconhecer alguns tipos de
contas.

**\
**

+-----------------------------------------------------------------------+
| # Backlogs do Produto                                                 |
+-----------------------------------------------------------------------+

**Requisitos principais (o que será implementado):\
**1. Reconhecimento automatizado de contas via IA\
- O sistema permitirá que o usuário escaneie boletos, faturas e outras
contas usando a câmera do celular.\
- Um modelo de inteligência artificial será responsável por extrair data
de vencimento, valor e beneficiário automaticamente.\
2. Calendário inteligente com lembretes automáticos\
- Após o reconhecimento dos dados, o sistema armazenará as informações
em um calendário digital.\
- O usuário receberá notificações automáticas próximas ao vencimento das
contas, ajudando a evitar atrasos.\
3. Interface amigável para gerenciamento das contas\
- Será desenvolvida uma interface simples e intuitiva, onde o usuário
poderá visualizar suas contas registradas, editar informações
manualmente e configurar alertas personalizados.

**Limites da implementação (o que não será incluído nesta versão):\
**- Pagamentos automáticos: O sistema não realizará o pagamento das
contas, apenas ajudará a organizá-las e lembrar das datas.\
- Reconhecimento de todas as contas existentes: Inicialmente, o sistema
poderá ter limitações quanto aos formatos de contas reconhecidos,
podendo precisar de ajustes para alguns modelos de boleto ou fatura.\
- Integração com bancos: A primeira versão do sistema não terá
integração direta com instituições financeiras, sendo apenas um
gerenciador de lembretes e organização de contas.

+-----------------------------------------------------------------------+
| # Cronograma                                                          |
+-----------------------------------------------------------------------+

+-----------------------------------------------------------------------+
| # Materiais e Métodos                                                 |
+-----------------------------------------------------------------------+

a.  **Modelagem do sistema**:

b.  **Tecnologias utilizadas**:

c.  **Arquitetura do sistema**:

+-----------------------------------------------------------------------+
| # Resultados                                                          |
+-----------------------------------------------------------------------+

a.  **Protótipo**:

b.  **Códigos das principais funcionalidades**:

+-----------------------------------------------------------------------+
| # Conclusão                                                           |
+-----------------------------------------------------------------------+

a.  **Impacto do sistema:**

b.  **Melhorias Futuras**:

+-----------------------------------------------------------------------+
| # Homologação do MVP junto ao cliente                                 |
+-----------------------------------------------------------------------+

Após as entregas parciais, realizadas de acordo com os requisitos do
sistema e cronograma, o MVP foi apresentado em uma reunião, realizada
entre o time de desenvolvedores e o cliente.

  ---------------------------------- ------------------------------------
                                     

      Da esquerda para direita:      

                                     

     Participantes da homologação        Participantes da homologação
      assistindo a apresentação      
  ---------------------------------- ------------------------------------

> Segue abaixo a lista de presentes na homologação do MVP.

  -----------------------------------------------------------------------
                   **Lista de presentes na Homologação**

  -----------------------------------------------------------------------

> Ao final da apresentação, o sistema foi homologado pelo cliente.

+-----------------------------------------------------------------------+
| # Divulgação                                                          |
+-----------------------------------------------------------------------+

a.  **Linkedin do Projeto**

  --------------------------------- -------------------------------------
                                    

  --------------------------------- -------------------------------------

b.  **Seminário de Projetos de Software**

> **[Vídeo da apresentação:]{.mark}**

  ---------------------------------- ------------------------------------
                                     

      Da esquerda para direita:      

                                     

  Participantes do evento assistindo Participantes do evento assistindo a
            a apresentação                       apresentação
  ---------------------------------- ------------------------------------

> [Segue]{.mark} abaixo a lista de presentes na apresentação.

  -----------------------------------------------------------------------
                  **Lista de presentes na Apresentação**

  -----------------------------------------------------------------------

c.  **FENETEC: Feira de Negócios em Tecnologia**

> **Apresentação do projeto:**

  ---------------------------------- ------------------------------------
                                     

      Da esquerda para direita:      

                                     

  Participantes do evento assistindo         Estandes da FENETEC
            a apresentação           
  ---------------------------------- ------------------------------------

> Segue abaixo a lista de presentes na FENETEC.

  -----------------------------------------------------------------------
                  **Lista de presentes na Apresentação**

  -----------------------------------------------------------------------

+-----------------------------------------------------------------------+
| # Carta de Apresentação                                               |
+-----------------------------------------------------------------------+

Vimos por desta apresentar o grupo de acadêmicos do Centro Universitário
Unimetrocamp, localizada à Rua Sales de Oliveira, 1661 - Campinas - SP,
a fim de convidá-lo a participar de uma atividade extensionista
associada ao componente curricular Programação Orientada a Objetos em
Java, sob responsabilidade do orientador Prof. Kesede Rodrigues Julio
(profkesede64@gmail.com).

Em consonância ao Plano Nacional de Educação vigente, o Centro
Universitário Unimetrocamp promove o Desenvolvimento de Software que,
norteados pela metodologia de Gerenciamento Ágil Scrum, tem por
princípios fundantes o diagnóstico dos problemas/demandas/necessidades,
a participação ativa dos interessados/públicos participantes, a
construção dialógica, coletiva e experiencial de conhecimentos, o
planejamento de ações, o desenvolvimento e avaliação das ações, a
sistematização dos conhecimentos, a avaliação das ações desenvolvidas.

Nesse contexto, a disciplina acima mencionada tem como principal escopo
os temas relacionados à Programação Orientada à Objeto / Padrões de
Projetos de Software, no que diz respeito ao desenvolvimento de um
software utilizando Programação Orientada à Objeto.

Sendo assim, [pedimos o apoio de \_\_\_\_\_\_\_\_\_\_\_\_\_ para a
realização das seguintes atividades: levantamento de requisitos,
validação das entregas parciais, revalidação dos requisitos, homologação
do MVP, ou qualquer outra intervenção que auxilie no desenvolvimento das
competências de nossos acadêmicos e ao mesmo tempo possa contribuir para
a comunidade em que estamos inseridos.]{.mark}

[Aproveitamos a oportunidade para solicitarmos, em caso de aceite, que a
parceria seja formalizada, mediante assinatura da Carta de Autorização,
as atividades e informações que o(s) aluno(s) poderá(ão) ter
acesso.]{.mark}

[Em tempo, registramos ainda, o convite para a participação de todos os
interessados no fórum semestral de acompanhamento e avaliação das
atividades realizadas, que está previsto para o final deste semestre, e
será comunicado previamente em convite específico.]{.mark}

[Desde já nos colocamos à sua disposição para quaisquer
esclarecimentos.]{.mark}

[Atenciosamente,]{.mark}

Campinas, \_\_\_\_ de \_\_\_\_\_\_\_\_\_ de
202\_\_\_.![](media/image1.jpg){width="1.391761811023622in"
height="0.8158606736657917in"}

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Assinatura Direção Acadêmica da IES**

![](media/image2.jpg){width="5.0in" height="1.22666447944007in"}

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Assinatura Docente**

+-----------------------------------------------------------------------+
| # Carta de Autorização                                                |
+-----------------------------------------------------------------------+

Eu,\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_autorizo
a realização das seguintes atividades acadêmicas do componente
extensionista \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ do Centro
Universitário Unimetrocamp, sob orientação do Prof. Kesede Rodrigues
Julio.

+:----------------------------------------------------------------------+
| > **Atividades:**                                                     |
+-----------------------------------------------------------------------+
|                                                                       |
+-----------------------------------------------------------------------+
|                                                                       |
+-----------------------------------------------------------------------+
|                                                                       |
+-----------------------------------------------------------------------+
|                                                                       |
+-----------------------------------------------------------------------+

Conforme combinado em contato prévio, as atividades acima descritas são
autorizadas para os seguintes alunos:

+:----------------------------:+:---------------:+:-------------------:+
| > **Nome dos/das alunos/as** | > **Curso**     | > **Matrícula**     |
+------------------------------+-----------------+---------------------+
|                              |                 |                     |
+------------------------------+-----------------+---------------------+
|                              |                 |                     |
+------------------------------+-----------------+---------------------+
|                              |                 |                     |
+------------------------------+-----------------+---------------------+
|                              |                 |                     |
+------------------------------+-----------------+---------------------+
|                              |                 |                     |
+------------------------------+-----------------+---------------------+

Declaro que fui informado por meio da **Carta de Apresentação** sobre as
características e objetivos das atividades que serão realizadas na
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ a qual
represento e afirmo estar ciente de tratar-se de uma atividade realizada
com intuito **exclusivo de ensino de alunos de graduação**, sem a
finalidade de exercício profissional.

Desta forma, autorizo, em caráter de confidencialidade:

- o acesso a informações e dados que forem necessários à execução da
  atividade;

- o registro de imagem por meio de fotografias;

- outro:

Campinas, \_\_\_ de \_\_\_\_\_\_\_\_\_\_\_de 202\_.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

(Assinatura, nome completo do responsável, email de contato e com
carimbo da empresa)

+-----------------------------------------------------------------------+
| # Relato individual do processo                                       |
+-----------------------------------------------------------------------+

  -----------------------------------------------------------------------
  \<nome do aluno\>

  \<um breve relato pessoal sobre o trabalho extensionista desenvolvido\>
  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  \<nome do aluno\>

  \<um breve relato pessoal sobre o trabalho extensionista desenvolvido\>
  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  \<nome do aluno\>

  \<um breve relato pessoal sobre o trabalho extensionista desenvolvido\>
  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  \<nome do aluno\>

  \<um breve relato pessoal sobre o trabalho extensionista desenvolvido\>
  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  \<nome do aluno\>

  \<um breve relato pessoal sobre o trabalho extensionista desenvolvido\>
  -----------------------------------------------------------------------

```
