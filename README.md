# ⏱️ Controle de Tempo de Serviço

Sistema web para controle e cálculo de tempo de serviço para aposentadoria, seguindo as regras brasileiras de pontuação por idade e tempo de contribuição.

## 📋 Sobre o Projeto

Este aplicativo foi desenvolvido para ajudar trabalhadores a acompanhar seu tempo de serviço e verificar quando poderão se aposentar de acordo com as regras atuais da Previdência Social brasileira.

## ✨ Funcionalidades

### 📊 Gerenciamento de Dados Pessoais
- Cadastro de data de nascimento (salvo automaticamente)
- Seleção de sexo (Homem/Mulher)
- Dados persistem mesmo após fechar o navegador

### 📝 Controle de Contratos
- **Adicionar contratos de trabalho** com:
  - Nome da empresa
  - Data de início
  - Data de término
  - Opção para marcar como "Emprego Atual"
- **Editar contratos** existentes
- **Excluir contratos** com confirmação
- Visualização clara de todos os contratos registrados

### 🧮 Cálculo de Aposentadoria
- Cálculo automático do tempo total de serviço (anos, meses e dias)
- Verificação da idade atual
- Cálculo de pontos para aposentadoria
- Indicação de quanto falta para:
  - Atingir a pontuação necessária
  - Atingir a idade mínima

### 💾 Exportar e Importar Dados
- **Exportar** todos os contratos em formato JSON
- **Importar** dados salvos anteriormente
- Facilita backup e transferência entre dispositivos

### 🗑️ Limpeza de Dados
- Opção para limpar todos os dados do sistema
- Confirmação dupla para segurança
- Útil para novo usuário ou recomeço

## 📐 Regras de Aposentadoria

O sistema utiliza as seguintes regras:

### Homens
- **Idade mínima:** 65 anos
- **Pontuação necessária:** 105 pontos (idade + tempo de contribuição)

### Mulheres
- **Idade mínima:** 62 anos
- **Pontuação necessária:** 95 pontos (idade + tempo de contribuição)

## 🚀 Como Usar

### 1️⃣ Configuração Inicial
1. Abra o arquivo HTML no seu navegador
2. Preencha sua **data de nascimento**
3. Selecione seu **sexo**
4. Esses dados serão salvos automaticamente

### 2️⃣ Adicionar Contratos
1. Vá até a seção "Adicionar Contrato"
2. Preencha:
   - Nome da empresa
   - Data de início do contrato
   - Data de término (ou marque "Emprego Atual")
3. Clique em **"Adicionar Contrato"**
4. O contrato aparecerá na lista abaixo

### 3️⃣ Calcular Aposentadoria
1. Certifique-se de ter adicionado todos os seus contratos
2. Clique em **"Calcular Tempo Total e Aposentadoria"**
3. Visualize o resultado com:
   - Tempo total de serviço
   - Idade atual
   - Pontos atuais
   - Quanto falta para se aposentar

### 4️⃣ Exportar Dados (Backup)
1. Clique em **"Exportar JSON"**
2. Um arquivo `tempo_servico.json` será baixado
3. Guarde este arquivo em local seguro

### 5️⃣ Importar Dados
1. Clique no campo de upload de arquivo
2. Selecione seu arquivo JSON salvo anteriormente
3. Os dados serão restaurados automaticamente

## 💡 Dicas de Uso

- ✅ **Mantenha backups regulares** usando a função de exportar
- ✅ **Atualize contratos ativos** periodicamente
- ✅ **Verifique a data de término** ao sair de um emprego
- ✅ **Use nomes descritivos** para as empresas
- ⚠️ **Cuidado ao limpar dados** - a ação é irreversível!

## 🔒 Privacidade e Segurança

- ✅ Todos os dados são armazenados **localmente no seu navegador**
- ✅ Nenhuma informação é enviada para servidores externos
- ✅ Seus dados permanecem **100% privados**
- ✅ Funciona **offline** após o primeiro carregamento

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização moderna e responsiva
- **JavaScript** - Lógica de cálculos e armazenamento
- **LocalStorage** - Persistência de dados no navegador

## 📱 Compatibilidade

O sistema é totalmente responsivo e funciona em:
- 💻 Desktops e notebooks
- 📱 Tablets
- 📱 Smartphones
- 🌐 Todos os navegadores modernos (Chrome, Firefox, Safari, Edge)

## ⚠️ Observações Importantes

1. **Este sistema é uma ferramenta de auxílio** e não substitui a consulta oficial ao INSS
2. As regras de aposentadoria podem mudar - sempre verifique as regras atuais
3. Para informações oficiais, consulte o site do [INSS](https://www.gov.br/inss/pt-br)
4. Os cálculos consideram apenas tempo de serviço e idade, não contemplam outras regras especiais

## 🐛 Problemas Conhecidos

Caso encontre algum problema:
1. Verifique se está usando um navegador atualizado
2. Limpe o cache do navegador
3. Verifique se o JavaScript está habilitado

## 📝 Changelog

### Versão 2.0
- ✅ Salvamento automático de dados pessoais
- ✅ Função de limpar todos os dados
- ✅ Interface visual melhorada
- ✅ Melhor responsividade mobile
- ✅ Confirmação ao excluir contratos

### Versão 1.0
- ✅ Lançamento inicial
- ✅ Cadastro de contratos
- ✅ Cálculo de aposentadoria
- ✅ Exportar/Importar JSON

## 📄 Licença

Este projeto é de código aberto e pode ser utilizado livremente.

## 👨‍💻 Suporte

Para dúvidas sobre o uso do sistema ou sugestões de melhorias, sinta-se à vontade para entrar em contato.

---

**Desenvolvido com ❤️ para ajudar trabalhadores brasileiros a planejarem sua aposentadoria**
