# DIO-AI-SearchIndexUI
Atividade: Descreva o passo a passo para se configurar uma pesquisa, assim como seus insights, possibilidades de ferramentas que se beneficiam com esse tipo de ferramenta e aprendizados adquiridos durante o processo.

Passo a passo para configurar uma pesquisa:

1. Criar um serviço de "Azure AI Search"
2. Criar um serviço de "Azure AI Services"
3. Criar uma Storage Account pública
4. Faz o upload das reviews para a Storage Account
5. Faz o link da storage account com o Azure AI Search parametrizando a pesquisa conforme tutorial.
6. A final, o Wizard cria um Data source, skillset, index e indexer.
7. O indexer roda automaticamente and roda a indexação do pipeline que:
a. extrai o os campos de metadata do documento e seu conteúdo da origem dos dados.
b. Roda a função cognitiva em cima do skillset e gera campos mais enriquecidos.
c. Mapeia os campos extraídos para o index.

Este serviço de IA do azure pode ser utilizado para muitas coisas, exemplo coletar placa de carros que estão passando por determinado local, tendo as imagens capturadas por uma câmera.