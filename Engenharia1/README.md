### Trecho 1: O Conceito de Engenharia de Software

> What precisely do we mean by software engineering? What distinguishes “software engineering” from “programming” or “computer science”? And why would Google have a unique perspective to add to the corpus of previous software engineering literature written over the past 50 years? The terms “programming” and “software engineering” have been used interchangeably for quite some time in our industry, although each term has a different emphasis and different implications. University students tend to study computer science and get jobs writing code as “programmers.” “Software engineering,” however, sounds more serious, as if it implies the application of some theoretical knowledge to build something real and precise. Mechanical engineers, civil engineers, aeronautical engineers, and those in other engineering disciplines all practice engineering. They all work in the real world and use the application of their theoretical knowledge to create something real. Software engineers also create “something real,” though it is less tangible than the things other engineers create. Unlike those more established engineering professions, current software engineering theory or practice is not nearly as rigorous. Aeronautical engineers must follow rigid guidelines and practices, because errors in their calculations can cause real damage; programming, on the whole, has traditionally not followed such rigorous practices. But, as software becomes more integrated into our lives, we must adopt and rely on more rigorous engineering methods. We hope this book helps others see a path toward more reliable software practices.

**Comentário:**

A engenharia de software é vista de uma maneira muito simples e de subestimada, a falta de licença é diretrizes deixar muito aberta e de fácil de se iniciar mesmo sem ensino superior o que é bom, mas ignorar que essa falta de seriedade também é tão perigosa quanto outras engenharias é burrice, principalmente hoje em dia onde vários sistemas dependem de profissionais competentes para mantê-los seguros como, sua conta no banco, sistemas de navegação, etc, softwares que se mal projetados e protegidos podem também causar danos à população,  não físico, mas estrutural( e em alguns casos físicos também, porque um mal funcionamento do software do hospital também pode ser problemático para a saúde dos pacientes).

Outra questão é que essa engenharia, diferente das outras, se trata se mexer com imaterial(o mundo digital) o que a torna mais cara e complexa comparada a outras em suas funções, o que a torna também mais demorada para gerar lucros significativos e necessita mais atenção, por que até mesmo ações pequenas vista de fora, como retirar uma informação de um banco de dados, pode custar milhões.

---

### Trecho 2: Programming Over Time

> Programming Over Time We propose that “software engineering” encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time. What practices can a software organization introduce that will best keep its code valuable over the long term? How can engineers make a codebase more sustainable and the software engineering discipline itself more rigorous? We don’t have fundamental answers to these questions, but we hope that Google’s collective experience over the past two decades illuminates possible paths toward finding those answers. One key insight we share in this book is that software engineering can be thought of as “programming integrated over time.” What practices can we introduce to our code to make it sustainable—able to react to necessary change—over its life cycle, from conception to introduction to maintenance to deprecation? The book emphasizes three fundamental principles that we feel software organizations should keep in mind when designing, architecting, and writing their code:
> 
> - **Time and Change:** How code will need to adapt over the length of its life
> - **Scale and Growth:** How an organization will need to adapt as it evolves
> - **Trade-offs and Costs:** How an organization makes decisions, based on the lessons of Time and Change and Scale and Growth

**Comentário:**

Alguém que revisa e atualiza o código é igualmente importante comparada a aquele que o criou, pois é essa função que protege o código de hackers e garante que o código se mantém útil e funcional de acordo com o passar do tempo e as suas mudanças e necessidades.

Uma parte importante e muita ignorada durante o desenvolvimento de um software é o trade-off no processo, todas as escolhas importam desde a linguagem usada, por exemplo, se você vai precisar usar uma mais rápida, consequentemente ela vai ser mais complexa de mexer, como o C, ou se preferir usar uma mais simples, consequentemente ela vai ser mais lenta, como o Python, isso ocorre durante o código também, se preferir utilizar uma solução mais rápida e fácil, como resultado ela vai ter mais chance de gerar erros futuramente no código.

### Exemplos de Trade-Off:

**1.Velocidade x Memória:**
- **Situação:** Salvar os dados em uma estrutura para deixar a resposta mais rápida.
- **Trade-Off:** Essa estrutura vai consumir mais memória.

**2.Código Simples x Otimizado:**
- **Situação:** Você escreve um código simples para facilitar o entendimento de terceiros.
- **Trade-Off:** Essa estrutura pode ser mais lenta de processar, simplicidade x desempenho

**3.Privacidade x Personalização:**
- **Situação:** Um programa que coleta informações do usuário e usa para fornecer um serviço mais único.
- **Trade-Off:** Sacrifica a segurança dos usuários por um serviço mais personalizado.

---

### Minhas Contribuições no Projeto (API)
- Não tive contribuições significativas, e vou melhorar na sprint 2

### Habilidades Aprendidas
- Integração do IA local do Ollama em um bot
- estruturação de um código no formato da biblioteca do DSPy
- comandar uma IA local a realizar tarefas específicas 
