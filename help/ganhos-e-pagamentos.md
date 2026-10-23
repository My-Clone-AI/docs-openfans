# Ganhos, pagamentos ao criador e extratos / Earnings, payouts and statements

> **RASCUNHO / DRAFT** — pendente de revisão jurídica e contabilística. Os pagamentos a criadores ainda não
> estão ativos: a app mostra "Em breve" até existir o contrato de pagamentos aprovado. Os prazos, a reserva, o
> mínimo e as taxas mostrados são uma **proposta**, não condições finais.

**PT-PT.**
- **Ganhos.** Cada venda confirmada entra como *Pendente*. Depois do período de espera passa a *Disponível*,
  menos uma pequena *Reserva* que fica guardada durante algum tempo para cobrir reembolsos e contestações.
  A reserva continua a ser sua e é libertada no fim do prazo.
- **Antes do primeiro pagamento.** Verificação de ID do criador, chave de acesso ou autenticador, dados
  fiscais (nome, morada, NIF, data de nascimento) e conta bancária (IBAN). A equipa confirma que o nome da
  conta corresponde (verificação do beneficiário) antes do primeiro uso.
- **Pedir um pagamento.** Escolha o valor; vê o valor bruto, a taxa, o valor líquido e o prazo previsto antes
  de confirmar. O valor fica reservado logo. Uma pessoa da equipa aprova (duas, para valores altos ou uma conta
  nova) e o banco faz a transferência SEPA. Só aparece *Pago* quando o extrato do banco o confirma.
- **Estados.** Pedido, Aprovado, Enviado ao banco, Pago, A confirmar com o banco (o valor continua reservado,
  nunca é pago duas vezes), Falhou (o valor volta), Devolvido (o banco devolveu; adicione outra conta),
  Cancelado, Anulado.
- **Mudar de conta bancária.** Pede uma confirmação recente; recebe um aviso; começa um período de espera; os
  pedidos ainda não enviados ao banco são anulados e o valor volta ao disponível. Gestores da equipa nunca
  podem ver nem mudar a conta bancária ou os dados fiscais.
- **Reembolso depois de pago.** Se uma venda já paga for reembolsada, o valor é descontado do pendente, da
  reserva e do disponível. Se não chegar, fica *Em dívida* e é compensado com ganhos futuros — nunca é retirado
  da sua conta bancária.
- **Extratos.** Por mês: saldo inicial, movimentos e saldo final de cada conta, com verificação contra o
  registo contabilístico. Exporte em CSV (link válido 5 minutos, só para si).

**EN.**
- **Earnings.** Each confirmed sale is *Pending*. After the waiting period it becomes *Available*, minus a small
  *Reserve* kept for a while to cover refunds and chargebacks. The reserve is still yours and is released at the
  end of its period.
- **Before the first payout.** Creator ID check, passkey or authenticator, tax details (name, address, tax
  number, date of birth) and a bank account (IBAN). The team checks that the account name matches (payee
  verification) before first use.
- **Requesting a payout.** Pick the amount; you see gross, fee, net and expected timing before you confirm. The
  amount is reserved at once. A team member approves (two for large amounts or a new account) and the bank makes
  the SEPA transfer. It shows *Paid* only when the bank statement confirms it.
- **States.** Requested, Approved, Sent to the bank, Paid, Being confirmed with the bank (still reserved, never
  paid twice), Failed (the amount comes back), Returned (the bank sent it back; add another account), Cancelled,
  Voided.
- **Changing bank account.** Needs a fresh check; you get a notice; a waiting period starts; requests not yet sent
  to the bank are voided and the amount returns to available. Team managers can never see or change your bank
  account or tax details.
- **Refund after a payout.** If an already paid sale is refunded, the amount comes out of pending, reserve and
  available. If that is not enough it is shown as *Owed* and offset against future earnings — never taken from
  your bank account.
- **Statements.** Per month: opening balance, movements and closing balance of every account, checked against
  the ledger. Export as CSV (link valid for 5 minutes, only for you).

Contactos / contact: página "Fale connosco" (`/contacto`) na app.
