# 🚀 Guia Rápido: Ativação do Windows via CMD

## 📋 Visão Geral
Este guia mostra como ativar permanentemente o Windows 10/11 usando o método **HWID** (Hardware ID) através de um script automatizado. A ativação é vinculada ao hardware do seu computador e persiste após reinstalações.

## ⚡ Método Rápido (Recomendado)

### 📥 Opção 1: Usando o Script MAS (Oficial)
Execute no PowerShell como **Administrador**:

```powershell
irm https://get.activated.win | iex
```

**No menu do script:**
1. Pressione `1` (HWID Activation)
2. Pressione `1` novamente (Permanent HWID Activation)
3. Aguarde a conclusão

### 📥 Opção 2: Usando Script Alternativo
1. **Baixe o script** `ativador.cmd`:
   ```powershell
   curl -o ativador.cmd "https://github.com/josuejuca/ativador-windows/raw/main/ativador.cmd"
   ```

2. **Execute como Administrador:**
   - Clique direito no arquivo
   - Selecione "Executar como administrador"

3. **No menu:**
   - Escolha a opção `1` (HWID Activation)

## 🔍 Verificação da Ativação
Após a conclusão, verifique se o Windows está ativado:

**Via PowerShell:**
```powershell
slmgr /xpr
```

**Via Configurações:**
- `Configurações` → `Atualização e Segurança` → `Ativação`

## ⚠️ Avisos Importantes

### 📜 Legalidade
- A ativação de Windows sem licença paga **viola os Termos de Serviço da Microsoft**
- Uso **empresarial** está sujeito a auditorias e penalidades
- Considere adquirir uma licença oficial para suporte completo

### 🔒 Segurança
- Antivírus podem detectar falsos positivos
- Use apenas scripts de fontes confiáveis
- Revise o código antes da execução quando possível

## 🛠️ Solução de Problemas

| Problema | Solução |
|----------|---------|
| Acesso negado | Execute como **Administrador** |
| Script bloqueado | Desative temporariamente o antivírus |
| HWID falhou | Tente ativação KMS (opção 2 no menu) |
| Erro de conexão | Verifique sua conexão com a internet |

## 📚 Recursos Úteis
- [Documentação Oficial MAS](https://massgrave.dev/)
- [Repositório do Script](https://github.com/massgravel/Microsoft-Activation-Scripts)
- [FAQ e Solução de Problemas](https://massgrave.dev/faq.html)

## ✅ Status da Ativação
- ✅ **Permanente** (vinculada ao hardware)
- ✅ **Persistente** (sobrevive a reinstalações)
- ⚠️ **Hardware principal** (mudanças na placa-mãe podem requerer reativação)

---

> **Nota:** Este guia é apenas para fins educacionais. Sempre verifique a legalidade do uso de software em sua região. Para ambientes de produção, recomenda-se adquirir licenças oficiais da Microsoft.

---

**Última Atualização:** 15/12/2025
