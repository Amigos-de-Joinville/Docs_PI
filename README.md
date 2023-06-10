
# Projeto Integrador - Amigos de Joinville
![Header](./pi.png)


<p align="justify">Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Alunos: [Ana Paula de Souza](https://github.com/aanappaula) e [Ana Luiza Dias da Rocha](https://github.com/AnaLuizaDias) - 3info1

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)](github.com/aanappaula/projeto_integrador)
-   [Backend](github.com/marcoandre/pi-backend)
-   [Frontend](github.com/marcoandre/pi-frontend)


# Modelos de Sistemas

<p align="justify">A base do nosso projeto foi inspirada no modelo ponto de vendas (PDV). Desde o início queríamos fazer o site referente a adoções de animais, visto que temos bastante familiarização do assunto, já que em anos anteriores tivemos a chance de trabalhar com esse modelo de site. E o modelo que mais se encaixa nesse quesito de realizar uma "compra" do animal, é o (PDV).


#  Introdução

<h2>Amigos de Joinville</h2>

<p align="justify">Paula e Luiza são duas amigas que sempre amaram os animais. Resgatando um gato ou um cachorro de vez em quando, elas decidiram realizar um sonho antigo. Em 2021, elas inauguraram uma ONG para adoção de animais em Joinville e região, para ajudar os animais que foram abandonados ou estão perdidos a acharem um lar. A ONG “Amigos de Joinville”, é divulgada somente em suas redes sociais (Instagram e Facebook). Com a grande repercussão da ONG, foi vista uma necessidade da criação de um site, para ter o melhor controle dos animais e das adoções, e fazer a avaliação dos tutores para  assim realizar a possível adoção.


# Situação Problema


<h2>Problemas:</h2>

**A chegada do animal:** <p align="justify"> Ao localizar um animal perdido ou abandonado, iremos acionar uma de nossas atendentes para levá-lo até a ONG. O cadastro desse animal é feito por intermédio de planilhas, realizado pelas nossas próprias atendentes, o que se torna cansativo visto que é feito a mão.

**Divulgação:** <p align="justify"> Assim que o animal é alocado na ONG, é feita uma divulgação para assim buscar adotantes. Utiliza-se as redes sociais como Instagram e Facebook para realizar as postagens dos animais, contendo foto e as informações pessoais.

**Falta de recursos e infraestrutura:** <p align="justify">Devido ao grande número de animais que a ONG aloca, é visto então uma necessidade de um alto investimento, com os gastos dos animais (água, ração, vacinas...). E como a ONG não possui seu próprio site, fica difícil ganhar visibilidade para obter parcerias com grandes empresas.

**Documentação:** 
<p align="justify"> Para adotar algum animal da ONG, a pessoa responsável deve comparacer ao local, e responder a algumas perguntas das nossas atendentes, e assim será anotado os dados na planilha de adotantes. A pessoa deve se encaixar nas perguntas deferidas para assim realizar a adoção.

**Falta de transparência no processo de adoção:**
<p align="justify"> Como os dados dos animais estão adotados numa planilha, fica exposto a riscos de perda de dados, então a pessoa interessada em adotar um animal da ONG muitas vezes não tem todo acesso as informações e aos documentos do animal. 


**Conclusão**

<p align="justify">Diante da visão anterior, é notório uma falta de segurança nos dados tanto dos animais quanto dos adotantes. A planilha como fonte de armanazemento de dados para uma ONG deste tamanho, não atende as todas as suas necessidades. E o modo como esses animais são divulgados somente pelas redes sociais, se vê uma perda de público e de interesse por meio de empressas para então poder realizar parcerias. A falta de investimento é um problema que pode ficar cada vez pior ao longo do tempo, se não a ONG não tiver ajuda de parcerias em breve.


#  Descrição da proposta

<p align="justify">Devido aos problemas citados acima, foi pensando em desenvolver um software em que o foco é gerenciar e promover a adoção de animais perdidos ou abandonados na rua.

