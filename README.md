Programa de gestão - Gerenciamento e controle de Empresa .
Este programa tem por objetivo calcular automaticamente os preços que os produtos devem ser vendidas, com o percentual de lucro escolhido pelo 
administrador,facilitando o cálculo do preço de venda, considerando todos os custos envolvidos e a margem de lucro desejada, bem como
controle de estoque e registros de notas fiscais. A seguir está as principais funcionalidades que o programa deve ter, para que o administrador 
acesse o programa e consiga realizar as funções desejadas para alcançar seus objetivos.

Caso de Uso: Acesso ao Sistema
1. Nome do Caso de Uso
Acesso ao Sistema
2. Ator Principal
Administrador da Empresa
3. Objetivo
Permitir que o administrador faça login no sistema de forma segura para acessar suas funcionalidades.
4. Pré-condições
O administrador deve ter um nome de usuário e senha válidos cadastrados no sistema.
5. Fluxo Principal
Abertura da Tela de Login: O administrador abre a tela de login do sistema.
Inserção de Credenciais: O administrador insere seu nome de usuário e senha nos campos apropriados.
Envio das Credenciais: O administrador clica no botão de login para enviar as credenciais.
Verificação de Credenciais: O sistema verifica se o nome de usuário e a senha são válidos.
Acesso ao Sistema: Se as credenciais forem válidas, o administrador é redirecionado para o dashboard principal.
6. Fluxos Alternativos
A1: Se o nome de usuário ou a senha estiverem incorretos, o sistema exibe uma mensagem de erro e solicita que o administrador tente novamente.
A2: Se o administrador esquecer a senha, ele pode clicar em “Esqueci minha senha” para iniciar o processo de recuperação de senha.
7. Pós-condições
O administrador está autenticado no sistema e tem acesso às funcionalidades disponíveis.
Em caso de falha na autenticação, o administrador permanece na tela de login com uma mensagem de erro.
8. Requisitos Especiais
O sistema deve utilizar HTTPS para garantir a segurança na transmissão de dados.
As senhas devem ser armazenadas de forma segura.

Caso de Uso: Cadastro de Custos
1. Nome do Caso de Uso
Cadastro de Custos
2. Ator Principal
Administrador da Empresa
3. Objetivo
Permitir que o administrador insira e gerencie os custos relacionados à produção das bolsas.
4. Pré-condições
O administrador deve estar autenticado no sistema.
O administrador deve ter acesso ao módulo de cadastro de custos.
5. Fluxo Principal
Acesso ao Módulo de Cadastro de Custos: Após o login, o administrador navega até a seção de cadastro de custos no dashboard.
Inserção de Dados de Custos: O administrador insere os seguintes dados:
Material utilizado
Custo de mão de obra
Custo de entrega de produtos
Custo de entrega das bolsas
Validação dos Dados: O sistema valida os dados inseridos para garantir que estão completos e corretos.
Salvamento dos Dados: O administrador clica no botão de salvar, e o sistema armazena os dados no banco de dados.
Confirmação: O sistema exibe uma mensagem de confirmação indicando que os dados foram salvos com sucesso.
6. Fluxos Alternativos
A1: Se os dados inseridos estiverem incompletos ou incorretos, o sistema exibe uma mensagem de erro e solicita a correção dos dados.
A2: Se o administrador desejar cancelar a operação, ele pode clicar no botão de cancelar, e o sistema descarta os dados inseridos.
7. Pós-condições
Os dados de custos são armazenados no sistema e podem ser utilizados para cálculos futuros.
O administrador pode visualizar e editar os dados de custos cadastrados.
8. Requisitos Especiais
A interface deve ser intuitiva e fácil de usar para o administrador.
O sistema deve garantir a segurança e integridade dos dados armazenados.
Diagrama de Caso de Uso

