# 🧠 Detalhes Técnicos — Reciclo Educação

## 🧩 Visão Geral da Arquitetura

O **Reciclo Educação** integra **inteligência artificial**, **kits educacionais reutilizáveis** e **processos de desmontagem segura** para o reaproveitamento de cigarros eletrônicos apreendidos.  

**Fluxo Principal Simplificado:**  
`Imagem → IA para Análise → Identificação de Componentes → Kit Educacional`

---

## 🔍 Visão Computacional e Inteligência Artificial

* **Frameworks Utilizados:** `TensorFlow` , `PyTorch`, `Yolo` ,com `OpenCV` para processamento de imagem.  
* **Objetivo:** Identificar **componentes reutilizáveis** em cigarros eletrônicos antes da desmontagem manual.  
* **Modelo:**  
  - **Tipo:** CNN otimizada para **classificação de peças eletrônicas**.  
  - **Treinamento:**  
    - **Dataset:** Imagens coletadas durante o Hackathon, ampliadas posteriormente.  
    - **Anotação:** Ferramentas como `LabelImg`.  
    - **Saída:** JSON contendo **tipo de componente, status de recuperação e recomendação**.  

🔗 [Consulte o README do projeto](README.md)  
🔗 [Veja a análise de custo](custo.md)  