<p align="justify">As donas da ONG, juntamente com as atendentes, terão acesso ao sistema de forma administradora. Poderá ser feito o cadastro de cada novo animal que chegar na ONG, e assim os dados dos animais ficarão salvos no sistema. Caso o animal for adotado, ele poderá ser excluído do sistema, porém ele ficará mantido na parte de Adotados. O sistema terá um status para o acompanhamento do animal pós adoção, assim, as atendentes terão acesso a essas informações se o animal está se adptando ao novo lar.

<p align="justify">Já os visitantes poderão acessar o site, visualizando os animais disponíveis para adoção, e caso se interessem, deveram realizar o login ou cadastro no site, para poder ter acesso as funcionalides do perfil de adotante. 

<p align="justify">O usuário poderá acessar o site fazendo ou não o login, e caso não tenha poderá se cadastrar. Então poderá visualizar as páginas disponivéis: a home, dos animais cadastrados, das informações da ONG, das minhas informações (conta), e da estática de animais adotados por mês. Caso o usuário se interesse por algum animal, ele deverá enivar toda a documentação necessária que o site requere. Se aprovado, o usuário poderá agendar a retirada do animal na ONG. Se reprovado, deverá esperar 1 dia para poder enviar a documentação novamente. 


#  Regras de Negócio
.<p align="justify"> **RN001:** Para registro de adotantes deverá preencher um cadastro seguindo os critérios claros de elegibilidade para adotantes de animais, tais como idade mínima, disponibilidade de tempo para cuidar do animal, espaço adequado para acomodar o animal, entre outros
.<p align="justify">   **RN002**:  Para realizar a adoção, o adotante deverá obrigatoriamente ser maior de idade (18 anos)
.<p align="justify">   **RN003**: No processo de adoção deverá estabelecer-se uma taxa de adoção para ajudar a cobrir os custos associados à adoção, como cuidados veterinários, alimentação e suprimentos. O valor da taxa será de 25 reais
.<p align="justify">   **RN004**:  Deve ser realizado um acompanhamento pós-adoção para garantir que o animal esteja sendo bem cuidado e para oferecer suporte adicional, se necessário. O acompanhamento ficará disponível no sistema por 20 dias
.<p align="justify">   **RN004**:  Em caso de devolução dos animais, a política de devolução deverá ser clara, quando em problemas de saúde ou comportamentais, ou de mudanças nas circunstâncias do adotante que impeçam a manutenção do animal
.<p align="justify">   **RN006**:  Para registro de animais para doação deve-se fornecer informações claras e precisas sobre os animais disponíveis para adoção. Dados necessários: idade, histórico de saúde, comportamento e necessidades especiais, sendo transparente em relação às suas políticas e procedimentos.

# Requisitos Funcionais 

<h2>Entradas:</h2>

- **RF001 - Registro de animais:** O sistema deve permitir o registro de dados sobre animais disponíveis para adoção. 
  - **Dados necessários:** tipo de animal (cão, gato, etc.), raça, idade, sexo, porte, histórico médico e comportamental.
  - **Usuários:** gerente e atendente. 
- **RF002 - Registro de adotante:** O sistema deve permitir o registro de informações sobre o adotante.
  - **Dados necessários:** Nome, RG e CPF, endereço, telefone, e-mail, idade, histórico de adoção de animais, comprovante de residência.
  - **Usuários:** Gerente e atendente.
- **RF003 - Requisitos do adotante:** O sistema deve permitir que os adotantes informem suas preferências de animal.
  -  **Dados necessários:** tipo de animal desejado, tamanho, idade, temperamento e outras informações relevantes.
  -  **Usuários:** Adotante
- **RF004 - Agendamento de visitas:** O sistema deve permitir que os adotantes agendem visitas para conhecer os animais em um determinado horário, e que o abrigo ou centro de adoção possa agendar visitas correspondentes.
  - **Dados necessários:** data e horário da visita agendada.
  - **Usuários:** Adotante, gerente e atendente.

<h2>Processamento:</h2> 

