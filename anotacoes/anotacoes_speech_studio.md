# 🎤 Anotações Práticas: Azure Speech Studio

## 💡 Objetivo do Teste
Documentar a aplicação prática e os insights obtidos ao explorar as funcionalidades de fala (Speech) da plataforma Azure AI.

---

## 🔬 Teste Prático 1: Reconhecimento de Fala (Speech-to-Text)

### 1. Funcionalidade Explorada
Transcrição de áudio para texto.

### 2. Passos de Execução
1.  Acessado o Speech Studio no portal do Azure e criado um novo recurso.
2.  Utilizado um arquivo de áudio de teste no idioma **Português (Brasil)** com duração de 15 segundos.
3.  O sistema forneceu a transcrição e marcou os pontos onde houve maior pontuação de confiança.

### 3. Resultados e Insights
* **Taxa de Precisão Observada:** A precisão foi de aproximadamente **97% em condições ideais**. Houve dificuldade em identificar pontuação em frases longas sem pausas vocais claras.
* **Vantagem da Plataforma:** A plataforma facilita a **transcrição em lote**, permitindo que grandes quantidades de áudio sejam processadas de forma eficiente, ideal para call centers.
* **Desafio Encontrado:** O modelo demonstrou menor precisão ao tentar transcrever **nomes próprios e termos técnicos** não comuns no vocabulário geral.

---

## 🔬 Teste Prático 2: Síntese de Fala (Text-to-Speech)

### 1. Funcionalidade Explorada
Criação de voz sintética a partir de texto (Voz Neural).

### 2. Passos de Execução
1.  Acessado o serviço "Síntese de Fala" no Studio.
2.  Digitado um texto de amostra sobre o projeto DIO.
3.  Testado diferentes vozes neurais brasileiras, como "Francisca" e "Antonio".
4.  Ajustado a velocidade de leitura para um tom mais natural.

### 3. Resultados e Insights
* **Qualidade da Voz:** As vozes neurais são de **altíssima qualidade** e extremamente naturais. A entonação é realista e com boa fluidez.
* **Aplicação Potencial:** Ideal para a criação de conteúdo de e-learning, narração de audiobooks ou sistemas de assistentes virtuais de alta fidelidade.
* **Customização:** O recurso de **SSML** (Speech Synthesis Markup Language) é crucial, pois permite controlar a ênfase, a pronúncia e adicionar pausas, resultando em uma fala ainda mais humana.
