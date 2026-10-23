1. Desativar a detecção automática de dados pessoais
Na sua imagem, a opção “Detectar automaticamente dados enviados pelo usuário” está marcada, incluindo:
- E-mail
- Número de telefone
- Nome e endereço
Isso permite que a tag procure essas informações na página para recursos de medição.

Como estamos configurando o site de uma clínica odontológica, recomendo desativar essa detecção automática. Ela não é necessária para medir os cliques no WhatsApp e pode envolver dados pessoais de pacientes.

Faça o seguinte:
1. Desmarque Detectar automaticamente dados enviados pelo usuário (a caixa azul principal).
2. Mantenha Especificar seletores de CSS ou variáveis JavaScript desmarcado.
3. Não adicione nenhum snippet com user_data.



Se eu quiser habilitar novamente a opção **Detectar automaticamente dados enviados pelo usuário (email, telefone, nome e endereço)**  e Permitir recursos de dados fornecidos pelo usuário como faço?

Sim. Você pode reativar essas duas opções a qualquer momento pelo Google Tag Manager, inclusive depois de publicar a configuração atual.

## Como reativar

1. Acesse [Google Tag Manager](https://tagmanager.google.com/?utm_source=chatgpt.com).
2. Abra o contêiner `GTM-5LVJ9357`.
3. No menu lateral, entre em Configurações e procure Permitir recursos de dados fornecidos pelo usuário.
4. Abra essa configuração e clique no ícone de edição, se necessário.
5. Ative Permitir recursos de dados fornecidos pelo usuário.
6. Marque Detectar automaticamente dados enviados pelo usuário.
7. Selecione os tipos de dados que deseja detectar: E-mail, Número de telefone e Nome e endereço.
8. Clique em Salvar.

Se a opção não aparecer em Configurações, procure a seção Tags do Google, abra a tag correspondente e acesse suas configurações.&#x20;

Depois, no GTM, clique em Visualizar para testar e em Enviar → Publicar para disponibilizar as alterações no site. Será criada uma nova versão do contêiner.

## Atenção para a clínica odontológica

Esses recursos são utilizados principalmente para melhorar a atribuição de conversões usando informações fornecidas pelos visitantes, que podem ser enviadas com hash ao Google.&#x20;

Porém, dados com hash ainda exigem cuidados de privacidade, especialmente no contexto de saúde. Antes de reativar a detecção automática, recomendo verificar a finalidade da coleta, as permissões dos visitantes, a LGPD e as políticas do Google.&#x20;


Para o rastreamento atual da Parnaso Ateliê Oral — visualizações de página e cliques no WhatsApp — essas opções não são necessárias.

Portanto, você pode mantê-las desativadas agora e reativá-las futuramente, sem precisar refazer a configuração do Google Ads ou do GA4.

