# redhat-3scale
3scale
Formas de criar apis

![image](https://github.com/tjca1/redhat-3scale/assets/28515964/2c362f96-e786-4534-b640-387707a40fc4)
Vamos pelo portal adm
Fluxo api:
 
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/543df24b-7749-4a06-8a96-6042e4fb2cd9)

Criando back-end:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/5516a73e-778b-4c42-a629-ca6c9c06e83d)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/e52f2d46-a8df-4244-824c-dcb540c048c3)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/0f459442-ffac-4a12-bedd-4c7c1a02069f)
->voltar para dashborard
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/8c65d587-bc3c-4136-9c55-d25c78b58ee3)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/290495ad-7903-46b0-b228-eac9bbe5ad3f)
Vamos criar um produto para o nosso back-end(demo-integarion-backend-name)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/33f5755f-044b-4e11-87b0-067303438a66)
O produto é quem dita as regras de acesso para o back-end
Poriamos configurar no produto uma série de regras para a nossa api, começando no produto acessar nossa api back-end conforme a imagem:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/db4cb388-1819-454d-afe4-9da9d8d0431b)
Criando um produto para fazer isso:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/4e682fe1-232a-4f74-8279-5bf8e7c89c5d)
Com o produto podemos configurar várias regras confome abaixo:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/b7cc58c5-9e12-4bfe-af45-6280481fbd76)
Preciso ter uma conta apartir da conta ligo com o aplication e o aplication liga a um aplication plan, poderiamos ter varias contas consumindo um aplication como uma conf defalut
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/792780fb-71fc-4939-897a-0ff743a82eb5)
Pratica:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/f3293f11-3cd6-47ce-86d4-0c2413cfd731)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/35f9de21-cbbc-4bef-8d17-a1fbf5a0cd83)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/3d64d75b-a9e2-47bd-9bad-04389707564f)
Criando o account ou conta:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/08ff33f6-cb12-425f-ba71-9f94e63942e2)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/15c13018-ec23-498a-99d7-7d26cd7fd081)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/97a3ea87-2d0a-4b27-b72a-e6893d3008df)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/be6f7e31-baa5-4fb5-9b9a-751b1c2bcd0f)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/bdc3cc1d-da6a-4353-b821-7a93aac65544)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/96646881-44b1-4fb3-b6f9-c5504b6fa2ed)
Criei 2 usuarios thiago1 e thiago2 ligado ao group organization demo-integarion-organization-group
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/e961de29-1bf5-4253-a04e-a3b870d1c683)
Acessar o produto:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/fe0de025-10af-497f-bc0d-66dac5da23fc)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/69629dce-ac4d-49bc-b80a-a0ee7b7f17fa)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/356d459e-4f88-44d2-8037-31c0ecd00e53)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/5904aa5d-6332-406a-a4eb-2dd37cc10e2b)
Criar aplication:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/6e98baa1-141d-4fb6-9333-db70ed0e980d)
Olha so as 2 contas que criei thiago e thiago2 da ornanização demo-integarion-organization-group
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/abd0c721-d020-4de2-a248-91a82c97012a)
Olha so o aplication-plan que criamos para o vinculo:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/4a92ea8f-12a6-49f1-a911-78ea9bef6f22)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/c6aaf181-ac5d-4c92-ac05-0552a2b5381a)
Criamos nosso aplication e user-key na hora de consumir a api do 3scale vamos entender melhor essa chave: 
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/4fec7d2b-042b-4cd9-a82b-ea17f9e1d821)
Associar nosso product com o back-end:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/39bbdd31-b3a4-4fce-86ca-9a5b6487f85b)
Click em produtos globais ”products” no combo no cabeçalho da página:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/3bc0b4e6-f72b-4629-8775-58d9e339e1f1)
Click no produto que criamos:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/8ff9b6e3-9295-4642-a4fd-f1d3b6d0c7b8)
Vai aparecer o menu click em backend:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/04abfe5b-83db-424b-844d-5499a8c393bf)
Add backend:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/fea06348-8a4e-42ca-b054-cd2d156c6bdf)
Selecionar o backend criado para esse tutorial:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/acd61d98-1c8d-4b34-8712-84416e8c183a)
Uma coisa importante que me perdi no inicio, repare que a estamos dentro do produto que qremos associar, selecionei em verde !
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/0469a380-00b4-42af-9a16-14f50f7e552e)
Backend associado ao nosso produto, devidamente configurado
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/0ea2dbdc-7b4a-47b4-b7d0-e839a6adbffe)
Api response do backend sem passar pelo 3scale sem nenhum tipo de segurança, metrica ou controle de acesso:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/74b24f3e-bb65-4683-ae21-70d6fbfb81ba)
No mesmo menu vamos olha o item Mapping Rules so pra saber que com essa conf o 3scale so aceita metodo get não importa o verbo do backend podemos acrescentar isso, mas vamos deixar assim por enquanto.
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/2e5daea6-6d92-485d-a508-53c78429e0b5)
Usando o back-end : http://economia.awesomeapi.com.br/ “308 Permanent Redirect” não me aprodfundei na correção, e optei em usar outro api back-end para adicionar a camada 3scale e suas diversas funcionalidades fui em edit/backend/demo-integarion-backend-name e troquei o back-end para:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/07a8acf1-090d-44dc-a7e1-c2d48a00a623)
Um get simples da nosso novo api backend
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/3033ad56-0fc6-417a-909b-3497783fb963)

