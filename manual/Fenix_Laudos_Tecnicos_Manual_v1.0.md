# Fênix | Laudos Técnicos — Manual do usuário (v1.0)

## 1. Primeiros passos
1. **Empresa**: cadastre uma vez (digite o CNPJ e toque em *Buscar CNPJ* para preencher razão social e endereço). Envie a logomarca.
2. **Profissionais**: informe conselho (CFT/CRT ou CREA), número de registro e **marque as categorias de equipamento** que a atribuição cobre. Desenhe ou envie a assinatura.
3. **Contratantes**: cadastre quem solicita o serviço (CPF/CNPJ validados).

## 2. Criando um laudo (9 etapas)
| Etapa | O que registrar |
|---|---|
| 1 Identificação | Profissional, contratante, data, local, finalidade, categoria |
| 2 Equipamento | Dados da placa, campos da categoria, fotos. Fabricante+modelo já usados preenchem sozinhos |
| 3 Histórico | Relato do contratante (separado da constatação técnica) |
| 4 Procedimentos | Cada procedimento: realizado, não realizado ou não aplicável. Instrumentos usados |
| 5 Medições | Parâmetro, referência, **fonte do critério**, resultado e avaliação |
| 6 Diagnóstico | Constatações (comprovadas) e hipóteses (a investigar) em campos separados |
| 7 Conclusão | Classificação, justificativa, recomendações e prazo |
| 8 Responsabilidade | TRT/ART (apenas informado), local, referências, tipo de assinatura |
| 9 Revisão | Pendências automáticas, visualização e emissão |

O app **não presume limites de aceitação**: só avalia como conforme/não conforme se houver referência e fonte (fabricante, norma ou critério justificado).

## 3. Fluxo documental
**Rascunho → Em revisão → Definitivo → Arquivado.**
- Rascunho: editável; o PDF sai com marca d'água *RASCUNHO – SEM VALIDADE COMO DOCUMENTO DEFINITIVO*.
- Emissão: exige zero pendências bloqueantes e a declaração de responsabilidade. O conteúdo é congelado com data, hora e código SHA-256.
- Correção: *Corrigir (nova versão)* cria a v2 em rascunho; a versão emitida é preservada.
- Definitivos não podem ser excluídos (apenas arquivados).

## 4. PDF
Em *Visualizar documento* ou *Meus laudos > Documento / PDF*, toque em **Imprimir / Salvar PDF** e escolha "Salvar como PDF". O arquivo recebe o número do laudo no nome. Use Chrome ou Edge atualizados para numeração de páginas.

## 5. Assinatura
- **Visual**: imagem da assinatura (não é assinatura digital certificada).
- **Eletrônica**: registro de autoria e integridade (nome, data/hora e SHA-256).
- **ICP-Brasil**: o app prepara o documento; o certificado é aplicado fora do app.

## 6. Dados e backup
Tudo é salvo no aparelho e funciona offline. Em **Sincronização** exporte e importe backups (inclui fotos). A nuvem Fênix será conectada em versão futura.

## 7. Prompt para IA
Na etapa 6, *Copiar prompt para IA* gera um texto com regras permanentes (não inventar medições, normas ou testes) e os dados do laudo. Revise sempre o que a IA devolver.

## 8. Responsabilidade
Este app é ferramenta auxiliar de documentação. A inspeção, os dados técnicos, a interpretação e a emissão são do profissional legalmente habilitado. Confira a edição vigente e a aplicabilidade de cada norma citada.
