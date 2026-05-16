# AgendaMedica
Sabe aquela tia que sempre pede para você marcar exame, e quer que você lembre ela depois. Esse pequeno código vai resolver seu problema.

Com ele, você cadastrará e ele te lembrará e lembrará sua tia do médico. 
# 📱 Como Funciona o Envio de Mensagens WhatsApp

## ⚠️ Limitação Importante: WhatsApp NÃO Permite Envio Totalmente Automático

O WhatsApp **não permite** que sites enviem mensagens automaticamente por segurança. Isso é uma proteção do WhatsApp para evitar spam.

## ✅ O Que o Sistema Atual FAZ:

1. **Abre automaticamente o WhatsApp Web/App** com a mensagem já pronta
2. **Preenche toda a mensagem automaticamente**
3. Você só precisa clicar em "Enviar" uma vez em cada aba

### Fluxo de Envio:
```
Você clica no botão "Enviar Lembrete"
    ↓
Sistema abre 1ª aba: WhatsApp para a Tia (mensagem pronta)
    ↓
Você clica "Enviar" ✅
    ↓
Após 3 segundos, abre 2ª aba: WhatsApp para você (mensagem pronta)
    ↓
Você clica "Enviar" ✅
    ↓
Concluído!
```

## 🚀 Para Envio 100% Automático Você Precisaria:

### Opção 1: WhatsApp Business API (Pago)
- **Custo:** R$ 100-500/mês dependendo do volume
- **Permite:** Envio automático programado
- **Requer:** Conta empresarial verificada
- **Plataformas:** Twilio, Vonage, MessageBird

### Opção 2: Usar um Serviço de Automação
- **Evolution API** (gratuito, self-hosted)
- **Baileys** (biblioteca para Node.js)
- **WPPConnect** (open source)

**PROBLEMA:** Essas soluções requerem:
- Um servidor rodando 24/7
- Conhecimento técnico avançado
- Podem violar os Termos de Uso do WhatsApp

### Opção 3: Bot no Google Apps Script (Semi-automático)
O Google Apps Script pode verificar a planilha diariamente e **enviar um EMAIL** automático ao invés de WhatsApp.

## 💡 Solução Recomendada Atual:

### Sistema de Notificações do Navegador:
O que temos agora é o melhor equilíbrio:

1. ✅ **Notificações do navegador** alertam você automaticamente
2. ✅ **Mensagens pré-escritas** no WhatsApp (só clicar em enviar)
3. ✅ **Marcação automática** na planilha
4. ✅ **Legal e seguro** (não viola termos do WhatsApp)

### Como Usar:
1. Mantenha o site aberto em uma aba do navegador
2. Permita notificações quando solicitado
3. Quando chegar o momento, você receberá uma notificação
4. Clique no botão e envie pelo WhatsApp (2 cliques apenas)