- **RF005 - Processo de solicitação de adoção:** O possível adotante preencherá um formulário para solicitar a adoção, e o sistema registrará essas informações. O adotante enviará as documentações necessárias e o gerente ou atendente verificará sua veracidade, permitindo que a solicitação da adoção seja autenticada.
  - **Dados necessários:** Nome, RG e CPF, endereço, telefone, e-mail, idade, histórico de adoção de animais, comprovante de residência

  - **Usuários:** Adotante, Gerente e atendente..

- **RF006 - Triagem do adotante:** O sistema deve permitir que o abrigo realize uma triagem do adotante, incluindo um questionário de adoção e uma entrevista, para garantir que ele esteja apto a adotar um animal e possua a capacidade de cuidar adequadamente do animal.
  - **Dados necessários:** Horário de trabalho; Declaração de renda; Comprovante de residência.
  - **Usuários:** Adotante, gerente e atendente.
   
- **RF007 - Avaliação do ambiente doméstico:** O sistema deve permitir que o abrigo avalie o ambiente doméstico do adotante para garantir que é um ambiente seguro e adequado para o animal.
  - **Dados necessários:** Características da moradia (tamanho do terreno, presença ou não de muros, e portões, etc.)
  - **Usuários:** Adotante, gerente e atendente.

<h2>Saída:</h2>

- **RF008 - Efetivação da adoção:** Caso o adotante cumpra com todos os requerimentos necessários para o processo da adoção (desde a solicitação até a avaliação do ambiente doméstico), o animal poderá ser retirado do abrigo, e o gerente ou atendente será responsável por retirar o animal do sistema.

  - **Dados necessários:** Status de adoção do animal (o animal só poderá ser retirado do sistema caso a adoção tiver sido aprovada)

  - **Usuários:** Gerente e atendente.

- **RF009 - Documento de adoção:** O sistema deve gerar um documento de adoção para o adotante.
  - **Dados necessários:** nome do animal, data de adoção, taxa de adoção.
  - **Usuários:** Gerente e atendente.
- **RF010 - Registro de adoção:** O sistema deve atualizar o registro do animal como adotado e retirá-lo da lista de animais disponíveis para adoção.
  - **Dados necessários:** Comprovante de adoção.
  - **Usuários:** Gerente e atendente.


- **RF011 - Informações de contato do adotante:** O sistema deve armazenar informações de contato do adotante para futuras atualizações e verificações de bem-estar do animal adotado.
  - **Dados necessários:** Telefone e email do adotante.
  - **Usuários:** Gerente e atendente.

- **Relatórios das adoções:** O sistema deve gerar relatórios contendo informações da quantidade de animais adotados por mês, e de animais que ainda não foram adotados.
  - **Dados necessários:** Quantidade de adoção por mês, quantidade de animais não adotados.
  - **Usuários:** Gerente e atendente.

# Requisitos Não Funcionais 

- **RFN001 - Segurança:** O sistema deve ser seguro e proteger as informações pessoais dos usuários e dos animais cadastrados. O acesso ao sistema deve ser restrito a usuários autorizados e as informações devem ser armazenadas de forma segura.

- **RFN002 - Escalabilidade:** O sistema deve ser capaz de lidar com um grande número de usuários e animais cadastrados. O sistema deve ser projetado de forma escalável para garantir que possa crescer e se adaptar ao aumento do tráfego.

- **RFN003 - Performance:** O sistema deve ser rápido e responsivo, permitindo que os usuários acessem e atualizem as informações com rapidez e eficiência.

- **RFN004 - Disponibilidade:** O sistema deve estar disponível e funcionando o tempo todo, com um tempo de inatividade mínimo para garantir que os usuários possam acessá-lo sempre que necessário.

- **RFN005:** Regulamentações aplicáveis, como a proteção de dados pessoais e os regulamentos de adoção de animais.

- **RFN006 - Banco de Dados:** O sistema será implementado com MySQL.

- **RFN007 - Desenvolvimento:** Os frameworks utilizados para o desenvolvimento do sistema serão VueJS, React Native para o FrotEnd e Django para backend.
