[💊 Gerenciador de Medicamentos do Encontro.md](https://github.com/user-attachments/files/23106747/Gerenciador.de.Medicamentos.do.Encontro.md)
# 💊 Gerenciador de Medicamentos dos Encontros J.O.S.U.É. e E.M.P.A.S.

Uma aplicação web moderna e completa para gerenciar medicamentos de participantes em eventos da igreja. Desenvolvida com HTML5, CSS3 e JavaScript puro, funciona 100% offline e em qualquer navegador.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-ativo-brightgreen.svg)
![Versão](https://img.shields.io/badge/versão-1.0.0-blue.svg)

## ✨ Características

### 📋 Gerenciamento de Medicações
- ✅ Cadastro de participantes com medicamentos
- ✅ Múltiplos horários por dia
- ✅ Seleção de dias (sexta, sábado, domingo)
- ✅ Edição e exclusão de registros
- ✅ Observações por dia

### ✅ Controle de Administração
- ✅ Marcar medicações como tomadas
- ✅ Histórico com data/hora exata
- ✅ Status em tempo real (pendente/completo/parcial)
- ✅ Visualização clara do progresso

### 📊 Análise e Relatórios
- ✅ Gráficos de medicações por dia
- ✅ Gráfico de status geral
- ✅ Estatísticas em tempo real
- ✅ Taxa de conclusão
- ✅ Relatório detalhado em tabela
- ✅ Lista de medicações pendentes

### 🔍 Filtros e Busca
- ✅ Buscar por nome do participante
- ✅ Filtrar por dia
- ✅ Filtrar por status
- ✅ Atualizar e limpar filtros

### 💾 Dados e Backup
- ✅ Dados salvos localmente (localStorage)
- ✅ Backup automático
- ✅ Exportar em JSON
- ✅ Exportar em CSV
- ✅ Importar dados

### 🎨 Interface
- ✅ Design responsivo (desktop, tablet, celular)
- ✅ Tema claro/escuro
- ✅ Animações suaves
- ✅ Cards expansíveis
- ✅ Interface intuitiva

### ⌨️ Funcionalidades Extras
- ✅ Atalhos de teclado
- ✅ Autocompletar nomes
- ✅ Impressão de relatório
- ✅ Progressive Web App (PWA)
- ✅ Funciona offline

## 🚀 Como Usar

### Opção 1: Abrir Diretamente (Mais Fácil)
1. Baixe o arquivo `index.html`
2. Abra no navegador (Chrome, Firefox, Safari, Edge)
3. Comece a usar!

### Opção 2: Hospedar no GitHub Pages
1. Faça um fork deste repositório
2. Renomeie para `seu-usuario.github.io` (opcional)
3. Acesse em `https://seu-usuario.github.io/gerenciador-medicamentos`

### Opção 3: Instalar como App (PWA)
1. Abra o arquivo no navegador
2. **Android**: Clique nos 3 pontos → "Instalar aplicativo"
3. **iOS**: Clique em compartilhar → "Adicionar à Tela Inicial"
4. Funciona offline!

## 📖 Guia de Uso

### Cadastrar Medicação
1. Clique em **"➕ Nova Medicação"**
2. Preencha:
   - Nome da pessoa
   - Nome do medicamento
   - Selecione os dias (sexta, sábado, domingo)
   - Adicione os horários para cada dia
3. Clique em **"Adicionar"**

### Marcar Administração
1. Clique no card do participante para expandir
2. Marque o checkbox do horário quando a medicação for tomada
3. A data/hora é registrada automaticamente
4. O status muda para "tomado"

### Adicionar Observações
1. Expanda o card do participante
2. Vá até o dia desejado
3. Digite a observação no campo de texto
4. Clique em **"💾 Salvar Obs"**

### Usar Filtros
1. Use a **barra de busca** para procurar por nome
2. Selecione um **dia** no filtro
3. Selecione um **status** (pendentes, completos, parciais)
4. Clique em **"🔄 Atualizar"** para aplicar

### Exportar Dados
- **JSON**: Clique em **"⬇️ JSON"** (para backup)
- **CSV**: Clique em **"⬇️ CSV"** (para planilha)

### Importar Dados
1. Clique em **"⬆️ Importar"**
2. Selecione um arquivo JSON
3. Os dados serão restaurados

### Imprimir Relatório
1. Clique em **"🖨️ Imprimir"**
2. Configure a impressora
3. Clique em imprimir

## ⌨️ Atalhos de Teclado

| Atalho | Ação |
|--------|------|
| `Ctrl+N` / `Cmd+N` | Nova medicação |
| `Ctrl+S` / `Cmd+S` | Exportar JSON |
| `Esc` | Fechar modal |
| `Enter` | Salvar medicação |

## 🌙 Tema Escuro

Clique no botão **"🌙"** no canto superior direito para alternar entre temas claro e escuro. A preferência é salva automaticamente.

## 📊 Abas Disponíveis

### 💊 Medicações
Lista completa de todos os participantes com suas medicações. Expanda para ver detalhes.

### 📋 Relatório
Tabela detalhada com:
- Participante
- Medicamento
- Dia
- Horários
- Status

### ⏳ Pendentes
Mostra apenas as medicações que ainda não foram tomadas, facilitando o controle.

## 💾 Armazenamento de Dados

- **Localização**: Navegador (localStorage)
- **Privacidade**: Dados não são enviados para nenhum servidor
- **Segurança**: Dados ficam apenas no seu dispositivo
- **Backup Automático**: Cria backup a cada salvamento

## 📱 Responsividade

A aplicação funciona perfeitamente em:
- 🖥️ Desktop (Windows, Mac, Linux)
- 📱 Celulares (Android, iOS)
- 📲 Tablets
- 🌐 Qualquer navegador moderno

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura
- **CSS3**: Estilo e animações
- **JavaScript (ES6+)**: Funcionalidades
- **Chart.js**: Gráficos
- **Service Worker**: Funcionalidade offline
- **Progressive Web App**: Instalação como app

## 📋 Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Sem necessidade de servidor ou instalação

## 🐛 Solução de Problemas

### Os dados desapareceram
- **Solução**: Não limpe os dados do navegador. Faça backup regularmente em JSON.

### O app não funciona offline
- **Solução**: Abra uma vez online para cachear os dados. Depois funciona offline.

### Os gráficos não aparecem
- **Solução**: Certifique-se de que o Chart.js está carregando (verifique a conexão de internet).

### Não consigo instalar como app
- **Solução**: Use um navegador moderno (Chrome, Firefox, Edge ou Safari). Recarregue a página.

## 📝 Exemplos de Uso

### Exemplo 1: Participante com Múltiplos Horários
```
Nome: João Silva
Medicamento: Losartana
Sexta: 06:30, 18:30
Sábado: 06:30, 18:30
Domingo: 06:30, 18:30
```

### Exemplo 2: Adicionar Observação
```
Dia: Sábado
Observação: "Participante teve dificuldade em engolir"
```

## 🎯 Casos de Uso

- ✅ Encontros de homens/mulheres da igreja
- ✅ Retiros religiosos
- ✅ Acampamentos
- ✅ Eventos comunitários
- ✅ Clínicas de saúde
- ✅ Asilos e casas de repouso

## 📞 Suporte

Se encontrar problemas:
1. Verifique se está usando um navegador atualizado
2. Limpe o cache e recarregue a página
3. Tente em outro navegador
4. Abra uma issue neste repositório

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para:
- Reportar bugs
- Sugerir melhorias
- Fazer pull requests

## 👨‍💻 Desenvolvido por

Desenvolvido com ❤️ para facilitar o gerenciamento de medicamentos em eventos.

## 🙏 Agradecimentos

- Chart.js pela biblioteca de gráficos
- Comunidade open source
- Todos os usuários que testaram e deram feedback

## 📈 Roadmap

- [ ] Sincronização em nuvem
- [ ] Notificações de lembretes
- [ ] Histórico completo de alterações
- [ ] Suporte a múltiplos eventos
- [ ] Integração com calendário
- [ ] Modo offline melhorado

## 🔐 Privacidade

- ✅ Nenhum dado é enviado para servidores
- ✅ Nenhum rastreamento
- ✅ Nenhuma coleta de dados pessoais
- ✅ Totalmente privado e seguro

## 💡 Dicas

1. **Antes do Evento**: Cadastre todos os participantes e medicações
2. **Durante o Evento**: Use a aba "Pendentes" para controle rápido
3. **Backup**: Exporte em JSON antes do evento
4. **Impressão**: Imprima o relatório final para registro
5. **Celular**: Instale como app para melhor experiência

## 📞 Contato

Para dúvidas ou sugestões, abra uma issue neste repositório.

---

**Desenvolvido com ❤️ para a comunidade**

⭐ Se este projeto foi útil, considere dar uma estrela!

