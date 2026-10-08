# MX Revisão Fiscal — painel do Departamento Fiscal

Carteira de alertas da apuração fiscal: variação do valor do imposto, prazo da
guia e justificativas em aberto, de todas as empresas e de todas as máquinas.

Uma página só. Os dados ficam no Supabase da MAXIMOS e **não estão neste
repositório** — a página só os busca depois do login, e quem não tem o cartão
`revisao_fiscal` no portal não enxerga nada (RLS).

Quem publica a carteira é o **MX CRÉDITOS** instalado em cada máquina:
tela de Empresas → Conectar → Publicar carteira. Sobe só o resumo; EFD e XML
nunca saem do computador.
