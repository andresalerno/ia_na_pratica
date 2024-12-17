---
layout: default
title: IA na Prática I
description: Projetos e ferramentas de IA aplicadas à gestão e produtividade.
---

<link rel="stylesheet" href="assets/custom.css">


<!-- <p align="center">
  <a href="https://ipog.edu.br/cursos/pos-graduacao/mba-em-inteligencia-artificial-para-gestao-e-negocios">
    <img src="https://ipog.edu.br/_next/image?url=%2Flogo-ipog.png&w=1920&q=75" alt="IPOG" width="300" />
  </a>
</p> -->


<p align="center">
  <strong style="font-size: 36px;">🎓 Professor André Salerno</strong>
</p>

---

# 🌟 **IA na Prática I**

> Projetos e ferramentas de IA aplicadas à gestão e produtividade.

**Objetivo:**  
Interação prática com ferramentas de gestão para que os alunos possam experimentar a criação de conteúdo e soluções geradas por IA.

---

## 🚀 **Conteúdo do Curso**

- **RPA (Robotic Process Automation)** com ferramentas como **UiPath**.  
- **Análise preditiva** para decisões empresariais com **Power BI**.  
- **Automação de Tarefas e Workflow** com **Zapier**.  
- **Ferramentas de IA Generativa** como **ChatGPT**.  
- **Gerenciamento de Documentos**, **Gestão de Tempo** e **Produtividade**.

---

## 🤖 **RPA - Robotic Process Automation**

### 🧐 **O que é RPA?**

RPA é uma tecnologia que utiliza **robôs de software** (bots) para automatizar tarefas repetitivas e baseadas em regras em sistemas digitais. Esses robôs imitam as ações humanas, como:

- Clicar em botões  
- Inserir e transferir dados  
- Executar cálculos  
- Gerar relatórios  

---

### ⚙️ **Como Funciona?**

O processo de implementação de **RPA** envolve as seguintes etapas:

| **Etapa**               | **Descrição**                                                   |
|-------------------------|-----------------------------------------------------------------|
| **1. Mapeamento**       | Identificação de tarefas manuais e repetitivas.                 |
| **2. Desenvolvimento**  | Criação do robô utilizando plataformas de RPA.                 |
| **3. Execução**         | O robô executa as ações conforme as regras definidas.          |
| **4. Monitoramento**    | Avaliação da performance e dos resultados obtidos pelos bots.  |

---

### ✅ **Exemplos de Aplicação**

1. **Automação de entrada de dados**: Transferir informações de planilhas para sistemas ERP.  
2. **Processamento de faturas**: Ler documentos e atualizar sistemas financeiros.  
3. **Geração de relatórios**: Consultar sistemas e criar relatórios automaticamente.  
4. **Atendimento ao cliente**: Responder a solicitações e processar dados.  
5. **Validação de informações**: Verificar inconsistências em documentos ou sistemas.

---

### 🎯 **Benefícios da RPA**

- ✅ **Redução de Custos**: Elimina tarefas repetitivas e libera tempo dos funcionários.  
- ✅ **Aumento de Produtividade**: Robôs trabalham 24/7 sem interrupções.  
- ✅ **Precisão**: Minimiza erros manuais.  
- ✅ **Escalabilidade**: Amplia a capacidade conforme a demanda.  
- ✅ **Compliance**: Garante processos padronizados e auditáveis.

---

### 🧠 **Diferenças entre RPA e IA**

- **RPA**: Automatiza **tarefas estruturadas e baseadas em regras**.  
- **IA**: Aprende com dados, identifica padrões e toma decisões.

> **Combinação RPA + IA**: Permite automação **inteligente**. Por exemplo:  
> Uso de **OCR (Reconhecimento de Texto)** para leitura de documentos e **análise preditiva**.

---

## 🔧 **Ferramentas Populares de RPA**

Aqui estão algumas das plataformas mais utilizadas:

| **Ferramenta**              | **Descrição**                             |
|-----------------------------|-------------------------------------------|
| **UiPath**                  | Interface visual e fácil integração.      |
| **Automation Anywhere**     | Soluções robustas e escaláveis.           |
| **Blue Prism**              | Foco em grandes empresas.                 |
| **Microsoft Power Automate**| Automação conectada ao ecossistema MS.    |
| **Kofax RPA**               | Soluções avançadas para empresas.         |

---

## 🔧 Tecnologias Utilizadas

- Python
- RPA com UiPath
- Automação de Processos
- GitHub Pages

E falando em Python, teste ele aqui embaixo:

<h2>Execute Python Online</h2>

<p>Digite 2 + 2 e clique em Run Code</p>

<!-- Área para entrada de código -->
<textarea id="code" rows="8" cols="50">

</textarea>
<br>

<!-- Botão para executar o código -->
<button onclick="runPython()">Run Code</button>

<!-- Local onde a saída será exibida -->
<pre id="output"></pre>

<script type="text/python3">
from browser import document, window
import sys
import io

# Definir a função para execução do código
def runPython():
    output = document["output"]  # Elemento de saída
    code = document["code"].value  # Código inserido no textarea

    # Redirecionar stdout para capturar a saída do print()
    old_stdout = sys.stdout
    sys.stdout = io.StringIO()

    try:
        exec(code)  # Executar o código Python
        result = sys.stdout.getvalue()

        # Avaliar expressões simples como "2 + 2"
        if not result.strip():
            result = str(eval(code))

        output.text = result  # Mostrar resultado na área de saída
    except Exception as e:
        output.text = f"Erro: {e}"
    finally:
        sys.stdout = old_stdout  # Restaurar stdout

# Expor a função ao escopo global do JavaScript
window.runPython = runPython
</script>



---

## 📚 **Referências e Links**

- [Documentação oficial do UiPath](https://www.uipath.com/)  
- [Power BI - Microsoft](https://powerbi.microsoft.com/)  
- [Zapier - Automação de Workflows](https://zapier.com/)  
- [Conheça o ChatGPT](https://chat.openai.com/)

---

<p align="center">
  <a href="http://www.datafintechsolutions.com">
    <img src="https://www.datafintechsolutions.com/img/logo.png" alt="Data FinTech Solutions" width="120"/>
  </a>
</p>

<p align="center">
  <strong>© 2024 Data FinTech Solutions | Todos os direitos reservados.</strong>
</p>

