<div align="center">

![License](https://img.shields.io/github/license/eldinaldolustosa/resume?style=flat-square&color=blue)
![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-473d3f?logo=latex&style=flat-square)
![Maintained](https://img.shields.io/badge/Maintained-Yes-green?style=flat-square)

</div>

<div align="center">
  <h3>
    <a href="#português">🇧🇷 Português</a>
  </h3>
</div>

---

<div id="português"></div>

# Modelo de Currículo em LaTeX

Um modelo de currículo profissional, limpo e fácil de usar, feito em LaTeX. **Você não precisa ser um programador para usar ele!**

## 🧩 Como usar (Sem precisar programar)

Se você não tem familiaridade com GitHub ou código, a maneira mais fácil de usar este modelo é com o **[Prism](https://prism.openai.com/)**, um editor de código com inteligência artificial.

> 💡 **O que é um arquivo em LaTeX?** 
> Muitas pessoas confundem LaTeX com uma linguagem de programação complexa, mas na verdade é apenas um arquivo de texto usado para gerar um **PDF de alta qualidade**. Você não precisa saber programar para usar!

**Passo a passo:**
1. **Copie o código**: Abra e copie todo o texto do arquivo de currículo em PORTUGUES ou INGLES: [`[BR]Resume-LaTeX.tex`]([BR]Resume-LaTeX.tex) ou [`[EN]Resume-LaTeX.tex`]([EN]Resume-LaTeX.tex).
2. **Acesse o Prism**: Acesse [prism.openai.com](https://prism.openai.com/). *Você nem precisa criar conta para editar e baixar!*
3. **Cole e Edite**: Crie um arquivo no Prism e cole o código.
4. **Use a IA a seu favor**: Você pode alterar o texto manualmente, ou pode enviar seu currículo atual no chat e pedir direto para a IA fazer as modificações para você, como num ChatGPT.
5. **Baixe o PDF**: Para gerar o PDF de alta qualidade, é só baixar pelo próprio Prism no painel lateral direito que sera compilado com a visualizacao do PDF que esta sendo editado. Procure no canto superior direito o icone para fazer o download!

## ❓ Perguntas Frequentes (FAQ)

<details>
<summary><strong>Qual versão devo usar?</strong></summary>

- Use a **versão em Português** (`[[BR]Resume-LaTeX.tex`) para o mercado brasileiro.
- Use a **versão em Português** (`[EN]ResumeLa-TeX.tex`) para o mercado internacional.
</details>

<details>
<summary><strong>Eu não sei LaTeX. Ainda posso usar?</strong></summary>

**Sim!** Como você usará o Prism, não precisa entender nada de LaTeX. Você pode simplesmente pedir para a IA do Prism preencher suas informações pessoais e ela lidará com toda a estrutura do código para você.
</details>

<details>
<summary><strong>Onde consigo ajuda para escrever o conteúdo?</strong></summary>

Você pode pedir diretamente para a IA integrada do Prisma! Nós também incluímos neste repositório prompt que podem te ajudar a estudar para uma entrevista ingles, caso aplique par auma vaga no mercado internacional e, caso queira um curriculo em ingles, basta solicitar para a IA do Prisma que ele escreve a trducao desejada.
</details>

<details>
<summary><strong>Devo colocar foto no meu currículo?</strong></summary>

**Não.** Para a maioria das vagas de tecnologia e setores corporativos (especialmente internacionais), fotos não são recomendadas e podem atrapalhar a leitura por sistemas automáticos (ATS).
</details>

<details>
<summary><strong>Posso converter para Word?</strong></summary>

Embora seja possível, **não é recomendado**. Um dos principais benefícios do LaTeX é criar um PDF perfeitamente formatado que parece profissional em qualquer dispositivo. Converter para Word geralmente quebra o design.
</details>

<details>
<summary><strong>Como gero os PDFs do meu currículo?</strong></summary>

Se você estiver usando o **Prism**, basta baixar o PDF gerado diretamente pela interface deles.

Alternativamente, se você tem familiaridade com o GitHub, para cada push (envio de código) no repositório, um fluxo de trabalho (workflow) gerará automaticamente novos PDFs. Você pode baixá-los na aba "Actions" (Ações) ou Fork este repositorio.
</details>

---

## License / Licença

This project is licensed under the Apache License 2.0 - see the [LICENSE](license.md) file for details.
--------------------------------------------------------
# Modelo de Currículo em Português

Se você precisa de ajuda para criar frases impactantes para seu currículo, utilize o prompt disponível na pasta "prompts" e insira-o em um LLM (modelo de linguagem) para pedir sugestões. Recomendo fortemente que você tente primeiro escrever suas próprias ideias e, depois, peça ao agente sugestões de melhoria. Pedir para o agente criar todo o currículo do zero pode resultar em um texto genérico, facilmente identificado por recrutadores.

Você pode fornecer ao agente algo como:

> "Meu objetivo principal é encontrar vagas [internacionais, nacionais]. Tenho preferência por empresas [do Brasil, dos EUA, da Europa etc.], mas estou aberto(a) a oportunidades em [Brasil, EUA, Europa etc.].  
> Atualmente, (trabalho como [sua função]) OU (sou estudante de [seu curso]), e busco vagas de [nível, ex: júnior, pleno, sênior] para [cargo desejado].  
> Vamos revisar cada tópico do meu currículo para corrigir erros gramaticais e encontrar formas melhores de expressar o que escrevi. Quero que você foque no mercado profissional [brasileiro, internacional] e seja cuidadoso com a terminologia utilizada."

Consulte também o arquivo [Professor de Inglês Técnico para RH e Entrevistas.md] para obter um prompt detalhado e orientações específicas de estudo de ingles para entrevistas e comportamento durente a entrevista com RH ou Recrutador Tecnico. Nao esqueca de informar o seu cargo e funcao desejada no prompt para uma melhor performance da IA que voce escolher executar o prompt.

## Seções do Modelo

### Formação Acadêmica

- Liste universidade, local, grau e datas para cada experiência.
- Se estiver buscando o primeiro emprego ou estágio, coloque esta seção logo abaixo do cabeçalho; caso contrário, deixe-a ao final do currículo.

### Atividades de Liderança

- Ótima seção para demonstrar iniciativa e trabalho em equipe fora das experiências profissionais tradicionais.

### Experiência Profissional

- Use verbos de ação para descrever conquistas. Quantifique resultados sempre que possível.
- Detalhe as experiências da mais recente para a mais antiga.
- Foque em realizações, não apenas em tarefas. Utilize o método STAR (Situação, Tarefa, Ação, Resultado) para estruturar os tópicos.
- Destaque habilidades transferíveis como mentoria, comunicação e colaboração.

### Habilidades

- Seja conciso e relevante para as vagas desejadas.

# Dicas para Currículo

Estas dicas foram adaptadas do artigo da [Harvard](https://careerservices.fas.harvard.edu/resources/create-a-strong-resume/). Recomendo a leitura completa do artigo.

## O currículo deve ser:

- Específico, não genérico
- Ativo, não passivo
- Escrito para expressar, não impressionar
- Claro e objetivo, evitando floreios
- Baseado em fatos (quantifique e qualifique)
- Escrito para pessoas e sistemas que fazem leitura rápida

---

Para dúvidas sobre o template LaTeX, consulte os comentários no arquivo `[BR]Resume-LaTeX.tex` ou `[EN]Resume-LaTeX.tex`.