Caso de Uso: Definição de Margem de Lucro
1. Nome do Caso de Uso
Definição de Margem de Lucro
2. Ator Principal
Administrador da Empresa
3. Objetivo
Permitir que o administrador defina a margem de lucro desejada para calcular o preço de venda das bolsas.
4. Pré-condições
O administrador deve estar autenticado no sistema.
O administrador deve ter acesso ao módulo de definição de margem de lucro.
5. Fluxo Principal
Acesso ao Módulo de Margem de Lucro: Após o login, o administrador navega até a seção de definição de margem de lucro no dashboard.
Inserção da Margem de Lucro: O administrador insere a porcentagem de margem de lucro desejada.
Validação dos Dados: O sistema valida a margem de lucro inserida para garantir que está dentro dos parâmetros aceitáveis.
Salvamento da Margem de Lucro: O administrador clica no botão de salvar, e o sistema armazena a margem de lucro no banco de dados.
Confirmação: O sistema exibe uma mensagem de confirmação indicando que a margem de lucro foi salva com sucesso.
6. Fluxos Alternativos
A1: Se a margem de lucro inserida estiver fora dos parâmetros aceitáveis, o sistema exibe uma mensagem de erro e solicita a correção dos dados.
A2: Se o administrador desejar cancelar a operação, ele pode clicar no botão de cancelar, e o sistema descarta os dados inseridos.
7. Pós-condições
A margem de lucro é armazenada no sistema e pode ser utilizada para cálculos futuros.
O administrador pode visualizar e editar a margem de lucro definida.
8. Requisitos Especiais
A interface deve ser intuitiva e fácil de usar para o administrador.
O sistema deve garantir a segurança e integridade dos dados armazenados.

Caso de Uso: Cálculo do Preço de Venda
1. Nome do Caso de Uso
Cálculo do Preço de Venda
2. Ator Principal
Administrador da Empresa
3. Objetivo
Permitir que o administrador calcule o preço de venda das bolsas com base nos custos e na margem de lucro desejada.
4. Pré-condições
O administrador deve estar autenticado no sistema.
Os custos de materiais, mão de obra e entrega devem estar cadastrados no sistema.
A margem de lucro deve estar definida.
5. Fluxo Principal
Acesso ao Módulo de Cálculo de Preço de Venda: Após o login, o administrador navega até a seção de cálculo de preço de venda no dashboard.
Seleção dos Custos: O administrador seleciona os custos previamente cadastrados (material, mão de obra, entrega).
Aplicação da Margem de Lucro: O sistema aplica a margem de lucro definida aos custos selecionados.
Cálculo do Preço de Venda: O sistema calcula automaticamente o preço de venda com base nos custos e na margem de lucro.
Exibição do Preço de Venda: O sistema exibe o preço de venda calculado na tela para o administrador.
Confirmação e Salvamento: O administrador confirma o preço de venda e o sistema salva os dados.
6. Fluxos Alternativos
A1: Se os custos não estiverem completos ou corretos, o sistema exibe uma mensagem de erro e solicita a correção dos dados.
A2: Se a margem de lucro não estiver definida, o sistema solicita que o administrador defina a margem antes de prosseguir.
7. Pós-condições
O preço de venda das bolsas é calculado e armazenado no sistema.
O administrador pode visualizar e editar o preço de venda calculado.
8. Requisitos Especiais
A interface deve ser intuitiva e fácil de usar para o administrador.
O sistema deve garantir a segurança e integridade dos dados armazenados.


Caso de uso: Geração de Relatórios detalhados sobre Custos e Lucros
1. Nome do Caso de Uso
Geração de Relatórios Detalhados sobre Custos e Lucros
2. Ator Principal
Administrador da Empresa
3. Objetivo
Permitir que o administrador gere relatórios detalhados sobre os custos e lucros das bolsas, facilitando a análise financeira e a tomada de decisões.
4. Pré-condições
O administrador deve estar autenticado no sistema.
Os custos e margens de lucro devem estar cadastrados no sistema.
5. Fluxo Principal
Acesso ao Módulo de Relatórios: Após o login, o administrador navega até a seção de relatórios no dashboard.
Seleção de Parâmetros: O administrador seleciona os parâmetros desejados para o relatório, como período, tipo de custo, e tipo de bolsa.
Geração do Relatório: O sistema processa os dados e gera o relatório detalhado com base nos parâmetros selecionados.
Visualização do Relatório: O administrador visualiza o relatório na tela, que inclui gráficos e tabelas detalhadas.
Exportação do Relatório: O administrador pode exportar o relatório em formatos como PDF ou Excel para análise offline.
6. Fluxos Alternativos
A1: Se os parâmetros selecionados não gerarem dados suficientes, o sistema exibe uma mensagem de erro e solicita a redefinição dos parâmetros.
A2: Se o administrador desejar cancelar a operação, ele pode clicar no botão de cancelar, e o sistema descarta a geração do relatório.
7. Pós-condições
O relatório detalhado é gerado e pode ser visualizado e exportado pelo administrador.
Os dados do relatório são armazenados para futuras consultas.
8. Requisitos Especiais
A interface deve ser intuitiva e fácil de usar para o administrador.
O sistema deve garantir a segurança e integridade dos dados armazenados e gerados.

