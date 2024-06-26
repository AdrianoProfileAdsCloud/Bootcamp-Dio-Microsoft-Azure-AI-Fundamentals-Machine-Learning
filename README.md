# Microsoft Azure AI Fundamentals - Machine Learning na Prática no Azure ML.

Projeto proposto pela Dio para um aprendizado mais prático, saindo um pouco da teoria, mas, ao mesmo tempo, levando a mesma em todas as etapas. Já que para realizar o projeto é necessário navegar no Portal Azure; explorando outras possibilidades e recursos do portal. Ampliando os conhecimentos adquiridos nas aulas; vendo e fazendo na prática os recursos do Portal Azure para IA, melhorando a fixação dos conteúdos ministrados no bootcamp. O projeto em si é simples, mas através dele foi possível navegar pelo Portal Azure e conhecer o Azure Machine Learning Studio.

Este projeto foi realizado com base nas aulas ministradas e na documentação da Microsoft.

  Este projeto foi realizado com base nas aulas ministradas e a documentaçãodo Microsoft Learn(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

Primeiro passo criar um Workspace no Azure Machine Learning Studio.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/adc3e27b-4f5e-46fa-8c60-e8fe4b192aba)

Com o Workspace criado, clicando no mesmo temos todos os recursos exixtentes do workspace a esquerda.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/5bd370b7-966d-4df4-85c9-1e86c08aee03)

Clicar no menu esquerda já dentro do workspace em <b>ML automatizado</b>

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/434715ef-b846-4c4c-be65-eae5956a7628)

Na tela seguinte, clinado no botão <b> Novo Trabalho de ML automatizado</b>.Teremos algumas propriedades a serem preenchidas também lembrando de acordo com o exemplo na documentação.Para este exemplo as opções marcadas a seguir são o sufucientes.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/10a33a24-8eb3-4377-a704-8c57dc52ea8a)

Clique no botão avançar para seguir com as configurações.De acordo com o exemplo da documentação.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/426b332f-b1bf-4476-848f-6af6b6ceb47f)

Escolher fonte de dados como  <b>De Arquivos da Web</br>.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/4a3e9de6-ea81-4b23-9dad-ac3f343f75c5)

Indicar o endereço da fonte de dados.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/ffea2478-1cc6-442d-81b3-bbdf618a49b5)

Clique em avançar

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/b3c10171-b482-4e45-84b7-050c7a3736a0)

 Confere em clique em avançar:

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/e06cbbf1-6162-4b6f-8c9d-18d725fb2408)

Examamine caso hja necessidade de alteração em seguida clique em criar.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/57690627-6d16-4fc1-9d66-2c25843952cc)

Se tudo foi configurado como devido terá a tela a seguir que indica o status de criação de uma tarefa.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/1f52cbbc-daff-4881-992d-ab95a852c39d)

Selecione a tarefa para dar continuidade das configurações.Em seguida clique em avançar.
Na tela seguinte seguir estas configurações:

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/a78cb05b-4152-497d-a844-7189c91c0a16)

Salve esta etapa e continue as configurações ainda neste tela.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/160b636c-7f98-4b60-a0f7-663c2ada4234)

Configuração de como será processada a níel de hardware(cloud).O processo de criação então inicia, esta etapa pode demorar um pouco.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/f60099d5-328b-42c4-b7e0-1c6ee10f443a)

Em  clicando em <b>Tarefas(Jobs)</b> localizado a esquerda em segida localizamos o nome do experimento e selecionamos.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/06321ee6-f90c-43f1-ac4e-6cbffef221b9)

Clicando no nome do experimento selecionado iremos para esta outra etapa.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/16c2a541-85bf-417c-9198-fd84d3f64ca4)

Clicando no nome de exibião do experimento somos levado a tela seuinte onde temos uma visão geral sobre o modelo.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/7a5c63e2-7c64-4634-a624-dce14693252c)

Entre algumas informações que são apresentadas,a informção <b>Melhor Resumo</b> é a que nos interessa para no momento.Pois traz o <b>Nome do algoritmo</b> que representa o melhor modelo para uso da fonte https://aka.ms/bike-rentals (Documetação)

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/d757aa32-2d2c-4c53-a3a7-334a15b57241)

Ao clicar no <b>Nome do algoritmo</b> somos levados para outra tela na qual faremos a <b>Implantação</b>.
Nesta tela temos outros recursos referente ao modelo que será implantado como as <b>Metricas</b>, <b>Visão Geral</b> entre outras Informaçõed importantes.
 Para comerçarmos a implatação basta clicar eno botão <b>Implantar</b>

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/58bd5c91-7391-4cf9-8598-43f009f5f75c)

Este é o ponto onde passaremos algumas instruções importantes como o <b> O tipo de Computação<b> que será usada e o nome.
Lembrando essas informçãoesseguem a documentação(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/43e63698-ef94-4cbc-bc5a-8b28101382e6)

Após preencher conforme a documentação e clicar no botão implantar, levará alguns minutos e carregará a tela a seguir indicando o status da implantação.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/539e4f88-3bab-4457-b27a-0643c34c0dd0)


Ao selecionar <b>Ponto de extremidade</b> no menu lateral a esquerda. Será exibido o ponto de extremidade criado.

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/2a357408-8b7a-47dc-8f3e-637a8f9fb465)

Clicando no ponto de extremidade selecionado,somos levados a outra tela com algumas abas informativas como Logs etc.É nesta tela que será possível testar, clicando na aba <b>Testar</b>

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/802ede5f-342b-4b93-92cb-b961e92b1716)

![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/b383684c-49a6-4414-bc5e-28efc5b1c408)

Para validar clicar na guia <b>Testar</b> e alterar os valores de acordo com a necssidade:
![image](https://github.com/AdrianoProfileAdsCloud/AI-900/assets/141897391/ddde7ca1-2f16-4aff-a379-62ce4bac8ffe)



























