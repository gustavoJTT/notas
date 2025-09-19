
# Funcionalidades do Lume

## Novas Funcionalidades

| Código   | Nome                        | Descrição                                                                 | Prioridade    |
|----------|-----------------------------|---------------------------------------------------------------------------|--------------|
| RF-05    | Busca por Palavra-Chave     | Implementar uma barra de busca para procurar obras por título, produtor, gênero ou tags. | Alta         |
| RF-09    | Seguir Produtores           | Permitir que usuários possam seguir o perfil de seus produtores favoritos. | Média        |
| RF-10    | Sistema de Notificações     | Notificar usuários sobre interações relevantes (novas obras de quem segue, respostas, etc.). | Média        |
| RF-15    | Gerenciar Produções Próprias| Permitir que o produtor possa editar ou excluir suas próprias obras já publicadas. | Alta |
| RNF-04   | Desempenho                  | O tempo de carregamento das páginas principais não deve exceder 3 segundos em uma conexão padrão. | Obrigatório  |
| RNF-05   | Privacidade de Dados (LGPD) | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados, garantindo o tratamento transparente e seguro dos dados. | Obrigatório  |
| RNF-06   | Backup e Recuperação        | Devem existir rotinas de backup automático para garantir a recuperação de dados em caso de falha crítica. | Obrigatório  |
| RNF-07   | Escalabilidade              | A arquitetura deve permitir crescimento modular sem reescrever a base do sistema. | Desejável    |
| RNF-09   | Disponibilidade             | A plataforma deve visar uma disponibilidade de 99.5% do tempo.            | Desejável    |

---

## Funcionalidades Alteradas

### 01 - Filtrar

**Antes:**

| Código | Nome                        | Descrição                                                        | Prioridade |
|--------|-----------------------------|------------------------------------------------------------------|------------|
| F09    | Filtrar produções por região | Permitir que o usuário possa filtrar as produções publicadas por região | Baixa      |

**Depois:**

| Código | Nome                        | Descrição                                                                                                   | Prioridade |
|--------|-----------------------------|-------------------------------------------------------------------------------------------------------------|------------|
| RF-06  | Filtrar e Ordenar Produções | Permitir que o usuário possa filtrar as obras por múltiplos critérios (gênero, região, data de publicação) e ordená-las (mais recentes, mais bem avaliadas). | Baixa      |

### 02 - Comentar e Avaliar

**Antes:**

| Código | Nome                        | Descrição                                                        | Prioridade |
|--------|-----------------------------|------------------------------------------------------------------|------------|
| F03    | Comentar e avaliar produções | Usuários cadastrados podem comentar e avaliar produções publicadas | Alta       |

**Depois:**

| Código | Nome                        | Descrição                                                        | Prioridade |
|--------|-----------------------------|------------------------------------------------------------------|------------|
| RF-08  | Comentar e/ou Avaliar Produções | Usuários cadastrados podem comentar e/ou avaliar produções publicadas. | Alta       |

### 03 - Segurança de Informações

**Antes:**

| Código | Nome                        | Descrição                                                        | Prioridade |
|--------|-----------------------------|------------------------------------------------------------------|------------|
| NF01   | Segurança de Informações     | Proteger dados pessoais e documentos enviados, utilizando criptografia e autenticação segura | Obrigatório |

**Depois:**

| Código | Nome                        | Descrição                                                        | Prioridade |
|--------|-----------------------------|------------------------------------------------------------------|------------|
| RNF-01 | Segurança de Informações     | Proteger dados pessoais e documentos enviados, utilizando criptografia, HTTPS e proteção contra ataques. | Obrigatório |