Caso de Uso: Adicionar Dados para Automação de Controle de Estoque
Ator Principal: Administrador
Objetivo: Inserir dados no sistema para automatizar o controle de estoque, garantindo precisão e eficiência na gestão.
Pré-condições:
O Administrador deve estar autenticado no sistema.
O sistema deve estar configurado para aceitar dados de entrada e saída de estoque.
Fluxo Principal:
O Administrador acessa a funcionalidade de “Adicionar Dados” no sistema.
O sistema exibe um formulário para inserção de dados de produtos.
O Administrador insere as informações necessárias, como:
Nome do produto
Código do produto
Quantidade inicial em estoque
Fornecedor
Data de entrada
Preço de compra
O Administrador confirma a inserção dos dados.
O sistema valida as informações e salva os dados no banco de dados.
O sistema atualiza automaticamente o estoque com as novas informações.
O sistema exibe uma mensagem de confirmação da operação.
Fluxos Alternativos:
Dados incompletos ou inválidos:
Se os dados inseridos estiverem incompletos ou inválidos, o sistema exibe uma mensagem de erro.
O Administrador deve corrigir os dados e tentar novamente.
Produto já cadastrado:
Se o produto já estiver cadastrado no sistema, o sistema exibe uma mensagem informando que o produto já existe.
O Administrador pode optar por atualizar as informações do produto existente.
Pós-condições:
Os dados do produto são registrados no sistema.
O estoque é atualizado automaticamente com as novas informações.
Um registro da operação é salvo no histórico do sistema.
Benefícios:
Precisão: Garante que os dados de estoque estejam sempre atualizados e corretos.
Eficiência: Automatiza o processo de entrada de dados, reduzindo erros e economizando tempo.
Controle: Facilita a gestão do estoque, permitindo um acompanhamento detalhado das movimentações.


Caso de Uso: Aviso de Estoque Baixo
Ator Principal: Administrador
Objetivo: Receber alertas quando a quantidade de um item no estoque atinge um nível crítico.
Pré-condições:
O Administrador deve estar autenticado no sistema.
O sistema deve ter um registro atualizado dos níveis de estoque de todos os itens.
Fluxo Principal:
O Administrador acessa a funcionalidade de “Configurar Avisos de Estoque Baixo” no sistema.
O sistema exibe uma lista de produtos cadastrados.
O Administrador seleciona o produto para o qual deseja configurar o aviso.
O sistema solicita a quantidade mínima de unidades para o aviso (ex.: 10 unidades).
O Administrador insere a quantidade mínima e confirma a configuração.
O sistema monitora continuamente os níveis de estoque do produto selecionado.
Quando a quantidade do produto atinge ou fica abaixo do limite configurado, o sistema envia um alerta ao gerente de estoque.
O sistema exibe uma mensagem de alerta, informando que o estoque do produto está baixo.
Fluxos Alternativos:
Produto não cadastrado:
Se o produto não estiver cadastrado, o sistema exibe uma mensagem de erro.
O Administrador pode optar por cadastrar o novo produto antes de configurar o aviso.
Quantidade mínima inválida:
Se a quantidade mínima inserida for inválida (ex.: número negativo), o sistema exibe uma mensagem de erro.
O gerente de estoque deve inserir uma quantidade válida.
Pós-condições:
O gerente de estoque recebe alertas sobre produtos com níveis críticos de estoque.
Um registro da configuração do aviso é salvo no histórico do sistema.
Benefícios:
Proatividade: Permite ao gerente de estoque tomar ações preventivas para evitar a falta de produtos.
Eficiência: Facilita a gestão de reabastecimento de estoque.
Controle: Ajuda a manter o estoque sempre em níveis ideais, evitando interrupções nas operações.

