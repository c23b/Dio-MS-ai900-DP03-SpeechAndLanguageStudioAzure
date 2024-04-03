# Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure
Desafio de Projeto da DIO para bootcamp ai900 Azure AI Fundamentals - Speech Language Studio Azure e Language Studio Azure

- Dentro desse desafio é pedido apenas o passo a passo da documentação do Language Studio Azure, mas como extra vou exibir o passo a passo dentro do Speech Language Studio.
- Documentações
  - Language => [https://aka.ms/ai900-6-text-analysis](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
  - Speech => [https://aka.ms/ai900-speech](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)

# Language Studio Azure
## STEP 01
- Seguindo a documentação [https://aka.ms/ai900-6-text-analysis](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
- No partal do Azure: https://portal.azure.com/ 
- Crie um novo recurso, dependendo em qual tela estiver pode clicar em "**+ Create a resurce**" ou "**Create**".
![Screenshot 2024-04-01 203409](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/f92c4758-0308-4398-90cb-f68a3bea52ea)

- O recurso a ser criado será o "**Language Services**", pode pesquisar por esse nome na barra de pesquisa ou dentro da categori "**AI + Machine Learning**".
![Screenshot 2024-04-01 203425](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/4fcbb1e6-6b1e-419e-a832-f6fea4fff060)

- Clique em "**Continue to create your resource**"
![Screenshot 2024-04-01 203516](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/668d1a74-9cd4-45c5-bb66-12a4e8d85ffb)

- Preencha o "**Resource Group**", "**Name**", "**Pricing tier**" com o valor "**Free F0**" e por fim marque o checkbox. Agora Clique em "**Review + create**" e na tela final "**Create**".
- "**Lembre**": Criar os resources com a "**Region**" nos EUA consome menos créditos do Azure.
![Screenshot 2024-04-01 203730](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/ca449e5f-746a-4f3e-84c2-9cebc8b58f47)

- Aguarde o deploy do resource estar completo.
![Screenshot 2024-04-01 204040](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/7474da9b-18e8-404e-ae1f-b165772baf52)

## STEP 02
- Abra em uma nova aba do navegador o https://language.cognitive.azure.com .
- Verifique se ao abrir o link você ja esta logado, caso contrario faça login.
![Screenshot 2024-04-01 204118](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/7a909e46-eb26-4d55-912b-44b3d0f2cedc)

## STEP 03
- Após o login ira abrir um pop-up para selecionar o recurce criado no Portal do azure. Selecione todas das opções e clique em "**Done**".
- **NOTE:** O meu resource esta com nome diferente, isso aconteceu porque levou um tempo para o resource aparecer, o que me fez excluir e criar outro pensando que houve açgum erro,
mas era apenas uma questão de esperar, isso me custou "**Pricing tier**" com o valor "**Free F0**", apenas podemos criar uma vez nessa modalidade de preço.
![Screenshot 2024-04-01 205912](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/c40ef9e5-0c78-4bf5-b04d-42b1c6bbdf82)

## STEP 04
- Com o resource selecionado, clieque em "**Classify text**" e depois em "**Analyze sentiment and mine opinions**"
![Screenshot 2024-04-01 210015](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/1ad13ae8-3416-4489-b96e-159a80f444b0)
  
## STEP 05
- Dentro de "**Enter some text to try out**", selecione o idioma "**English**" caso não estiver selecionado, selecione o resource e dentro de "**Enter your own text, upload ...**" cole o texto presente na documentação.
```
 Tired hotel with poor service
 The Royal Hotel, London, United Kingdom
 5/6/2018
 This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.
```
- Deça na barra de rolagem, selecione o checkbox e clieque em "**Run**".
![Screenshot 2024-04-01 210225](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/8790638e-4753-41ee-83bd-8b31eebb9688)

## STEP 06
- O resultado ira ser exibido dentro da box na aba Result
![Screenshot 2024-04-01 210248](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/7b18dda2-6477-4df2-b208-57b0a1b9b6b2)

## Resultados
### Sentence 1
![Screenshot 2024-04-01 210328](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/77b849a0-b803-42f2-bd7b-64c932ed31af)


### Sentence 2
![Screenshot 2024-04-01 210345](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/cf0bdf8b-6ece-4f22-9cf1-477fd4a133ae)

### Sentence 3
![Screenshot 2024-04-01 210358](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/72adbc6c-e869-4f0b-80c9-c513aac1d726)

### Original text
![Screenshot 2024-04-01 210410](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/4c97b57d-36af-4428-8e27-e79bbc87c95f)

## Concluções
- Realmente tratando de uma avaliação de experiência, feedbacks de clientes e usuários ou circustância simelhante podemos ver que essa ferramenta de IA da Microsoft pode atender bem.
- Creio que em idiomas onde talvez não se tem domínio, essa ferramenta pode ajudar com as expressões idiomaticas entendendo melhor o sentimento expressado.


# Speech Studio Azure
## STEP 01
- Seguindo a documentação [https://aka.ms/ai900-speech](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html).
- Entre link do "**Speech Studio**" https://portal.vision.cognitive.azure.com .
- Verifique se ao abrir o link você ja esta logado, caso contrario faça login.
![Screenshot 2024-04-01 195917](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/adff5e84-5d33-4e83-995b-81d997b0b645)

## STEP 02
- Clique nas "**Configurações**".
![Screenshot 2024-04-01 195946](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/9a692604-3e0b-4941-98cd-a1cb0e5cc26a)

- Dentro de "**Todos os recursos**" clieque em "**Criar novo recurso**"
![Screenshot 2024-04-01 200016](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/1f2e79a8-29de-48c2-a2af-f2fd1e86ced3)

- - Preencha o "**Nome do novo recurso**", "**Assinatura**", "**Região**", "**Tipo de preço**" com o valor "**Padrão S0**" e selecione o "**Grupo de recursos**". Agora Clique em "**Criar um recurso**".
- "**Lembre**": Criar os resources com a "**Região**" nos EUA consome menos créditos do Azure.
![Screenshot 2024-04-01 201038](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/508b9711-6482-4619-81b3-fcac9c0bdc26)

- Com o recurso criado, selecione e clique em "**Usar o recurso**".
![Screenshot 2024-04-01 201139](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/615b709f-abdd-4508-853b-0262e6d85f0c)

## STEP 03
- Volte a tela inicial e dentro de "**Conversºao de fala em texto**", clique em "**Conversão de fala em texto em tempo real**"
![Screenshot 2024-04-01 201237](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/fe5a2829-951e-4acb-b7a8-f3adf55724ab)

## STEP 04
- Marque o checkbox escolha o idioma e insira um arquivo que contenha alguém falando ou cantando.
![Screenshot 2024-04-01 202132](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/f05b803a-23fa-4d48-9ec0-1c15dfda8eb0)

- Veja em "**Resultados de teste**", o testo sendo gerado segundo o audio inserido. No meu caso inseri uma audio de um curso de inglês sobre nacionalidades.
![Screenshot 2024-04-01 202253](https://github.com/c23b/Dio-MS-ai900-DP03-SpeechAndLanguageStudioAzure/assets/12342627/192e7419-f05a-4de0-a119-b631445b8a97)

