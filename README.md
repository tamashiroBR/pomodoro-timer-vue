# 🍅 Pomodoro Timer (Vue.js)

Um aplicativo web interativo que implementa a técnica Pomodoro para melhorar produtividade, construído com Vue.js 3 e design responsivo.

## 🚀 Funcionalidades

- **Timer Pomodoro Completo**: Ciclos de trabalho (25 min) e pausa (5 min)
- **Interface Responsiva**: Funciona em desktop, tablet e mobile
- **Controles Intuitivos**: Iniciar, pausar, resetar e pular sessões
- **Configurações Personalizáveis**: Ajuste duração de trabalho e pausa
- **Som de Notificação**: Alerta ao término de cada sessão
- **Histórico de Sessões**: Rastreia últimas 5 sessões completadas
- **Estatísticas**: Mostra número de pomodoros e tempo total
- **Barra de Progresso**: Visualização visual do tempo restante
- **Tema Moderno**: Design com gradientes e animações suaves

## 🛠️ Tecnologias

- Vue.js 3 (via CDN)
- HTML5
- CSS3 (Flexbox, Grid, Animações)
- JavaScript Vanilla (Web Audio API)

## 📦 Como executar

1. Clone o repositório
2. Navegue até o diretório do projeto:
   ```bash
   cd 10-pomodoro-timer-vue
   ```
3. Abra o arquivo `index.html` no seu navegador

**Opção com servidor local:**
```bash
python3 -m http.server 8000
# Acesse http://localhost:8000
```

## 📖 Como Usar

### Ciclo Pomodoro Básico

1. **Iniciar Sessão**:
   - Clique em "▶️ Iniciar"
   - O timer começará a contar regressivamente

2. **Trabalhar**:
   - Trabalhe por 25 minutos (padrão)
   - Ao terminar, um som toca automaticamente

3. **Pausar**:
   - Aproveite 5 minutos de pausa (padrão)
   - O timer alterna automaticamente

4. **Repetir**:
   - Continue o ciclo conforme necessário

### Controles Disponíveis

- **▶️ Iniciar/⏸️ Pausar**: Inicia ou pausa o timer
- **🔄 Reset**: Reinicia o timer da sessão atual
- **⏭️ Pular**: Pula para a próxima sessão
- **⚙️ Configurações**: Ajusta duração de trabalho e pausa
- **🔊/🔇 Som**: Ativa/desativa notificação sonora

### Visualizações

- **Modo Trabalho**: Indicador azul (⏱️ Trabalho)
- **Modo Pausa**: Indicador verde (☕ Pausa)
- **Barra de Progresso**: Mostra percentual de tempo decorrido
- **Estatísticas**: Sessões completas e tempo total

## 🎨 Design

- **Cores Principais**: Roxo (#667eea) para trabalho, Verde (#48bb78) para pausa
- **Layout Responsivo**: Adapta-se a qualquer tamanho de tela
- **Animações Suaves**: Transições e efeitos visuais
- **Tipografia Clara**: Fonte grande e legível

## 🔊 Notificações Sonoras

O aplicativo gera um tom de 800Hz ao completar cada sessão usando Web Audio API. Pode ser desativado nas configurações.

## 💾 Dados

O histórico de sessões é armazenado na memória durante a sessão. Para persistência permanente, considere adicionar localStorage.

## 🚀 Melhorias Futuras

- Salvar histórico com localStorage
- Notificações do navegador
- Temas personalizáveis
- Integração com calendário
- Relatórios semanais

## 📄 Licença

Este projeto está sob a licença MIT.