Caso de Uso: Alerta de Estoque de Bolsas Paradas
Ator Principal: Administrador
Objetivo: Receber alertas quando um modelo de bolsa está há muito tempo sem movimentação no estoque.
Pré-condições:
O Administrador deve estar autenticado no sistema.
O sistema deve ter um registro de todas as movimentações de estoque.
Fluxo Principal:
O Administrador acessa a funcionalidade de “Configurar Alertas” no sistema.
O sistema exibe uma lista de produtos cadastrados.
O Administrador seleciona o modelo de bolsa para o qual deseja configurar o alerta.
O sistema solicita o período de tempo sem movimentação para gerar o alerta (ex.: 3 meses).
O Administrador insere o período e confirma a configuração.
O sistema monitora as movimentações de estoque do modelo de bolsa selecionado.
Se o modelo de bolsa não tiver movimentação no período configurado, o sistema envia um alerta ao Administrador
O sistema exibe uma mensagem de alerta, informando que o modelo de bolsa está há X meses sem movimentação.
Fluxos Alternativos:
Produto não cadastrado:
Se o modelo de bolsa não estiver cadastrado, o sistema exibe uma mensagem de erro.
O Administrador pode optar por cadastrar o novo modelo antes de configurar o alerta.
Período inválido:
Se o período inserido for inválido (ex.: número negativo), o sistema exibe uma mensagem de erro.
O Administrador deve inserir um período válido.
Pós-condições:
O Administrador recebe alertas sobre modelos de bolsas paradas no estoque.
Um registro da configuração do alerta é salvo no histórico do sistema.
Benefícios:
Proatividade: Permite ao gerente de estoque tomar ações preventivas para evitar acúmulo de produtos parados.
Eficiência: Facilita a gestão de produtos com baixa rotatividade.
Controle: Ajuda a manter o estoque atualizado e otimizado

Caso de Uso: Registro de Notas Fiscais
Ator Principal: Administrador
Objetivo: Registrar notas fiscais de compras e vendas no sistema para controle financeiro e fiscal.
Pré-condições:
O Administrador deve estar autenticado no sistema.
As notas fiscais devem estar disponíveis em formato digital (ex.: XML).
Fluxo Principal:
O Administrador acessa a funcionalidade de “Registro de Notas Fiscais” no sistema.
O sistema exibe opções para registrar notas fiscais de compras e vendas.
O Administrador seleciona o tipo de nota fiscal a ser registrada (compra ou venda).
O sistema solicita o upload do arquivo da nota fiscal (ex.: XML).
O Administrador faz o upload do arquivo da nota fiscal.
O sistema valida o arquivo e extrai as informações necessárias (ex.: data, valor, fornecedor/cliente, itens).
O Administrador revisa e confirma as informações extraídas.
O sistema salva o registro da nota fiscal no banco de dados.
O sistema exibe uma mensagem de confirmação da operação.
Fluxos Alternativos:
Arquivo inválido:
Se o arquivo da nota fiscal for inválido ou estiver corrompido, o sistema exibe uma mensagem de erro.
O Administrador deve fazer o upload de um arquivo válido.
Informações incompletas:
Se as informações extraídas estiverem incompletas, o sistema solicita que o Administrador insira os dados faltantes manualmente.
O Administrador insere as informações e confirma a operação.
Pós-condições:
A nota fiscal é registrada no sistema com todas as informações necessárias.
Um registro da operação é salvo no histórico do sistema.
Benefícios:
Conformidade: Garante que todas as transações estejam registradas conforme as regulamentações fiscais.
Controle: Facilita o acompanhamento de compras e vendas, ajudando na gestão financeira.
Eficiência: Automatiza o processo de registro, reduzindo erros e economizando tempo.

Caso de Uso: Cadastrar Novo Produto
Ator Principal: Administrador
Objetivo: Adicionar um novo produto ao sistema de gestão de estoque.
Pré-condições:
O Administrador deve estar autenticado no sistema.
O sistema deve permitir o cadastro de novos produtos.
Fluxo Principal:
O Administrador acessa a funcionalidade de “Cadastrar Novo Produto” no sistema.
O sistema exibe um formulário para inserção de dados do produto.
O Administrador insere as informações necessárias, como:
Nome do produto
Código do produto
Categoria
Fornecedor
Preço de compra
Preço de venda
Quantidade inicial em estoque
Descrição do produto
O Administrador confirma a inserção dos dados.
O sistema valida as informações e salva o novo produto no banco de dados.
O sistema exibe uma mensagem de confirmação da operação.
Fluxos Alternativos:
Dados incompletos ou inválidos:
Se os dados inseridos estiverem incompletos ou inválidos, o sistema exibe uma mensagem de erro.
O Administrador deve corrigir os dados e tentar novamente.

Pós-condições:
O novo produto é registrado no sistema.
O estoque é atualizado com a quantidade inicial do novo produto.
Um registro da operação é salvo no histórico do sistema.