Como mostrei a cima mudei meu backend para https://homolog.biometria.sp.gov.br/
Agora precisamos configurar nosso patch “/api/imagem/version” no Mapping Rules do project para acessar a api 

![image](https://github.com/tjca1/redhat-3scale/assets/28515964/2583db87-7b4d-43bf-92fd-8178a3dd393d)

Não esquecer de aprovar no configuration....
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/4fc95d51-eb33-4c35-a229-26c20ea8a20f)
Consumindo o backend direto sem nenhum tipo de segurança....
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/8ea66faa-ac5b-4811-a595-715e51e81064)
Consumindo com acamada 3scale passando user-key padrão de segurança default para apis no 3scale, vale lembrar que no item policies do product podemos aplicar diversas verificações de segurança como RH-SSO/Keycloak Role Check / CORS Request Handling / OAuth 2.0  etc...
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/6130634c-3cef-4ae8-8285-a91777a22fdb)
Configurando nossa api com autenticação Red Hat SSO:
Logando selecione item cliente:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/67d72f38-25ea-4680-acb5-95b67d64b182)
Clique no link 3scale-admin para ver os detalhes.
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/a71131da-caaf-4921-9ed3-731a7efbf92a)
Na aba Credentials
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/60b7403a-769e-45dd-a471-63e613a7fb99)
Clique na guia settings do cliente 3scale-Admin e certifique que o Service Accounts Enabled esteja habilitado:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/e9ecb5ef-0b3c-4a82-a159-100337bc4f60)
Em Client Roles , digite realm-management . Selecione todas as funções disponíveis e clique em Add Selected para ir para a caixa de texto Assigned Roles. Ignore se as funções já estiverem na caixa de texto Funções atribuídas
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/ed1621a2-3e4f-4848-928d-9ab073002337)
No menu principal click em user:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/fa6451a2-f639-4f54-b9cd-12edd54e153b)
E add user:
Userneme:apiuser e save:

![image](https://github.com/tjca1/redhat-3scale/assets/28515964/60ad991a-0c2f-4d38-9db3-2e03e68f342f)
Clique na guia Credenciais para redefinir a senha. Digite apipassword como Nova senha e Confirmação de senha . Desligue o Temporário para evitar a redefinição de senha no próximo login.
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/e1076862-c6d7-418a-9e80-347b45c1e9fb)
Configurar integração 3scale:
Faça login no [3scale Admin](https://user3-admin.apps.cluster-gjglv.gjglv.sandbox1741.opentlc.com/p/login) web console usando ***** uma senha: ******
Na lista de produtos click em ... e click em integration:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/af29c691-b475-46a1-8a70-e11ab98642ae)
Clique em Settings para editar as configurações de API para o gateway e selecione a opeção Use OpenID Connect for any OAuth 2.0 flow.
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/fce359c1-50ae-414f-a453-2ecc3ee5d092)
Defina os seguintes valores para Configurações de autenticação :
•	Tipo de emissor do OpenID Connect:Red Hat Single Sign-On
•	Emissor do OpenID Connect:https://hostrhsso/auth/realms/user3-realm
Obs: o OpenID Connect vai depender vai depender de onde estar hospedado seu keycloac
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/99bbdd38-954d-46f1-bda3-62a803b2090c)
Em CREDENTIALS LOCATION selecione:
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/9e8f23b2-f70d-4847-bdd1-430ca4b934e7)
Em configuration aprove stage/production
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/974fd925-11b2-4d3c-abed-7dafcb9a400c)
No 3scale...
Criar um aplicativo de teste
Vá para o menu suspenso Público e clique em Desenvolvedores.
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/d0e3861c-77bd-4b99-a9e7-17380d0f50a7)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/d22878e8-94c1-4156-bb51-7e1cb25aebf4)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/c2396294-a471-4511-8439-6d260274f2ee)
So uma obs, no meu caso vou criar para usuário thiago e não Develop.
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/392b1aee-5c5d-4048-a19c-ce5f3eac720d)
Caso tenha duvida sobre a url, é aquela que se encontra na topologia do openShift
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/17544216-d604-49f0-9991-14e865d71ba7)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/14a871c7-7f7d-4cfd-ba9f-f8355b0d3dc0)
NOTA: Se o ID e o segredo do cliente não forem vistos, navegue até a página do aplicativo novamente e você verá o segredo gerado .
Edite o URL de redirecionamento e insira o valorhttp://www-user3.apps.cluster-gjglv.gjglv.sandbox1741.opentlc.com/
Anote o Client ID e o Client Secret , que são necessários posteriormente para testar sua integração.
Navegue de volta ao portal SSO e clique na lista de clientes . Você deve ver o novo cliente com o mesmo id do cliente em 3scale criado no SSO.
//
Na seção Recurso, clique no link Console do OpenShift .
Autentique usando seu usuário e senha.
Navegue até a página de visão geral do seu projeto. Ele será chamado user3.
Clique na exibição Topologia .
Clique no ícone do pod para abrir as informações de implantação.
Na parte superior, clique no nome da implantação, www
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/5251767e-6b59-4e31-85b3-b79480d4fffb)
Com a página de configuração de implantação aberta, clique em ambiente
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/4951ff16-cfea-4a54-a0b4-97163843a585)
Click em Environment
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/144472c2-a6a1-4a78-ae7b-57d90e66f713)
Digite o clientId que geramos no rh-sso
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/556d8d24-5570-4fbf-9620-022b6e7a688f)
Depois de copiar o client_id , volte para a guia de configuração de implantação.
Atualize o valor CLIENT_ID e clique no botão Salvar .
Isso acionará uma nova implantação de aplicativo, agora em execução com a configuração correta.
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/52c7418a-025a-49b8-9f09-0b4be533b42e)
Atualizar SSO no retorno de chamada do aplicativo
URLs de redirecionamento são uma parte crítica do fluxo OAuth. Depois que um usuário 
autorizar um aplicativo com sucesso, o servidor de autorização redirecionará 
o usuário de volta ao aplicativo com um código de autorização ou token de acesso na URL. 
Como o URL de redirecionamento conterá informações confidenciais, é fundamental que 
o serviço não redirecione o usuário para locais arbitrários.
Navegue até Administrador SSO
Faça login no Red Hat Single Sign On usando suas credenciais. Clique em Entrar .
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/97385ddb-311e-42d5-9a35-0955f8b5974a)
Role para baixo, digite e selecione as seguintes opções na configuração do aplicativo:

![image](https://github.com/tjca1/redhat-3scale/assets/28515964/01341d90-520d-4cd6-83bf-0bb26b31cac7)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/385e9176-a95a-4448-a800-c3f7d2fff871)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/210f0385-4362-4a0d-98e4-680b65ccd708)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/8b3e6e2f-c892-455d-a596-a967d9f5b4f7)
![image](https://github.com/tjca1/redhat-3scale/assets/28515964/2c84727b-38bb-4791-a1d9-ad504027b679)
