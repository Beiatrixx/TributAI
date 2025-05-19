# 💼 TributAI – Assistente Contábil Inteligente especializado na Reforma Tributária

Projeto para auxiliar contadores e empreendedores com as mudanças provocadas pela Reforma Tributária, utilizando agentes de IA da Google ADK para consultar, analisar situações e gerar um planejamento contábil personalizado, com os pontos de atenção considerando os impactos da reforma para a sua empresa.

## 🚀 Descrição

O **TributAI** é um sistema de inteligência artificial **multiagente (consultor legislativo, analista tributário e contador)** desenvolvido em **Python**, projetado para **interpretar, analisar e aplicar a nova Reforma Tributária (EC 132/2023)** de forma personalizada. Ideal para profissionais e empreendedores que buscam agilidade, precisão e atualização.

---

## 🧩 Funcionalidades

Por meio das informações fornecidas pelo usuário, o TributAI oferece:

- 🔍 Consulta automática a fontes atualizadas sobre a reforma tributária (via Google Search)
- 🧠 Interpretação legal personalizada por tipo de empresa, regime de tributação e localização
- 📊 Análise comparativa entre regime atual e novo cenário pós-reforma
- 📋 Geração de plano contábil com base nas normas do CFC

---

## 🛠 Tecnologias Utilizadas

- **Python 3.11.12**
- **Google ADK (Google AI Developers Kit)**
- **Gradio para interface web**
- **Google Colab (ambiente de execução)**
- **Google GenAI**

---

## 📦 Como utilizar:

1. Clone este repositório.
2. Abra o notebook no Google Colab.
3. Configure sua chave API do Google definindo a variável GOOGLE_API_KEY no ambiente:

       import os
       from google.colab import userdata
    
       os.environ["GOOGLE_API_KEY] = userdata.get('GOOGLE_API_KEY')

4. Execute todas as células do notebook para carregar os agentes e iniciar a interface Gradio.
5. Abra o link no navegador ou interaja diretamente pela interface gerada.

---

## 👤 Contato

Fique a vontade para me enviar dúvidas, sugestões ou contribuições através dos canais:

📧 **E-mail:** bac.beatriz@hotmail.com

💻 **Git Hub:** [Beiatrixx] (https://github.com/Beiatrixx)

💼 **LinkedIn:** (www.linkedin.com/in/beatrizapcelestino)