Caso de Uso: Editar Produtos Existentes
Ator Principal: Administrador
Objetivo: Atualizar as informações de produtos já cadastrados no sistema.
Pré-condições:
O Administrador deve estar autenticado no sistema.
O produto a ser editado deve estar cadastrado no sistema.
Fluxo Principal:
O Administrador acessa a funcionalidade de “Editar Produto” no sistema.
O sistema exibe uma lista de produtos cadastrados.
O Administrador seleciona o produto que deseja editar.
O sistema exibe um formulário com os dados atuais do produto.
O Administrador atualiza as informações necessárias, como:
Nome do produto
Código do produto
Categoria
Fornecedor
Preço de compra
Preço de venda
Quantidade em estoque
Descrição do produto
O Administrador confirma a atualização dos dados.
O sistema valida as informações e salva as alterações no banco de dados.
O sistema exibe uma mensagem de confirmação da operação.

Fluxos Alternativos:
Produto não encontrado:
Se o produto não estiver cadastrado, o sistema exibe uma mensagem de erro.
O Administrador pode optar por cadastrar o novo produto.
Dados inválidos:
Se os dados atualizados forem inválidos, o sistema exibe uma mensagem de erro.
O Administrador deve corrigir os dados e tentar novamente.
Pós-condições:
As informações do produto são atualizadas no sistema.
Um registro da operação é salvo no histórico do sistema.
Benefícios:
Precisão: Garante que os dados dos produtos estejam sempre atualizados e corretos.
Eficiência: Facilita a gestão de produtos, permitindo atualizações rápidas e precisas.
Controle: Ajuda a manter o estoque organizado e otimizado.

Caso de Uso: Gerar Relatório de Estoque
Ator Principal: Administrador
Objetivo: Gerar um relatório detalhado do estoque para análise e tomada de decisões.
Pré-condições:
O Administrador deve estar autenticado no sistema.
O sistema deve ter um registro atualizado dos níveis de estoque de todos os itens.
Fluxo Principal:
O Administrador acessa a funcionalidade de “Relatórios de Estoque” no sistema.
O sistema exibe opções para personalizar o relatório (ex.: período, categorias de produtos, status do estoque).
O Administrador seleciona os filtros desejados para o relatório.
O sistema gera o relatório com base nos filtros aplicados.
O Administrador visualiza o relatório, que pode incluir informações como:
Nome do produto
Código do produto
Quantidade em estoque
Data da última movimentação
Valor total do estoque
O Administrador pode optar por exportar o relatório em diferentes formatos (ex.: PDF, Excel).
O sistema exibe uma mensagem de confirmação da operação.
Fluxos Alternativos:
Filtros inválidos:
Se os filtros aplicados forem inválidos ou inconsistentes, o sistema exibe uma mensagem de erro.
O Administrador deve ajustar os filtros e tentar novamente.
Dados incompletos:
Se os dados do estoque estiverem incompletos, o sistema exibe uma mensagem de alerta.
O Administrador pode optar por revisar e atualizar os dados antes de gerar o relatório.
Pós-condições:
O relatório de estoque é gerado e disponibilizado para análise.
Um registro da operação é salvo no histórico do sistema.
Benefícios:
Visibilidade: Proporciona uma visão detalhada do estado atual do estoque.
Tomada de Decisão: Facilita a análise e a tomada de decisões estratégicas.
Controle: Ajuda a identificar produtos com baixa rotatividade, excesso de estoque ou necessidade de reabastecimento.

Caso de Uso: Sair do Sistema
1. Nome do Caso de Uso
Sair do Sistema
2. Ator Principal
Administrador da Empresa
3. Objetivo
Permitir que o administrador encerre sua sessão de forma segura, garantindo que nenhum dado sensível permaneça acessível.
4. Pré-condições
O administrador deve estar autenticado no sistema.
5. Fluxo Principal
Acesso à Opção de Logout: O administrador clica no botão ou link de logout disponível na interface do sistema.
Confirmação de Logout: O sistema pode solicitar uma confirmação para garantir que o administrador deseja realmente sair.
Encerramento da Sessão: O sistema encerra a sessão do administrador, invalidando o token de autenticação.
Redirecionamento para a Tela de Login: O administrador é redirecionado para a tela de login, confirmando que a sessão foi encerrada com sucesso.
6. Fluxos Alternativos
A1: Se o administrador não confirmar o logout, a sessão permanece ativa e o administrador retorna à tela anterior.
A2: Se ocorrer um erro durante o processo de logout, o sistema exibe uma mensagem de erro e solicita que o administrador tente novamente.
7. Pós-condições
A sessão do administrador é encerrada e ele é redirecionado para a tela de login.
Nenhum dado sensível do administrador permanece acessível após o logout.
8. Requisitos Especiais
O sistema deve garantir que todos os tokens de autenticação sejam invalidados após o logout.
A interface deve ser intuitiva e fácil de usar para o administrador.

