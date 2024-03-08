# dio-azure-text-and-speech
## Introdução
Este projeto apresenta o processo de análise de texto da plataforma do Azure.

## Pré-requisitos

 -Conta do Azure: Se você ainda não tem uma, crie uma conta gratuita no Portal do Azure.
 
 -Workspace do Azure Synapse Analytics: Configure um workspace do Azure Synapse Analytics com uma conta de armazenamento do Azure Data Lake Storage Gen2.

 -Pool do Spark: Crie um pool do Spark no workspace do Azure Synapse. Isso permitirá que executemos análises de texto.

 -Serviços de IA do Azure vinculados: Configure os serviços de IA do Azure no Azure Synapse. Isso inclui o serviço de Análise de Sentimento.

 
## Passo-a-passo

Na tela inicial, clique em criar um recurso.

<a href="https://ibb.co/yp2wFqq"><img src="https://i.ibb.co/vh974kk/Captura-de-tela-2024-03-08-192543.png" alt="Captura-de-tela-2024-03-08-192543" border="0"></a><br />
Em seguida, clique em IA + Machine Learning, e depois em Análise de Texto, clique em criar.

<a href="https://ibb.co/7phV61D"><img src="https://i.ibb.co/PWk4f6y/Captura-de-tela-2024-03-08-192616.png" alt="Captura-de-tela-2024-03-08-192616" border="0"></a><br />

Após a criação do recurso, abra uma nova guia e digite a seguinte url: https://language.cognitive.azure.com, onde você encontrará a página incial do portal Language Studio.

<a href="https://ibb.co/HpjbJkx"><img src="https://i.ibb.co/bRkCf82/Captura-de-tela-2024-03-08-193058.png" alt="Captura-de-tela-2024-03-08-193058" border="0"></a><br />

Na pagina inicial, clique em "Analyze sentiment an mine opinions". Abrindo uma nova página, selecione uma idioma, e o recurso que será utilizado. Em seguida, carregue o arquivo que será analisado, marque a caxa acima do botão e clique em "Run".

<a href="https://ibb.co/LtHQtY7"><img src="https://i.ibb.co/7WLgWjm/Captura-de-tela-2024-03-08-193450.png" alt="Captura-de-tela-2024-03-08-193450" border="0"></a>

Com isso, os resultado serão exibidos após alguns segundos, onde serão exibidos tanto o texto original, como o mesmo divido em três sentenças, com os resultados da análise individual de cada uma das mesmas.

<a href="https://ibb.co/WgJvmZW"><img src="https://i.ibb.co/wMmh5VN/Captura-de-tela-2024-03-08-191402.png" alt="Captura-de-tela-2024-03-08-191402" border="0"></a>

<a href="https://ibb.co/r4gwD5b"><img src="https://i.ibb.co/J5NsDrx/Captura-de-tela-2024-03-08-191409.png" alt="Captura-de-tela-2024-03-08-191409" border="0"></a>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/MDNdngY/Captura-de-tela-2024-03-08-191425.png" alt="Captura-de-tela-2024-03-08-191425" border="0"></a>

