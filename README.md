# Redundância de Arquivos no Azure

Este repositório contém materiais de apoio em PDF e PowerPoint sobre estratégias de redundância de arquivos utilizando **Azure Data Lake Storage Gen2** e **Azure Data Factory**, incluindo detalhes técnicos, boas práticas e cenários de aplicação.

## 📂 Arquivos

- `Redundancia_Azure_DataLake_Atualizado.pdf` – Documento com explicações, capturas de tela e cenários técnicos.
- `Redundancia_Azure_DataLake_Atualizado.pptx` – Apresentação em slides com os principais pontos abordados.

## 📸 Capturas de Tela

### Configuração de Redundância no Data Lake
![Configuração de Redundância](imagens/configuracao_redundancia.png)

### Habilitação do Namespace Hierárquico
![Habilitação do Namespace Hierárquico](imagens/habilitacao_namespace.png)

### Pipeline com Cópia de Dados no ADF
![Atividade de Cópia de Dados](imagens/atividade_copia_dados.png)

### Monitoramento de Pipelines
![Monitoramento de Pipelines](imagens/monitoramento_pipelines.png)

## 📘 Cenários Técnicos Abordados

- Redundância Local (LRS) para ambientes de desenvolvimento.
- Redundância Geográfica (GRS/RA-GRS) para ambientes críticos.
- Pipelines resilientes com políticas de retentativa e alertas.
- Integração com CI/CD utilizando Azure DevOps.

## 🔧 Tecnologias Utilizadas

- Azure Data Lake Storage Gen2
- Azure Data Factory (ADF)
- Azure Portal
- Azure DevOps (CI/CD)

---

