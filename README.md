# PDV - Fontes em PDF

Repositório de PDFs com fontes e documentação do projeto de PDV em AdvPL/TLPP.

## Organização

Os documentos ficam em `PADRAO/`, agrupados por assunto:

| Pasta | Conteúdo |
| --- | --- |
| `PADRAO/Registra Produtos/` | `PDV_Fontes_10.pdf` - rotina de registro de produtos |
| `PADRAO/A Classificar/` | PDFs cujo assunto ainda precisa ser confirmado pelo conteúdo |

Os demais arquivos numerados não foram classificados porque seus títulos e conteúdos não puderam ser extraídos nesta etapa. Evite inferir o assunto apenas pelo número.

## Organizar os PDFs

No PowerShell, na raiz do repositório, execute:

```powershell
.\organizar-pdfs.ps1
```

O script move os PDFs que ainda estiverem diretamente em `PADRAO/`, sem sobrescrever arquivos existentes. Quando o assunto de um documento for identificado, mova-o de `A Classificar/` para uma pasta com o nome do assunto e atualize esta tabela.