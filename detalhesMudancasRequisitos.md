
# Funcionalidades do Lume - Histórico de Mudanças

## Novas Funcionalidades Adicionadas

| Código   | Nome                        | Descrição                                                                 | Prioridade    |
|----------|-----------------------------|---------------------------------------------------------------------------|--------------|
| RF-05    | Busca por Palavra-Chave     | Implementar busca por título, produtor, gênero ou tags das obras. | Alta         |
| RF-09    | Seguir Produtores           | Permitir que usuários sigam produtores para receber atualizações de novas obras. | Média        |
| RF-10    | Sistema de Notificações     | Notificar usuários sobre novas obras de produtores seguidos e interações em seus conteúdos. | Baixa        |
| RF-15    | Gerenciar Produções Próprias| Permitir que produtores editem ou excluam suas próprias obras publicadas. | Alta |
| RF-19    | Buscar Produtores por Localização | Permitir busca por produtores próximos baseada na localização do usuário. | Baixa |
| RF-22    | Buscar Festivais | Permitir busca por festivais de cinema independente na plataforma. | Baixa |
| RF-23    | Visualizar Detalhes de Festival | Permitir visualização de informações detalhadas sobre festivais divulgados. | Baixa |
| RF-14    | Curtir Comentários | Permitir que usuários curtam comentários de outros usuários nas produções. | Média |

### Requisitos Não-Funcionais Adicionados

| Código   | Nome                        | Descrição                                                                 | Classificação |
|----------|-----------------------------|---------------------------------------------------------------------------|--------------|
| RNF-04   | Desempenho                  | O tempo de carregamento das páginas principais não deve exceder 10 segundos em uma conexão padrão. | Obrigatório  |
| RNF-05   | Privacidade de Dados (LGPD) | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados, garantindo o tratamento transparente e seguro dos dados. | Obrigatório  |
| RNF-06   | Backup e Recuperação        | Devem existir rotinas de backup automático para garantir a recuperação de dados em caso de falha crítica. | Obrigatório  |
| RNF-07   | Escalabilidade              | A arquitetura deve permitir crescimento modular sem reescrever a base do sistema. | Desejável    |
| RNF-09   | Disponibilidade             | A plataforma deve visar uma disponibilidade de 99.5% do tempo.            | Desejável    |

---

## Funcionalidades Reorganizadas e Alteradas

### 01 - Cadastrar-se

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-01  | Cadastrar-se | Permitir que o visitante se cadastre como consumidor ou produtor. | Alta |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-01  | Cadastrar-se | Permitir que visitantes se cadastrem como consumidor ou produtor na plataforma. | Alta |

### 02 - Autenticar-se

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-02  | Autenticar-se | Permitir que usuários possam fazer login no sistema. | Alta |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-02  | Autenticar-se | Permitir que usuários façam login e logout no sistema de forma segura. | Alta |

### 03 - Editar Perfil

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-03  | Editar Perfil | Permitir que o usuário possa editar suas informações no perfil. | Média |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-09  | Editar Perfil | Permitir que usuários editem informações do perfil (nome, bio, foto, localização). | Média |

### 04 - Visualizar Detalhes de Produção

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-04  | Visualizar Detalhes de produção | Visitantes e usuários podem acessar detalhes sobre as obras publicadas. | Alta |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-04  | Visualizar Detalhes de Produção | Permitir que visitantes e usuários acessem informações detalhadas das obras publicadas. | Alta |

### 05 - Filtrar e Ordenar Produções

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-06  | Filtrar e Ordenar Produções | Permitir que o usuário possa filtrar as obras por múltiplos critérios (gênero, região, data de publicação) e ordená-las (mais recentes, mais bem avaliadas). | Baixa |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-13  | Filtrar e Ordenar Produções | Permitir filtros por gênero, região, data e ordenação por relevância, data ou avaliação. | Média |

### 06 - Acessar Link de Produção

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-07  | Acessar Link de Produção | Permitir o acesso ao link da produção quando disponibilizado pelo produtor. | Média |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-11  | Acessar Link de Produção | Permitir acesso direto ao conteúdo da obra quando disponibilizado pelo produtor. | Média |

### 07 - Comentar e Avaliar Produções

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-08  | Comentar e/ou Avaliar Produções | Usuários cadastrados podem comentar e/ou avaliar produções publicadas. | Alta |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-07  | Comentar e Avaliar Produções | Permitir que usuários cadastrados comentem e avaliem obras com nota e texto. | Alta |

### 08 - Publicar Produção

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-14  | Publicar Produção | Permitir que o produtor publique obras através de um formulário detalhado (título, sinopse, ficha técnica, tags, capa, link, etc.). | Alta |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-03  | Publicar Produção | Permitir que produtores publiquem obras com formulário completo (título, sinopse, ficha técnica, tags, capa, link). | Alta |

### 09 - Visualizar Métricas

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-16  | Visualização de Métricas | Permitir ao produtor visualizar métricas de suas publicações. | Média |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-12  | Visualizar Métricas de Produção | Permitir que produtores visualizem estatísticas de engajamento de suas obras. | Média |

### 10 - Visualizar Perfil de Usuário

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-12  | Visualizar Perfil de Usuário | Permitir a visualização de um perfil público de outros usuários. | Baixa |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-10  | Visualizar Perfil de Usuário | Permitir visualização de perfis públicos de outros usuários e produtores. | Média |

### 11 - Gerenciar Cadastros de Produtores

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-17  | Gerenciar Cadastro de Produtores | Permitir ao moderador autorizar, ou não, o cadastro de produtores. | Alta |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-08  | Gerenciar Cadastros de Produtores | Permitir que moderadores aprovem ou rejeitem solicitações de cadastro como produtor. | Alta |

### 12 - Moderar Obras

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-18  | Gerenciar Obras | Permitir ao moderador editar ou excluir obras publicadas na plataforma. | Média |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-17  | Moderar Obras | Permitir que moderadores editem ou removam obras que violem diretrizes da plataforma. | Média |

### 13 - Gerenciar Contas de Usuários

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-19  | Gerenciar Contas de Usuários | Permitir ao moderador excluir ou suspender contas de usuários. | Média |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-18  | Gerenciar Contas de Usuários | Permitir que moderadores suspendam ou excluam contas de usuários que violem termos de uso. | Média |

### 14 - Moderar Comentários

**Antes:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-20  | Gerenciar Comentários | Permitir ao moderador excluir comentários denunciados por usuários. | Baixa |

**Depois:**
| Código | Nome | Descrição | Prioridade |
|--------|------|-----------|------------|
| RF-24  | Moderar Comentários | Permitir que moderadores removam comentários denunciados após análise. | Baixa |
