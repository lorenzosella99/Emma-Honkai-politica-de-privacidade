# Política de Privacidade — Emma Honkai

**Versão:** 1.0 — 5 de novembro de 2026

> Documento inicial. Antes de ser considerado política legal definitiva, o responsável deve preencher contato, confirmar controlador, fornecedores, retenção e atendimento aos titulares. Não publique promessas ainda não implementadas.

## Dados tratados
- Conta: nome de usuário, identificador interno e credenciais gerenciadas pelo Supabase Auth. A aplicação não deve guardar senhas em texto puro.
- Perfil/uso: avatar, preferências, personagem atribuído, moedas, missões, assinatura, bloqueios e estatísticas.
- Conteúdo: mensagens, conversas, personagens, denúncias e solicitações.
- Segurança: logs de autenticação, eventos de erro, horários e informações técnicas dos provedores.

## Finalidades
Criar e proteger contas, manter conversas/personagens, sincronizar o serviço, aplicar regras e moderação, processar moedas/assinaturas internas, prevenir fraude e resolver falhas.

## Conversas e moderação
Conversas são privadas entre participantes autorizados. **Somente o administrador principal pode consultar todos os chats e históricos.** Moderadores e vice-administradores não possuem acesso geral: só podem visualizar uma conversa específica quando ela estiver vinculada a uma denúncia ou tarefa de moderação sob sua responsabilidade, e apenas no limite necessário à análise. A permissão para gerenciar denúncias não autoriza navegar por todos os chats. É proibido acessar conversas por curiosidade, interesse pessoal ou finalidade alheia à moderação. O acesso deve ser restrito e auditável.

O recurso de bot assumir personagem deve respeitar a preferência do responsável. O histórico só deve ser enviado a serviço externo de IA quando necessário, com transparência e controles adequados.

## Compartilhamento e operadores
O serviço utiliza Supabase para autenticação/banco e GitHub para código e, quando configurado, sincronização de arquivos. Outros provedores só devem ser declarados quando realmente integrados. Não vendemos dados pessoais. Não compartilhe credenciais, tokens ou dados privados em repositórios públicos.

## Retenção e exclusão
Os dados são mantidos pelo tempo necessário à operação, segurança, disputas e obrigações legais. Deve existir processo para solicitar acesso, correção, portabilidade e exclusão. Backups podem manter cópias por período limitado e documentado.

**Prazos de retenção:** o operador deve definir prazos reais para contas inativas, mensagens, denúncias, logs e backups antes da adoção final.

## Direitos dos titulares
Titulares podem solicitar confirmação, acesso, correção, informação sobre compartilhamento, portabilidade, eliminação e revisão de decisões automatizadas, quando aplicável. O canal de contato deve ser publicado pelo operador. A identidade pode ser verificada proporcionalmente.

## Segurança
São adotadas medidas técnicas e administrativas proporcionais ao risco, incluindo controle de acesso, políticas de banco, autenticação, proteção de segredos e monitoramento. Nenhum sistema é livre de riscos. Incidentes serão tratados conforme a legislação aplicável.

## Crianças e adolescentes
O operador deve definir faixa etária mínima e salvaguardas adequadas, inclusive participação de responsáveis quando exigida, antes de permitir o uso por menores.

## Alterações
Mudanças relevantes devem ser comunicadas no serviço, com data e versão.

## Checklist antes de publicar
- [ ] Informar identificação do controlador e contato válido.
- [ ] Confirmar faixa etária e regras para menores.
- [ ] Confirmar provedores e fluxos de IA realmente ativos.
- [ ] Definir prazos de retenção por categoria.
- [ ] Implementar fluxo funcional de acesso, correção e exclusão.
- [ ] Explicar transferências internacionais e bases legais.
- [ ] Revisar com profissional qualificado para adequação à LGPD.
