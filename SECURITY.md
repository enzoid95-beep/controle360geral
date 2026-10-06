# Seguranca - checklist antes de vender

- Nunca usar a chave `service_role` no navegador.
- RLS deve permanecer ativa em todas as tabelas com dados de clientes.
- Toda nova tabela financeira deve ter `workspace_id` e politica de tenant.
- Operacoes administrativas e webhooks de pagamento devem rodar server-side.
- Validar isolamento com duas contas de teste antes de cada release relevante.
- Anexos devem continuar privados e prefixados pelo `workspace_id`.
- Ativar MFA como opcao e manter a regra atual para quem habilitar o recurso.
- Configurar backups e estrategia de restauracao do banco.
- Registrar erros tecnicos sem gravar valores financeiros desnecessarios em logs.
- Revisar LGPD, politica de privacidade, termos de uso e processo de exclusao/exportacao de dados antes do lancamento publico.
