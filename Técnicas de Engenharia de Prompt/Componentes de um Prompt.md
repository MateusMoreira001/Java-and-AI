# 🧠 Componentes de um Prompt (8 Aulas)
> **Domine a engenharia de prompts com essas 8 peças essenciais**  
> *Como instruir IAs como ChatGPT para obter resultados profissionais*

## 🔍 Os 8 Elementos-Chave (com exemplos práticos)

| Componente          | 🎯 Função                | ⚡ Exemplo Conciso (Clique para ver) |
|---------------------|-------------------------|--------------------------------------|
| **1. Instruções**   | Define a tarefa         | [`"Resuma em 3 frases técnicas"`](#) |
| **2. Exemplos**     | Demonstra o padrão      | [`Few-shot: Entrada → Saída ideal`](#) |
| **3. Contexto**     | Configura o cenário     | [`"Você é um tutor de Java"`](#) |
| **4. Restrições**   | Limita o escopo         | [`"Máx. 50 palavras, sem opiniões"`](#) |
| **5. Conteúdo**     | Dados para processar    | [`Texto/PDF/Tabela de input`](#) |
| **6. Indicações**   | Guia o estilo           | [`"Liste como tópicos técnicos"`](#) |
| **7. Formato**      | Estrutura da saída      | [`"Gere em JSON com campos X,Y"`](#) |
| **8. Suporte**      | Dados complementares    | [`"Contexto: dezembro/2024"`](#) |

### 💡 Exemplo Integrado (IA para Eventos):
```python
"Você é um organizador criativo (contexto). 
Liste 3 ideias sustentáveis (instrução) para: 
'Evento comunitário multigeracional' (conteúdo). 
Restrições: orçamento baixo, ao ar livre (suporte). 
Formato: tabela com colunas 'Ideia' e 'Materiais' (formato)."