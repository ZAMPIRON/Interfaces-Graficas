# SELENIUM e PYAUTOGUI

**Definição**

Ferramenta para automação de navegadores web.

**O que faz**

- Controla páginas da web de forma automatizada.
- Localiza elementos e interage com eles.
- Compara resultados esperados e obtidos.

**Linguagens compatíveis**

- Funciona com Python, Java, C#, Ruby, JavaScript, etc.

**Instalação**

```bash
pip install selenium
pip install webdriver-manager
```

**Componentes**

- **WebDriver**: controla navegadores reais (Chrome, Firefox, Edge).
- **Selenium IDE**: grava e reproduz ações (ideal para iniciantes).
- **Selenium Grid**: executa testes em vários dispositivos/navegadores ao mesmo tempo.

**Pontos positivos**

- Reduz erros e aumenta produtividade.
- Suporte a metodologias ágeis.
- Feedback rápido.

**Pontos negativos**

- Não funciona para aplicativos desktop.
- Relatórios limitados.
- Pode ser lento em suítes grandes.
- Curva de aprendizado alta.

**Métodos comuns**

- `back()`, `close()`, `execute_script()`, `forward()` `refresh()`

**Aplicações reais**

- Automação de login, testes web, scraping controlado.
- Usado por empresas como Netflix e Spotify.

---

## **PyAutoGUI**

**Definição**

Biblioteca Python para automação de tarefas gráficas no computador.

**O que faz**

- Move o mouse, clica, digita textos e pressiona teclas.
- Simula ações humanas na interface gráfica.

**Instalação**

```bash
pip install pyautogui
```

**Funcionamento**

- Traduz comandos Python em interações simuladas no sistema operacional.
- Baseia-se nas coordenadas da tela, sem "entender" o que está na tela.

**Funções comuns**

- Digitar texto.
- Mover e clicar com o mouse.
- Pressionar atalhos do teclado.
- Abrir e navegar por programas.

**Cuidados**

- Depende da resolução e posição dos elementos na tela.
- Qualquer mudança na interface pode quebrar o script.

**Aplicações**

- Testes simples.
- Preenchimento automático de formulários.
- Repetição de tarefas rotineiras.

## **Comparação rápida**

| Característica | Selenium | PyAutoGUI |
| --- | --- | --- |
| **Área de uso** | Automação de navegadores web | Automação da interface gráfica |
| **Linguagens** | Várias | Python |
| **Complexidade** | Média-alta | Baixa |
| **Pontos +** | Testes e automação web | Simplicidade |
| **Pontos -** | Mais difícil de aprender e configurar | Pouco preciso, depende da tela |
| **Uso real** | Testes automatizados | Rotinas repetitivas |