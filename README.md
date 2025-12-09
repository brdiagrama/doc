# Documentação do Projeto

Bem-vindo ao repositório de documentação! Este espaço foi criado para centralizar toda a documentação técnica e conceitual do projeto, incluindo diagramas, especificações e manuais.

## Sobre Este Repositório

A ideia aqui é manter tudo organizado em um único lugar. Chega de procurar aquele diagrama que estava "em algum lugar do drive" ou a especificação que ficou perdida no email de alguém. Aqui você vai encontrar:

- **Diagramas UML**: casos de uso, diagramas de classe, sequência e tudo mais
- **Especificações**: documentos técnicos detalhados sobre funcionalidades e requisitos
- **Manuais**: guias de uso, instalação e configuração

## Estrutura do Repositório

```
doc/
├── docs/
│   ├── diagrams/           # Diagramas UML (casos de uso, classes, etc.)
│   ├── especificacoes/     # Documentos de especificação (.docx, .pdf)
│   └── manuais/            # Manuais de usuário e técnicos
└── README.md               # Este arquivo
```

## Como Usar

### Navegando pela Documentação

Cada pasta tem um propósito específico:

- **`docs/diagrams/`** - Coloque aqui os arquivos de diagramas. Formatos aceitos: `.png`, `.jpg`, `.drawio`, `.puml`, `.svg`
- **`docs/especificacoes/`** - Documentos de especificação técnica, requisitos, casos de uso detalhados
- **`docs/manuais/`** - Guias e manuais para usuários finais ou desenvolvedores

### Adicionando Novos Documentos

1. Clone o repositório:
   ```bash
   git clone https://github.com/brdiagrama/doc.git
   ```

2. Adicione seus arquivos na pasta apropriada

3. Commit e push:
   ```bash
   git add .
   git commit -m "Adiciona [descrição do documento]"
   git push
   ```

### Convenções de Nomenclatura

Para manter tudo organizado, siga estas convenções ao nomear arquivos:

- Use letras minúsculas
- Substitua espaços por hífens (`-`)
- Seja descritivo mas conciso
- Inclua versão quando necessário

Exemplos:
- ✅ `diagrama-caso-uso-v1.png`
- ✅ `especificacao-requisitos-funcionais.docx`
- ✅ `manual-instalacao-sistema.pdf`
- ❌ `Diagrama 1.png`
- ❌ `doc final FINAL (2).docx`

## Tipos de Diagramas

### Diagramas de Caso de Uso
Mostram as interações entre usuários (atores) e o sistema. Úteis para entender as funcionalidades do ponto de vista do usuário.

### Diagramas de Classe
Representam a estrutura estática do sistema, mostrando classes, atributos, métodos e relacionamentos.

### Outros Diagramas
Conforme necessário, podemos incluir diagramas de sequência, atividades, estados, entre outros.

## Versionamento

Este repositório segue princípios básicos de versionamento:

- Documentos em evolução devem ter indicação de versão no nome ou em uma seção do documento
- Mantenha um histórico claro através de commits descritivos
- Para mudanças maiores, considere criar uma branch e depois fazer merge

## Contribuindo

Todos os membros da equipe podem contribuir com a documentação:

1. Mantenha os documentos atualizados conforme o projeto evolui
2. Revise periodicamente para garantir que nada está obsoleto
3. Use linguagem clara e objetiva
4. Inclua exemplos quando apropriado

## Ferramentas Recomendadas

Para editar e visualizar diferentes tipos de documentos:

- **Diagramas UML**: Draw.io, Lucidchart, PlantUML, StarUML
- **Documentos**: Microsoft Word, LibreOffice, Google Docs
- **Visualização de diagramas**: Qualquer navegador para arquivos `.png`, `.jpg`, `.svg`
- **Draw.io**: Para arquivos `.drawio`, use [app.diagrams.net](https://app.diagrams.net/)

## Dúvidas?

Se tiver alguma dúvida sobre onde colocar um documento ou como organizar algo, abra uma issue neste repositório ou entre em contato com a equipe.

---

*Última atualização: Dezembro 2025*